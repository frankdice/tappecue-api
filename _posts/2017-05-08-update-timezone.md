---
apipath: '/timezone'
title: 'Set Timezone'
type: 'POST'
category: 'Timezone'

layout: null
---

This method sets the user's timezone.

### Request
* The header must include "X-Auth-Header: \<Auth Token>"

```{
	timezone: 'US/Central'
}```

### Response
Sends back the timezone as a confirmation.

```{
	timezone: 'US/Central'
}```
