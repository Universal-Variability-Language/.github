# Universal Variability Language (UVL)

Welcome to the **Universal Variability Language (UVL)** organization on GitHub!

---

## About UVL

UVL is a concise, extensible language for modeling variability in software product lines.  
This organization houses multiple related projects that support the definition, parsing, tooling, and ecosystem around UVL.  
See our public site: https://universal-variability-language.github.io/

### Key Repositories

Here are some of the main projects under this organization:

| Repository | Purpose |
|---|---|
| `uvl-parser` | The grammar / parser definition of UVL, based on ANTLR :contentReference[oaicite:1]{index=1} |
| `java-fm-metamodel` | Java library to manipulate UVL metamodels; uses the UVL grammar :contentReference[oaicite:2]{index=2} |
| `uvl-models` | A repository containing a catalog of publicly available feature models expressed in UVL :contentReference[oaicite:3]{index=3} |
| `uvl-lsp` | A Language Server Protocol (LSP) implementation for UVL :contentReference[oaicite:4]{index=4} |
| `uvl-tutorials-material` | Teaching / tutorial resources for UVL usage :contentReference[oaicite:5]{index=5} |
| `UVLEP` | The UVL Enhancement Process (for evolving the language) :contentReference[oaicite:6]{index=6} |
| Others | Additional repositories include evaluation projects, example models, etc. :contentReference[oaicite:7]{index=7} |

---

## Organization Governance & Contribution

We aim to maintain transparency, collaboration, and quality across all projects in this organization. Below are some guidelines:

### Contribution Welcome 🎯

- **Issue tracker**: Use issues in the respective repository to propose enhancements, report bugs, or request features.
- **Pull requests**: Fork the repo, create a feature branch, commit changes, and open a PR. Please follow the repository’s coding / style / testing conventions.
- **Review process**: At least one reviewer will approve changes; maintainers may suggest adjustments.
- **Code of Conduct / License**: Each repository should include a license (e.g. LGPL, MIT) and a code of conduct. If not present, raise an issue to have one added.

### UVL Enhancement (Language Evolution)

Changes to the UVL language itself should follow a formal proposal process (e.g. via `UVLEP`).  
Language-level changes must be backwards-compatible where possible, or include migration guidance if incompatible.

### Coordination & Communication

- We recommend using GitHub Discussions or Issues within this org for cross-repo coordination.
- Major announcements, releases, or roadmap items may be published on the org website or via a “meta” repository (if created).
- Use repository-level GitHub Actions and CI consistently, where relevant, to enforce build, style, and tests.

---

## Getting Started

If you are new, here’s how to begin:

1. Browse the **`uvl-parser`** repository to understand the grammar and language definition.
2. Explore the **`java-fm-metamodel`** library to see how UVL models are processed in Java.
3. Try editing or extending example models in **`uvl-models`**.
4. If you wish to contribute tooling, you may work on or propose changes in **`uvl-lsp`** or other supportive repositories.
5. Consult tutorials in **`uvl-tutorials-material`** for step-by-step guides.

---

## Conventions & Best Practices (Suggested)

- **Repository naming**: Use `uvl-‹component›` or descriptive names (e.g., `java-fm-metamodel`, `uvl-evaluation-…`)
- **Branching**: Use branches like `main` (or `master`) for stable, release-ready code; use feature branches for new work.
- **Versioning**: Use semantic versioning where applicable.
- **Documentation**: Each repo should include `README.md`, API documentation, and examples.
- **CI / Testing**: Automate builds, tests, linters, and checks via GitHub Actions or other CI.
- **License**: Ensure each repo includes a clear license file; prefer permissive or academia-friendly licenses.

---

## Useful Links & Resources

- Organization website / home: https://universal-variability-language.github.io/ :contentReference[oaicite:8]{index=8}  
- Main repositories:
  - `uvl-parser`  
  - `java-fm-metamodel`  
  - `uvl-models`  
  - `uvl-lsp`  
  - `uvl-tutorials-material`  
  - `UVLEP`  
- Tutorials, examples, and sample models in `uvl-tutorials-material`  
- Language enhancement proposals via `UVLEP`

---
