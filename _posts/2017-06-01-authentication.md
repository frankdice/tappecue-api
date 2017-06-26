---
apipath: '/login'
title: 'Authenticate'
type: 'POST'

layout: null
---

This method performs the login and sends back an authentication token that is required to interact with the rest of the platform.

The session tokens are valid for 24 hours.

### Request
Standard POST request
```{
	username: <Tappecue Username>
	Password: <Tappecue Password>
}```

##### Example
`curl -d "username=test&password=testpass" {{ site.base_api_url }}{{ page.apipath }}`

### Response (JSON)

Sends back a json object containing an X-Auth-Header which needs to be included in all subsequent requests

```{
	"X-Auth-Header": "<UUID>"
}```

### Notes
**This site does not store your password.**

I take a cryptographic hash of your password (sha256) and store it temporarily to allow for session durability across multiple logins while the existing session is still active.

