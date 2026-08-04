# IncludeCacheEntry

> 55 nodes · cohesion 0.08

## Key Concepts

- **IncludeCacheEntry** (47 connections) — `src/ansible_aom/core/models.py`
- **includes.py** (36 connections) — `src/ansible_aom/core/includes.py`
- **preflight.py** (22 connections) — `src/ansible_aom/ansible/preflight.py`
- **graft_include_children()** (19 connections) — `src/ansible_aom/core/includes.py`
- **Path** (15 connections)
- **resolve_includes_from_playbook()** (15 connections) — `src/ansible_aom/core/includes.py`
- **_discover_role()** (14 connections) — `src/ansible_aom/core/includes.py`
- **parse_include_tasks_file()** (13 connections) — `src/ansible_aom/core/includes.py`
- **resolve_role_relative_includes()** (12 connections) — `src/ansible_aom/core/includes.py`
- **_discover_include()** (11 connections) — `src/ansible_aom/core/includes.py`
- **discover_include_with_runtime_path()** (11 connections) — `src/ansible_aom/core/includes.py`
- **_graft_section_dfs()** (11 connections) — `src/ansible_aom/core/includes.py`
- **parse_role_tasks()** (11 connections) — `src/ansible_aom/core/includes.py`
- **_load_task_list()** (9 connections) — `src/ansible_aom/core/includes.py`
- **_walk_documents_for_includes()** (9 connections) — `src/ansible_aom/core/includes.py`
- **_graft_imported_playbook()** (8 connections) — `src/ansible_aom/core/includes.py`
- **_lookup_directive()** (8 connections) — `src/ansible_aom/core/includes.py`
- **_scan_tasks_for_includes_impl()** (8 connections) — `src/ansible_aom/core/includes.py`
- **_build_name_index()** (7 connections) — `src/ansible_aom/core/includes.py`
- **_scan_role_tasks_for_includes()** (7 connections) — `src/ansible_aom/core/includes.py`
- **_scan_tasks_for_includes()** (6 connections) — `src/ansible_aom/core/includes.py`
- **_collect_role_refs_from_tasks()** (5 connections) — `src/ansible_aom/core/includes.py`
- **_find_nested_role_includes()** (5 connections) — `src/ansible_aom/core/includes.py`
- **_graft_children()** (5 connections) — `src/ansible_aom/core/includes.py`
- **_roles_referenced()** (5 connections) — `src/ansible_aom/core/includes.py`
- *... and 30 more nodes in this community*

## Relationships

- [Path](Path.md) (34 shared connections)
- [TestGraftIncludeChildren](TestGraftIncludeChildren.md) (15 shared connections)
- [TaskDefinition](TaskDefinition.md) (13 shared connections)
- [RunState](RunState.md) (8 shared connections)
- [run_preflight](run_preflight.md) (6 shared connections)
- [PlayDefinition](PlayDefinition.md) (6 shared connections)
- [run_state.py](run_state.py.md) (6 shared connections)
- [TestDiscoverRole](TestDiscoverRole.md) (6 shared connections)
- [Status](Status.md) (5 shared connections)
- [RoleCacheEntry](RoleCacheEntry.md) (5 shared connections)
- [_play_start](_play_start.md) (5 shared connections)
- [assemble_definitions](assemble_definitions.md) (3 shared connections)

## Source Files

- `src/ansible_aom/ansible/preflight.py`
- `src/ansible_aom/core/includes.py`
- `src/ansible_aom/core/models.py`

## Audit Trail

- EXTRACTED: 337 (94%)
- INFERRED: 22 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*