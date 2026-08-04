# datetime

> 45 nodes · cohesion 0.08

## Key Concepts

- **datetime** (15 connections)
- **._handle_v2_playbook_on_task_start()** (14 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_runner_on_start()** (13 connections) — `src/ansible_aom/core/run_state.py`
- **._task_dict()** (13 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_runner_on_failed()** (12 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_runner_on_ok()** (12 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_runner_on_skipped()** (12 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_runner_on_unreachable()** (12 connections) — `src/ansible_aom/core/run_state.py`
- **._resolve_play_id()** (12 connections) — `src/ansible_aom/core/run_state.py`
- **_reserve_host_run_state()** (11 connections) — `src/ansible_aom/core/run_state.py`
- **._resolve_runner_task()** (11 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_runner_item_on()** (9 connections) — `src/ansible_aom/core/run_state.py`
- **._hosts_dict()** (9 connections) — `src/ansible_aom/core/run_state.py`
- **._note_unmatched()** (8 connections) — `src/ansible_aom/core/run_state.py`
- **._prior_host_start_time()** (8 connections) — `src/ansible_aom/core/run_state.py`
- **._finalize_play()** (7 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_playbook_on_play_start()** (7 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_playbook_on_handler_task_start()** (5 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_playbook_on_stats()** (5 connections) — `src/ansible_aom/core/run_state.py`
- **._parent_role_from_cache()** (5 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_playbook_on_start()** (4 connections) — `src/ansible_aom/core/run_state.py`
- **._resolve_play_for_task()** (4 connections) — `src/ansible_aom/core/run_state.py`
- **._resolve_play_hosts()** (4 connections) — `src/ansible_aom/core/run_state.py`
- **Look up preflight resolved_hosts for a runtime play.          Preflight assigns** (1 connections) — `src/ansible_aom/core/run_state.py`
- **Handle v2_playbook_on_handler_task_start event (same as task_start).** (1 connections) — `src/ansible_aom/core/run_state.py`
- *... and 20 more nodes in this community*

## Relationships

- [RunState](RunState.md) (24 shared connections)
- [HostRunState](HostRunState.md) (19 shared connections)
- [JsonlEvent](JsonlEvent.md) (17 shared connections)
- [models.py](models.py.md) (4 shared connections)
- [_BoundedDict](_BoundedDict.md) (2 shared connections)
- [TestTimestampLocalTimezone](TestTimestampLocalTimezone.md) (1 shared connections)
- [TreeProjection](TreeProjection.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/run_state.py`

## Audit Trail

- EXTRACTED: 234 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*