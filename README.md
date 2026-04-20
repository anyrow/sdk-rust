# Anyrow Rust SDK

[![MIT License](https://img.shields.io/badge/license-MIT-blue)](./LICENSE)

Rust client for the [Anyrow](https://anyrow.ai) API.

## Installation

```toml
[dependencies]
anyrow = "0"
```

## Quick start

```rust
use anyrow::AnyrowSDK;

fn main() {
    let client = AnyrowSDK::new("https://api.anyrow.ai")
        .with_header("Authorization", "Bearer YOUR_API_KEY");

    let _ = client;
}
```

## Resources

- [OpenAPI spec](https://anyrow.ai/openapi.json)
- [TypeScript SDK](https://github.com/anyrow/sdk-typescript)
- [Go SDK](https://github.com/anyrow/sdk-go)
- [Python SDK](https://github.com/anyrow/sdk-python)
- [CLI](https://github.com/anyrow/cli)

## License

MIT — see [LICENSE](./LICENSE).
