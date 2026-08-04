# build_run_config_key

> 65 nodes · cohesion 0.07

## Key Concepts

- **build_run_config_key()** (44 connections) — `src/ansible_aom/core/run_config.py`
- **find_previous_run()** (36 connections) — `src/ansible_aom/session/history.py`
- **test_history.py** (17 connections) — `tests/unit/test_history.py`
- **test_run_config.py** (14 connections) — `tests/unit/test_run_config.py`
- **test_history_roundtrip.py** (13 connections) — `tests/integration/test_history_roundtrip.py`
- **Path** (13 connections)
- **run_config.py** (12 connections) — `src/ansible_aom/core/run_config.py`
- **_write_session()** (12 connections) — `tests/unit/test_history.py`
- **Path** (12 connections)
- **RunConfigKey** (9 connections) — `src/ansible_aom/core/run_config.py`
- **test_runner_pushes_prior_run_into_renderer()** (8 connections) — `tests/integration/test_history_roundtrip.py`
- **_match_strict()** (6 connections) — `src/ansible_aom/session/history.py`
- **Path** (6 connections)
- **test_different_tags_match_via_fallback()** (6 connections) — `tests/integration/test_history_roundtrip.py`
- **test_failed_session_is_not_returned()** (6 connections) — `tests/integration/test_history_roundtrip.py`
- **test_corrupt_meta_is_skipped()** (6 connections) — `tests/unit/test_history.py`
- **test_fallback_loose_match_when_config_differs()** (6 connections) — `tests/unit/test_history.py`
- **test_loose_match_filters_mismatched_host_count()** (6 connections) — `tests/unit/test_history.py`
- **test_loose_match_works_with_any_flag_variation()** (6 connections) — `tests/unit/test_history.py`
- **test_returns_most_recent_matching_completed_run()** (6 connections) — `tests/unit/test_history.py`
- **test_skips_non_completed_status()** (6 connections) — `tests/unit/test_history.py`
- **test_skips_sessions_missing_counts()** (6 connections) — `tests/unit/test_history.py`
- **test_strict_match_takes_precedence_over_loose()** (6 connections) — `tests/unit/test_history.py`
- **test_different_host_count_does_not_match()** (5 connections) — `tests/integration/test_history_roundtrip.py`
- **test_most_recent_completed_wins()** (5 connections) — `tests/integration/test_history_roundtrip.py`
- *... and 40 more nodes in this community*

## Relationships

- [history.py](history.py.md) (18 shared connections)
- [Run Diagnostics Accumulator](Run_Diagnostics_Accumulator.md) (11 shared connections)
- [SessionManager](SessionManager.md) (6 shared connections)
- [runner.py](runner.py.md) (3 shared connections)
- [test_history_loop_totals.py](test_history_loop_totals.py.md) (3 shared connections)
- [Terminal Size Check](Terminal_Size_Check.md) (3 shared connections)
- [run_playbook](run_playbook.md) (3 shared connections)
- [json.py](json.py.md) (2 shared connections)
- [models.py](models.py.md) (1 shared connections)
- [store.py](store.py.md) (1 shared connections)
- [PlayDefinition](PlayDefinition.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/run_config.py`
- `src/ansible_aom/session/history.py`
- `tests/integration/test_history_roundtrip.py`
- `tests/unit/test_history.py`
- `tests/unit/test_run_config.py`

## Audit Trail

- EXTRACTED: 354 (98%)
- INFERRED: 6 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*