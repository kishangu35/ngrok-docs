<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "bindings": [
    "public"
  ],
  "created_at": "2025-04-21T10:07:03Z",
  "description": "Sample Cloud Endpoint",
  "domain": {
    "id": "rd_2w2BvWDXXA7KmmXxkB06Bci5YV3",
    "uri": "https://api.ngrok.com/reserved_domains/rd_2w2BvWDXXA7KmmXxkB06Bci5YV3"
  },
  "hostport": "endpoint-example2.com:443",
  "id": "ep_2w2Bw9lFjQCmS9wT0FssIeqhO5b",
  "metadata": "{\"environment\": \"staging\"}",
  "pooling_enabled": false,
  "proto": "https",
  "public_url": "https://endpoint-example2.com",
  "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
  "type": "cloud",
  "updated_at": "2025-04-21T10:07:03Z",
  "uri": "https://api.ngrok.com/endpoints/ep_2w2Bw9lFjQCmS9wT0FssIeqhO5b",
  "url": "https://endpoint-example2.com"
}
