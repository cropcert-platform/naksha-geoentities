# 📦 naksha-geoentities

> Geo-entities for the Naksha map component

![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg) ![Language](https://img.shields.io/badge/language-Java-ED8B00?logo=openjdk&logoColor=white) ![Part of](https://img.shields.io/badge/part%20of-CropCert%20Platform-2e7d32.svg)

## 🌱 Overview

The geo-entities module, a part of the Naksha map component used by the CropCert platform.

This repository is part of the [CropCert Platform](https://github.com/cropcert-platform), an open-source platform for crop certification and traceability that helps small growers add value to their crops and reach better markets.

## ✨ Features

- Geospatial entity definitions
- Java / Maven library

## 🚀 Getting started

### 📋 Prerequisites

- Java Development Kit (JDK) — see `pom.xml` for the required version
- [Apache Maven](https://maven.apache.org/) 3.x

### 🔧 Build & run

```bash
git clone https://github.com/cropcert-platform/naksha-geoentities.git
cd naksha-geoentities
mvn clean package
```

To use it from another module, install it into your local Maven repository:

```bash
mvn clean install
```

Then add it as a dependency using the `groupId`, `artifactId` and `version` defined in `pom.xml`.

## 📁 Project structure

```text
.
├── pom.xml          # Maven build definition
├── src/main         # Application source code
└── LICENSE
```

## 🔗 Related repositories

| Repository | Description |
|---|---|
| [cropcert-entities](https://github.com/cropcert-platform/cropcert-entities) | Shared entities used across CropCert services |
| [auth-utils](https://github.com/cropcert-platform/auth-utils) | Authentication and authorisation utilities |
| [cropcert-mail-utils](https://github.com/cropcert-platform/cropcert-mail-utils) | Shared utilities for the CropCert mail service |
| [naksha-api](https://github.com/cropcert-platform/naksha-api) | Naksha map component API |
| [naksha-integrator](https://github.com/cropcert-platform/naksha-integrator) | Naksha integration service |

See all repositories in the [cropcert-platform](https://github.com/cropcert-platform) organisation.

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-change`
3. Commit your changes with clear messages
4. Push the branch and open a pull request

For bugs and feature requests, please [open an issue](https://github.com/cropcert-platform/naksha-geoentities/issues).

## 📄 License

Distributed under the **Apache License 2.0**. See [`LICENSE`](LICENSE) for details.

## 🙏 Acknowledgements

This repository is a fork of [biodiv-platform/naksha-geoentities](https://github.com/biodiv-platform/naksha-geoentities) maintained for the CropCert platform. Thanks to the original authors and the [biodiv-platform](https://github.com/biodiv-platform) community.
