# ._emit_event_log

> 66 nodes · cohesion 0.04

## Key Concepts

- **._emit_event_log()** (24 connections) — `src/ansible_aom/compact/renderer.py`
- **_wrap()** (19 connections) — `src/ansible_aom/compact/format.py`
- **._flush_ready_summaries()** (10 connections) — `src/ansible_aom/compact/renderer.py`
- **.print_log()** (10 connections) — `src/ansible_aom/compact/renderer.py`
- **._announce_task()** (9 connections) — `src/ansible_aom/compact/renderer.py`
- **_truncate_msg()** (8 connections) — `src/ansible_aom/compact/format.py`
- **._emit_task_summary()** (8 connections) — `src/ansible_aom/compact/renderer.py`
- **._format_loop_item_line()** (8 connections) — `src/ansible_aom/compact/renderer.py`
- **._flush_pending_skips()** (7 connections) — `src/ansible_aom/compact/renderer.py`
- **._maybe_flush_completed()** (7 connections) — `src/ansible_aom/compact/renderer.py`
- **is_async_poll_payload()** (7 connections) — `src/ansible_aom/core/_async_poll.py`
- **_verbose_ok_body()** (6 connections) — `src/ansible_aom/compact/format.py`
- **._count_completed_task()** (6 connections) — `src/ansible_aom/compact/renderer.py`
- **._inline_duration_suffix()** (6 connections) — `src/ansible_aom/compact/renderer.py`
- **._stale_task_suffix()** (6 connections) — `src/ansible_aom/compact/renderer.py`
- **_replace_surrogates()** (5 connections) — `src/ansible_aom/compact/format.py`
- **.add()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **.add_warning()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **._enter_terminal_event()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **._format_duration()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **._maybe_emit_pause_seconds_hint()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **.set_definitions()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **_extract_error_msg()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **_count_cell()** (4 connections) — `src/ansible_aom/compact/format.py`
- **._build_status_suffix()** (4 connections) — `src/ansible_aom/compact/renderer.py`
- *... and 41 more nodes in this community*

## Relationships

- [CompactRenderer](CompactRenderer.md) (22 shared connections)
- [JsonlEvent](JsonlEvent.md) (15 shared connections)
- [renderer.py](renderer.py.md) (12 shared connections)
- [format.py](format.py.md) (6 shared connections)
- [test_r6_encoding_roundtrip.py](test_r6_encoding_roundtrip.py.md) (4 shared connections)
- [format_host_rows](format_host_rows.md) (2 shared connections)
- [_compute_mode_label](_compute_mode_label.md) (2 shared connections)
- [format_host_summary](format_host_summary.md) (2 shared connections)
- [test_task_progress.py](test_task_progress.py.md) (2 shared connections)
- [Host Result Hide Filter](Host_Result_Hide_Filter.md) (2 shared connections)
- [TreeProjection](TreeProjection.md) (2 shared connections)
- [inspect_model.py](inspect_model.py.md) (2 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/compact/renderer.py`
- `src/ansible_aom/core/_async_poll.py`
- `src/ansible_aom/core/duration.py`
- `tests/integration/test_r6_encoding_roundtrip.py`

## Audit Trail

- EXTRACTED: 248 (98%)
- INFERRED: 5 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*