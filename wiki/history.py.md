# history.py

> 17 nodes · cohesion 0.22

## Key Concepts

- **history.py** (31 connections) — `src/ansible_aom/session/history.py`
- **_iter_completed_sessions()** (7 connections) — `src/ansible_aom/session/history.py`
- **_mine_and_replace()** (7 connections) — `src/ansible_aom/session/history.py`
- **Path** (7 connections)
- **_build_prior()** (6 connections) — `src/ansible_aom/session/history.py`
- **_match_loose()** (6 connections) — `src/ansible_aom/session/history.py`
- **_mine_task_wall()** (5 connections) — `src/ansible_aom/session/history.py`
- **_parse_iso()** (5 connections) — `src/ansible_aom/session/history.py`
- **_mine_loop_totals()** (4 connections) — `src/ansible_aom/session/history.py`
- **Any** (4 connections)
- **datetime** (4 connections)
- **Pure history lookup: find the most recent prior run matching a config + host cou** (1 connections) — `src/ansible_aom/session/history.py`
- **Mine the per-task wall profile + result segmentation from a session.      Return** (1 connections) — `src/ansible_aom/session/history.py`
- **Yield ``(end_time, meta, session_path)`` for every valid completed session.** (1 connections) — `src/ansible_aom/session/history.py`
- **True when the stored session matches the current invocation loosely.      Loose** (1 connections) — `src/ansible_aom/session/history.py`
- **Mine per-task wall and loop totals for *prior*, returning a new PriorRun.** (1 connections) — `src/ansible_aom/session/history.py`
- **Mine ``{task.path: {host: item_count}}`` from a session's events.      Scans ``e** (1 connections) — `src/ansible_aom/session/history.py`

## Relationships

- [build_run_config_key](build_run_config_key.md) (14 shared connections)
- [PriorRun](PriorRun.md) (4 shared connections)
- [load_session](load_session.md) (3 shared connections)
- [runner.py](runner.py.md) (1 shared connections)
- [format.py](format.py.md) (1 shared connections)
- [renderer.py](renderer.py.md) (1 shared connections)
- [json.py](json.py.md) (1 shared connections)
- [drivers/replay.py](drivers-replay.py.md) (1 shared connections)
- [test_prior_denominator.py](test_prior_denominator.py.md) (1 shared connections)
- [Shift Modifier Keybindings](Shift_Modifier_Keybindings.md) (1 shared connections)
- [test_history_loop_totals.py](test_history_loop_totals.py.md) (1 shared connections)
- [Run Diagnostics Accumulator](Run_Diagnostics_Accumulator.md) (1 shared connections)

## Source Files

- `src/ansible_aom/session/history.py`

## Audit Trail

- EXTRACTED: 92 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*