# renderer.py

> 59 nodes · cohesion 0.07

## Key Concepts

- **renderer.py** (106 connections) — `src/ansible_aom/compact/renderer.py`
- **RunProgress** (27 connections) — `src/ansible_aom/core/estimate.py`
- **test_estimate.py** (20 connections) — `tests/unit/test_estimate.py`
- **_est()** (19 connections) — `tests/unit/test_estimate.py`
- **._render_status_panel()** (18 connections) — `src/ansible_aom/compact/renderer.py`
- **_BoundedSet** (16 connections) — `src/ansible_aom/compact/renderer.py`
- **project_remaining()** (16 connections) — `src/ansible_aom/core/estimate.py`
- **RunEstimate** (12 connections) — `src/ansible_aom/core/estimate.py`
- **.__init__()** (10 connections) — `src/ansible_aom/compact/renderer.py`
- **add_completed()** (10 connections) — `src/ansible_aom/core/estimate.py`
- **add_in_flight()** (10 connections) — `src/ansible_aom/core/estimate.py`
- **run_state_status_counts()** (10 connections) — `src/ansible_aom/core/tree.py`
- **estimate.py** (8 connections) — `src/ansible_aom/core/estimate.py`
- **_color_enabled()** (7 connections) — `src/ansible_aom/compact/format.py`
- **._cached_count_total_tasks()** (4 connections) — `src/ansible_aom/compact/renderer.py`
- **test_add_completed_buckets_by_prior_result()** (4 connections) — `tests/unit/test_estimate.py`
- **test_add_completed_fixed_task_does_not_touch_var_actual()** (4 connections) — `tests/unit/test_estimate.py`
- **test_add_completed_ignores_unmatched_path()** (4 connections) — `tests/unit/test_estimate.py`
- **test_add_in_flight_caps_credit_at_prior_but_not_actual()** (4 connections) — `tests/unit/test_estimate.py`
- **test_add_in_flight_credits_variable_bucket_and_actual()** (4 connections) — `tests/unit/test_estimate.py`
- **test_add_in_flight_fixed_task_credits_floor_only()** (4 connections) — `tests/unit/test_estimate.py`
- **test_fast_rerun_keeps_floor_but_collapses_variable()** (4 connections) — `tests/unit/test_estimate.py`
- **test_fixed_floor_projected_unscaled()** (4 connections) — `tests/unit/test_estimate.py`
- **test_no_prior_returns_none()** (4 connections) — `tests/unit/test_estimate.py`
- **test_remaining_never_negative()** (4 connections) — `tests/unit/test_estimate.py`
- *... and 34 more nodes in this community*

## Relationships

- [CompactRenderer](CompactRenderer.md) (15 shared connections)
- [._emit_event_log](_emit_event_log.md) (12 shared connections)
- [format.py](format.py.md) (10 shared connections)
- [JsonlEvent](JsonlEvent.md) (8 shared connections)
- [format_host_summary](format_host_summary.md) (6 shared connections)
- [test_task_progress.py](test_task_progress.py.md) (5 shared connections)
- [Status](Status.md) (5 shared connections)
- [TreeProjection](TreeProjection.md) (5 shared connections)
- [_compute_mode_label](_compute_mode_label.md) (4 shared connections)
- [history.py](history.py.md) (4 shared connections)
- [Display](Display.md) (3 shared connections)
- [format_host_rows](format_host_rows.md) (3 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/compact/renderer.py`
- `src/ansible_aom/core/estimate.py`
- `src/ansible_aom/core/tree.py`
- `tests/compact/test_status_bar_colors.py`
- `tests/unit/test_estimate.py`

## Audit Trail

- EXTRACTED: 378 (95%)
- INFERRED: 21 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*