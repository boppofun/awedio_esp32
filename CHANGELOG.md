## [0.8.0] - 2025-12-14

### Features

- Preload samples when resuming audio channel
- [**breaking**] Update awedio to v0.6

## [0.7.0] - 2025-11-17

### Bug Fixes

- Report-render-time: reference Duration correctly

### Refactor

- Use iterator instead of index when filling buffer

## [0.6.0] - 2025-06-02

### Features

- [**breaking**] Update esp-idf-hal
- Update for esp-idf v5.4
- Add auto_disable_channel and on_channel_enable_change callback

### Documentation

- Update github org to boppofun

# Changelog

## Unreleased

Unreleased changes, if any, can be listed using `git log` or `git cliff -u`.


## [0.5.0] - 2024-05-29

### Features

- [**breaking**] Update to newest awedio allowing for custom BackendSource

### Documentation

- Minor README.md update


## [0.4.1] - 2023-12-15

### Bug Fixes

- Stack size was not being set properly

## [0.4.0] - 2023-12-08

- [**breaking**] update awedio to v0.3.1

## [0.3.0] - 2023-11-14

- refactor!: use thread spawn instead of creating a task
- feat!: update to ESP-IDF v5 and new I2S API in hal
- refactor!: do not set a default for num_frames_per_write
- fix: use new name of library in task name
- feat: make pinned_core_id public so Backend struct can be instantiated
- feat: add report-render-time cargo feature
- refactor: switch buffer from u8 to i16

## [0.2.0] - 2023-05-11

- add comment to rust-toolchain
- update README
- update awedio to v0.2

## [0.1.2] - 2023-05-10

- Add build-std to docs.rs metadata.

## [0.1.1] - 2023-05-10

- Add docs.rs metadata for targets.

## [0.1.0] - 2023-05-10

- Initial release
