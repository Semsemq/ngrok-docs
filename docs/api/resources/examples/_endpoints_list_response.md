<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-20T10:07:12Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2xM6WYIU8d7iKVi150BuXUlx89e",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2xM6WYIU8d7iKVi150BuXUlx89e"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2xM6XBap4iZ0EYEAuXaOLpCPQer",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-05-20T10:07:12Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2xM6XBap4iZ0EYEAuXaOLpCPQer",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-20T10:07:10Z",
      "hostport": "6610be3ca8aa.ngrok.paid:443",
      "id": "ep_2xM6Wy37YVH5xsrvlTd4z67JZzj",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2xM6UVwlrdlq8o0394qovcafyqY",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://6610be3ca8aa.ngrok.paid",
      "tunnel": {
        "id": "tn_2xM6Wy37YVH5xsrvlTd4z67JZzj",
        "uri": "https://api.ngrok.com/tunnels/tn_2xM6Wy37YVH5xsrvlTd4z67JZzj"
      },
      "tunnel_session": {
        "id": "ts_2xM6WzWwAIgOlx7ZRX1rztoIhkP",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2xM6WzWwAIgOlx7ZRX1rztoIhkP"
      },
      "type": "ephemeral",
      "updated_at": "2025-05-20T10:07:10Z",
      "upstream_url": "http://localhost:80",
      "url": "https://6610be3ca8aa.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-20T10:07:07Z",
      "domain": {
        "id": "rd_2xM6WYIU8d7iKVi150BuXUlx89e",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2xM6WYIU8d7iKVi150BuXUlx89e"
      },
      "edge": {
        "id": "edgtls_2xM6WZXRYrgxIiMjQkHEt7fWZIy",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2xM6WZXRYrgxIiMjQkHEt7fWZIy"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2xM6Wec5tyT5sjzJdiAxfs9GyQh",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-05-20T10:07:07Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
