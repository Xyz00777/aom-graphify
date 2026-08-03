# HostRunState

> 388 nodes · cohesion 0.01

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
- **TestSignalHandling** (19 connections) — `tests/integration/test_compact_renderer.py`
- **TestRendererProtocol** (17 connections) — `tests/unit/test_cli.py`
- **format_failure_recap()** (16 connections) — `src/ansible_aom/compact/format.py`
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
- **TestCLIEntryPoint** (14 connections) — `tests/unit/test_cli.py`
- **TestCoreModuleStructure** (14 connections) — `tests/unit/test_cli.py`
- **TestExitCodes** (14 connections) — `tests/unit/test_cli.py`
- *... and 363 more nodes in this community*

## Relationships

- [Status](Status.md) (194 shared connections)
- [RunState](RunState.md) (178 shared connections)
- [TaskDefinition](TaskDefinition.md) (115 shared connections)
- [CompactRenderer](CompactRenderer.md) (67 shared connections)
- [TreeProjection](TreeProjection.md) (45 shared connections)
- [create_parser](create_parser.md) (44 shared connections)
- [JsonRenderer](JsonRenderer.md) (35 shared connections)
- [.from_run_state](from_run_state.md) (32 shared connections)
- [Display](Display.md) (29 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (23 shared connections)
- [format_host_rows](format_host_rows.md) (15 shared connections)
- [._render_status_panel](_render_status_panel.md) (14 shared connections)

## Source Files

- `src/ansible_aom/compact/exit_code.py`
- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/core/exit_code.py`
- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/parity.py`
- `tests/compact/test_completion_recap.py`
- `tests/compact/test_status_bar_colors.py`
- `tests/compact/test_task_progress.py`
- `tests/compact/test_tree_render.py`
- `tests/compact/test_tree_upcoming_plays.py`
- `tests/compact/test_tree_upcoming_tasks.py`
- `tests/integration/test_compact_renderer.py`
- `tests/tui/test_panels.py`
- `tests/unit/test_cli.py`
- `tests/unit/test_json_renderer.py`
- `tests/unit/test_models.py`
- `tests/unit/test_run_state_index.py`
- `tests/unit/test_stale_running_cleanup.py`
- `tests/unit/test_status_tally.py`
- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 1345 (58%)
- INFERRED: 991 (42%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*