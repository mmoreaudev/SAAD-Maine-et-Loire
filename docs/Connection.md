### Connection

```http
  POST https://api.maine-et-loire/saad/user/login
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `email` | `string` | **Required**. User's e-mail |
| `password` | `string` | **Required**. User's password |

Possible answers:

Code|Message|Description
---|---|---
200|OK|The request was received successfully
400|Bad Request|Invalid E-Mail or Password

### Logout
```http
  DELETE https://api.maine-et-loire/saad/user/logout
```

Possible answers:

Code|Message|Description
---|---|---
200|OK|The request was received successfully

