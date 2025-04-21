<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"add":{"x-frontend":"ngrok"},"enabled":true,"remove":["cache-control"]}' \
https://api.ngrok.com/edges/https/edghts_2w2BwcnqScvRCxs8vJJb38mnTDz/routes/edghtsrt_2w2BwcGd9DZqmHYBQ3OmTyyHn0C/request_headers
