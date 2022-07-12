# Custom images for Rust Cross

Container images to be used with [Rust cross](https://github.com/cross-rs/cross).

Currently included:

- Build dependencies for the [dbus](https://docs.rs/dbus/latest/dbus/) crate:
    * `dbus-aarch64-gnu` (`aarch64-unknown-linux-gnu`)
    * `dbus-armv7-gnu` (`armv7-unknown-linux-gnueabihf`)
    * `dbus-armv7-musl` (`armv7-unknown-linux-musleabihf`)

## CHANGELOG

## 1.1.1 / _Not released yet_


## 1.1.0 / 2022-05-29

- Add `dbus-aarch64-gnu`.
- Use base images from `ghcr.io/cross-rs/` instead of Docker Hub. Pin to the latest "main" until a stable release has been tagged.

## 1.0.0 / 2022-02-20

- First versions of `dbus-arm-gnu` and `dbus-arm-musl`.
