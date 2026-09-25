# omni-stellar-omni-stellar-mainstay Rust SDK

`omni-stellar-mainstay-sdk` is the official typed Rust facade for the omni-stellar-omni-stellar-mainstay Asset
Registry Soroban contract. It wraps the generated contract client and keeps
application code independent of generated-client details.

```rust
use omni-stellar-mainstay_sdk::{omni-stellar-omni-stellar-mainstayClient, SearchFilter};

let client = omni-stellar-omni-stellar-mainstayClient::new(&env, &asset_registry_id);
let page = client.search_assets(&SearchFilter {
    asset_type: None,
    manufacturer: None,
    min_age_months: None,
    max_age_months: None,
    sort: None,
    lifecycle_contract: None,
});
println!("{} matching assets", page.total);
```

The crate is included in the workspace, so it can be tested with
`cargo test -p omni-stellar-mainstay-sdk`.
