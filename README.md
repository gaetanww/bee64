# bee64

One-line base64 standard encoding and decoding.
Thin-wrapper over [base64](https://crates.io/crates/base64) to enable you to write

```rust
let b64_encoded = bee64::endode(&vec![1; 42]);
let b64_decoded = bee64::decode(&b64_encoded).unwrap();
```