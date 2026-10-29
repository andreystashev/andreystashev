# Project guide

A guide to my public repositories, grouped by what you can explore or run. Each project's README is the starting point for setup, dependencies, validation, and current limitations.

## Applications and backend services

| Repository | What to explore | Scope and starting point |
| --- | --- | --- |
| [Scenario Runner](https://github.com/andreystashev/scenario-runner) | A browser dashboard for reusable Bash workflows, workspace variables, and process tracking. | Local application for macOS/Linux with optional Docker execution. Start with the [usage guide](https://github.com/andreystashev/scenario-runner/blob/main/docs/usage.md). |
| [Sensor Data Manager](https://github.com/andreystashev/sensor-data-manager) | S3/MinIO dataset browsing, category downloads, Parquet trimming, and metadata recovery. | FastAPI/React application with a synthetic Docker demo. Read the [data format](https://github.com/andreystashev/sensor-data-manager/blob/main/docs/data-format.md); demo JSON payloads are not playable ROS2 CDR recordings. |
| [Trading Robot](https://github.com/andreystashev/trading-robot) | Backtests, paper trading, and T-Invest Sandbox execution experiments. | Research application with live trading disabled. See the [architecture](https://github.com/andreystashev/trading-robot/blob/main/docs/architecture.md) and [usage guide](https://github.com/andreystashev/trading-robot/blob/main/docs/usage.md). Detailed guides are in Russian. |
| [Video Language Manager](https://github.com/andreystashev/video-language-manager) | Media downloads and English vocabulary extraction with IPA pronunciation and Russian translations. | Tkinter prototype using Whisper, FFmpeg, and external translation services. |
| [Dialogue Service API](https://github.com/andreystashev/dialogue-service-api) | JWT authentication, queued jobs, and request history. | FastAPI coursework using Celery, Redis, and PostgreSQL, with a local joke implementation. Explore the [OpenAPI snapshot](https://github.com/andreystashev/dialogue-service-api/blob/main/openapi.yaml). |

## Desktop and embedded device communication

| Repository | Focus | Scope |
| --- | --- | --- |
| [Device Control Hub](https://github.com/andreystashev/device-control-hub) | TCP, UDP, and serial telemetry; charts, maps, recording, and playback. | C++/Qt integration prototype requiring compatible devices and custom packets. |
| [Serial Port Commander](https://github.com/andreystashev/serial-port-commander) | Send file-management commands and inspect binary device replies. | Qt prototype using a custom serial protocol; requires matching firmware. |
| [SSH XML Manager](https://github.com/andreystashev/ssh-xml-manager) | Download, inspect, compare, and update remote XML configuration files. | Qt prototype using OpenSSH SCP; connection settings are configured in source. |
| [UDP Transmission](https://github.com/andreystashev/udp-transmission) | A console sender and desktop telemetry receiver. | Qt networking example with a native-memory packet layout, requiring compatible sender/receiver builds. |
| [STM32 Card Logger](https://github.com/andreystashev/stm32-card-logger) | Log framed UART commands to an SD card using SPI and FatFs. | STM32F103C8T6 firmware prototype; board wiring, toolchain setup, and physical validation are required. |

## Research and coursework

| Repository | Contents | Context |
| --- | --- | --- |
| [Local Estimates Lighting](https://github.com/andreystashev/local-estimates-lighting) | Illumination experiments, numerical comparisons, denoising, and a thesis report. | Master's thesis prototypes in Python, C++, and MATLAB. Numerical models and rendering backends have separate assumptions and dependencies. |
| [Big Data Applied Problems](https://github.com/andreystashev/big-data-applied-problems) | Boyer–Moore string search in Scala. | MISIS algorithm coursework. |
| [Data Storage Systems](https://github.com/andreystashev/data-storage-systems) | Data-platform design report and Kubernetes examples. | MISIS architecture coursework; example manifests do not constitute a complete deployable application. |
| [Databases and SQL](https://github.com/andreystashev/databases-and-sql) | A relational database project, report, sample data, and PostgreSQL dump. | MISIS coursework; follow the repository's restore instructions and distinguish the dump from historical SQL notes. |

## Games and VR releases

| Repository | What is public | Status |
| --- | --- | --- |
| [Hitman: Blood Money VR](https://github.com/andreystashev/hitman-blood-money-vr-showcase) | Installers, setup instructions, controls, and support information. | Experimental alpha. See [releases](https://github.com/andreystashev/hitman-blood-money-vr-showcase/releases) and [installation](https://github.com/andreystashev/hitman-blood-money-vr-showcase/blob/main/INSTALLATION.md). |
| [Hitman: Contracts VR](https://github.com/andreystashev/hitman-contracts-vr-showcase) | Installers, setup instructions, controls, and support information. | Experimental review releases. See [releases](https://github.com/andreystashev/hitman-contracts-vr-showcase/releases) and [controls](https://github.com/andreystashev/hitman-contracts-vr-showcase/blob/main/CONTROLS.md). |
| [Hitman 2: Silent Assassin VR](https://github.com/andreystashev/hitman-2-silent-assassin-vr-showcase) | Installers, setup instructions, controls, and support information. | Experimental alpha preview. See [releases](https://github.com/andreystashev/hitman-2-silent-assassin-vr-showcase/releases) and [known issues](https://github.com/andreystashev/hitman-2-silent-assassin-vr-showcase/blob/main/KNOWN-ISSUES.md). |
| [Honor in Law](https://github.com/andreystashev/honor-in-law) | Editable Ren'Py scripts and assets for a Russian-language visual novel with three genre-parody chapters. | Source project; no verified packaged release or current engine compatibility. |

The VR showcase repositories publish binaries and user documentation, not implementation source. Their release pages contain the current versions and compatibility notes. Each adaptation requires the corresponding original game.

[Back to profile](README.md)
