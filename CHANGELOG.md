# Changelog

All notable changes to the homebridge-eufy-security-e340 plugin will be documented in this file.

## [4.3.10] - 2025-10-03

### Added
- Enhanced plugin metadata for better Homebridge directory discovery
- Improved package.json with standardized fields
- Additional README badges for better visibility

### Fixed
- Plugin directory discoverability issues

## [4.3.9] - 2025-10-03

### Added
- Node.js 24.9.0+ native PKCS1 support detection
- Smart configuration recommendations based on environment
- Enhanced error messages for better troubleshooting
- Updated configuration UI with version information
- Comprehensive config.schema.json for better UI integration

### Fixed
- E340 doorbell "No Response" issues in Apple Home
- Livestream timeout errors on Node.js 24.9.0+ with OpenSSL 3.5.2+
- Automatic detection of native vs embedded PKCS1 support
- Improved error handling for missing OpenSSL versions

### Changed
- Updated repository URLs to point to fork
- Enhanced README with fork-specific information
- Improved package metadata for npm discoverability

## [4.3.8] - 2025-10-03

### Fixed
- Initial release preparation
- Package configuration improvements

## [4.3.7] - 2025-10-03

### Added
- Initial fork release
- Node.js 24.x compatibility fixes

You can find the complete detailled changelog for every release [here](https://github.com/homebridge-eufy-security/plugin/releases).

Before transitioning to a major version, it's strongly advised to back up your configuration and begin anew. Major updates have the potential to disrupt automation setups and bridge/unbridge accessory functionalities.