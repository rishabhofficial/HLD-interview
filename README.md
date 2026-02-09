# High-Level Design (HLD) Interview Prep

A collection of system design documents for interview preparation. Each topic is organized in its own directory with comprehensive documentation, diagrams, and quick revision notes.

## 📚 Topics

| Topic | Difficulty | Key Concepts |
|-------|------------|--------------|
| [Payment System](./payment-system/README.md) | Hard | Idempotency, Event Sourcing, CDC, Financial Integrity |

## 🗂️ Repository Structure

```
hld/
├── README.md                    # This index file
├── payment-system/              # Payment processing system design
│   └── README.md
├── [future-topic]/              # Future system designs
│   └── README.md
```

## 📖 How to Use

1. Each topic folder contains a comprehensive `README.md`
2. Diagrams are embedded as Mermaid (viewable on GitHub)
3. Quick revision sections at the end of each doc
4. Capacity estimations included for scale discussions

## 🎯 Interview Levels

Each document includes expectations for:
- **Mid-level**: Core functionality, basic security awareness
- **Senior**: Drive conversation, identify edge cases, propose robust solutions
- **Staff+**: Deep expertise, product thinking, handle complex trade-offs
