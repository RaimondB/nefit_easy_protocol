# forcedSwitchedOff



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/forcedSwitchedOff   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/ecus/rrc/weatherDependent/forcedSwitchedOff` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `off` |  |
|  writeable | `1` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/weatherDependent/forcedSwitchedOff",
    "recordable": 0,
    "type": "stringValue",
    "value": "off",
    "writeable": 1
}
```
