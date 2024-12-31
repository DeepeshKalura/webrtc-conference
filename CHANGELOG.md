# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - 2025-12-30

### Added
- Screen sharing options with configurable quality settings
- Support for VP8, H264, VP9, and AV1 codecs
- 4K screen sharing capability
- E2E encryption support for media streams

### Changed
- Updated all dependencies to latest versions
- Improved room handling with separate AwaitQueue per room
- Enhanced simulcast configuration with separate webcam and sharing streams

### Fixed
- Fixed absCaptureTime header extension compatibility issues
- Resolved DataChannel connectivity issues

## [0.9.0] - 2025-12-15

### Added
- TypeScript rewrite of server for better type safety
- New API server architecture with improved error handling
- PipeTransports support for multi-router setup

### Changed
- Migrated server to TypeScript
- Updated mediasoup to 3.19.x series
- Improved queue handling for consumer requests

## [0.8.0] - 2025-11-30

### Added
- Node.js broadcaster support
- Enhanced terminal connection for debugging
- Throttling support via sitespeed.io

### Changed
- Updated mediasoup-client to latest version
- Improved build configuration

## [0.7.0] - 2025-11-15

### Added
- Initial project setup
- WebRTC video conferencing with mediasoup SFU
- React-based client application
- Vite build system
- Face detection feature (optional)
- Consumer replicas for testing

### Features
- Multi-participant video calls
- Audio/video muting controls  
- Screen sharing
- DataChannels for messaging
- Responsive UI design
