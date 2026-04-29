 <p align="center">
    <img src="docs/header.png" alt="defguard">
 </p>

[Protocol buffers](https://github.com/protocolbuffers/protobuf) service definitions used for internal [gRPC](https://grpc.io/) communication between [defguard](https://github.com/DefGuard/defguard) services.

## Documentation

See the [documentation](https://defguard.gitbook.io) for more information about the system.

## Buf CLI

This repository uses [Buf](https://buf.build/) to validate the protobuf module layout and schema quality across the versioned snapshots in `v1/`, `v2/`, `enterprise/v1/`, and `enterprise/v2/`. Imports are repo-root-relative.

- `buf build` — verify that the module and imports resolve correctly.
- `buf lint` — run the repository's Buf lint rules.
- `buf format -w` — format .proto files.

## Community and Support

Reach out to our community via [GitHub Discussions](https://github.com/DefGuard/defguard/discussions/new/choose)

## Contribution

Please review the [Contributing guide](https://defguard.gitbook.io/defguard/for-developers/contributing) for information on how to get started contributing to the project. You might also find our [environment setup guide](https://defguard.gitbook.io/defguard/for-developers/dev-env-setup) handy.

# Legal

WireGuard is [registered trademarks](https://www.wireguard.com/trademark-policy/) of Jason A. Donenfeld.
