---
apipath: '/timezone/all'
title: 'All Available Timezones'
type: 'GET'
category: 'Timezone'

layout: null
---

This method returns all currently supported timezones. 
* Default timezone is US/Eastern

### Request
* The header must include "X-Auth-Header: \<Auth Token>"

### Response
JSON list of currently supported timezones.
