# hc1-holidayMode-end



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /heatingCircuits/hc1/holidayMode/end   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/heatingCircuits/hc1/holidayMode/end` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `2000-01-01T00:00:00` |  |
|  writeable | `1` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/heatingCircuits/hc1/holidayMode/end",
    "recordable": 0,
    "type": "stringValue",
    "value": "2000-01-01T00:00:00",
    "writeable": 1
}
```
