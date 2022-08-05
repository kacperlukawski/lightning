# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/).

## [0.6.0] - 2022-MM-DD

### Added

- Add support for `Lightning App Commands` through the `configure_commands` hook on the Lightning Flow and the `ClientCommand`  ([#13602](https://github.com/Lightning-AI/lightning/pull/13602))
- Add support for Lightning AI BYOC cluster management ([#13835](https://github.com/Lightning-AI/lightning/pull/13835))
- Add support to run Lightning apps on Lightning AI BYOC clusters ([#13894](https://github.com/Lightning-AI/lightning/pull/13894))
- Adds `LightningTrainingComponent`. `LightningTrainingComponent` orchestrates multi-node training in the cloud ([#13830](https://github.com/Lightning-AI/lightning/pull/13830))

### Changed

- Update the Lightning App docs ([#13537](https://github.com/Lightning-AI/lightning/pull/13537))

### Changed

- Added `LIGHTNING_` prefix to Platform AWS credentials ([#13703](https://github.com/Lightning-AI/lightning/pull/13703))

### Deprecated

### Fixed

- Resolved a bug where the work statuses will grow quickly and be duplicated ([#13970](https://github.com/Lightning-AI/lightning/pull/13970))
