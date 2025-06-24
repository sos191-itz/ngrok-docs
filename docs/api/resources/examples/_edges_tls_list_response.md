<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-06-24T23:15:11Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2yyVgXZKcDRIMRuBduZWGCLcFEo",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2yyVgXZKcDRIMRuBduZWGCLcFEo"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2yyVfBrogZ3U60TfbadH1LSK66N",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2yyVfBrogZ3U60TfbadH1LSK66N"
        },
        "enabled": true
      },
      "created_at": "2025-06-24T23:15:00Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2yyVfAZaF0Zdjy7nXROcxljolL7",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2yyVfAZaF0Zdjy7nXROcxljolL7"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
