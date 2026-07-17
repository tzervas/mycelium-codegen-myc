# Remap Manifest — mycelium-mir-passes → mir.passes

_DN-109 §5.2 provenance ledger. Guarantee: **Declared** — this records proposed/performed structural and idiom choices; it does not certify them (no guarantee-tag upgrade from the manifest's existence alone, VR-5). Rendered from `remap` in `summary.json` — this file is a pure projection, never a second source of truth._

## Nodules (6)

| Target nodule | Operation | Safety | API surface changed | Identity neutral | Sources | Rationale |
|---|---|---|---|---|---|---|
| `mir.passes.balance` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-mir-passes/src/balance.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `mir.passes.corpus` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-mir-passes/src/corpus.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `mir.passes.emit` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-mir-passes/src/emit.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `mir.passes.eval` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-mir-passes/src/eval.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `mir.passes` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-mir-passes/src/lib.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `mir.passes.rc_ir` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-mir-passes/src/rc_ir.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |

## Idiom choices (0)

_(none in this run — v0 Mechanical-only auto-fire with no located idiom-choice instrumentation yet; see DN-109 §7-e and this module's doc comment)_
