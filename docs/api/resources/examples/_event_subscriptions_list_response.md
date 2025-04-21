<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-04-21T10:07:04Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_2w2BwClox0ooUazoC8v3gwlKDxL",
          "uri": "https://api.ngrok.com/event_destinations/ed_2w2BwClox0ooUazoC8v3gwlKDxL"
        }
      ],
      "id": "esb_2w2BwGntRhQ8PIK5LIC6gSNicwL",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_2w2BwGntRhQ8PIK5LIC6gSNicwL/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_2w2BwGntRhQ8PIK5LIC6gSNicwL"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
