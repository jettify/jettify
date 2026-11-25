# uflight

Making Rust fly.

These open-source embedded Rust libraries cover sensor fusion, telemetry, motor control, board support, and logging for flight controllers, FPV hardware, and robotics.

### Attitude and sensing

| Project | Features | Links |
| --- | --- | --- |
| [uf-ahrs](https://github.com/jettify/uf-ahrs) | Mahony, Madgwick, and VQF sensor fusion behind one API, with accuracy benchmarks on the BROAD dataset. | [Crate](https://crates.io/crates/uf-ahrs) · [API](https://docs.rs/uf-ahrs) |
| [uf-dps3xx](https://github.com/jettify/uf-dps3xx) | DPS310 and DPS368 pressure and temperature driver with blocking and async I²C support. | [Crate](https://crates.io/crates/uf-dps3xx) · [API](https://docs.rs/uf-dps3xx) |

### Protocols and control

| Project | Features | Links |
| --- | --- | --- |
| [uf-crsf](https://github.com/jettify/uf-crsf) | Raw and typed Crossfire packets for RC channels and telemetry on TBS Crossfire and ExpressLRS links. | [Crate](https://crates.io/crates/uf-crsf) · [API](https://docs.rs/uf-crsf) |
| [uf-msp](https://github.com/jettify/uf-msp) | MultiWii Serial Protocol v1 and v2 with zero-copy parsing for contiguous frames and typed requests and responses. | [Crate](https://crates.io/crates/uf-msp) · [API](https://docs.rs/uf-msp/latest/uf_msp/) |
| [uf-dshot](https://github.com/jettify/uf-dshot) | DShot motor commands and bidirectional telemetry, with optional Embassy STM32 support. | [Crate](https://crates.io/crates/uf-dshot) · [API](https://docs.rs/uf-dshot) |
| [smartaudio](https://github.com/jettify/smartaudio) | TBS SmartAudio 1.0, 2.0, and 2.1 for FPV video transmitters. | [Crate](https://crates.io/crates/smartaudio) · [API](https://docs.rs/smartaudio) |

### Board support, display, and logging

| Project | Features | Links |
| --- | --- | --- |
| [uf-bsp](https://github.com/jettify/uf-bsp) | Embassy board support for the TBS Lucid H7 and SpeedyBee F405 V4, including pin mappings, clock presets, and peripheral setup. | [Board crates](https://github.com/jettify/uf-bsp#uf-bsp) |
| [uf-max7456](https://github.com/jettify/uf-max7456) | Platform-agnostic driver for MAX7456 and AT7456E analog on-screen displays. | [Crate](https://crates.io/crates/uf-max7456) · [API](https://docs.rs/uf-max7456) |
| [uf-ulog](https://github.com/jettify/uf-ulog) | Allocator-free PX4 ULog export with derive macros and optional async output. | [Crate](https://crates.io/crates/uf-ulog) · [API](https://docs.rs/uf-ulog) |
