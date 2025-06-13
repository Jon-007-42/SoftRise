# SoftRise Business Repository

Central hub for all non‑technical artefacts of the **SoftRise** project: business model, funding materials, marketing assets, and regulatory documentation.

## Table of Contents

* [About SoftRise](#about-softrise)
* [Repository Structure](#repository-structure)
* [Getting Started](#getting-started)
* [Documentation](#documentation)
* [Contributing](#contributing)
* [Project Management](#project-management)
* [Roadmap](#roadmap)
* [License](#license)
* [Contact](#contact)

## About SoftRise

SoftRise develops **portable, inflatable support cushions** that gently lift a resident’s legs and reduce heavy lifting for caregiving staff.
Our mission is to **improve quality of care** while **minimising work‑related injuries** among healthcare professionals.

## Repository Structure

```
docs/              # Living documentation (BMC, CE‑plan, etc.)
pitch/             # Pitch decks, scripts, video storyboards
funding/           # Grant applications, budgets, investor one‑pagers
marketing/         # Logos, product renders, social‑media copy
.github/           # Issue/PR templates, label config
README.md          # This file
```

> **Tip:** Large binaries (e.g., videos, high‑res images) should be committed with **Git LFS**.

## Getting Started

1. **Prerequisites**

   * [Git](https://git-scm.com/) ≥ 2.40
   * [Git LFS](https://git-lfs.github.com/) enabled (`git lfs install`)

2. **Clone the repository**

   ```bash
   git clone git@github.com:SoftRise/soft-rise-business.git
   cd soft-rise-business
   ```

3. **Browse the docs**

   ```
   docs/Business_Model_Canvas.md
   docs/Pitch_v1_4.md
   ```

## Documentation

We keep all living documents in Markdown inside the `docs/` folder.
If you prefer rendered HTML, run:

```bash
pip install mkdocs
mkdocs serve
```

and open [http://localhost:8000](http://localhost:8000).

## Contributing

We welcome pull requests and suggestions 🎉

1. Fork the repo and create your branch: `git checkout -b feat/your-feature`
2. Commit using **[Conventional Commits](https://www.conventionalcommits.org/)**:

   ```
   feat: add grant budget draft
   ```
3. Push and open a **Pull Request**. One approval + passing CI is required to merge.

Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) for details.

## Project Management

* **Issues** use the following labels: `type/feature`, `type/docs`, `priority/high`, …
* **GitHub Project**: see [Roadmap 2025](https://github.com/orgs/SoftRise/projects/1) for milestones and status.

## Roadmap

| Quarter | Milestone                       | Status |
| ------- | ------------------------------- | ------ |
| Q3 2025 | MVP‑prototype v0                | ☐      |
| Q4 2025 | CE pre‑check & clinical test    | ☐      |
| Q1 2026 | Pilot production (50‑100 units) | ☐      |

## License

Content in this repository is released under the **MIT License** unless stated otherwise.
See [`LICENSE`](LICENSE) for full details.

## Contact

> Have a question? Reach out via **issues** or email **[contact@softrise.dk](mailto:contact@softrise.dk)**.

---

*Last updated: 2025‑06‑13*
