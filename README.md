# 👋 Hi, I'm Anton

Engineering Manager and Principal Software Engineer, focused on developer experience, platform engineering, and distributed systems.

Go practitioner for many years, building distributed systems, sometimes with Raft consensus. Kubernetes practitioner focused on cluster ops, multi-cloud, and security (cert-manager, PKI automation). Nowadays also writing production Rust. I've built closed-source platform systems and open-sourced pieces of them along the way.

By preference: Go, Rust, Kubernetes, CockroachDB, Redis, Terraform, and whatever cloud environment the problem actually needs.

## Projects

A few things I've built and some I kept maintaining too.

| Project | Stars | What it is |
| --- | --- | --- |
| [syndbg/onetui](https://github.com/syndbg/onetui) | ![stars](https://img.shields.io/github/stars/syndbg/onetui?style=flat&label=%E2%98%85) | My most recent Rust OSS project and my main focus. The goal is to be the only terminal UI you need to access any data source. If you know the DevEx of k9s, you'll get used to it in minutes. Easy viewing and management of PostgreSQL, Qdrant, Kafka/Redpanda, NATS, AWS DynamoDB and RabbitMQ. |
| [coredns/dynapi](https://github.com/coredns/dynapi) | ![stars](https://img.shields.io/github/stars/coredns/dynapi?style=flat&label=%E2%98%85) | A CoreDNS plugin with an authenticated HTTP API to read, replace and delete A and AAAA records. It started as a CoreDNS pull request in 2018, got its own repository in the CoreDNS org, and shipped v0.1.0 in 2026. |
| [hyperledger/fabric-x-migrate](https://github.com/hyperledger/fabric-x-migrate) | ![stars](https://img.shields.io/github/stars/hyperledger/fabric-x-migrate?style=flat&label=%E2%98%85) | The official Go CLI in the Hyperledger org for migrating a Fabric network to Fabric-X. It streams official peer snapshots into each organization's committer database and reuses source MSPs and endorsement policies. It started from an LFDT mentorship, based on my [snapshot migration RFC](https://github.com/syndbg/fabric-x-rfcs/blob/feat-fabric-snapshot-migration/0003-fabric-x-snapshot-migration.md). |
| [syndbg/zjyo](https://github.com/syndbg/zjyo) | ![stars](https://img.shields.io/github/stars/syndbg/zjyo?style=flat&label=%E2%98%85) | A Rust port of [rupa/z](https://github.com/rupa/z), same frecency algorithm and database format. The one I use every day to jump between directories. |
| [syndbg/goenv](https://github.com/syndbg/goenv) | ![stars](https://img.shields.io/github/stars/syndbg/goenv?style=flat&label=%E2%98%85) | A Go version manager, like pyenv or rbenv but for Go. 🎅 Created during a slow Christmas season in 2016, it grew into something I never imagined would be so useful to the Go community. My most-used project by other people. |
| [sumup-oss/gocat](https://github.com/sumup-oss/gocat) | ![stars](https://img.shields.io/github/stars/sumup-oss/gocat?style=flat&label=%E2%98%85) | Like `socat`, but in Go. A multipurpose relay for data transfer and monitoring. At SumUp we used it to proxy SSH traffic for Docker auth when `socat` was randomly hanging, in a build system with nearly a thousand apps to build. |
| [sumup-oss/vaulted](https://github.com/sumup-oss/vaulted) | ![stars](https://img.shields.io/github/stars/sumup-oss/vaulted?style=flat&label=%E2%98%85) | Encryption/decryption tool using AES256-GCM, for teams that need auditable secrets workflows. Enabled SumUp to shift-left on secret management. |
| [sumup-oss/terraform-provider-vaulted](https://github.com/sumup-oss/terraform-provider-vaulted) | ![stars](https://img.shields.io/github/stars/sumup-oss/terraform-provider-vaulted?style=flat&label=%E2%98%85) | A Terraform provider for storing vaulted secrets safely in source control. Also enables provisioning your HashiCorp Vault secrets. |
| [syndbg/terraform-provider-vaulted-null](https://github.com/syndbg/terraform-provider-vaulted-null) | ![stars](https://img.shields.io/github/stars/syndbg/terraform-provider-vaulted-null?style=flat&label=%E2%98%85) | Secure secrets for every SCM and every Terraform resource, without needing a running HashiCorp Vault backend. |
| [syndbg/webpack-google-cloud-storage-plugin](https://github.com/syndbg/webpack-google-cloud-storage-plugin) | ![stars](https://img.shields.io/github/stars/syndbg/webpack-google-cloud-storage-plugin?style=flat&label=%E2%98%85) | From when uploading Webpack assets to Google Cloud Storage wasn't supported out of the box. I don't know if that is still true. I haven't touched it in years, but it picked up traction on its own. |

## Contact

- GitHub: [github.com/syndbg](https://github.com/syndbg)
- Blog: [syndbg.github.io](https://syndbg.github.io/)
- LinkedIn: [linkedin.com/in/syndbg](https://www.linkedin.com/in/syndbg)
