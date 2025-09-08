<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-09-08T10:08:02Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_32PdLAZIdjvfc83HLzlL6KrYNev",
          "uri": "https://api.ngrok.com/event_destinations/ed_32PdLAZIdjvfc83HLzlL6KrYNev"
        }
      ],
      "id": "esb_32PdLCAqZT9w86CKdZvqpZNqoeh",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_32PdLCAqZT9w86CKdZvqpZNqoeh/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_32PdLCAqZT9w86CKdZvqpZNqoeh"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
```
