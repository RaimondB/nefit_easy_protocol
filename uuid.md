# uuid



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /gateway/uuid   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/gateway/uuid` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `123456789` | Unique ID  |
|  writeable | `0` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/gateway/uuid",
    "recordable": 0,
    "type": "stringValue",
    "value": "123456789",
    "writeable": 0
}
```
