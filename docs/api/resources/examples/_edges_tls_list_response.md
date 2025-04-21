<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-04-21T10:07:08Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2w2BwiQrgYPexAK5H0VWjpwbFMh",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2w2BwiQrgYPexAK5H0VWjpwbFMh"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2w2BvUW9XxC9tegLx9t47vGcde8",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2w2BvUW9XxC9tegLx9t47vGcde8"
        },
        "enabled": true
      },
      "created_at": "2025-04-21T10:06:58Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2w2BvSJtxlK2G5NZwRSfYvH8mW5",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2w2BvSJtxlK2G5NZwRSfYvH8mW5"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
