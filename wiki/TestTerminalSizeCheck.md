# TestTerminalSizeCheck

> 18 nodes · cohesion 0.14

## Key Concepts

- **TestTerminalSizeCheck** (16 connections) — `tests/integration/test_compact_renderer.py`
- **TestCompactRendererHandleCompletion** (15 connections) — `tests/integration/test_compact_renderer.py`
- **.check_terminal_size()** (6 connections) — `tests/integration/test_compact_renderer.py`
- **.test_update_state_streams_log_lines_for_significant_events()** (4 connections) — `tests/integration/test_compact_renderer.py`
- **.test_error_message_format()** (3 connections) — `tests/integration/test_compact_renderer.py`
- **.test_terminal_larger_passes()** (3 connections) — `tests/integration/test_compact_renderer.py`
- **.test_terminal_minimum_size_passes()** (3 connections) — `tests/integration/test_compact_renderer.py`
- **.test_terminal_too_small_reports_error()** (3 connections) — `tests/integration/test_compact_renderer.py`
- **TC-043: Minimum terminal size is 24 lines x 80 columns.** (2 connections) — `tests/integration/test_compact_renderer.py`
- **.test_minimum_size_constants()** (2 connections) — `tests/integration/test_compact_renderer.py`
- **Tests for CompactRenderer.handle_completion() method.** (1 connections) — `tests/integration/test_compact_renderer.py`
- **Each significant JSONL event must produce a log line above the panel.          W** (1 connections) — `tests/integration/test_compact_renderer.py`
- **Tests for TC-043, TC-044, TC-045: Terminal size requirements.** (1 connections) — `tests/integration/test_compact_renderer.py`
- **Check if terminal meets minimum size.** (1 connections) — `tests/integration/test_compact_renderer.py`
- **TC-043: Below minimum shows error.** (1 connections) — `tests/integration/test_compact_renderer.py`
- **TC-043: Minimum size passes check.** (1 connections) — `tests/integration/test_compact_renderer.py`
- **TC-043: Larger terminal passes check.** (1 connections) — `tests/integration/test_compact_renderer.py`
- **TC-044: Error message shows dimensions and minimum.** (1 connections) — `tests/integration/test_compact_renderer.py`

## Relationships

- [HostRunState](HostRunState.md) (8 shared connections)
- [CompactRenderer](CompactRenderer.md) (7 shared connections)
- [Display](Display.md) (2 shared connections)
- [Status](Status.md) (2 shared connections)
- [TaskDefinition](TaskDefinition.md) (2 shared connections)
- [PlayDefinition](PlayDefinition.md) (2 shared connections)

## Source Files

- `tests/integration/test_compact_renderer.py`

## Audit Trail

- EXTRACTED: 48 (74%)
- INFERRED: 17 (26%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*