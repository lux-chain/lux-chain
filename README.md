# Lux-Chain Protocol 🜁

> “Vibration organizes. Magnetism positions. Consciousness binds. Matter obeys.”

**Non-custodial protocol for peer-to-peer value exchange.**  
Lux-Chain defines a minimum standard for two parties to exchange value  
**without intermediaries, without custody, and without permission.**

---

## 📌 Overview

Lux-Chain is a **coordination standard**, not an application.

It describes a simple state machine for value exchange:

```
PENDING → LOCKED → RELEASED | REFUNDED → CLOSED
```

No token.  
No company.  
No identity system.  
No admin keys.  
No treasury to capture.

Only **clarity + cryptography + time**.

---

## ✨ Core Principles

- **Non-custodial:** no third party ever holds funds  
- **Permissionless:** nobody decides who may exchange  
- **Fork-friendly:** derivative versions are valid forever  
- **Minimal proof:** hash, timestamp, chain — nothing personal  

Lux-Chain is to **value exchange** what TCP/IP is to **messages**.

---

## 🧬 Technical Foundation

- Hash: **SHA-256** (LPIP-0002)
- TimeLock default: **72 hours** (LPIP-0003)
- Optional privacy: **zk-proofs** (LPIP-0004)
- Recommended clients: JS, Python, Go, Rust, Java (LPIP-0005)

Specification is defined in:

- `RFC-0001.md`
- `LPIP` folder (Lux Protocol Improvement Proposals)

---

## 🌀 Hybrid Thesis

Lux-Chain is grounded in two simultaneous layers:

- **Technical:** proofs, signatures, timeout, state machines  
- **Vibrational:** sovereignty, mutual responsibility, transparency  

> “Proof replaces belief. Time replaces authority.”

Full context in:  
📄 `THESIS.md` (English)  
📄 `THESIS-es.md` (Español)

---

## 🚀 Quick Start

Lux-Chain is a **specification**, not software.  
But you can implement it in any language.

Example pseudocode:

```js
lux.connect(A, B)
lux.lock(amount, timeout)
lux.release()
lux.refund()
lux.proof()
```

Clients SHOULD store a final `proof` object:

```json
{
  "tx": "0xHASH",
  "state": "CLOSED",
  "proof": "SHA256(...data)",
  "timestamp": 1700000000,
  "chain": "ANY"
}
```

---

## 🧰 Contributing

Lux-Chain uses **LPIP** (Lux Protocol Improvement Proposal).

To propose changes:

1. Open an Issue  
2. Create a file in `/LPIP/`  
3. Follow structure from `LPIP-0001.md`

> Clarity, simplicity, no custody, no permission.

---

## 🪬 Eternal Clauses

Lux-Chain will NEVER accept proposals that:

- Introduce custody  
- Require permission to exchange  
- Restrict forks  

This is enforced by **LPIP-0001.md**.

---

## 📝 License

MIT — free, perpetual, irrevocable, fork-friendly.

---

## 🪩 Origin

Created **02 December 2025 — Colombia (-05:00)**  
Repository: https://github.com/lux-chain/lux-chain

> “Freedom is structure without chains.”
