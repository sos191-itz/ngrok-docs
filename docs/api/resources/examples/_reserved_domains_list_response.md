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
          "started_at": "2025-07-14T21:57:54Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.uylmuerycn3rhn9w.local-ngrok-cname.com",
      "created_at": "2025-07-14T21:57:54Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2zsqkuFsl167nX8VpgSDRrcMaml",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2zsqkuFsl167nX8VpgSDRrcMaml"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2zsqksqIc3CjcTbcL7JLFxzpmEb",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2zsqksqIc3CjcTbcL7JLFxzpmEb"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.uylmuerycn3rhn9w.local-ngrok-cname.com",
      "created_at": "2025-07-14T21:57:54Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2zsqkskKjE2uXHlncvCBMqlWfMu",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2zsqkskKjE2uXHlncvCBMqlWfMu"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-07-14T21:57:24Z",
      "description": "Your dev domain",
      "domain": "equipped-scarcely-elephant.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2zsqhDV9vDnCD6AmMGr45yNEMvm",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2zsqhDV9vDnCD6AmMGr45yNEMvm"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
