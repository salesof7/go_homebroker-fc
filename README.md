<p align="center">
<a href=https://github.com/salesof7/go_homebroker-fc target="_blank">
<img src='/placeholder.jpg' width="100%" alt="Banner" />
</a>
</p>



<p align="center">
<img src="https://img.shields.io/github/languages/code-size/salesof7/go_homebroker-fc" alt="GitHub code size in bytes" />
<img src="https://img.shields.io/github/last-commit/salesof7/go_homebroker-fc" alt="GitHub last commit" />
<img src="https://img.shields.io/github/commit-activity/m/salesof7/go_homebroker-fc" alt="GitHub commit activity month" />
<img src="https://img.shields.io/github/license/salesof7/go_homebroker-fc" alt="GitHub license" />
</p>

## 📌 Overview

go_homebroker-fc is a project that utilizes essential dependencies like confluent-kafka-gov1.9.2 and uuidv1.4.0.

## 🔍 Table of Contents

* [📁 Project Structure](#project-structure)

* [📝 Project Summary](#project-summary)

* [💻 Stack](#stack)

* [⚙️ Setting Up](#setting-up)

* [🚀 Run Locally](#run-locally)

* [🙌 Contributors](#contributors)

* [☁️ Deploy](#deploy)

* [📄 License](#license)

## 📁 Project Structure

```bash
├── .editorconfig
├── .gitignore
├── README.md
├── cmd
│   └── trade
│       └── main.go
├── docker-compose.yaml
├── go.mod
├── go.sum
└── internal
    ├── infra
    │   └── kafka
    │       ├── consumer.go
    │       └── producer.go
    └── market
        ├── dto
        │   └── dto.go
        ├── entity
        │   ├── asset.go
        │   ├── book.go
        │   ├── investor.go
        │   ├── order.go
        │   ├── order_queue.go
        │   └── transaction.go
        └── transformer
            └── transformer.go
```

## 📝 Project Summary

- [**cmd**](cmd): Contains main executable and entry point for the project.
- [**internal**](internal): Houses internal packages and modules for the project.
- [**internal/infra**](internal/infra): Implements infrastructure-related functionalities.
- [**internal/infra/kafka**](internal/infra/kafka): Handles Kafka integration and messaging.
- [**internal/market**](internal/market): Implements market-related functionalities.
- [**internal/market/dto**](internal/market/dto): Defines data transfer objects for market entities.
- [**internal/market/entity**](internal/market/entity): Defines market entities and their behavior.
- [**internal/market/transformer**](internal/market/transformer): Provides transformation utilities for market entities.
- [**cmd/trade**](cmd/trade): Implements trade-related functionalities.
- [**internal/market**](internal/market): Implements market-related functionalities.

## 💻 Stack

- [github.com/confluentinc/confluent-kafka-gov1.9.2](https://github.com/confluentinc/confluent-kafka-gov1.9.2): Kafka client for Go, used for data streaming and messaging.
- [github.com/google/uuidv1.4.0](https://github.com/google/uuidv1.4.0): Generates and manages universally unique identifiers (UUIDs) for authentication and data identification.

## ⚙️ Setting Up

#### Your Environment Variable

- No variables

## 🚀 Run Locally
1.Clone the go_homebroker-fc repository:
```sh
git clone https://github.com/salesof7/go_homebroker-fc
```
2.Install the dependencies with one of the package managers listed below:
```bash
go build cmd/trade/main.go
```
3.Start the development mode:
```bash
go run cmd/trade/main.go
```

## 🙌 Contributors
<a href="https://github.com/salesof7/go_homebroker-fc/graphs/contributors">
<img src="https://contrib.rocks/image?repo=salesof7/go_homebroker-fc" />
</a>

## ☁️ Deploy

`[Application name](Your App URL)`

## 📄 License

[**Add Your License**](https://choosealicense.com)

