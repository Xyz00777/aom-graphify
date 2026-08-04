# HostRunState

> 251 nodes · cohesion 0.02

## Key Concepts

- **HostRunState** (285 connections) — `src/ansible_aom/core/models.py`
- **PlayRunState** (252 connections) — `src/ansible_aom/core/models.py`
- **TaskRunState** (244 connections) — `src/ansible_aom/core/models.py`
- **test_compact_renderer.py** (22 connections) — `tests/integration/test_compact_renderer.py`
- **TestHostRunState** (22 connections) — `tests/unit/test_models.py`
- **TestPlayRunState** (22 connections) — `tests/unit/test_models.py`
- **TestTaskRunState** (20 connections) — `tests/unit/test_models.py`
- **determine_exit_code()** (19 connections) — `src/ansible_aom/core/exit_code.py`
- **TestSignalHandling** (19 connections) — `tests/integration/test_compact_renderer.py`
- **TestMemoryBounds** (17 connections) — `tests/unit/test_models.py`
- **format_failure_recap()** (16 connections) — `src/ansible_aom/compact/format.py`
- **TestDisplayClass** (16 connections) — `tests/integration/test_compact_renderer.py`
- **TestNonTTYBehavior** (16 connections) — `tests/integration/test_compact_renderer.py`
- **TestRefreshStrategy** (16 connections) — `tests/integration/test_compact_renderer.py`
- **test_tree_upcoming_plays.py** (15 connections) — `tests/compact/test_tree_upcoming_plays.py`
- **TestCompactRendererProtocol** (15 connections) — `tests/integration/test_compact_renderer.py`
- **TestExitCodes** (15 connections) — `tests/integration/test_compact_renderer.py`
- **TestFormatFailureRecap** (13 connections) — `tests/compact/test_completion_recap.py`
- **TestPasswordPassThrough** (13 connections) — `tests/integration/test_compact_renderer.py`
- **TestExitCode1** (13 connections) — `tests/unit/test_cli.py`
- **TestExitCode2** (13 connections) — `tests/unit/test_cli.py`
- **TestCompactDependencies** (12 connections) — `tests/integration/test_compact_renderer.py`
- **TestCompactRendererStart** (12 connections) — `tests/integration/test_compact_renderer.py`
- **TestNonTTYRefreshFallback** (12 connections) — `tests/integration/test_compact_renderer.py`
- **TestRichLiveConfiguration** (12 connections) — `tests/integration/test_compact_renderer.py`
- *... and 226 more nodes in this community*

## Relationships

- [RunState](RunState.md) (129 shared connections)
- [StatusBarConfig](StatusBarConfig.md) (58 shared connections)
- [test_cli.py](test_cli.py.md) (56 shared connections)
- [WarningType](WarningType.md) (51 shared connections)
- [WarningEntry](WarningEntry.md) (45 shared connections)
- [CompactRenderer](CompactRenderer.md) (43 shared connections)
- [TreeProjection](TreeProjection.md) (37 shared connections)
- [PlayDefinition](PlayDefinition.md) (33 shared connections)
- [TaskDefinition](TaskDefinition.md) (33 shared connections)
- [Status](Status.md) (31 shared connections)
- [Display](Display.md) (27 shared connections)
- [.from_run_state](from_run_state.md) (25 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/core/exit_code.py`
- `src/ansible_aom/core/models.py`
- `tests/compact/test_completion_recap.py`
- `tests/compact/test_status_bar_colors.py`
- `tests/compact/test_task_progress.py`
- `tests/compact/test_tree_render.py`
- `tests/compact/test_tree_upcoming_plays.py`
- `tests/integration/test_compact_renderer.py`
- `tests/tui/test_panels.py`
- `tests/unit/test_cli.py`
- `tests/unit/test_dynamic_counters.py`
- `tests/unit/test_json_renderer.py`
- `tests/unit/test_models.py`
- `tests/unit/test_stale_running_cleanup.py`

## Audit Trail

- EXTRACTED: 961 (53%)
- INFERRED: 838 (47%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*