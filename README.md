# nutexb

> **Note**: This repository is forked from [@jam1garner/nutexb](https://github.com/jam1garner/nutexb) with additional PC nutexb format support.

A Rust library for working with namco nutexb textures commonly found in Smash Ultimate (among others).

Features  

* Supports reading/writing 2D textures, 3D textures, and cube maps for nutexb
* Deswizzling the nutexb image data
* Converting DDS files from the [ddsfile](https://crates.io/crates/) crate to and from nutexb
* Convert formats supported by [image-rs](https://github.com/image-rs/image) to nutexb
* **Enhanced PC nutexb format support**: Added support for PC-specific nutexb formats
* ```"46XT"``` prefix support**: Handles texture files with "46XT" prefixes used by games like:
  - Mobile Suit Gundam Extreme Vs 2 series
  - Taiko no Tatsujin (太鼓達人) series
  - For implementation details, see [lib.rs#L297](https://github.com/kjjkjjzyayufqza/nutexb/blob/18d0be4a64fb04cf166f70e7e733d14a0f8848cd/nutexb/src/lib.rs#L297)

Also check out [img2nutexb](https://github.com/jam1garner/img2nutexb) for command line usage.
