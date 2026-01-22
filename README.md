## Overview

This repository documents the methodology behind audit-ready,
reproducible on-chain accounting reports for crypto treasuries.

The goal is simple:
to produce financial reports where every number is traceable,
defensible, and reproducible directly from on-chain data.

This is not a dashboard or analytics tool.
It is reporting infrastructure designed for real financial responsibility.

## Methodology

All reports are generated using deterministic, versioned calculation rules.

Core principles:
- Transaction-level traceability (every figure links to a tx hash)
- Timestamp-based USD valuation
- Fixed rules for decimals, rounding, and missing data
- Identical inputs always produce identical outputs

Each report is tagged with a specific calculation methodology version
(e.g. Calculation Method v0.1).

## Supported Chains

The methodology currently supports the following EVM-compatible chains:

- Ethereum (Layer 1)
- Polygon
- Arbitrum
- Optimism

All chains are processed using the same calculation engine
and identical reporting rules.

## Scope & Limitations

This methodology is designed to produce clean, defensible accounting data.
It explicitly does NOT:

- Provide tax advice
- Interpret accounting standards or regulations
- Replace auditors, accountants, or compliance professionals
- Offer real-time monitoring or dashboards

It is intended to support professionals by reducing reconciliation
and audit preparation friction.

## Reproducibility Statement

All figures generated using this methodology are reproducible
from public on-chain data using the stated rules and data sources.

Given the same inputs, independent parties should be able
to reproduce identical results.

## Contact

For reporting inquiries or methodology questions:

Twitter: @Marco314878
Email: marco.smile08@outlook.com
