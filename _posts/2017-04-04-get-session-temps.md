---
apipath: '/session/:id'
title: 'Session Temperatures'
type: 'GET'
category: 'Sessions'

layout: null
---

This method returns a list of all available sensor temperatures for the given session.

### Request
* The header must include "X-Auth-Header: \<Auth Token>"

##### Example
`curl -H "X-Auth-Token: <token>" {{ site.base_api_url }}{{ page.apipath }}`

### Response
JSON object of current session's temperature probe data (and other useful info)

```{
  "1": {
    "active": "0", 
    "chamber": "0", 
    "current_temp": "0  ", 
    "last_update": "6/26/2017 3:25:36 PM", 
    "max_temp": "0", 
    "min_temp": "0", 
    "name": " None", 
    "wifi_disconnected": "0"
  }, 
  "2": {
    "active": "0", 
    "chamber": "0", 
    "current_temp": "0  ", 
    "last_update": "6/26/2017 3:25:36 PM", 
    "max_temp": "0", 
    "min_temp": "0", 
    "name": " None", 
    "wifi_disconnected": "0"
  }, 
  "3": {
    "active": "1", 
    "chamber": "1", 
    "current_temp": "70 ", 
    "last_update": "6/26/2017 3:25:36 PM", 
    "max_temp": "275", 
    "min_temp": "22", 
    "name": "Ribs (chamber)", 
    "wifi_disconnected": "0"
  }, 
  "4": {
    "active": "0", 
    "chamber": "0", 
    "current_temp": "0  ", 
    "last_update": "6/26/2017 3:25:36 PM", 
    "max_temp": "0", 
    "min_temp": "0", 
    "name": " None", 
    "wifi_disconnected": "0"
  }
}```

