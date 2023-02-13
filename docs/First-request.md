## Make the first request

**The SAAD API is coded in PHP, but it can be used in several languages.**

For your first query we will display the communes.

```http
  GET https://api.maine-et-loire/saad/communes
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

Possible answers:

Code|Message|Description
---|---|---
200|OK|The request was received successfully
401|Unauthorized|Insufficient permission

## Use on several languages

Take a look at how you could call this method using different languages

### JavaScript
 ```js
function getdata() {
    fetch('https://api.maine-et-loire/saad/communes')
    .then(res => res.json())
    .then(json => {
        Object.entries(json.retour).forEach(([key, value]) => {
            console.log(value.id)
            console.log(value.nom)           
        });   
    })
    .catch((err) => console.log(err));
}
```
### PHP
```php
<?php
$url = 'https://api.maine-et-loire/saad/communes';
$json = file_get_contents($url);
$decode = json_decode($json);
?>
```
### Python
```python
import urllib.request
import json

user_agent = 'Mozilla/0.5 (Windows; U; Windows NT 5.1; en-US; rv:1.9.0.7) Gecko/2009021910 Firefox/3.0.7'
url = "https://api.maine-et-loire/saad/communes"
headers={'User-Agent':user_agent,}
request = urllib.request.urlopen(request)
data = json.load(response)
print(data['url'])
```
