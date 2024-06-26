# RustPivot

This is a reverse socks proxy written in Rust,
the SOCKS5 code is largely implemented from the 
code from https://github.com/ajmwagar/merino.
References have been remove so as not to associate the original
oracle repo with what could effectively be used as malware.

This is the first iteration of a larger project for private use, placed here
for community reference, usage, etc, as I had not seen a reverse socks proxy
yet written in Rust. That said, unless there are some critical bugs,
I likely will not be updating this project.

Further information on building and using this tool can be found in each
component's respective README.md files. [server](server/README.md) and [client](client/README.md).  

Rustup/Cargo is required to build the component binaries, information for installing these can be located [here](https://www.rust-lang.org/tools/install).

Build binaries will be placed in `./target/release/` if `--release` is used during compilation or `./target/debug/` if `--release` was NOT used.
