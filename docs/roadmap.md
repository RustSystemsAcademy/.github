# Rust Systems Academy — Roadmap

This roadmap outlines the strategic direction for the Academy’s open-source materials and training curriculum.

---

## 1. Foundations (Beginner → Intermediate)
- Complete beginner-friendly Rust lessons
- Memory model (stack, heap, ownership, borrowing)
- Practical CLI utilities
- Error handling patterns
- Module and crate architecture
- Testing, benchmarking, and documentation

---

## 2. Systems Programming Track
- OS fundamentals in Rust
- File systems, processes, scheduling
- Memory mapping, unsafe code, FFI
- Sandboxing: seccomp, namespaces, capabilities
- Container internals (Podman, runc)
- Embedded systems foundations

---

## 3. Concurrency & Distributed Systems Track
- Threads, channels, Atomics, Mutex/RwLock
- Async foundations (Tokio, async-std)
- Zero-copy and mmap design
- High-performance IPC (shared memory, lock-free)
- Networking: QUIC, gRPC, custom protocols
- Distributed job orchestration and peer-to-peer systems

---

## 4. Applied Rust Projects
- CLI tools
- Simulation framework demos
- Parsing engines (binary and textual)
- High-performance data pipelines
- Dashboard + backend combinations (eGUI, WASM, Bevy)

---

## 5. GraphML + Rust (new emerging domain)
- Rust + Graph Machine Learning examples
- Data pipeline: ingest → graph store → ML pipeline
- Applied example: **Stock Correlation Graph ML**

---

## 6. Rust Education Platform
- Full book series:
  - *Rust eGUI Programming*
  - *Graphics, Games, and Simulation in Rust*
  - *Systems Programming Deep Dives*
  - *Async Rust Mastery*
  - *Advanced Concurrency Models*
- Each book hosted within the organization under separate repos

---

## 7. Long-Term Vision
- Well-organized GitHub organization containing:
  - Training paths
  - Books
  - Example systems implementations
  - Reference architectures
  - Security guides
- A unified website (possibly GitHub Pages) linking all learning materials.

---

## Contribution Workflow (High-Level)
- Conventional commits
- Keep a Changelog
- Automated CI + formatting + lint + security scanning
- Rust workspace templates for new repos
