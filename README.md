```zsh
cargo new [project's name] --bin
```

모듈을 -> 크레이트 라고 부른다.

기존 프로젝트에 cargo를 사용하고 싶다면.
src/main.rs 만들고 Cargo.toml 파일을 만들어 주면된다.

```zsh
cargo build // 빌드한다.
```

빌드 결과물은 target에 생긴다 실행방법은
Cargo.lock은 Cargo가 관리 하는 파일로 신경쓸 일이 없다.

```zsh
./target/debug/hello_cargo
```

한 번에 빌드와 실행을 같이하려면?

```zsh
cargo run // 한 방이면 된다.
```

실행파일을 생성하지는 않고 빌드가 잘 되는지 체크만 할 수 있다.

```zsh
cargo check
```

릴리즈 버전 빌드

```zsh
cargo build --release
```
