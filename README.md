# semver_constraints

...because I don't like `semver::VersionReq`.

## Usage

Add this to your `Cargo.toml`:

``` toml
[dependencies]
# ...snip
# you'll probably want to use versions if you're using version
# constraints
semver = "0.9" 
# the actual constraints library
semver_constraints = "0.1"
# if you want to use serde:
# semver_constraints = { version = "0.1", features = ["serde"] }
```

See the crate docs for motivation and info on the API.

## License

semver_constraints is distributed under the [MIT License](./LICENSE).
