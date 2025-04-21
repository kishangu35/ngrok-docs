<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2w2BwsFmRU55g6brxJ7Gc2kOjs5","ipp_2w2Bwruah5DyXoDbaZUXvFjRYOW"]}' \
https://api.ngrok.com/edges/tls/edgtls_2w2BwnqWSJmWZU1cFqrYyBb3q4P/ip_restriction
