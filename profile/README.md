# Unit27 Research

`PUBLIC_RELEASE_INDEX // OPEN_TOOLING`

Unit27 Research maintains a public source channel for selected field kits from the departmental archive.

Some Unit27 materials remain controlled. The repositories below are different: released instruments, visible, inspectable, and intended for orientation, testing, and practical use.

## Start Here

If you are new to the Unit27 public tooling channel, start with the operating sequence, not the release dates.

```text
Stack Engine -> Context Engine -> Knowledge Readiness -> Handoff Engine -> Eval Bench -> Proof Ledger -> Boundary Engine -> u27-check
```

The short version:

1. Shape the work.
2. Package the context.
3. Classify what the context is allowed to become.
4. Write the handoff.
5. Run the evals.
6. Record the proof.
7. Contain the public claim.
8. Check the launch surface.

Each repository is usable on its own. Together, they form a public example of how Unit27 builds AI-assisted work: structured before execution, evidence-bearing before publication, and bounded before scale.

For the guided public binder, start here:

- [`unit27-field-kit-suite`](https://github.com/unit27research/unit27-field-kit-suite)

## Use The Chain

```bash
git clone https://github.com/unit27research/unit27-stack-engine
git clone https://github.com/unit27research/unit27-context-engine
git clone https://github.com/unit27research/unit27-knowledge-readiness
git clone https://github.com/unit27research/unit27-handoff-engine
git clone https://github.com/unit27research/unit27-eval-bench
git clone https://github.com/unit27research/unit27-proof-ledger
git clone https://github.com/unit27research/unit27-boundary-engine
git clone https://github.com/unit27research/u27-check
```

The current public packages are GitHub-first. Install and run them from a local checkout unless a repository README explicitly names a package registry command.

## Open Tooling

These packages support a narrow doctrine:

AI-assisted work should be structured, context-aware, evidence-bearing, and claim-bound.

| Repository | Class | Operating Position | Purpose |
|---|---:|---:|---|
| [`unit27-stack-engine`](https://github.com/unit27research/unit27-stack-engine) | `U27-S02` | `01/08` | Strategy-to-implementation planning for AI workflow architectures. |
| [`unit27-context-engine`](https://github.com/unit27research/unit27-context-engine) | `U27-S03` | `02/08` | Governed, token-aware context packaging for AI-assisted work. |
| [`unit27-knowledge-readiness`](https://github.com/unit27research/unit27-knowledge-readiness) | `U27-S08` | `03/08` | Knowledge status classification before context becomes memory, onboarding, automation context, handoff material, or public proof. |
| [`unit27-handoff-engine`](https://github.com/unit27research/unit27-handoff-engine) | `U27-S04` | `04/08` | Agent-ready work packets from objectives and approved context. |
| [`unit27-eval-bench`](https://github.com/unit27research/unit27-eval-bench) | `U27-S05` | `05/08` | Deterministic eval case execution before proof recording. |
| [`unit27-proof-ledger`](https://github.com/unit27research/unit27-proof-ledger) | `U27-S06` | `06/08` | Durable proof artifacts for tests, demos, evals, and release evidence. |
| [`unit27-boundary-engine`](https://github.com/unit27research/unit27-boundary-engine) | `U27-S07` | `07/08` | Public-claim review against recorded proof and declared boundaries. |
| [`u27-check`](https://github.com/unit27research/u27-check) | `U27-C01` | `08/08` | Pre-launch review discipline for public-facing systems. |

## Adjacent Utilities

These public utilities sit beside the field-kit operating sequence rather than inside it.

| Repository | Position | Purpose |
|---|---:|---|
| [`zero-env-proxy`](https://github.com/unit27research/zero-env-proxy) | `ADJACENT_RUNTIME_BOUNDARY_UTILITY` | Routes approved local automation workers through a governed credential boundary without handing provider keys to worker files. |
| [`humility-engine`](https://github.com/unit27research/humility-engine) | `ADJACENT_CLAIM_REVIEW_UTILITY` | Reviews drafts for likely uncertainty laundering, proofwashing, and claim/evidence scope mismatch before publication. |
| [`claim-drift`](https://github.com/unit27research/claim-drift) | `ADJACENT_CLAIM_REVIEW_UTILITY` | Reviews how public claims change between draft versions and flags possible confidence, scope, and proof-language drift. |
| [`proof-decay`](https://github.com/unit27research/proof-decay) | `ADJACENT_CLAIM_REVIEW_UTILITY` | Reviews whether stale or condition-shifted proof is being reused to support current claims. |
| [`evidence-floor`](https://github.com/unit27research/evidence-floor) | `ADJACENT_CLAIM_REVIEW_UTILITY` | Reviews whether claims meet declared evidence floors for their claim class. |
| [`caveat-drop`](https://github.com/unit27research/caveat-drop) | `ADJACENT_CLAIM_REVIEW_UTILITY` | Reviews whether public claims dropped limitations that should still bound the evidence. |

## Suite Package

[`unit27-field-kit-suite`](https://github.com/unit27research/unit27-field-kit-suite) is the public binder for the open tooling channel. It is not another engine. It preserves the operating order, field-kit map, and first-use workflow in one orientation package.

## Numbering Doctrine

Unit27 uses structural class numbers and operating positions separately.

```text
U27-S## = structural system class
U27-C## = check / gate class
U27-FKS## = field kit suite class
OPERATING_POSITION = order inside the public field-kit chain
REF_ID = stable public package identifier tied to the structural class
```

`Stack Engine` is `U27-S02`, but it is first in this public operating chain. The class number belongs to the broader Unit27 registry; the operating position describes how these public field kits are used together.

## System Order

The public field kits have two orders: the order they were released, and the order they now form as a working system.

### Release Order

```text
u27-check -> Stack Engine -> Context Engine -> Proof Ledger -> Boundary Engine -> Handoff Engine -> Eval Bench -> Knowledge Readiness
```

`u27-check` was the first public field kit released by Unit27. It began as a launch discipline: before anything public goes out, check whether the first real user path breaks.

That origin still matters. The first tool built the gate.

### Operating Sequence

```text
Stack Engine -> Context Engine -> Knowledge Readiness -> Handoff Engine -> Eval Bench -> Proof Ledger -> Boundary Engine -> u27-check
```

- `Stack Engine` shapes the work.
- `Context Engine` prepares the material.
- `Knowledge Readiness` classifies what the prepared context is allowed to become.
- `Handoff Engine` turns the objective and approved context into a bounded work packet.
- `Eval Bench` runs declared eval cases.
- `Proof Ledger` records the evidence.
- `Boundary Engine` contains the public claim.
- `u27-check` gates the first user path.

The sequence is simple by design: define the system, prepare the context, classify what the context is allowed to become, write the handoff, run the evals, record the proof, constrain the claim, then check the launch surface.

In release history, `u27-check` came first. In operational use, it stands last: the final gate before a real user reaches the surface.

## First Use Path

For a new project, use the public kits this way:

```text
1. Use Stack Engine when the project shape is still unclear.
2. Use Context Engine when a repository needs a governed context package.
3. Use Knowledge Readiness when prepared context may be stale, disputed, restricted, role-specific, or unsafe for action.
4. Use Handoff Engine when an agent needs a bounded work packet.
5. Use Eval Bench when acceptance checks need executable eval results.
6. Use Proof Ledger when evidence needs to survive the terminal session.
7. Use Boundary Engine when public language needs to stay inside proof.
8. Use u27-check before a public demo or launch link is shared.
```

The goal is not ceremony. The goal is to keep AI-assisted work inspectable after the moment of generation has passed.

## Release Doctrine

Public field kits are not secondary artifacts.

They are small released instruments: narrow enough to understand, inspectable enough to verify, and practical enough to use outside the Unit27 archive.

Each repository should answer four questions quickly:

- What does it do?
- Why use it now?
- What proof does it produce?
- Where are its boundaries?

## Access Status

`SOURCE_STATUS: PUBLIC_PACKAGE`  
`ACCESS_STATUS: CLEARED_FOR_EXTERNAL_USE`

Detailed technical materials, protocol diagrams, private research notes, and transaction discussions remain gated through Unit27 inquiry channels.

## Operating Line

Structure first.  
Proof before claim.  
Boundaries before scale.
