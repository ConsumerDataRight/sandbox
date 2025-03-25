# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [3.0.0] -  2025-03-26
### Fixed
- Fixed issue where Data Recipient could not access TLS resource APIs

### Added
- Added ability to update Dynamic Client Registrations from Data Recipient UI

### Removed
- Removed all OIDC Hybrid Flow related code and functionality
- Removed ID Token Decryption from Data Recipient Utilities

## [2.2.0] -  2025-02-20
### Changed
- Updated TLS cipher suite requirements to comply with CDS standards v1.32.0

## [2.1.0] -  2024-09-12
### Changed
- Updated TLS cipher suite requirements to comply with CDS standards v1.31.0

## [2.0.0] - 2024-06-12
### Changed
- Migrated from .NET 6 to .NET 8
- Upgraded Azure Kubernetes (AKS) version and renewed Sandbox certificates

## [1.0.0] - 2022-07-22
### Added
- First release of the CDR Sandbox GitHub repository
