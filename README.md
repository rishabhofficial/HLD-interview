# High-Level Design (HLD) Interview Prep

A collection of system design documents for interview preparation. Each topic is organized in its own directory with comprehensive documentation, diagrams, and quick revision notes.

## 📚 Topics

| Topic | Difficulty | Key Concepts | Quick Revision |
|-------|------------|--------------|----------------|
| [Payment System](./payment-system/README.md) | Hard | Idempotency, Event Sourcing, CDC, Financial Integrity | [⚡ Cheatsheet](./payment-system/CHEATSHEET.md) |
| [Rate Limiter](./rate-limiter/README.md) | Medium-Hard | Token Bucket, Redis Sharding, Lua Scripts, Fail-Closed | [⚡ Cheatsheet](./rate-limiter/CHEATSHEET.md) |
| [Ad Click Aggregator](./ad-click-aggregator/README.md) | Hard | Stream Processing, Kafka, Flink, Reconciliation, Hot Shards | [⚡ Cheatsheet](./ad-click-aggregator/CHEATSHEET.md) |
| [Web Crawler](./web-crawler/README.md) | Hard | Multi-stage Pipeline, robots.txt, DNS Caching, Crawler Traps | [⚡ Cheatsheet](./web-crawler/CHEATSHEET.md) |

## 🗂️ Repository Structure

```
hld/
├── README.md                    # This index file
├── payment-system/
│   ├── README.md                # Full detailed design
│   └── CHEATSHEET.md            # 5-min quick revision
├── rate-limiter/
│   ├── README.md
│   └── CHEATSHEET.md
├── ad-click-aggregator/
│   ├── README.md
│   └── CHEATSHEET.md
├── web-crawler/
│   ├── README.md
│   └── CHEATSHEET.md
└── [future-topic]/
    ├── README.md
    └── CHEATSHEET.md
```

## 📖 How to Use

1. **Full Study**: Read the comprehensive `README.md` for each topic
2. **Quick Revision**: Use `CHEATSHEET.md` for 5-minute pre-interview refresh
3. **Diagrams**: Embedded as Mermaid (viewable on GitHub)
4. **Good vs Bad**: Each cheatsheet shows recommended vs anti-patterns

## 🎯 Interview Levels

Each document includes expectations for:
- **Mid-level**: Core functionality, basic security awareness
- **Senior**: Drive conversation, identify edge cases, propose robust solutions
- **Staff+**: Deep expertise, product thinking, handle complex trade-offs
