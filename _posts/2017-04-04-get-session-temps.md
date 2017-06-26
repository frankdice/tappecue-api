---
apipath: '/session/:id'
title: 'Session Temperatures'
type: 'GET'
category: 'Sessions'

layout: null
---

This method returns a list of all current sessions associated with your Tappecue account.

### Request
* The header must include "X-Auth-Header: \<Auth Token>"

### Response
JSON object of current session's temperatures (and other useful info)

```{
	timezone: 'US/Eastern'
}```

