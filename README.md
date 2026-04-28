# Data Sample for All Kafka Topics

This repository contains sample data for all Bitquery Kafka streaming topics.

The production Kafka stream data is encoded using **Protocol Buffers (Protobuf)**.  
For readability and easier inspection, the samples in this repository are shared as **JSON**.

## Kafka Streaming Documentation

Learn more about Bitquery Kafka streaming concepts here:

[Bitquery Kafka Streaming Concepts](https://docs.bitquery.io/docs/streams/kafka-streaming-concepts/)

## Structure

Samples are grouped by blockchain or data category:

- `evm/` — Ethereum/EVM-related topics
- `solana/` — Solana-related topics
- `tron/` — Tron-related topics
- `utxo/` — UTXO-based chain topics
- Root-level files — shared market/trading sample topics

## Usage

Use these JSON files to understand the structure, fields, and example payloads for each Kafka topic before consuming the corresponding Protobuf messages from the live Kafka stream.
