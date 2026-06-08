# Multimodal Agent Steering Surface Workflow Map

Source: [[../../Ideas/Multimodal Agent Interfaces Beyond Chat.md|Multimodal Agent Interfaces Beyond Chat]]

```mermaid
flowchart LR
  A[X signal] --> B[Extract reusable workflow]
  B --> C[Prototype a local operator surface]
  C --> D[Run one real trial]
  D --> E{Decision}
  E -->|promote| F[Skill / product wedge]
  E -->|pilot only| G[Project-specific artifact]
  E -->|iterate| H[Improve loop]
  E -->|hold| I[Archive with reason]
```

## Why it matters
Chat-only agent products miss the way humans actually steer collaborators: pointing, circling, talking, interrupting, and reviewing shared context. This package turns that signal into a concrete UI pattern Vinay can reuse for ResumeSetGo-style reviews and agent workbenches.

## Operator rule
Prepared artifacts are not validation. Only filled trial evidence can justify promotion.
