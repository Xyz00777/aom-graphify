# IO

> 16 nodes · cohesion 0.13

## Key Concepts

- **IO** (13 connections)
- **test_renderer_stats_parity.py** (6 connections) — `tests/unit/test_renderer_stats_parity.py`
- **test_display_ansi.py** (5 connections) — `tests/compact/test_display_ansi.py`
- **TestSynchronizedOutput** (5 connections) — `tests/compact/test_display_ansi.py`
- **print_summary_if_debug()** (4 connections) — `src/ansible_aom/core/diagnostics.py`
- **_drive_json()** (4 connections) — `tests/unit/test_renderer_stats_parity.py`
- **.test_non_tty_update_emits_no_ansi()** (3 connections) — `tests/compact/test_display_ansi.py`
- **.test_update_wraps_content_in_dec_2026_sync()** (2 connections) — `tests/compact/test_display_ansi.py`
- **test_json_renderer_publishes_stats_on_completion()** (2 connections) — `tests/unit/test_renderer_stats_parity.py`
- **Emit a single-line ``[aom-debug] …`` post-run digest to ``file``.      Silent un** (1 connections) — `src/ansible_aom/core/diagnostics.py`
- **Tests for nom-style ANSI rendering in compact mode.  These tests pin the new-spe** (1 connections) — `tests/compact/test_display_ansi.py`
- **Each Display.update() in TTY mode emits a single DEC 2026 frame.** (1 connections) — `tests/compact/test_display_ansi.py`
- **is_tty=False is the pipe/CI fallback (PQ6): never emit positioning.** (1 connections) — `tests/compact/test_display_ansi.py`
- **Any** (1 connections)
- **Phase 12: JsonRenderer publishes RendererStats at completion.  Spec: docs/superp** (1 connections) — `tests/unit/test_renderer_stats_parity.py`
- **_reset()** (1 connections) — `tests/unit/test_renderer_stats_parity.py`

## Relationships

- [Display](Display.md) (3 shared connections)
- [diagnostics.py](diagnostics.py.md) (2 shared connections)
- [Inspect CLI Module](Inspect_CLI_Module.md) (1 shared connections)
- [RunSummary Schema Contract](RunSummary_Schema_Contract.md) (1 shared connections)
- [Per-Task Timing Tests](Per-Task_Timing_Tests.md) (1 shared connections)
- [test_small_terminal.py](test_small_terminal.py.md) (1 shared connections)
- [TestPerEventLogColors](TestPerEventLogColors.md) (1 shared connections)
- [Status](Status.md) (1 shared connections)
- [Secret Redaction Layers](Secret_Redaction_Layers.md) (1 shared connections)
- [Color ASCII Fallback](Color_ASCII_Fallback.md) (1 shared connections)
- [KeyAction TypedDict](KeyAction_TypedDict.md) (1 shared connections)
- [ansible_aom/cli.py](ansible_aom-cli.py.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/diagnostics.py`
- `tests/compact/test_display_ansi.py`
- `tests/unit/test_renderer_stats_parity.py`

## Audit Trail

- EXTRACTED: 49 (96%)
- INFERRED: 2 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*