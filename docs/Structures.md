### Create a structure
```http
  POST https://api.maine-et-loire/saad/structure
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `name` | `string` | **Required**. Name of the structures|

Code|Message|Description
---|---|---
200|OK|The request was received successfully
401|Unauthorized|Insufficient permission
403|Forbidden|Insufficient permission

### Remove a structure
```http
  DELETE https://api.maine-et-loire/saad/structure/:id
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `string` | **Required**. ID of the structures|

Code|Message|Description
---|---|---
200|OK|The request was received successfully
401|Unauthorized|Insufficient permission
403|Forbidden|Insufficient permission
404|Not found|Structures not found

### Modify a structure

```http
  PUT https://api.maine-et-loire/saad/structure/:id
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `string` | **Required**. ID of the structures|

Code|Message|Description
---|---|---
200|OK|The request was received successfully
401|Unauthorized|Insufficient permission
403|Forbidden|Insufficient permission
404|Not found|Structures not found

### Obtaining a structure

```http
  GET https://api.maine-et-loire/saad/structure/:id
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `string` | **Required**. ID of the structures|

Code|Message|Description
---|---|---
200|OK|The request was received successfully
401|Unauthorized|Insufficient permission
403|Forbidden|Insufficient permission
404|Not found|Structures not found

### Obtaining list of structures

```http
  GET https://api.maine-et-loire/saad/structures
```

Code|Message|Description
---|---|---
200|OK|The request was received successfully
401|Unauthorized|Insufficient permission
403|Forbidden|Insufficient permission

---
## Service à la personne - Département de Maine et Loire

© All rights reserved - MIT License.
[@mmoreaudev](https://www.github.com/mmoreaudev) | [DLSI - Maine-et-Loire](https://maine-et-loire.fr)
