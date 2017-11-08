# RustTutorial

## install rust
```sh
brew install rust
```

## create project
```sh
mkdir hoge
cd hoge
mkdir src
touch src/main.rs
touch Cargo.toml
```

## main.rs
```rust
fn main(){
    println!("hoge");
}
```

## Cargo.toml
```toml
[package]

name = "hello_world"
version = "0.0.1"
authors = ["hoge fuga <admin@admin.com>"]
```

## result
```sh
cargo build
cargo run
```
