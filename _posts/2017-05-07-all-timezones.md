---
apipath: '/timezone/all'
title: 'All Available Timezones'
type: 'GET'
category: 'Timezone'

layout: null
---

This method returns all currently supported timezones. 
* Default timezone is **US/Eastern**

### Request
* The header must include "X-Auth-Header: \<Auth Token>"

##### Example
`curl -H "X-Auth-Token: 11111111-1111-1111-1111-111111111111" {{ site.base_api_url }}{{ page.apipath }}`


### Response (JSON)
JSON list of currently supported timezones.
```[
  "GMT", 
  "UTC", 
  "US/Alaska", 
  "US/Arizona", 
  "US/Central", 
  "US/Eastern", 
  "US/Hawaii", 
  "US/Mountain", 
  "US/Pacific"
]```
