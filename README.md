# rust-qt-ceasar

## Source

https://dev.to/logrocket/build-a-desktop-app-with-qt-and-rust-1cfi
https://blog.logrocket.com/build-desktop-app-qt-rust/
https://github.com/azzamsa/learn/tree/master/src/caesars/desktop/qt

## Install prerequisites

### Install Rust

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

### Install dependencies

Minimal Ubuntu
```sh
sudo apt install qt6-base-dev qt6-declarative-dev
```

All Qt6 libs for Ubuntu
```sh
sudo apt install qt6*
```

Minimal Fedora
```sh
sudo dnf install qt6-qtbase-devel qt6-qtdeclarative-devel
```

All Qt6 libs for Fedora
```sh
sudo dnf install qt6*
```

## Building and running

`cargo c` is an alias to `cargo check`
```sh
cargo c
```

Run the application
```sh
cargo --quiet r
```
