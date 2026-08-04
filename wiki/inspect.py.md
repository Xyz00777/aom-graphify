# inspect.py

> 29 nodes · cohesion 0.10

## Key Concepts

- **inspect.py** (42 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **build_verbose_lines()** (14 connections) — `src/ansible_aom/core/inspect_model.py`
- **task_ids_by_play()** (13 connections) — `src/ansible_aom/core/inspect_model.py`
- **query_verbose()** (11 connections) — `src/ansible_aom/session/index.py`
- **test_inspect_model_verbose.py** (7 connections) — `tests/unit/test_inspect_model_verbose.py`
- **test_build_verbose_lines_uses_precomputed_memberships()** (7 connections) — `tests/unit/test_inspect_model_verbose.py`
- **._render_detail_block()** (6 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **._render_verbose_placeholder()** (6 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **_stats_label()** (6 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **_session_with_verbose_events()** (5 connections) — `tests/unit/test_inspect_model_verbose.py`
- **_summarise_hosts()** (4 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **test_task_ids_by_play_from_prebuilt_tree()** (4 connections) — `tests/unit/test_inspect_model_verbose.py`
- **_fmt_duration_short()** (3 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **_render_stdout_lines()** (3 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **_stats_label_plain()** (3 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **test_build_verbose_lines_filters_by_scope()** (3 connections) — `tests/unit/test_inspect_model_verbose.py`
- **test_build_verbose_lines_ignores_unmatched_play_task_lines()** (3 connections) — `tests/unit/test_inspect_model_verbose.py`
- **Return ``play_name -> task_id`` membership from an already-built tree.      Call** (1 connections) — `src/ansible_aom/core/inspect_model.py`
- **Build the verbose-panel body for one session dict and focus scope.      In-memor** (1 connections) — `src/ansible_aom/core/inspect_model.py`
- **Verbose lines for a focus scope, filtered inside sqlite.      The WHERE clauses** (1 connections) — `src/ansible_aom/session/index.py`
- **Inspect TUI app — three-pane browser for past AOM sessions.  Pane layout (Horizo** (1 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **Render the per-task detail body.          Everything here is specific to the foc** (1 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **Render a colour-coded stats summary using Rich markup.** (1 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **Same as :func:`_stats_label` but without colour markup.      Used in the Runs-ro** (1 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **Colour-coded per-host roll-up using Rich markup.** (1 connections) — `src/ansible_aom/tui/screens/inspect.py`
- *... and 4 more nodes in this community*

## Relationships

- [index.py](index.py.md) (15 shared connections)
- [TaskTreeNode](TaskTreeNode.md) (12 shared connections)
- [inspect_model.py](inspect_model.py.md) (9 shared connections)
- [StatusCounts](StatusCounts.md) (9 shared connections)
- [text.py](text.py.md) (8 shared connections)
- [InspectApp](InspectApp.md) (6 shared connections)
- [_ConfirmDelete](_ConfirmDelete.md) (5 shared connections)
- [load_session](load_session.md) (4 shared connections)

## Source Files

- `src/ansible_aom/core/inspect_model.py`
- `src/ansible_aom/session/index.py`
- `src/ansible_aom/tui/screens/inspect.py`
- `tests/unit/test_inspect_model_verbose.py`

## Audit Trail

- EXTRACTED: 151 (99%)
- INFERRED: 1 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*