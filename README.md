This is a React Native example app that calls setInterval to write a timestamp every 10 seconds to a Redux store.

## Interval Method

- [ ] Uses [react-native-background-job](https://github.com/vikeri/react-native-background-job)
- [x] Simple setInterval
- [ ] option to start Foreground Service

## Action Performed at Each 10 Second Interval

- [x] Writes timestamp to Redux store
- [ ] Calls bluetoothScan from [react-native-ble-plx](https://github.com/Polidea/react-native-ble-plx) for devices
