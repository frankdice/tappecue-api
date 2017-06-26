---
apipath: '/session/:id/:probe_id'
title: 'Probe Temperature'
type: 'GET'
category: 'Sessions'

layout: null
---

This method returns a specific probe's temperature from the session.

### Request
* The header must include "X-Auth-Header: \<Auth Token>"

### Response
JSON object of probe temperature from session (and other useful info)

```{
	timezone: 'US/Eastern'
}```

