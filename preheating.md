# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/userprogram/preheating   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /ecus/rrc/userprogram/preheating | Message ID (URL) |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | stringValue | Data type of value |
|  value | on |  |
|  writeable | 1 | Writable parameter (0=No) |

### Example
```
{
    "id": "/ecus/rrc/userprogram/preheating",
    "recordable": 0,
    "type": "stringValue",
    "value": "on",
    "writeable": 1
}
```