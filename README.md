# blog_os

Install xbuild
```
cargo install cargo-xbuild
```

Add rust-src, needed to compile core library
```
rustup component add rust-src
```

Install bootimage crate
```
cargo install bootimage --version "^0.7.7"
```

Required by bootimage
```
rustup component add llvm-tools-preview
```

Install qemu

Run the OS on qemu
```
cargo xrun
```
