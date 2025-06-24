<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-24T23:15:05Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2yyVf9WBlnE7KVi2G3l4G2eaGpY",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2yyVf9WBlnE7KVi2G3l4G2eaGpY"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2yyVfqehefOLZzHFxah1oPbCx5M",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-06-24T23:15:05Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2yyVfqehefOLZzHFxah1oPbCx5M",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-24T23:15:03Z",
      "hostport": "a1823ee4f359.ngrok.paid:443",
      "id": "ep_2yyVfXt5ErDC2m0ugq7ogf5hDjS",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2yyVd7mkmsnCxK0m9GFbjMMc4k1",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://a1823ee4f359.ngrok.paid",
      "tunnel": {
        "id": "tn_2yyVfXt5ErDC2m0ugq7ogf5hDjS",
        "uri": "https://api.ngrok.com/tunnels/tn_2yyVfXt5ErDC2m0ugq7ogf5hDjS"
      },
      "tunnel_session": {
        "id": "ts_2yyVfYlAyDtL9NK0nH75XrRJJ9Z",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2yyVfYlAyDtL9NK0nH75XrRJJ9Z"
      },
      "type": "ephemeral",
      "updated_at": "2025-06-24T23:15:03Z",
      "upstream_url": "http://localhost:80",
      "url": "https://a1823ee4f359.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-24T23:15:00Z",
      "domain": {
        "id": "rd_2yyVf9WBlnE7KVi2G3l4G2eaGpY",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2yyVf9WBlnE7KVi2G3l4G2eaGpY"
      },
      "edge": {
        "id": "edgtls_2yyVfAZaF0Zdjy7nXROcxljolL7",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2yyVfAZaF0Zdjy7nXROcxljolL7"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2yyVfAqLv0itvDlu2YHsk9KXUHF",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-06-24T23:15:00Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
