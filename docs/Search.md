### Search

```http
  POST https://api.maine-et-loire/saad/search
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `type` | `string` | **Required**. Search for a type of structure |
| `municipalitie` | `string` | **Required**. Search for a municipality |
| `service` | `string` | Search for a service |

Possible answers:

Code|Message|Description
---|---|---
200|OK|The request was received successfully
401|Unauthorized|Insufficient permission
403|Forbidden|Insufficient permission
404|Not found|Municipality not found

---
## Service à la personne - Département de Maine et Loire

© All rights reserved - MIT License.
[@mmoreaudev](https://www.github.com/mmoreaudev) | [DLSI - Maine-et-Loire](https://maine-et-loire.fr)
