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

## Example
`curl -H "X-Auth-Token: <token>" {{ site.base_api_url }}{{ page.apipath }}`

### Response
JSON object of an individual probe temperature data from session (and other useful info)

```{
  "active": "1", 
  "chamber": "1", 
  "current_temp": "70 ", 
  "last_update": "6/26/2017 3:25:36 PM", 
  "max_temp": "275", 
  "min_temp": "22", 
  "name": "Ribs (chamber)", 
  "wifi_disconnected": "0"
}```
