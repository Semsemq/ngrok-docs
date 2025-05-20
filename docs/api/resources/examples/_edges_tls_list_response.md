<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-05-20T10:07:18Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2xM6Y0RfSRwS5KWTRBYNYfRfmyw",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2xM6Y0RfSRwS5KWTRBYNYfRfmyw"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2xM6WaepnbdWTKeJXC9isdMVwT4",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2xM6WaepnbdWTKeJXC9isdMVwT4"
        },
        "enabled": true
      },
      "created_at": "2025-05-20T10:07:07Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2xM6WZXRYrgxIiMjQkHEt7fWZIy",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2xM6WZXRYrgxIiMjQkHEt7fWZIy"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
