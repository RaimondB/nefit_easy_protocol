# maxSupply



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/maxSupply   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/ecus/rrc/weatherDependent/maxSupply` | Message ID (URL) |
|  maxValue | `90` | Maximum allowed value |
|  minValue | `25` | Minimum allowed value |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `floatValue` | Data type of value |
|  unitOfMeasure | `C` | Unit of Measure |
|  value | `90` |  |
|  writeable | `1` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/weatherDependent/maxSupply",
    "maxValue": 90,
    "minValue": 25,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 90,
    "writeable": 1
}
```
