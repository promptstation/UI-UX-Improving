Course 3 Research — CI/CD & Release Automation
Source: UI UX improving.txt — Course 3: "CI/CD & Release Automation: Advanced automation using GitHub Actions, semantic-release, and Conventional Commits to auto-sync versioning across multi-file architectures."
Method: Researching-Outline skill (curriculum-content-outlook) — beginner to expert, compressed to 8 sections (≤15)
Date: 2026-09-22

---

**Section 1: CI Foundations — GitHub Actions Workflows**

**Summary:** Workflow anatomy: events, jobs, matrices, caching, artifacts, and secrets hygiene, establishing reliable continuous integration for multi-file architectures.

**Absorbed Skill:** Author matrixed workflows with caching; manage secrets safely; keep CI fast and deterministic.

**Section 2: Conventional Commits — Machine-Readable History**

**Summary:** The Conventional Commits specification, commit linting in hooks and CI, scope discipline, and how clean history powers automated changelogs.

**Absorbed Skill:** Write spec-compliant commits; enforce linting; turn history into accurate changelogs.

**Section 3: semantic-release — Automated Versioning and Publishing**

**Summary:** semantic-release pipeline: commit analysis, version calculation, GitHub and npm publishing, and branch strategies for controlled automation.

**Absorbed Skill:** Configure semantic-release end to end; control publishing per branch; eliminate manual versioning.

**Section 4: Multi-File Version Sync — One Version Across Architectures**

**Summary:** Propagating a single version into manifests, lockfiles, generated clients, and docs, with verification steps proving every file agrees.

**Absorbed Skill:** Sync versions across heterogeneous files; verify consistency in CI; prevent drift permanently.

**Section 5: Quality Gates — Tests, Lint and Security in Pipeline**

**Summary:** Required status checks, test matrices, static analysis, dependency audit, and provenance attestation guarding every release.

**Absorbed Skill:** Design required-check policies; gate releases on tests and security; attest artifact provenance.

**Section 6: Release Channels — Beta, RC and Stable Flows**

**Summary:** Prerelease channels, promotion mechanics, dist-tag management, and communicating breaking changes across channels.

**Absorbed Skill:** Run beta and RC channels; promote safely to stable; communicate breaking changes clearly.

**Section 7: Rollback and Recovery — Safe Failure Handling**

**Summary:** Yank and deprecate procedures, revert-driven hotfixes, failed-publish recovery, and incident runbooks for release automation.

**Absorbed Skill:** Recover failed releases cleanly; execute hotfix flows; write runbooks teams trust.

**Section 8: Capstone — Fully Automated Release Pipeline**

**Summary:** Full capstone: repository where merged conventional commits auto-version, sync files, pass gates, and publish with zero manual steps.

**Absorbed Skill:** Deliver zero-touch release automation; evidence gates and sync; hand over operable pipelines.
