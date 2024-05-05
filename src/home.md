# Home

Edlang is an experimental statically-typed compiled programming language made with LLVM and Rust.

Syntax is subject to change any time right now. It has a rusty style for now.

This project is early in development and a work in progress.

```rust
pub fn main() -> i32 {
    let b: i32 = factorial(4);
    return b;
}

pub fn factorial(n: i32) -> i32 {
    if n == 1 {
        return n;
    } else {
        return n * factorial(n - 1);
    }
}

mod hello {
  pub fn world(ptr: *const u8) -> u8 {
    return *ptr;
  }
}
```

## Source code

Repository: [edg-l/edlang](https://github.com/edg-l/edlang)

Releases: [on github](https://github.com/edg-l/edlang/releases)

[Cargo docs](https://edg-l.github.io/edlang/edb/index.html)
