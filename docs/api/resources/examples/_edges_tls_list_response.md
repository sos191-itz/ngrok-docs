<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-07-02T10:05:35Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2zJYeA4qhqPEaa2H64bhKmVg8rg",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2zJYeA4qhqPEaa2H64bhKmVg8rg"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2zJYcwkMPQ1yfNVVLwfaXZV7C6h",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2zJYcwkMPQ1yfNVVLwfaXZV7C6h"
        },
        "enabled": true
      },
      "created_at": "2025-07-02T10:05:25Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2zJYcseq53ELHszBcCwRLJqpnfX",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2zJYcseq53ELHszBcCwRLJqpnfX"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
