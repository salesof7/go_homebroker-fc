<p align="center">
  <a href=https://github.com/salesof7/go_homebroker-fc target="_blank">
    <img src='/placeholder.jpg' width="100%" alt="Banner" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/contributors/salesof7/go_homebroker-fc" alt="GitHub contributors" />
  <img src="https://img.shields.io/github/discussions/salesof7/go_homebroker-fc" alt="GitHub discussions" />
  <img src="https://img.shields.io/github/issues/salesof7/go_homebroker-fc" alt="GitHub issues" />
  <img src="https://img.shields.io/github/issues-pr/salesof7/go_homebroker-fc" alt="GitHub pull request" />
</p>

## 🔍 Table of Contents

- [🔍 Table of Contents](#-table-of-contents)
- [💻 Stack](#-stack)
- [📝 Project Summary](#-project-summary)
- [⚙️ Setting Up](#️-setting-up)
  - [Your Environment Variable](#your-environment-variable)
- [🚀 Run Locally](#-run-locally)
- [🙌 Contributors](#-contributors)
- [📄 License](#-license)

## 💻 Stack

- [confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go): Kafka client library for Go, used for data fetching and server-client communication.
- [uuid](https://github.com/google/uuid): Package for generating and working with UUIDs, used for generating unique identifiers for authentication or data management purposes.

## 📝 Project Summary

- [cmd](cmd): Entry point for the application.
- [internal](internal): Contains internal packages and components.
- [internal/infra](internal/infra): Infrastructure-related functionalities.
- [internal/infra/kafka](internal/infra/kafka): Kafka-related functionalities for infrastructure.
- [internal/market](internal/market): Market-related functionalities.
- [internal/market/dto](internal/market/dto): Data transfer objects for market entities.
- [internal/market/entity](internal/market/entity): Market entities and their business logic.
- [internal/market/transformer](internal/market/transformer): Transformation logic for market data.

## ⚙️ Setting Up

### Your Environment Variable

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

<table style="border:1px solid #404040;text-align:center;width:100%">
<tr><td style="width:14.29%;border:1px solid #404040;">
        <a href="https://github.com/salesof7" spellcheck="false">
          <img src="https://avatars.githubusercontent.com/u/84966204?v=4?s=100" width="100px;" alt="salesof7"/>
          <br />
          <b>salesof7</b>
        </a>
        <br />
        <a href="https://github.com/salesof7/go_homebroker-fc/commits?author=salesof7" title="Contributions" spellcheck="false">
          6 contributions
        </a>
      </td></table>

## 📄 License

[**Add Your License**](https://choosealicense.com)
