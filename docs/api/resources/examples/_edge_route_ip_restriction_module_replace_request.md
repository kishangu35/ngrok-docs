<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2w2BwTlSOwaeKWKf8aYBZCSDQnI","ipp_2w2BwTFMqp7x71cMSOmM0cElMK8"]}' \
https://api.ngrok.com/edges/https/edghts_2w2BwSYOxGfLt5Tl8c8n8cFbfrZ/routes/edghtsrt_2w2BwX4JhzleRtn86EzKMaa2gSs/ip_restriction
