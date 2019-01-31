## HTTP Full proxy example

This proxy forwards all types of requests, including ones with body, to another HTTP server,
returning the response to the client.

To start:

``` shell
cargo run <listen addr> <listen port> <forward addr> <forward port>
```

## References:

* https://docs.aws.amazon.com/elasticloadbalancing/latest/application/listener-authenticate-users.html#user-claims-encoding
