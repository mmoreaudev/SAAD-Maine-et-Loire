### Create a municipality
```http
  POST https://api.maine-et-loire/saad/communes
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `name` | `string` | **Required**. Name of the municipality |

Code|Message|Description
---|---|---
200|OK|The request was received successfully
401|Unauthorized|Insufficient permission
403|Forbidden|Insufficient permission

### Remove a municipality
```http
  DELETE https://api.maine-et-loire/saad/communes/:id
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `string` | **Required**. ID of the municipality |

Code|Message|Description
---|---|---
200|OK|The request was received successfully
401|Unauthorized|Insufficient permission
403|Forbidden|Insufficient permission
404|Not found|Municipality not found

### Modify a municipality

```http
  PUT https://api.maine-et-loire/saad/communes/:id
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `string` | **Required**. ID of the municipality |

Code|Message|Description
---|---|---
200|OK|The request was received successfully
401|Unauthorized|Insufficient permission
403|Forbidden|Insufficient permission
404|Not found|Municipality not found

### Obtaining a municipality

```http
  GET https://api.maine-et-loire/saad/communes/:id
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `string` | **Required**. ID of the municipality |

Code|Message|Description
---|---|---
200|OK|The request was received successfully
401|Unauthorized|Insufficient permission
403|Forbidden|Insufficient permission
404|Not found|Municipality not found




