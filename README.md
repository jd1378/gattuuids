# GATT UUIDs
this npm package provides uuid list of [GATT specifications](https://www.bluetooth.com/specifications/gatt)

Example usage:
```
let UUIDList = require('gattuuids');
let Characteristic = require('bleno').Characteristic;
...
new Characteristic({
    uuid: UUIDList.Characteristics.battery_level,
    ...
})
```