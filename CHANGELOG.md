# Changelog

All notable changes to this deployment definition are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

## [0.0.1]

### Added

- Initial App-as-Code service definition for Watchtower, running the `containrrr/watchtower` image pinned to `amd64-0.3.5`.
- Docker socket bind mount so the container can inspect and update running containers.
- Environment defaults for time zone, cleanup of replaced images and polling interval.
- README with configuration reference and project icon.
