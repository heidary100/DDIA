# Designing Data-Intensive Applications (2nd Edition) — Systems Architecture Playbook

Welcome to my personal knowledge base and architectural reference guide for building reliable, scalable, and maintainable distributed systems. This repository contains deep-dive technical notes, mental models, structural trade-offs, and active-recall interview prep based on Kleppmann's *Designing Data-Intensive Applications (2nd Edition)*.

## 🎯 The System Design Philosophy
Engineering is the discipline of managing trade-offs. There are rarely "correct" answers—only choices that favor certain constraints (e.g., latency, throughput, consistency) over others. This repository acts as a live playbook to help me navigate those choices when designing production systems.

## 🗂️ Knowledge Map

| Chapter | Title | Status | Deep Dive Notes |
| :---: | :--- | :---: | :--- |
| **01** | Trade-Offs in Data Systems Architecture | 🔄 In Progress | [Notes](./chapters/01-data-systems-tradeoffs.md) |
| **02** | *Coming Soon* | ⏳ Pending | - |

---

## 🛠️ Active-Recall Review System

This repository is optimized for spaced repetition and interview preparation. 

* **The Production Checklist:** Look for the `## How This System Breaks` sections in the notes to understand failure modes (network partitions, disk bottlenecks, race conditions).
* **Self-Testing:** The system design questions within each chapter utilize Markdown accordions. Try to answer the question mentally *before* expanding the solution block to enforce retrieval effort.

---
*“If you can't explain the under-the-hood trade-offs of an architectural pattern, you don't own the knowledge; you've just rented the buzzword.”*
