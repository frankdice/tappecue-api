---
apipath: '/timezone'
title: 'Current Timezone'
type: 'GET'
category: 'Timezone'

layout: null
---

This method returns the user's current timezone.
* Default timezone is US/Eastern

### Request
* The header must include 'X-Auth-Header: <Auth Token>

### Response
```{
	timezone: 'US/Eastern'
}```
