# JsonlEvent

> 71 nodes · cohesion 0.04

## Key Concepts

- **JsonlEvent** (66 connections) — `src/ansible_aom/core/event_types.py`
- **._emit_event_log()** (24 connections) — `src/ansible_aom/compact/renderer.py`
- **_wrap()** (19 connections) — `src/ansible_aom/compact/format.py`
- **_BoundedSet** (16 connections) — `src/ansible_aom/compact/renderer.py`
- **JsonlTask** (14 connections) — `src/ansible_aom/core/event_types.py`
- **.update_state()** (12 connections) — `src/ansible_aom/compact/renderer.py`
- **._flush_ready_summaries()** (10 connections) — `src/ansible_aom/compact/renderer.py`
- **.__init__()** (10 connections) — `src/ansible_aom/compact/renderer.py`
- **.print_log()** (10 connections) — `src/ansible_aom/compact/renderer.py`
- **._task_dict()** (10 connections) — `src/ansible_aom/compact/renderer.py`
- **._announce_task()** (9 connections) — `src/ansible_aom/compact/renderer.py`
- **._bump_task_counters()** (8 connections) — `src/ansible_aom/compact/renderer.py`
- **._emit_task_summary()** (8 connections) — `src/ansible_aom/compact/renderer.py`
- **._flush_pending_skips()** (7 connections) — `src/ansible_aom/compact/renderer.py`
- **._maybe_flush_completed()** (7 connections) — `src/ansible_aom/compact/renderer.py`
- **._count_completed_task()** (6 connections) — `src/ansible_aom/compact/renderer.py`
- **._event_time()** (6 connections) — `src/ansible_aom/compact/renderer.py`
- **._inline_duration_suffix()** (6 connections) — `src/ansible_aom/compact/renderer.py`
- **._stale_task_suffix()** (6 connections) — `src/ansible_aom/compact/renderer.py`
- **.add()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **.add_warning()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **._enter_terminal_event()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **._format_duration()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **._hosts_dict()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **._maybe_emit_pause_seconds_hint()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- *... and 46 more nodes in this community*

## Relationships

- [CompactRenderer](CompactRenderer.md) (29 shared connections)
- [RunState](RunState.md) (19 shared connections)
- [renderer.py](renderer.py.md) (12 shared connections)
- [run_state.py](run_state.py.md) (8 shared connections)
- [format.py](format.py.md) (7 shared connections)
- [._render_status_panel](_render_status_panel.md) (5 shared connections)
- [run_playbook](run_playbook.md) (5 shared connections)
- [event_types.py](event_types.py.md) (5 shared connections)
- [_safe_loads](_safe_loads.md) (5 shared connections)
- [format_host_summary](format_host_summary.md) (3 shared connections)
- [Status](Status.md) (3 shared connections)
- [json.py](json.py.md) (3 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/compact/renderer.py`
- `src/ansible_aom/core/duration.py`
- `src/ansible_aom/core/event_types.py`

## Audit Trail

- EXTRACTED: 328 (91%)
- INFERRED: 31 (9%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*