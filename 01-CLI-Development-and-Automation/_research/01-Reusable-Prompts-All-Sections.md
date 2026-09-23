STEP 1 — Reusable prompts for all sections
Course 01 — CLI Development & Automation
Task source: 00-Research-Outline-Course-01.md

You are free to install software, programs and write codes, research the internet so as to meet our goals.

---

**Section 1: CLI Foundations — Node.js Runtimes and Argument Parsing**

Task: Node.js CLI anatomy: argument parsing, flags and subcommands, stdin-stdout-stderr streams, exit codes, and signal handling, establishing how professional command-line tools communicate with users and scripts.

Absorbed skills:
- Parse arguments and subcommands robustly
- use streams and exit codes correctly
- handle signals and errors like production tools


---

**Section 2: TypeScript for CLIs — Typed Commands and Config**

Task: Type-safe command definitions, option schemas, config-file layering with validation, and strict typing of filesystem operations so CLI behavior is predictable and refactor-safe.

Absorbed skills:
- Define typed commands and options
- validate layered configs with clear errors
- keep CLI codebases refactor-safe


---

**Section 3: Bun-Powered Tooling — Fast Cross-Platform Scripts**

Task: Bun runtime for instant-start scripting: file and shell APIs, bundling single-file binaries, package management speed, and when Bun beats Node for CLI distribution.

Absorbed skills:
- Write Bun-native scripts and CLIs
- bundle single-file executables
- choose Bun versus Node per distribution need


---

**Section 4: Scaffolding Engines — Building uipro init**

Task: Building the `uipro init` initializer: interactive prompts, template rendering, conditional file trees, idempotent re-runs, and dry-run previews before touching user systems.

Absorbed skills:
- Build interactive scaffolding commands
- render conditional templates
- guarantee idempotent and previewable initialization


---

**Section 5: System Configuration Editing — Safe Programmatic Modification**

Task: Programmatic modification of system and project configs: dotfiles, registries, and rc files, with backup, diff preview, validation, and rollback on every write.

Absorbed skills:
- Modify system configs programmatically
- preview diffs and keep backups
- roll back safely on failure


---

**Section 6: Cross-Platform Hardening — Windows, macOS and Linux Parity**

Task: Path, shell, permission, and line-ending differences across platforms, CI matrices covering all three OS families, and graceful degradation where parity is impossible.

Absorbed skills:
- Ship identical CLI behavior on three platforms
- test via OS matrices
- degrade gracefully with clear messaging


---

**Section 7: Distribution and Updates — Global Installs and Versioning**

Task: Global installation via npm, bunx, and standalone binaries, version channels, update notifications, and checksum-verified downloads for trustworthy distribution.

Absorbed skills:
- Publish global CLIs through multiple channels
- implement safe self-updates
- verify artifacts with checksums


---

**Section 8: Capstone — Production ui-ux-pro-max-cli**

Task: Full capstone delivering the global `ui-ux-pro-max-cli`: init scaffolding, config editing, cross-platform CI, tests, documentation, and versioned release ready for real users.

Absorbed skills:
- Deliver a production global CLI end to end
- evidence tests, docs, and releases
- support real users safely

