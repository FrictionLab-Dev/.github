# Friction Lab

**Local-first tools for developer workflow friction.**

Friction Lab builds small, practical tools for the moments that slow developers down: messy caches, painful folder navigation, confusing environments, long error logs, and scattered Mac workspaces.

Our tools are designed to be:

- **local-first** — your workflow stays on your machine
- **explainable** — tools should tell you what they are doing and why
- **safe by default** — especially when touching files, caches, or developer artifacts
- **small but useful** — focused tools for real daily friction
- **free for CLI users** — developer utilities should reduce friction, not add another paywall

## Tools

### Cleanroom

Safe cleanup for generated developer artifacts.

Cleanroom scans developer cache and build artifact locations, explains what it finds, and helps recover disk space without touching user work.

Current focus:

- Xcode DerivedData
- Xcode DeviceSupport
- Xcode Archives
- simulator caches
- profile-based artifact explanations
- Trash-backed cleanup
- privacy-safe aggregate stats

Planned command: `cr`

---

### Wayfinder

Interactive project and folder navigation.

Wayfinder helps move through files and folders from the terminal without manual `cd` pain. It supports local navigation, global indexed search, shell-integrated actions, open, copy path, and reveal in Finder.

Planned command: `way`

---

### Faultline

Command failure capture and report generation.

Faultline is planned as a tool for running failing commands, capturing long terminal output, extracting useful context, and producing formatted reports for debugging or asking AI.

Planned command: `fault` or `report`

---

### Env Doctor

Environment and dependency diagnosis.

Env Doctor is planned as a local diagnosis tool for Python environments, virtual environments, dependency mismatches, missing packages, wrong interpreters, and `.env` issues.

Planned command: `envd`

---

### Space Buddy

A task-workspace companion for macOS.

Space Buddy explores a better way to manage task contexts on Mac: named workspaces, app/window anchors, focus memory, workspace presets, minimized-window restore, and low-power state monitoring.

---

### Confusion Memory

An experimental research direction around learning from mistakes, confusion, and failure patterns.

The broader idea is simple:

> friction → structure → memory → better future behavior

## Philosophy

Friction Lab is not trying to build giant platforms first.

It starts with small tools that solve real developer pain:

- “Where is that project folder?”
- “Why is Xcode using so much storage?”
- “Which Python interpreter is this project using?”
- “How do I summarize this huge error log?”
- “How do I get back to the Mac workspace for this task?”

Each tool should make one painful workflow feel calmer, clearer, and safer.

## Brand separation

Friction Lab is separate from Roadscript / Cyphra.

- **Roadscript / Cyphra** focuses on image authenticity, invisible watermarking, verification, and content provenance.
- **Friction Lab** focuses on local-first developer tools, Mac utilities, cleanup, diagnostics, navigation, workspace control, and workflow experiments.

## Contact

General contact: contact@frictionlab.dev  
Support: support@frictionlab.dev  

Website: https://frictionlab.dev
