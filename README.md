# Status
- Demo for stm33F4 Discovery Board
- debugging works from VSCode

# What is needed to get started
VSCode Extensions
  - rust-analyzer
  - Maybe "Debugger for probe-rs"
  - Maybe "CodeLLDB"

rustup target add thumbv7em-none-eabihf
cargo install cargo-binstall
cargo binstall probe-rs-tools

# Troubleshooting
List attached debug probes
> probe-rs list 
