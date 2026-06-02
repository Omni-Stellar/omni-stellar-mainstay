# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-06-02

### Added

- **Asset Registry Contract**: Foundation contract for registering industrial assets with unique on-chain identities
- **Engineer Verification System**: Federated credentialing system for certified maintenance engineers
- **Lifecycle Tracking**: Soroban-based lifecycle contracts that track full asset maintenance history
- **Maintenance Event Signing**: Cryptographic signing and submission of maintenance records by verified engineers
- **Collateral Scoring System**: On-chain health scoring derived from verified maintenance completeness
- **DeFi Integration**: Support for using verified assets as collateral in Stellar-based lending protocols
- **Cross-platform Testing**: Comprehensive test suite with Windows PowerShell and Unix shell support
- **Emergency Pause Mechanism**: Administrative controls for emergency contract pausing
- **Loan Deadline Enforcement**: Time-based loan management with deadline tracking
- **TTL (Time-to-Live) Strategy**: Configurable asset lifecycle management based on time parameters
- **Lending Features**: Core lending functionality including loan issuance and collateral management
- **Voucher History Tracking**: Historical records for voucher-based asset operations
- **Admin Transfer Capabilities**: Privileged operations for administrative asset transfers
- **Full E2E Testing**: End-to-end integration tests covering complete user workflows

### Documentation

- Comprehensive architecture documentation
- Access control model documentation
- Collateral scoring methodology
- TTL (Time-to-Live) strategy guide
- Credentialing system overview
- Deployment runbook for testnet
- Audit report documentation
- Contributing guidelines
- Security policy

### Infrastructure

- CI/CD pipeline with automated testing
- Code quality checks (Clippy, rustfmt)
- Security scanning (cargo audit)
- Build and deployment scripts
- Cross-platform support (Windows PowerShell, Unix)

### Technical Details

- **Language**: Rust
- **Blockchain**: Stellar/Soroban
- **Minimum Rust Version**: 1.70+
- **Smart Contracts**: Multiple specialized contracts (Asset, Asset-Registry, Engineer-Registry, Lending, Lifecycle, Shared)
