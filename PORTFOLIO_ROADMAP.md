# .github portfolio roadmap

Baseline reviewed on November 17, 2026. Repository roadmap published on November 18, 2026.

This roadmap applies to this repository and follows the shared Null Catchers portfolio plan. Verify the documented state against the current code and runs before starting work.

**Estimated initial demo effort** 5–8 hours for a developer familiar with the project. The estimate excludes external reviews, store accounts, target environment setup, and later milestones.

## Project priorities

**Documented state** The organization profile introduces its projects and technologies. This repository provides the portfolio index and profile.

**P0 — Demo** Prepare cards for three featured projects once their evidence and reproduction steps are ready.

**P1 — Validation and depth** Review the existing issue and PR templates before adding acceptance criteria, evidence, impact, and verification fields. Maintain the roadmap index and check demo and artifact links for expiry.

**P2 — Later** Extract reusable workflows only from identical steps. Keep CI appropriate for each stack and use narrowly scoped permissions.

**Acceptance criteria** A visitor reaches a featured project’s demo and evidence within two clicks. Links work and credits are verifiable.

**Demo scenario** Organization profile → featured project → walkthrough → architecture → CI or release. [Profile](https://github.com/The-Null-Catchers/.github/blob/main/profile/README.md).

## Next milestones

| Priority | Projects | Evidence before featuring |
|---|---|---|
| Finalize the demos closest to publication | [DocMind](https://github.com/The-Null-Catchers/DocMind/blob/main/PORTFOLIO_ROADMAP.md), [ChessCoach-AI](https://github.com/The-Null-Catchers/ChessCoach-AI/blob/main/PORTFOLIO_ROADMAP.md), [GeoPulse](https://github.com/The-Null-Catchers/GeoPulse/blob/main/PORTFOLIO_ROADMAP.md) | A recording from a known revision, reproduction steps, and the demo’s scope. |
| Close device and Arabic evidence gaps | [FitTrack](https://github.com/The-Null-Catchers/FitTrack/blob/main/PORTFOLIO_ROADMAP.md), [TaskPilot](https://github.com/The-Null-Catchers/TaskPilot/blob/main/PORTFOLIO_ROADMAP.md), [Masroof](https://github.com/The-Null-Catchers/Masroof/blob/main/PORTFOLIO_ROADMAP.md) | Device or real OCR evidence and a results record tied to a commit SHA. |
| Approve a new project scope | [StockFlow](https://github.com/The-Null-Catchers/StockFlow/blob/main/PORTFOLIO_ROADMAP.md) | Review the draft and approve roles and balance rules before implementation. |

Publish a project card once it has a roadmap, a verifiable release or run, and reproduction steps. Check the links while signed out.

## Portfolio acceptance checklist

- [ ] Another person can reproduce the primary workflow from a clean checkout using the README and test credentials or fixtures.
- [ ] The demo tells one complete story with a defined user, problem, and saved result.
- [ ] Tests cover the main flow, an important failure, and access boundaries when multiple accounts are involved.
- [ ] Demo data is labeled synthetic and reproducible. Review screenshots and recordings for secrets and customer data.
- [ ] Include four to six real screenshots where appropriate, a 60–120 second recording, and working links. Identify the revision used for capture.
- [ ] The README describes implemented capabilities, setup, architecture, limits, tests, and the demo.
- [ ] A short case study explains two engineering decisions, a considered alternative, and how the system handles an actual failure.
- [ ] Release evidence records the commit SHA, CI, prerequisites, and limits. Performance data includes workload, hardware, and method.
- [ ] Licensing and contributor attribution are settled before distribution. Choose the license for each repository individually.

A hosted demo is optional. Code execution, server administration, and secret management can be demonstrated through a recording and a reproducible isolated environment. Keep public demo access scoped to the activities it needs.

## Implementation and follow-up

- Break P0 into tasks with expected behavior, acceptance criteria, and a suitable test.
- Verify existing functionality first. Update this plan when evidence tied to a commit or PR closes a milestone.
- Record the fixture source, the revision used for evidence, and the tested limits.
- Review the final diff and verify required checks for its exact SHA before merging. Follow branch protection.
- For documentation-only changes with no applicable workflow, verify content and links and record the checks actually performed.
- Tie performance, security, and readiness claims to supporting evidence.

## Repository roadmap index

| Repository | Roadmap |
|---|---|
| brand-assets | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/brand-assets/blob/main/PORTFOLIO_ROADMAP.md) |
| DocMind | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/DocMind/blob/main/PORTFOLIO_ROADMAP.md) |
| ChessCoach-AI | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/ChessCoach-AI/blob/main/PORTFOLIO_ROADMAP.md) |
| VaultPass | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/VaultPass/blob/main/PORTFOLIO_ROADMAP.md) |
| FitTrack | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/FitTrack/blob/main/PORTFOLIO_ROADMAP.md) |
| Masroof | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/Masroof/blob/main/PORTFOLIO_ROADMAP.md) |
| DeployForge | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/DeployForge/blob/claude/deployforge-platform-hppvk5/PORTFOLIO_ROADMAP.md) |
| BrowserGrid | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/BrowserGrid/blob/main/PORTFOLIO_ROADMAP.md) |
| StreamForge | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/StreamForge/blob/main/PORTFOLIO_ROADMAP.md) |
| .github | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/.github/blob/main/PORTFOLIO_ROADMAP.md) |
| TaskPilot | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/TaskPilot/blob/main/PORTFOLIO_ROADMAP.md) |
| CloudDeck | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/CloudDeck/blob/main/PORTFOLIO_ROADMAP.md) |
| StockFlow | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/StockFlow/blob/main/PORTFOLIO_ROADMAP.md) |
| GeoPulse | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/GeoPulse/blob/main/PORTFOLIO_ROADMAP.md) |
| PulseMesh | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/PulseMesh/blob/main/PORTFOLIO_ROADMAP.md) |
| EventCore | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/EventCore/blob/main/PORTFOLIO_ROADMAP.md) |
| CodeArena | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/CodeArena/blob/main/PORTFOLIO_ROADMAP.md) |
| SearchForge | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/SearchForge/blob/main/PORTFOLIO_ROADMAP.md) |
