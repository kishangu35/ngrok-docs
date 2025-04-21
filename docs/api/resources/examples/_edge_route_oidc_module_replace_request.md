<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"client_id":"some-client-id","client_secret":"some-client-secret","enabled":true,"issuer":"https://accounts.google.com","scopes":["profile"]}' \
https://api.ngrok.com/edges/https/edghts_2w2BwRe7CbEGLOy0Iy5RRzBbDSe/routes/edghtsrt_2w2BwUhi9OiTMmcDJ9KxhGbJV1s/oidc
