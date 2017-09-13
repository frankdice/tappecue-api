---
apipath: '/timezone'
title: 'Set Timezone'
type: 'POST'
category: 'Timezone'

layout: null
---

This method sets the user's timezone.

### Request
* The header must include "X-Auth-Token: \<Auth Token>"

Standard HTTP POST

```{
	"timezone": "US/Central"
}```

All Available/Supported Timezones are available from the /timezone/all call.

##### Example
`curl -d "timezone=US/Central" -H "X-Auth-Token: <token>" {{ site.base_api_url }}{{ page.apipath }}`

### Response (JSON)
Sends back the timezone as a JSON object for confirmation.

```{
	"success": true,
	"timezone": "US/Central"
}```
