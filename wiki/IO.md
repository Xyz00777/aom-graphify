# IO

> 19 nodes · cohesion 0.11

## Key Concepts

- **IO** (13 connections)
- **display.py** (11 connections) — `src/ansible_aom/compact/display.py`
- **test_small_terminal.py** (8 connections) — `tests/compact/test_small_terminal.py`
- **test_display_ansi.py** (5 connections) — `tests/compact/test_display_ansi.py`
- **TestSynchronizedOutput** (5 connections) — `tests/compact/test_display_ansi.py`
- **print_summary_if_debug()** (4 connections) — `src/ansible_aom/core/diagnostics.py`
- **TestThresholdConstant** (4 connections) — `tests/compact/test_small_terminal.py`
- **.test_non_tty_update_emits_no_ansi()** (3 connections) — `tests/compact/test_display_ansi.py`
- **check_terminal_size()** (2 connections) — `src/ansible_aom/compact/display.py`
- **.test_update_wraps_content_in_dec_2026_sync()** (2 connections) — `tests/compact/test_display_ansi.py`
- **Display logic for compact mode — nom-style fixed-bottom status panel.  Renders d** (1 connections) — `src/ansible_aom/compact/display.py`
- **Check if terminal meets minimum size requirements.      Args:         lines: Num** (1 connections) — `src/ansible_aom/compact/display.py`
- **Emit a single-line ``[aom-debug] …`` post-run digest to ``file``.      Silent un** (1 connections) — `src/ansible_aom/core/diagnostics.py`
- **Tests for nom-style ANSI rendering in compact mode.  These tests pin the new-spe** (1 connections) — `tests/compact/test_display_ansi.py`
- **Each Display.update() in TTY mode emits a single DEC 2026 frame.** (1 connections) — `tests/compact/test_display_ansi.py`
- **is_tty=False is the pipe/CI fallback (PQ6): never emit positioning.** (1 connections) — `tests/compact/test_display_ansi.py`
- **Tests for R4 — graceful degradation on terminals smaller than 80×24.  Today the** (1 connections) — `tests/compact/test_small_terminal.py`
- **The (cols, rows) threshold lives as a module constant so tests     can reference** (1 connections) — `tests/compact/test_small_terminal.py`
- **.test_minimum_size_is_80_cols_24_rows()** (1 connections) — `tests/compact/test_small_terminal.py`

## Relationships

- [Display](Display.md) (8 shared connections)
- [_fresh_display](_fresh_display.md) (2 shared connections)
- [_row_count](_row_count.md) (2 shared connections)
- [Inspect CLI Module](Inspect_CLI_Module.md) (1 shared connections)
- [RunSummary Schema Contract](RunSummary_Schema_Contract.md) (1 shared connections)
- [TestPerEventLogColors](TestPerEventLogColors.md) (1 shared connections)
- [HostRunState](HostRunState.md) (1 shared connections)
- [RunDiagnostics](RunDiagnostics.md) (1 shared connections)
- [Secret Redaction Layers](Secret_Redaction_Layers.md) (1 shared connections)
- [test_inspect_debug.py](test_inspect_debug.py.md) (1 shared connections)
- [core/__init__.py](core-__init__.py.md) (1 shared connections)
- [Path](Path.md) (1 shared connections)

## Source Files

- `src/ansible_aom/compact/display.py`
- `src/ansible_aom/core/diagnostics.py`
- `tests/compact/test_display_ansi.py`
- `tests/compact/test_small_terminal.py`

## Audit Trail

- EXTRACTED: 64 (97%)
- INFERRED: 2 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*