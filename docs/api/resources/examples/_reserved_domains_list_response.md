<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2yyVdDXW7yLKj632CE2h1Bldt8Q",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2yyVdDXW7yLKj632CE2h1Bldt8Q"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.5oto8hfrhy3rbmtk9.local-ngrok-cname.com",
      "created_at": "2025-06-24T23:14:44Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2yyVdDEdDWKge3HAfjtIvVjc6F8",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2yyVdDEdDWKge3HAfjtIvVjc6F8"
    },
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
          "started_at": "2025-06-24T23:14:44Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.5oto8hfrhy3rbmtk9.local-ngrok-cname.com",
      "created_at": "2025-06-24T23:14:44Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2yyVd89rO8bbs8n2o7o00m6osSW",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2yyVd89rO8bbs8n2o7o00m6osSW"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
