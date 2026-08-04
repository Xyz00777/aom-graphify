# JsonlEvent

> 82 nodes · cohesion 0.04

## Key Concepts

- **JsonlEvent** (66 connections) — `src/ansible_aom/core/event_types.py`
- **._emit_event_log()** (24 connections) — `src/ansible_aom/compact/renderer.py`
- **_BoundedSet** (16 connections) — `src/ansible_aom/compact/renderer.py`
- **JsonlTask** (14 connections) — `src/ansible_aom/core/event_types.py`
- **.update_state()** (12 connections) — `src/ansible_aom/compact/renderer.py`
- **._flush_ready_summaries()** (10 connections) — `src/ansible_aom/compact/renderer.py`
- **.__init__()** (10 connections) — `src/ansible_aom/compact/renderer.py`
- **.print_log()** (10 connections) — `src/ansible_aom/compact/renderer.py`
- **._task_dict()** (10 connections) — `src/ansible_aom/compact/renderer.py`
- **._announce_task()** (9 connections) — `src/ansible_aom/compact/renderer.py`
- **_truncate_msg()** (8 connections) — `src/ansible_aom/compact/format.py`
- **._bump_task_counters()** (8 connections) — `src/ansible_aom/compact/renderer.py`
- **._emit_task_summary()** (8 connections) — `src/ansible_aom/compact/renderer.py`
- **._format_loop_item_line()** (8 connections) — `src/ansible_aom/compact/renderer.py`
- **._flush_pending_skips()** (7 connections) — `src/ansible_aom/compact/renderer.py`
- **._maybe_flush_completed()** (7 connections) — `src/ansible_aom/compact/renderer.py`
- **is_async_poll_payload()** (7 connections) — `src/ansible_aom/core/_async_poll.py`
- **_verbose_ok_body()** (6 connections) — `src/ansible_aom/compact/format.py`
- **._count_completed_task()** (6 connections) — `src/ansible_aom/compact/renderer.py`
- **._event_time()** (6 connections) — `src/ansible_aom/compact/renderer.py`
- **._inline_duration_suffix()** (6 connections) — `src/ansible_aom/compact/renderer.py`
- **._stale_task_suffix()** (6 connections) — `src/ansible_aom/compact/renderer.py`
- **.add()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **.add_warning()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **._enter_terminal_event()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- *... and 57 more nodes in this community*

## Relationships

- [CompactRenderer](CompactRenderer.md) (31 shared connections)
- [datetime](datetime.md) (17 shared connections)
- [renderer.py](renderer.py.md) (15 shared connections)
- [format.py](format.py.md) (10 shared connections)
- [event_types.py](event_types.py.md) (6 shared connections)
- [_BoundedDict](_BoundedDict.md) (6 shared connections)
- [runner.py](runner.py.md) (5 shared connections)
- [_safe_loads](_safe_loads.md) (5 shared connections)
- [._render_status_panel](_render_status_panel.md) (4 shared connections)
- [models.py](models.py.md) (3 shared connections)
- [json.py](json.py.md) (3 shared connections)
- [_compute_mode_label](_compute_mode_label.md) (2 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/compact/renderer.py`
- `src/ansible_aom/core/_async_poll.py`
- `src/ansible_aom/core/duration.py`
- `src/ansible_aom/core/event_types.py`

## Audit Trail

- EXTRACTED: 355 (91%)
- INFERRED: 33 (9%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*