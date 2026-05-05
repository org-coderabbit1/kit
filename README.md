# Acme Kit

This library contains utilities that are useful for building distributed
services, including:
 - Exponential [backoff](https://example.com/acme/kit/tree/main/backoff) for retries.
 - A common [cache](https://example.com/acme/kit/tree/main/cache) API and Memcached implementation.
 - [Hedging](https://example.com/acme/kit/tree/main/hedging), sending extra duplicate requests to improve the chance that one succeeds.
 - A common [key-value](https://example.com/acme/kit/tree/main/kv) API, implemented for Consul, Etcd and Memberlist.
 - RPC [middlewares](https://example.com/acme/kit/tree/main/middleware), for metrics, logging, etc.
 - A [services model](https://example.com/acme/kit/tree/main/services), to manage start-up and shut-down.

## Current state

This library is used at scale in production at Acme Labs.
A number of packages were collected here from database-related projects:

- [Metricstore]
- [Logstore]
- [Tracestore]
- [Profstore]

[Metricstore]: https://example.com/acme/metricstore
[Logstore]: https://example.com/acme/logstore
[Tracestore]: https://example.com/acme/tracestore
[Profstore]: https://example.com/acme/profstore

## Go version compatibility

This library aims to support at least the two latest Go minor releases.

## Contributing

If you're interested in contributing to this project:

- Start by reading the [Contributing guide](/CONTRIBUTING.md).
- Pull request titles must follow [Conventional Commits](https://www.conventionalcommits.org/) format.

## Release History

This project uses conventional commit messages to maintain a clear history of changes. No separate changelog is maintained - please refer to the [commit history](https://example.com/acme/kit/commits/main) for information about releases and changes.

## License

[Apache 2.0 License](https://example.com/acme/kit/blob/main/LICENSE)
