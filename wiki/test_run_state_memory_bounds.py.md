# test_run_state_memory_bounds.py

> 48 nodes · cohesion 0.06

## Key Concepts

- **test_run_state_memory_bounds.py** (14 connections) — `tests/unit/test_run_state_memory_bounds.py`
- **_build_compact_renderer()** (9 connections) — `tests/unit/test_renderer_unbounded_caps.py`
- **test_renderer_unbounded_caps.py** (8 connections) — `tests/unit/test_renderer_unbounded_caps.py`
- **test_run_state_set_caps.py** (8 connections) — `tests/unit/test_run_state_set_caps.py`
- **state_machine.py** (7 connections) — `src/ansible_aom/core/state_machine.py`
- **_play_start()** (7 connections) — `tests/unit/test_run_state_memory_bounds.py`
- **_task_start()** (6 connections) — `tests/unit/test_run_state_memory_bounds.py`
- **test_max_hosts_per_task_enforced()** (6 connections) — `tests/unit/test_run_state_memory_bounds.py`
- **test_max_total_host_run_states_enforced()** (6 connections) — `tests/unit/test_run_state_memory_bounds.py`
- **_ts()** (6 connections) — `tests/unit/test_run_state_memory_bounds.py`
- **test_max_tasks_per_play_enforced()** (5 connections) — `tests/unit/test_run_state_memory_bounds.py`
- **test_truncated_events_independent_counters()** (5 connections) — `tests/unit/test_run_state_memory_bounds.py`
- **test_max_plays_enforced()** (4 connections) — `tests/unit/test_run_state_memory_bounds.py`
- **test_announced_task_uuids_capped()** (3 connections) — `tests/unit/test_renderer_unbounded_caps.py`
- **test_completed_task_ids_capped()** (3 connections) — `tests/unit/test_renderer_unbounded_caps.py`
- **test_renderer_constructor_uses_sane_initial_caps()** (3 connections) — `tests/unit/test_renderer_unbounded_caps.py`
- **test_seen_warning_messages_capped()** (3 connections) — `tests/unit/test_renderer_unbounded_caps.py`
- **test_streamed_loop_items_capped()** (3 connections) — `tests/unit/test_renderer_unbounded_caps.py`
- **test_truncated_events_starts_empty()** (3 connections) — `tests/unit/test_run_state_memory_bounds.py`
- **test_grafted_role_names_capped()** (3 connections) — `tests/unit/test_run_state_set_caps.py`
- **test_grafted_uuids_capped_at_max_tasks_per_play()** (3 connections) — `tests/unit/test_run_state_set_caps.py`
- **test_play_window_counts_capped_at_max_plays()** (3 connections) — `tests/unit/test_run_state_set_caps.py`
- **test_unknown_events_keys_naturally_bounded()** (3 connections) — `tests/unit/test_run_state_set_caps.py`
- **_runner_on_ok()** (2 connections) — `tests/unit/test_run_state_memory_bounds.py`
- **test_truncated_constants_pinned()** (2 connections) — `tests/unit/test_run_state_memory_bounds.py`
- *... and 23 more nodes in this community*

## Relationships

- [RunState](RunState.md) (10 shared connections)
- [run_state.py](run_state.py.md) (3 shared connections)
- [StreamPhase](StreamPhase.md) (1 shared connections)
- [test_parser_recap_cap.py](test_parser_recap_cap.py.md) (1 shared connections)
- [CompactRenderer](CompactRenderer.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/state_machine.py`
- `tests/unit/test_renderer_unbounded_caps.py`
- `tests/unit/test_run_state_memory_bounds.py`
- `tests/unit/test_run_state_set_caps.py`

## Audit Trail

- EXTRACTED: 147 (99%)
- INFERRED: 1 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*