# Markovian Protocol

I run a public transparency log: an append-only record where anyone can verify that an entry exists, when it was added, and that its history was never rewritten. Checkpoints are cosigned by seven witnesses from six operators at a 4-of-7 quorum and anchored to Bitcoin, so verification does not depend on trusting the operator — including me.

I use it to offer one service: independent verification. Point me at an audit log, an AI system's records, or a published measurement, and I recompute what it claims from the raw bytes and report what holds and what doesn't.

**Work you can check:**

- [audit-anchor](https://github.com/MarkovianProtocol/audit-anchor) — anchor an existing audit log so a third party can confirm it hasn't been altered
- [canoncheck](https://github.com/MarkovianProtocol/canoncheck) — cross-language JSON canonicalization conformance (RFC 8785); used as the byte-identity reference in the AXES Golden Trace ruling
- [log-monitor](https://github.com/MarkovianProtocol/log-monitor) / [log-terminal-export](https://github.com/MarkovianProtocol/log-terminal-export) — standing verification of a live log, and what survives after a log shuts down
- [x402-second-measurement](https://github.com/MarkovianProtocol/x402-second-measurement) — independent 24-hour on-chain re-check of a published payment-volume measurement (arXiv 2607.12575)
- [otel-canonical-profile](https://github.com/MarkovianProtocol/otel-canonical-profile) — pinned canonical form + conformance vectors for OpenTelemetry spans

**External record:**

- Listed test witness on [witness-network.org](https://witness-network.org/witness-tables/)
- Production anchor data on the public record at [IETF SCITT](https://mailarchive.ietf.org/arch/msg/scitt/QflSmbFqRgo-TlrE7jXET0aJ4rw/) (518 Bitcoin anchors, 0 header mismatches)
- Contributions credited in [ethereum/ERCs #1808](https://github.com/ethereum/ERCs/pull/1808) (ERC-8004 validation); guidance PR open at [cdevents/spec #320](https://github.com/cdevents/spec/pull/320)

Contract and consulting inquiries: hello@markovianprotocol.com · [markovianprotocol.com](https://www.markovianprotocol.com)
