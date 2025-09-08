<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-08T10:08:00Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_32PdKI9GWAkoL5qgIT85HywC3i2",
        "uri": "https://api.ngrok.com/reserved_domains/rd_32PdKI9GWAkoL5qgIT85HywC3i2"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_32PdKuW5zW4ry64ZCYEAanOkD5z",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-09-08T10:08:00Z",
      "uri": "https://api.ngrok.com/endpoints/ep_32PdKuW5zW4ry64ZCYEAanOkD5z",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-08T10:07:58Z",
      "hostport": "1049ebf6eecf.ngrok.paid:443",
      "id": "ep_32PdKeCKfMYXXriSOWRkbPOvpGK",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_32PdE5WDrw7D2kV4fvSBJTI9oDZ",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://1049ebf6eecf.ngrok.paid",
      "tunnel": {
        "id": "tn_32PdKeCKfMYXXriSOWRkbPOvpGK",
        "uri": "https://api.ngrok.com/tunnels/tn_32PdKeCKfMYXXriSOWRkbPOvpGK"
      },
      "tunnel_session": {
        "id": "ts_32PdKcw9D8xQbnex1SmWBduYQ5C",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_32PdKcw9D8xQbnex1SmWBduYQ5C"
      },
      "type": "ephemeral",
      "updated_at": "2025-09-08T10:07:58Z",
      "upstream_url": "http://localhost:80",
      "url": "https://1049ebf6eecf.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-08T10:07:55Z",
      "domain": {
        "id": "rd_32PdKI9GWAkoL5qgIT85HywC3i2",
        "uri": "https://api.ngrok.com/reserved_domains/rd_32PdKI9GWAkoL5qgIT85HywC3i2"
      },
      "edge": {
        "id": "edgtls_32PdKGNmhdXVx3rTHxJ7Jj4ESbw",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_32PdKGNmhdXVx3rTHxJ7Jj4ESbw"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_32PdKFB4xHqTzLT0D9xb5INunEE",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-09-08T10:07:55Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
