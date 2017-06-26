---
apipath: '/login'
title: 'Authenticate'
type: 'POST'

layout: null
---

This method performs the login and sends back an authentication token that is required to interact with the rest of the platform.

### Request
Standard POST request
```{
	username: <Tappecue Username>
	Password: <Tappecue Password>
}```

##### Example
`# curl -d "username=test&password=testpass" {{ site.base_api_url }}{{ page.apipath }}`

### Response (JSON)

Sends back a json object containing an X-Auth-Header which needs to be included in all subsequent requests

```{
	X-Auth-Header: <UUID>
}```



