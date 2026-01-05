# Fairbrix-Core-Wallet-V2.5.0
Fairbrix Core Wallet v2.5.0 is the official full-node-wallet implementation for the Fairbrix (FBX) Scrypt blockchain. It enhances peer discovery and network stability through protocol version enforcement, without modifying consensus, mining, or monetary rules. GUI and CLI supported.
## Overview
Fairbrix Core Wallet v2.5.0 

This release focuses on network-level improvements, including stricter protocol version enforcement and improved peer compatibility, while preserving full consensus and mining compatibility.

## Key Features
- Full node (validates blocks and transactions independently)
- GUI wallet (Qt) and CLI daemon
- Improved peer discovery and network stability
- Enforced minimum peer protocol version
- No changes to consensus rules or Scrypt mining

## What Changed in v2.5.0
- Hard-disconnects peers advertising protocol versions below `MIN_PEER_PROTO_VERSION`
- Improves outbound peer compatibility without requiring WITNESS / MWEB support
- No changes to block format, mining, or monetary policy

## Compatibility
- Blockchain: Fairbrix (FBX)
- Mining algorithm: Scrypt
- Backwards-compatible with existing chain data

## Disclaimer
This software is provided as-is, without warranty.  
Users are responsible for verifying binaries and safeguarding private keys.
