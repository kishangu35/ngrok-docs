<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-21T10:07:03Z",
      "description": "sample cloud endpoint",
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
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-21T10:07:00Z",
      "hostport": "a24e3cadc8e9.ngrok.paid:443",
      "id": "ep_2w2BvhfTZEkCE7UUtmjadvC616N",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2w2BtKQ0zPxbWALHvqJqk7iFVfN",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://a24e3cadc8e9.ngrok.paid",
      "tunnel": {
        "id": "tn_2w2BvhfTZEkCE7UUtmjadvC616N",
        "uri": "https://api.ngrok.com/tunnels/tn_2w2BvhfTZEkCE7UUtmjadvC616N"
      },
      "tunnel_session": {
        "id": "ts_2w2BviIGkXjB0wduWZkns4YHmOw",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2w2BviIGkXjB0wduWZkns4YHmOw"
      },
      "type": "ephemeral",
      "updated_at": "2025-04-21T10:07:00Z",
      "upstream_url": "http://localhost:80",
      "url": "https://a24e3cadc8e9.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-21T10:06:58Z",
      "domain": {
        "id": "rd_2w2BvWDXXA7KmmXxkB06Bci5YV3",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2w2BvWDXXA7KmmXxkB06Bci5YV3"
      },
      "edge": {
        "id": "edgtls_2w2BvSJtxlK2G5NZwRSfYvH8mW5",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2w2BvSJtxlK2G5NZwRSfYvH8mW5"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2w2BvUoIwGpnJlMfRUeZp2eiI1N",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-04-21T10:06:58Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
