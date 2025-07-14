<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-14T21:58:15Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2zsqmyBIsjtTZVHMm3pM9HfUBmN",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2zsqmyBIsjtTZVHMm3pM9HfUBmN"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2zsqnX7KuA6K8eAw60QhRxJ9N5X",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-07-14T21:58:15Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2zsqnX7KuA6K8eAw60QhRxJ9N5X",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-14T21:58:13Z",
      "hostport": "77da09720c7d.ngrok.paid:443",
      "id": "ep_2zsqnL7Ade2RMnwKHwdRMgqlTdL",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2zsqh9CNYNtcVaVOSB8unGDrVPY",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://77da09720c7d.ngrok.paid",
      "tunnel": {
        "id": "tn_2zsqnL7Ade2RMnwKHwdRMgqlTdL",
        "uri": "https://api.ngrok.com/tunnels/tn_2zsqnL7Ade2RMnwKHwdRMgqlTdL"
      },
      "tunnel_session": {
        "id": "ts_2zsqnH8mfTY198mFvF0FWoOqrgP",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2zsqnH8mfTY198mFvF0FWoOqrgP"
      },
      "type": "ephemeral",
      "updated_at": "2025-07-14T21:58:13Z",
      "upstream_url": "http://localhost:80",
      "url": "https://77da09720c7d.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-14T21:58:10Z",
      "domain": {
        "id": "rd_2zsqmyBIsjtTZVHMm3pM9HfUBmN",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2zsqmyBIsjtTZVHMm3pM9HfUBmN"
      },
      "edge": {
        "id": "edgtls_2zsqmyjr2u2HxWV0S1AjR5aqlPc",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2zsqmyjr2u2HxWV0S1AjR5aqlPc"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2zsqmzbeXaVa68GICdJyJ59CZpa",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-07-14T21:58:10Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
