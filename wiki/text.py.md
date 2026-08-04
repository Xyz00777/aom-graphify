# text.py

> 57 nodes · cohesion 0.07

## Key Concepts

- **text.py** (36 connections) — `src/ansible_aom/inspect/text.py`
- **render_session()** (18 connections) — `src/ansible_aom/inspect/text.py`
- **build_verbose_lines()** (14 connections) — `src/ansible_aom/core/inspect_model.py`
- **render_session_from_index()** (14 connections) — `src/ansible_aom/inspect/text.py`
- **task_ids_by_play()** (13 connections) — `src/ansible_aom/core/inspect_model.py`
- **test_inspect_text_golden.py** (13 connections) — `tests/compact/test_inspect_text_golden.py`
- **_render_verbose()** (11 connections) — `src/ansible_aom/inspect/text.py`
- **query_verbose()** (11 connections) — `src/ansible_aom/session/index.py`
- **_load()** (11 connections) — `tests/compact/test_inspect_text_golden.py`
- **_render_failures_from_index()** (8 connections) — `src/ansible_aom/inspect/text.py`
- **_resolve_verbose_scope()** (7 connections) — `src/ansible_aom/inspect/text.py`
- **test_inspect_model_verbose.py** (7 connections) — `tests/unit/test_inspect_model_verbose.py`
- **test_build_verbose_lines_uses_precomputed_memberships()** (7 connections) — `tests/unit/test_inspect_model_verbose.py`
- **_hydrate_node()** (6 connections) — `src/ansible_aom/inspect/text.py`
- **_iter_tree()** (6 connections) — `src/ansible_aom/inspect/text.py`
- **_play_name_for_task()** (6 connections) — `src/ansible_aom/inspect/text.py`
- **_render_failures()** (6 connections) — `src/ansible_aom/inspect/text.py`
- **_render_header()** (6 connections) — `src/ansible_aom/inspect/text.py`
- **._render_verbose_placeholder()** (6 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **_iter_failed_tasks()** (5 connections) — `src/ansible_aom/inspect/text.py`
- **_render_detail()** (5 connections) — `src/ansible_aom/inspect/text.py`
- **_session_with_verbose_events()** (5 connections) — `tests/unit/test_inspect_model_verbose.py`
- **_fmt_duration()** (4 connections) — `src/ansible_aom/inspect/text.py`
- **render_session_list()** (4 connections) — `src/ansible_aom/inspect/text.py`
- **test_task_ids_by_play_from_prebuilt_tree()** (4 connections) — `tests/unit/test_inspect_model_verbose.py`
- *... and 32 more nodes in this community*

## Relationships

- [TaskTreeNode](TaskTreeNode.md) (19 shared connections)
- [inspect_model.py](inspect_model.py.md) (16 shared connections)
- [StatusCounts](StatusCounts.md) (13 shared connections)
- [load_session](load_session.md) (8 shared connections)
- [inspect/cli.py](inspect-cli.py.md) (5 shared connections)
- [InspectApp](InspectApp.md) (1 shared connections)
- [json.py](json.py.md) (1 shared connections)
- [RunSummary Schema Contract](RunSummary_Schema_Contract.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/inspect_model.py`
- `src/ansible_aom/inspect/text.py`
- `src/ansible_aom/session/index.py`
- `src/ansible_aom/tui/screens/inspect.py`
- `tests/compact/test_inspect_text_golden.py`
- `tests/unit/test_inspect_model_verbose.py`

## Audit Trail

- EXTRACTED: 292 (99%)
- INFERRED: 2 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*