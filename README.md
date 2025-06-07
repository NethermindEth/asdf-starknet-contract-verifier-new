# asdf-starknet-contract-verifier

Starknet Contract Verifier plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

## Installation

```bash
asdf plugin add starknet-contract-verifier https://github.com/NethermindEth/asdf-starknet-contract-verifier.git
```

## Usage

```bash
# List all available versions
asdf list-all starknet-contract-verifier

# Install a specific version
asdf install starknet-contract-verifier 1.0.0-rc.1

# Set a version globally
asdf global starknet-contract-verifier 1.0.0-rc.1

# Set a version locally
asdf local starknet-contract-verifier 1.0.0-rc.1
```

## Requirements

- Rust toolchain (rustc, cargo)
- Git
- Make

## License

MIT