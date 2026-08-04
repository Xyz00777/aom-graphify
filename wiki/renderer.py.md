# renderer.py

> 37 nodes · cohesion 0.15

## Key Concepts

- **renderer.py** (106 connections) — `src/ansible_aom/compact/renderer.py`
- **RunProgress** (27 connections) — `src/ansible_aom/core/estimate.py`
- **test_estimate.py** (20 connections) — `tests/unit/test_estimate.py`
- **_est()** (19 connections) — `tests/unit/test_estimate.py`
- **project_remaining()** (16 connections) — `src/ansible_aom/core/estimate.py`
- **RunEstimate** (12 connections) — `src/ansible_aom/core/estimate.py`
- **add_completed()** (10 connections) — `src/ansible_aom/core/estimate.py`
- **add_in_flight()** (10 connections) — `src/ansible_aom/core/estimate.py`
- **estimate.py** (8 connections) — `src/ansible_aom/core/estimate.py`
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
- **test_variable_remainder_scaled_by_work_pace()** (4 connections) — `tests/unit/test_estimate.py`
- **test_warmup_fraction_gate()** (4 connections) — `tests/unit/test_estimate.py`
- **test_warmup_min_tasks_gate()** (4 connections) — `tests/unit/test_estimate.py`
- **test_work_pace_clamped_high()** (4 connections) — `tests/unit/test_estimate.py`
- **test_work_pace_clamped_low()** (4 connections) — `tests/unit/test_estimate.py`
- **test_work_pace_defaults_to_one_before_any_variable_completes()** (4 connections) — `tests/unit/test_estimate.py`
- *... and 12 more nodes in this community*

## Relationships

- [JsonlEvent](JsonlEvent.md) (15 shared connections)
- [format.py](format.py.md) (9 shared connections)
- [CompactRenderer](CompactRenderer.md) (9 shared connections)
- [._render_status_panel](_render_status_panel.md) (6 shared connections)
- [format_status_bar](format_status_bar.md) (4 shared connections)
- [_compute_mode_label](_compute_mode_label.md) (3 shared connections)
- [test_password.py](test_password.py.md) (3 shared connections)
- [history.py](history.py.md) (3 shared connections)
- [parity.py](parity.py.md) (2 shared connections)
- [TestPerEventLogColors](TestPerEventLogColors.md) (2 shared connections)
- [format_host_rows](format_host_rows.md) (2 shared connections)
- [PlayDefinition](PlayDefinition.md) (2 shared connections)

## Source Files

- `src/ansible_aom/compact/renderer.py`
- `src/ansible_aom/core/estimate.py`
- `tests/unit/test_estimate.py`

## Audit Trail

- EXTRACTED: 303 (99%)
- INFERRED: 4 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*