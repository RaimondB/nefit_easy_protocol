# dhwOperationType



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /dhwCircuits/dhwA/dhwOperationType   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/dhwCircuits/dhwA/dhwOperationType` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `follow ch` |  |
|  writeable | `1` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/dhwCircuits/dhwA/dhwOperationType",
    "recordable": 0,
    "type": "stringValue",
    "value": "follow ch",
    "writeable": 1
}
```
