# hc1-actualSupplyTemperature



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /heatingCircuits/hc1/actualSupplyTemperature   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/heatingCircuits/hc1/actualSupplyTemperature` | Message ID (URL) |
|  maxValue | `100` | Maximum allowed value |
|  minValue | `0` | Minimum allowed value |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `floatValue` | Data type of value |
|  unitOfMeasure | `C` | Unit of Measure |
|  value | `30` |  |
|  writeable | `0` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/heatingCircuits/hc1/actualSupplyTemperature",
    "maxValue": 100,
    "minValue": 0,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 30,
    "writeable": 0
}
```
