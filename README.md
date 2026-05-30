# CC-Prep Forge — ISC2 Certified in Cybersecurity Exam Prep

> Flashcard + quiz CLI tool for the ISC2 Certified in Cybersecurity (CC) exam.

## What it does

- **Flashcard mode** — flip through CC exam questions, self-rate your answers
- **Quiz mode** — multiple-choice rounds with immediate feedback
- **Progress tracking** — saves your study history
- **Domain-weighted questions** — matches the official CC exam outline

## Exam Domains

| Domain | Weight |
|--------|--------|
| Security Principles | 15% |
| Access Controls | 17% |
| Security Operations | 20% |
| Governance, Risk, and Compliance | 17% |
| Incident, Business Continuity, and Disaster Recovery | 15% |
| Network Security | 16% |

## Install


╔══════════════════════════════════════════════════════════════╗
║              🔥 CC-PREP FORGE 🔥                            ║
║      ISC2 Certified in Cybersecurity Exam Prep               ║
║      Built for El Matador — Sakamoto Nightly Build          ║
╚══════════════════════════════════════════════════════════════╝


What would you like to do?

  [1] 📖 Study Mode (Flashcards)
  [2] 🎯 Quiz Mode (10 Questions)
  [3] 📊 Progress Stats
  [4] 📋 Exam Domain Outline
  [5] 💾 Refresh Question Data

  [Q] Quit

Select: 
Goodbye, El Matador!

## Modes

### Flashcard Mode
```bash
python3 index.py
# Shows a question → you answer → press Enter to reveal → rate yourself
```

### Quiz Mode
```bash
python3 index.py quiz
# Multiple choice, 10 questions per round, domain-weighted selection
```

### Study by Domain
```bash
python3 index.py study "Access Controls"
```

## Progress

Progress is saved to `progress.json` in the same directory.

## Files



---
By Muhammad Aminu Musa
