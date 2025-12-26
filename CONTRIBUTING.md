# Contributing to Open-Wheel Racing Manager Sim Engine

Thank you for your interest in contributing to the **Open-Wheel Racing Manager Sim Engine**.  
This project aims to build a deep, realistic, and extensible open-wheel motorsport management simulation.

Contributions of all kinds are welcome, including code, documentation, testing, ideas, and discussions.

---

## 📋 Code of Conduct

By participating in this project, you agree to abide by the
[Contributor Covenant Code of Conduct](./CODE_OF_CONDUCT.md).

Please report unacceptable behavior as described in that document.

---

## 🧠 Project Philosophy

This project prioritizes:

- Data-driven simulation
- Deterministic and reproducible results
- Clear separation between **data**, **simulation logic**, and **presentation**
- Long-term maintainability over quick hacks
- Realism inspired by real-world motorsport structures (without licensed content)

---

## 🛠️ How to Contribute

### 1. Fork the Repository
Create a fork of the repository and clone it locally.

### 2. Create a Feature Branch
Use a clear and descriptive branch name:
feature/season-simulation
fix/points-calculation
docs/database-structure


### 3. Make Your Changes
- Keep changes focused and scoped
- Follow existing architecture and patterns
- Avoid mixing unrelated changes in a single commit

### 4. Commit Your Changes
Write clear commit messages:
Add season calendar simulation
Fix points calculation for sprint races
Refactor team performance model


### 5. Open a Pull Request
When opening a PR, please include:
- A clear description of **what** was changed
- The **reason** for the change
- Any relevant context or assumptions

---

## 🧱 Project Structure (High-Level)

While the structure may evolve, contributions should respect the core separation:

- **Data**: Static and dynamic game data (teams, drivers, rules, seasons)
- **Simulation**: Core logic (race simulation, championships, finances, AI decisions)
- **Systems**: Save/load, progression, regulations, events
- **UI / Presentation**: Interface logic only (no simulation rules)

Simulation logic must remain independent from UI code.

---

## 🧪 Testing & Validation

When applicable:
- Prefer deterministic logic
- Avoid random behavior without a controllable seed
- Document assumptions in code or comments

If adding new systems, explain how they integrate with the existing simulation flow.

---

## 📐 Coding Guidelines

- Keep code readable and well-documented
- Favor clarity over cleverness
- Avoid hard-coded values when data-driven alternatives exist
- Use meaningful names for variables, methods, and classes

---

## 📄 Documentation

Documentation improvements are highly appreciated.

If you introduce:
- A new system
- A new simulation layer
- A new data structure

Please document it clearly, either inline or in markdown files.

---

## 🚧 Scope of Contributions

This project does **not** accept:
- Licensed or copyrighted content (real teams, drivers, logos, trademarks)
- Third-party assets without proper rights
- Obfuscated or intentionally unreadable code

---

## 💬 Questions & Discussions

If you are unsure about a contribution:
- Open an issue for discussion
- Propose ideas before implementing large changes

Collaboration and thoughtful discussion are encouraged.

---

## 🙏 Final Notes

This project is built with long-term vision in mind.  
Thoughtful, well-structured contributions are valued more than quick patches.

Thank you for helping build the Open-Wheel Racing Manager Sim Engine.
