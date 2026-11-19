# Factory Firmware

[中文](./README_ZH.md)

| File | Purpose |
| --- | --- |
| [ESP32-S3-LCD-1.28_FactoryOnly_20250909.bin](ESP32-S3-LCD-1.28_FactoryOnly_20250909.bin) | Factory recovery firmware dated 2025-09-09. Flash from `0x0`. |

Before flashing:

- Back up device-specific data that must be preserved.
- Confirm the board model and hardware revision.
- Follow the offset and flashing procedure in the product documentation for this image. Do not infer the factory image from a source build.
- Do not mix this image with a bootloader or partition file built for another project.

This image was verified on the corresponding product with Flash Download Tool. SHA-256: `BB390D0D68BCC129D12B6D6692500BF6001E482C2827C48E53168AC7007A5075`.

See the [firmware guide](https://github.com/waveshareteam/esp32-repo-template/blob/main/docs/spec.md) for the difference between factory firmware and source-build firmware.

## Update the Factory Image

Replacing a factory binary is a development operation. Record its source, expected hardware revision, flashing procedure, checksum, and user-visible version in the Pull Request. Never overwrite an existing image with an unrelated local build.
