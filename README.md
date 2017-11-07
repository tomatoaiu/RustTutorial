# RustTutorial

install rust
```
brew install rust
```

create project
```
mkdir hoge
cd hoge
mkdir src
touch src/main.rs
touch Cargo.toml
```

main.rs
```
fn main(){
    println!("hoge");
}
```

Cargo.toml
```
[package]

name = "hello_world"
version = "0.0.1"
authors = ["hoge fuga <admin@admin.com>"]
```

result
```
cargo build
cargo run
```
