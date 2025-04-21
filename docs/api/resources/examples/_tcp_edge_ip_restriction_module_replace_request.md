<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2w2BwtxtM5CXZSRNddVZYTEyAtP"]}' \
https://api.ngrok.com/edges/tcp/edgtcp_2w2Bwtq5lW0uvXPOK3NCcma16Hz/ip_restriction
