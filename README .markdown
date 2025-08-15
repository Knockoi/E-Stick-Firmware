# E-Stick Firmware

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Status](https://img.shields.io/badge/status-in%20development-orange.svg)](https://github.com/Knockoi/E-Stick-Firmware)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.1%20adopted-ff69b4.svg)](CODE_OF_CONDUCT.md)

## Overview

The E-Stick Firmware repository contains the software powering E-Stick, an innovative presentation pen built on the Nordic Semiconductor platform. Designed for educators and presenters, E-Stick enables intuitive, lightweight interactions in classrooms and professional settings, freeing users from the constraints of traditional presentation tools. This firmware drives E-Stick’s advanced features, such as customizable interaction modes and peripheral integrations, ensuring a seamless and human-centered experience.

Inspired by my elementary school teacher, whose passion for teaching sparked this project, the E-Stick firmware is crafted to enhance classroom engagement through intuitive controls and interactive capabilities, while remaining versatile for all presenters. The firmware is under active development, and we welcome contributions to shape its evolution into a robust, user-focused solution.

## Firmware Features

The E-Stick firmware supports the following core interaction modes and peripheral functionalities, all customizable to adapt to various use cases:

### Core Interaction Modes

- **Key-Pad Control**: Manages a dual-button interface where left and right keys can be programmed for tasks like slide navigation or triggering custom tools.
- **Slider Control**: Implements a side-mounted slider that dynamically adjusts scroll speed based on swipe velocity. The slider also supports button-like functionality for custom actions.
- **Radial-Stick Control**: Enables a radial menu system where tilting to specific angles selects functions. Supports customizable angles and multiple configuration profiles (e.g., teaching or presentation modes) for quick switching.
- **Home-Tap Control**: Handles single-tap actions to revert to the previous step or activate features like Spotlight or a virtual magnifying glass.

### Peripheral Support

1. **X-Axis Vibration Feedback**: Drives configurable timed vibrations for tactile feedback and user cues.
2. **Dual-Channel Audio Recording**: Manages high-quality audio capture with advanced noise reduction (switchable to mono). Supports advanced use cases, such as using the built-in microphone as a backup presentation mic.
3. **Physical Laser Pointer**: Controls precise pointing for content emphasis.
4. **AR Integration & Indoor Positioning**: Implements support for augmented reality (AR) applications and indoor positioning for immersive interactions.
5. **Light-Bar**: Manages a color-coded status indicator, with advanced customization for pairing colors with timers to aid presentation segment management or rehearsal memory.
6. **Gyroscope Integration**: Processes data from the built-in gyroscope to enable intuitive, motion-based control with high precision.

### Technical Specifications

- **Platform**: Nordic Semiconductor SoC, leveraging its low-power and high-performance capabilities.
- **Wireless Protocols**: Supports Bluetooth Low Energy 6.0, Bluetooth Mesh, Zigbee, Thread, Matter, Amazon Sidewalk, and a proprietary 2.4 GHz protocol for robust connectivity.
- **Report Rate**: Achieves an industry-leading 8000 Hz for ultra-responsive performance, minimizing latency in user interactions.
- **Power Management**: Optimizes for up to 48 hours of high-intensity use and 3 years in sleep mode (limited by ~2-year battery self-discharge).

## Project Status

The E-Stick firmware is in active development, with ongoing work on:
- Refining interaction mode logic for smoother user experiences.
- Implementing profile-based customization for teaching and presentation scenarios.
- Integrating advanced peripheral features, such as AR support and audio processing.
- Developing a companion app to enhance configuration and user interaction.

## Getting Started

To explore or contribute to the E-Stick firmware:
1. Clone the repository: `git clone https://github.com/Knockoi/E-Stick-Firmware.git`
2. Ensure you have the necessary development environment for Nordic Semiconductor platforms (e.g., nRF Connect SDK).
3. Check the [issues](https://github.com/Knockoi/E-Stick-Firmware/issues) for open tasks and feature requests.
4. Follow the [contributing guidelines](CONTRIBUTING.md) to submit code or ideas.

### Prerequisites

- **Development Tools**: nRF Connect SDK, GCC, or compatible toolchain for compiling firmware.
- **Hardware**: E-Stick device or a compatible Nordic Semiconductor development kit for testing.
- **Dependencies**: Refer to the project’s `requirements.txt` or documentation for specific libraries and tools.

## Contributing

We welcome contributions to make E-Stick’s firmware the ultimate lightweight, intuitive solution for presenters. To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

See our [contributing guidelines](CONTRIBUTING.md) for detailed instructions.

## Community

Join the conversation to shape E-Stick’s firmware:
- Share feedback or ideas in the [discussions](https://github.com/Knockoi/E-Stick-Firmware/discussions).
- Collaborate on app development or firmware enhancements by contacting us at [knockoi@example.com](mailto:knockoi@example.com).

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

E-Stick is dedicated to my elementary school teacher, whose passion for education inspired this project, ensuring intuitive tools empower teaching and engagement.

*Crafted with passion for intuitive, human-centered design.*