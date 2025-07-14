<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-07-14T21:58:21Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2zsqoGtbzeiyJbJ1nwEsT5gtRaU",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2zsqoGtbzeiyJbJ1nwEsT5gtRaU"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2zsqmzoIzqnNxDs1jGGwG4NetlG",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2zsqmzoIzqnNxDs1jGGwG4NetlG"
        },
        "enabled": true
      },
      "created_at": "2025-07-14T21:58:10Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2zsqmyjr2u2HxWV0S1AjR5aqlPc",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2zsqmyjr2u2HxWV0S1AjR5aqlPc"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
