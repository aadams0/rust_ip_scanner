# Rust IP Scanner

## An IP scanner written with only the Rust Standard Library

### Usage

There isn't much to this thing. Run the application to see the ports being utilized on your network:

```text
cargo run -- -j <threads> <IPv4/IPv6>
```

An example of the expected output:

```text
........
88 is open
5000 is open
5900 is open
7000 is open
49152 is open
55110 is open
55169 is open
57621 is open
```
