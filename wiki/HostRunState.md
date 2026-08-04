# HostRunState

> 286 nodes · cohesion 0.01

## Key Concepts

- **HostRunState** (285 connections) — `src/ansible_aom/core/models.py`
- **PlayRunState** (252 connections) — `src/ansible_aom/core/models.py`
- **TaskRunState** (244 connections) — `src/ansible_aom/core/models.py`
- **test_cli.py** (34 connections) — `tests/unit/test_cli.py`
- **test_compact_renderer.py** (22 connections) — `tests/integration/test_compact_renderer.py`
- **TestHostRunState** (22 connections) — `tests/unit/test_models.py`
- **TestPlayRunState** (22 connections) — `tests/unit/test_models.py`
- **TestTaskRunState** (20 connections) — `tests/unit/test_models.py`
- **determine_exit_code()** (19 connections) — `src/ansible_aom/core/exit_code.py`
- **TestRendererProtocol** (17 connections) — `tests/unit/test_cli.py`
- **TestDisplayClass** (16 connections) — `tests/integration/test_compact_renderer.py`
- **TestNonTTYBehavior** (16 connections) — `tests/integration/test_compact_renderer.py`
- **TestRefreshStrategy** (16 connections) — `tests/integration/test_compact_renderer.py`
- **TestTerminalSizeCheck** (16 connections) — `tests/integration/test_compact_renderer.py`
- **TestPackageIdentity** (16 connections) — `tests/unit/test_cli.py`
- **TestRendererFactory** (16 connections) — `tests/unit/test_cli.py`
- **test_tree_upcoming_plays.py** (15 connections) — `tests/compact/test_tree_upcoming_plays.py`
- **TestCompactRendererHandleCompletion** (15 connections) — `tests/integration/test_compact_renderer.py`
- **TestCompactRendererProtocol** (15 connections) — `tests/integration/test_compact_renderer.py`
- **TestExitCodes** (15 connections) — `tests/integration/test_compact_renderer.py`
- **TestElapsedTimeFormat** (15 connections) — `tests/unit/test_event_processing.py`
- **TestHandleEventMalformedPayloads** (15 connections) — `tests/unit/test_event_processing.py`
- **TestCLIEntryPoint** (14 connections) — `tests/unit/test_cli.py`
- **TestTimestampLocalTimezone** (14 connections) — `tests/unit/test_event_processing.py`
- **TestPasswordPassThrough** (13 connections) — `tests/integration/test_compact_renderer.py`
- *... and 261 more nodes in this community*

## Relationships

- [Status](Status.md) (175 shared connections)
- [RunState](RunState.md) (156 shared connections)
- [PlayDefinition](PlayDefinition.md) (75 shared connections)
- [TaskDefinition](TaskDefinition.md) (73 shared connections)
- [CompactRenderer](CompactRenderer.md) (56 shared connections)
- [TreeProjection](TreeProjection.md) (41 shared connections)
- [Display](Display.md) (26 shared connections)
- [create_parser](create_parser.md) (24 shared connections)
- [JsonRenderer](JsonRenderer.md) (22 shared connections)
- [format_failure_recap](format_failure_recap.md) (21 shared connections)
- [format_host_rows](format_host_rows.md) (15 shared connections)
- [._render_status_panel](_render_status_panel.md) (14 shared connections)

## Source Files

- `src/ansible_aom/core/exit_code.py`
- `src/ansible_aom/core/models.py`
- `tests/compact/test_completion_recap.py`
- `tests/compact/test_task_progress.py`
- `tests/compact/test_tree_render.py`
- `tests/compact/test_tree_upcoming_plays.py`
- `tests/compact/test_tree_upcoming_tasks.py`
- `tests/integration/test_compact_renderer.py`
- `tests/tui/test_panels.py`
- `tests/unit/test_cli.py`
- `tests/unit/test_dynamic_counters.py`
- `tests/unit/test_event_processing.py`
- `tests/unit/test_json_renderer.py`
- `tests/unit/test_models.py`
- `tests/unit/test_stale_running_cleanup.py`
- `tests/unit/test_status_tally.py`

## Audit Trail

- EXTRACTED: 1094 (55%)
- INFERRED: 908 (45%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*