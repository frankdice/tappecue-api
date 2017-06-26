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

##### Example
`curl -H "X-Auth-Token: 11111111-1111-1111-1111-111111111111" {{ site.base_api_url }}{{ page.apipath }}`

### Response
JSON list of all current sessions

```[
  {
    "active": "1", 
    "id": 1, 
    "name": "test3", 
    "start": "6/26/2017 3:21:22 PM", 
    "tid": "57658"
  }
]```

The ID field is used to pull temperatures
