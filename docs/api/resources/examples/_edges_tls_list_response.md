<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-09-08T10:08:06Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_32PdLcHgHx2LowzZSYgAQ3gjP6N",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_32PdLcHgHx2LowzZSYgAQ3gjP6N"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_32PdKGOVOYkiWuXN5i4BGKefust",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_32PdKGOVOYkiWuXN5i4BGKefust"
        },
        "enabled": true
      },
      "created_at": "2025-09-08T10:07:55Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_32PdKGNmhdXVx3rTHxJ7Jj4ESbw",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_32PdKGNmhdXVx3rTHxJ7Jj4ESbw"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
