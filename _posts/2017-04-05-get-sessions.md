---
apipath: '/sessions'
title: 'Existing Sessions'
type: 'GET'
category: 'Sessions'

layout: null
---

This method returns a list of all current sessions associated with your Tappecue account.

### Request
* The header must include "X-Auth-Header: \<Auth Token>"

### Response
JSON object of all current sessions

```{
	timezone: 'US/Eastern'
}```

The ID field is used to pull temperatures
