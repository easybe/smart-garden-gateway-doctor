
# GARDENA Smart Gateway Boot Analyzer

Run the tool (for development):
```
cargo run
```

Create a release:
```
tag="v$(sed -nE 's/^version = "([^"]+)"/\1/p' Cargo.toml)"
git tag $tag
git push origin $tag
```
