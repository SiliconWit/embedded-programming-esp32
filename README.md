---
title: "Embedded Programming ESP32 - Collaboration Guide"
description: "Contributing guide for Embedded Programming ESP32 course content"
tableOfContents: true
sidebar:
  order: 999
---

# Embedded Programming ESP32

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Contributors Welcome](https://img.shields.io/badge/contributors-welcome-orange)

**Read this course at:** [https://siliconwit.com/education/embedded-programming-esp32/](https://siliconwit.com/education/embedded-programming-esp32/)

A course on ESP32 development using the ESP-IDF framework. Lessons cover Wi-Fi, HTTP, MQTT, BLE, OTA updates, and power management, building toward a connected sensor network project.

## Lessons

| # | Title |
|---|-------|
| 1 | ESP-IDF and Dual-Core Architecture |
| 2 | GPIO Peripherals and Drivers |
| 3 | Wi-Fi and Network Configuration |
| 4 | HTTP Server and REST API |
| 5 | MQTT and Cloud Communication |
| 6 | Bluetooth Low Energy BLE |
| 7 | OTA Updates and Secure Boot |
| 8 | Power Management and Deep Sleep |
| 9 | Connected Sensor Network |

## File Structure

```
embedded-programming-esp32/
├── lesson-0.mdx        # Course introduction
├── lesson-1.mdx        # ESP-IDF and Dual-Core Architecture
├── lesson-2.mdx        # GPIO Peripherals and Drivers
├── lesson-3.mdx        # Wi-Fi and Network Configuration
├── lesson-4.mdx        # HTTP Server and REST API
├── lesson-5.mdx        # MQTT and Cloud Communication
├── lesson-6.mdx        # Bluetooth Low Energy BLE
├── lesson-7.mdx        # OTA Updates and Secure Boot
├── lesson-8.mdx        # Power Management and Deep Sleep
├── lesson-9.mdx        # Connected Sensor Network
└── README.md
```

## How to Contribute

1. Fork the repository: [SiliconWit/embedded-programming-esp32](https://github.com/SiliconWit/embedded-programming-esp32)
2. Create a feature branch: `git checkout -b feature/your-topic`
3. Make your changes and commit with a clear message
4. Push to your fork and open a Pull Request against `main`
5. Describe what you changed and why in the PR description

## Content Standards

- All lesson files use `.mdx` format
- Do not use `<BionicText>` in this course
- Code blocks should include a title attribute:
  ````mdx
  ```c title="wifi_connect.c"
  esp_wifi_start();
  ```
  ````
- Use Starlight components (`<Tabs>`, `<TabItem>`, `<Steps>`, `<Card>`) where appropriate
- Keep paragraphs concise and focused on practical application
- Include working code examples that readers can compile and flash

## Local Development

Clone the main site repository and initialize submodules:

```bash
git clone --recurse-submodules <main-repo-url>
cd siliconwit-com
npm install
npm run dev
```

To test a production build:

```bash
npm run build
```

## License

This course content is released under the [MIT License](LICENSE).
