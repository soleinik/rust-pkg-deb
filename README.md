# rust-deb-daemon primer

## host info
```
$ lsb_release -a
No LSB modules are available.
Distributor ID:	Ubuntu
Description:	Ubuntu 18.04.4 LTS
Release:	18.04
Codename:	bionic
```

![cargo-deb](https://crates.io/crates/cargo-deb)

## local cargo setup
```
$ cargo install cargo-deb
```

## cargo deb
```
$ cargo deb
warning: license field is missing in Cargo.toml
warning: README.md file exists, but is not specified in `readme` Cargo.toml field
   Compiling rust-deb-daemon v0.1.0 (/home/soleinik/work/rust/rust-pkg-deb)
    Finished release [optimized] target(s) in 0.20s
/home/soleinik/work/rust/rust-pkg-deb/target/debian/rust-deb-daemon_0.1.0_amd64.deb

$ tree target/debian/
target/debian/
└── rust-deb-daemon_0.1.0_amd64.deb

0 directories, 1 file


```

