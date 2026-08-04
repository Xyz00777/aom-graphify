# format_failure_recap

> 21 nodes · cohesion 0.15

## Key Concepts

- **format_failure_recap()** (16 connections) — `src/ansible_aom/compact/format.py`
- **TestFormatFailureRecap** (13 connections) — `tests/compact/test_completion_recap.py`
- **TestFailureRecapColors** (11 connections) — `tests/compact/test_status_bar_colors.py`
- **test_completion_recap.py** (9 connections) — `tests/compact/test_completion_recap.py`
- **_state_with_failure()** (9 connections) — `tests/compact/test_completion_recap.py`
- **._state_with()** (9 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_failure_recap_lines_indented()** (4 connections) — `tests/compact/test_completion_recap.py`
- **.test_empty_state_returns_no_lines()** (3 connections) — `tests/compact/test_completion_recap.py`
- **.test_failed_label_is_visible()** (3 connections) — `tests/compact/test_completion_recap.py`
- **.test_failure_recap_names_host_and_task()** (3 connections) — `tests/compact/test_completion_recap.py`
- **.test_no_failures_returns_no_lines()** (3 connections) — `tests/compact/test_completion_recap.py`
- **.test_unreachable_is_recapped_separately_from_failed()** (3 connections) — `tests/compact/test_completion_recap.py`
- **.test_failure_completion_prints_recap()** (3 connections) — `tests/compact/test_completion_recap.py`
- **.test_failed_label_is_red()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_no_color_by_default()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_unreachable_label_is_magenta()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **Render a one-shot startup summary of plays/tasks/hosts from preflight.      Prin** (2 connections) — `src/ansible_aom/compact/format.py`
- **Build per-failure lines naming the host and task that went wrong.      Returns o** (1 connections) — `src/ansible_aom/compact/format.py`
- **Tests for the failure recap printed when a run ends in failure.  The per-host su** (1 connections) — `tests/compact/test_completion_recap.py`
- **Recap lines should align visually with the per-host summary block.** (1 connections) — `tests/compact/test_completion_recap.py`
- **Recap line labels carry the same colour as the per-host count.** (1 connections) — `tests/compact/test_status_bar_colors.py`

## Relationships

- [HostRunState](HostRunState.md) (21 shared connections)
- [RunState](RunState.md) (5 shared connections)
- [Status](Status.md) (4 shared connections)
- [CompactRenderer](CompactRenderer.md) (4 shared connections)
- [renderer.py](renderer.py.md) (2 shared connections)
- [format.py](format.py.md) (1 shared connections)
- [JsonlEvent](JsonlEvent.md) (1 shared connections)
- [._render_status_panel](_render_status_panel.md) (1 shared connections)
- [PriorRun](PriorRun.md) (1 shared connections)
- [run_state.py](run_state.py.md) (1 shared connections)
- [TestPerEventLogColors](TestPerEventLogColors.md) (1 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `tests/compact/test_completion_recap.py`
- `tests/compact/test_status_bar_colors.py`

## Audit Trail

- EXTRACTED: 76 (73%)
- INFERRED: 28 (27%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*