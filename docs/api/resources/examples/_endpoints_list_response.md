<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-02T10:05:30Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2zJYctZPCIOXHPVyB4CP2BcFhGY",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2zJYctZPCIOXHPVyB4CP2BcFhGY"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2zJYdYYlpszeIQ7vm8N1nPjqSL5",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-07-02T10:05:30Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2zJYdYYlpszeIQ7vm8N1nPjqSL5",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-02T10:05:28Z",
      "hostport": "ad080a7b7f50.ngrok.paid:443",
      "id": "ep_2zJYdHPv2y3rlX2ZKUn4mC7MaS8",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2zJYaoqEbzvDgXeML7UPJYfzqlI",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://ad080a7b7f50.ngrok.paid",
      "tunnel": {
        "id": "tn_2zJYdHPv2y3rlX2ZKUn4mC7MaS8",
        "uri": "https://api.ngrok.com/tunnels/tn_2zJYdHPv2y3rlX2ZKUn4mC7MaS8"
      },
      "tunnel_session": {
        "id": "ts_2zJYdKUBmg60tpKlkPegisChVgg",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2zJYdKUBmg60tpKlkPegisChVgg"
      },
      "type": "ephemeral",
      "updated_at": "2025-07-02T10:05:28Z",
      "upstream_url": "http://localhost:80",
      "url": "https://ad080a7b7f50.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-02T10:05:25Z",
      "domain": {
        "id": "rd_2zJYctZPCIOXHPVyB4CP2BcFhGY",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2zJYctZPCIOXHPVyB4CP2BcFhGY"
      },
      "edge": {
        "id": "edgtls_2zJYcseq53ELHszBcCwRLJqpnfX",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2zJYcseq53ELHszBcCwRLJqpnfX"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2zJYcwPKyxtYNJt1malQmXZ7DCU",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-07-02T10:05:25Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
