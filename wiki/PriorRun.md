# PriorRun

> 33 nodes · cohesion 0.12

## Key Concepts

- **PriorRun** (24 connections) — `src/ansible_aom/session/history.py`
- **format_preflight_summary()** (22 connections) — `src/ansible_aom/compact/format.py`
- **test_preflight_summary.py** (15 connections) — `tests/compact/test_preflight_summary.py`
- **collect_tags()** (10 connections) — `src/ansible_aom/compact/format.py`
- **test_prior_run_line.py** (10 connections) — `tests/compact/test_prior_run_line.py`
- **_play()** (8 connections) — `tests/compact/test_prior_run_line.py`
- **_td()** (7 connections) — `tests/compact/test_preflight_summary.py`
- **_td_tagged()** (7 connections) — `tests/compact/test_preflight_summary.py`
- **test_format_preflight_summary_counts_role_grouped_tasks()** (6 connections) — `tests/compact/test_preflight_summary.py`
- **test_collect_tags_handles_role_group_definition()** (5 connections) — `tests/compact/test_preflight_summary.py`
- **test_format_preflight_summary_handles_no_resolved_hosts()** (5 connections) — `tests/compact/test_preflight_summary.py`
- **test_format_preflight_summary_pluralization()** (5 connections) — `tests/compact/test_preflight_summary.py`
- **test_prior_run_line_prefers_observed_over_preflight_count()** (5 connections) — `tests/compact/test_prior_run_line.py`
- **test_collect_tags_empty_when_no_tags()** (4 connections) — `tests/compact/test_preflight_summary.py`
- **test_collect_tags_unique_sorted_across_plays()** (4 connections) — `tests/compact/test_preflight_summary.py`
- **test_format_preflight_summary_appends_tag_line_when_tags_present()** (4 connections) — `tests/compact/test_preflight_summary.py`
- **test_format_preflight_summary_multi_play()** (4 connections) — `tests/compact/test_preflight_summary.py`
- **test_format_preflight_summary_omits_tag_line_when_no_tags()** (4 connections) — `tests/compact/test_preflight_summary.py`
- **test_format_preflight_summary_single_play()** (4 connections) — `tests/compact/test_preflight_summary.py`
- **test_prior_run_line_hours_format()** (4 connections) — `tests/compact/test_prior_run_line.py`
- **test_prior_run_line_seconds_only_under_a_minute()** (4 connections) — `tests/compact/test_prior_run_line.py`
- **test_prior_run_line_shown_when_prior_exists()** (4 connections) — `tests/compact/test_prior_run_line.py`
- **_collect_role_group_tags()** (3 connections) — `src/ansible_aom/compact/format.py`
- **test_prior_run_line_is_omitted_when_none()** (3 connections) — `tests/compact/test_prior_run_line.py`
- **test_format_preflight_summary_empty_returns_none()** (2 connections) — `tests/compact/test_preflight_summary.py`
- *... and 8 more nodes in this community*

## Relationships

- [PlayDefinition](PlayDefinition.md) (13 shared connections)
- [TaskDefinition](TaskDefinition.md) (8 shared connections)
- [format.py](format.py.md) (7 shared connections)
- [renderer.py](renderer.py.md) (4 shared connections)
- [build_run_config_key](build_run_config_key.md) (4 shared connections)
- [history.py](history.py.md) (4 shared connections)
- [CompactRenderer](CompactRenderer.md) (3 shared connections)
- [test_prior_denominator.py](test_prior_denominator.py.md) (2 shared connections)
- [Shift Modifier Keybindings](Shift_Modifier_Keybindings.md) (2 shared connections)
- [Status](Status.md) (2 shared connections)
- [format_failure_recap](format_failure_recap.md) (1 shared connections)
- [._render_status_panel](_render_status_panel.md) (1 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/session/history.py`
- `tests/compact/test_preflight_summary.py`
- `tests/compact/test_prior_run_line.py`

## Audit Trail

- EXTRACTED: 150 (83%)
- INFERRED: 31 (17%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*