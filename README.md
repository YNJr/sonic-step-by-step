# sonic-step-by-step
# SONiC Step by Step

This repository records my step-by-step learning notes on SONiC.

The focus is not only how to use SONiC, but also how SONiC is designed internally, including its architecture, Redis-based communication model, orchagent, SAI, netlink, packet I/O, and ASIC adaptation.

## Learning Goals

- Understand the overall architecture of SONiC
- Understand how configuration flows from management plane to ASIC
- Understand the role of Redis DBs in SONiC
- Understand orchagent and its internal design
- Understand SAI and ASIC adaptation
- Understand netlink usage in SONiC
- Understand packet I/O, hostif, trap, CoPP and Linux protocol stack interaction

## Document Index

### 0. Learning Roadmap

- [00-learning-roadmap](docs/00-learning-roadmap.md)

### 1. Architecture

- [01-sonic-architecture-overview](docs/01-sonic-architecture-overview.md)

### 2. Redis and Configuration Flow

- [02-redis-db-and-config-flow](docs/02-redis-db-and-config-flow.md)

### 3. orchagent

- [03-orchagent-basic-framework](docs/03-orchagent-basic-framework.md)

### 4. SAI and ASIC Adaptation

- [04-sai-and-asic-adaptation](docs/04-sai-and-asic-adaptation.md)

### 5. Netlink

- [05-netlink-in-sonic](docs/05-netlink-in-sonic.md)

### 6. Packet I/O

- [06-packet-io-and-hostif](docs/06-packet-io-and-hostif.md)

### 99. Questions and Notes

- [99-questions-and-notes](docs/99-questions-and-notes.md)

## References

- [references](references.md)
