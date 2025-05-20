<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-05-20T10:06:51Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.3zg6m22gkdr9pqlgh.local-ngrok-cname.com",
      "created_at": "2025-05-20T10:06:51Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2xM6UXvqCvw297znUrutNQYWqiV",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2xM6UXvqCvw297znUrutNQYWqiV"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2xM6UYENc1H4Kfjmu3O0NP8jD9K",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2xM6UYENc1H4Kfjmu3O0NP8jD9K"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.3zg6m22gkdr9pqlgh.local-ngrok-cname.com",
      "created_at": "2025-05-20T10:06:51Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2xM6UbtWJsTjatBOXW9VORZr9Xi",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2xM6UbtWJsTjatBOXW9VORZr9Xi"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
