---
apipath: '/timezone'
title: 'Current Timezone'
type: 'GET'
category: 'Timezone'

layout: null
---

This method returns the user's current timezone.
* Default timezone is **US/Eastern**

### Request
* The header must include "X-Auth-Token: \<Auth Token>"

##### Example
`curl -H "X-Auth-Token: 11111111-1111-1111-1111-111111111111" {{ site.base_api_url }}{{ page.apipath }}`

### Response (JSON)
```{
	"timezone": "US/Eastern"
}```
