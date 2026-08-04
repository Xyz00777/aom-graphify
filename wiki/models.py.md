# models.py

> 202 nodes · cohesion 0.02

## Key Concepts

- **models.py** (86 connections) — `src/ansible_aom/core/models.py`
- **run_state.py** (63 connections) — `src/ansible_aom/core/run_state.py`
- **IncludeCacheEntry** (47 connections) — `src/ansible_aom/core/models.py`
- **parser.py** (43 connections) — `src/ansible_aom/core/parser.py`
- **Path** (43 connections)
- **includes.py** (36 connections) — `src/ansible_aom/core/includes.py`
- **preflight.py** (22 connections) — `src/ansible_aom/ansible/preflight.py`
- **graft_include_children()** (19 connections) — `src/ansible_aom/core/includes.py`
- **RoleCacheEntry** (19 connections) — `src/ansible_aom/core/models.py`
- **TestGraftIncludeChildren** (18 connections) — `tests/unit/test_include_cache.py`
- **Path** (15 connections)
- **resolve_includes_from_playbook()** (15 connections) — `src/ansible_aom/core/includes.py`
- **_discover_role()** (14 connections) — `src/ansible_aom/core/includes.py`
- **parse_include_tasks_file()** (13 connections) — `src/ansible_aom/core/includes.py`
- **test_include_cache.py** (13 connections) — `tests/unit/test_include_cache.py`
- **TestParseIncludeTasksFile** (13 connections) — `tests/unit/test_include_cache.py`
- **TestResolveIncludesFromPlaybook** (13 connections) — `tests/unit/test_include_cache.py`
- **resolve_role_relative_includes()** (12 connections) — `src/ansible_aom/core/includes.py`
- **_discover_include()** (11 connections) — `src/ansible_aom/core/includes.py`
- **discover_include_with_runtime_path()** (11 connections) — `src/ansible_aom/core/includes.py`
- **_graft_section_dfs()** (11 connections) — `src/ansible_aom/core/includes.py`
- **parse_role_tasks()** (11 connections) — `src/ansible_aom/core/includes.py`
- **TestDiscoverRole** (11 connections) — `tests/unit/test_include_cache.py`
- **TestParseRoleTasks** (11 connections) — `tests/unit/test_include_cache.py`
- **_make_play()** (10 connections) — `tests/unit/test_include_cache.py`
- *... and 177 more nodes in this community*

## Relationships

- [TaskDefinition](TaskDefinition.md) (27 shared connections)
- [RunState](RunState.md) (23 shared connections)
- [PlayDefinition](PlayDefinition.md) (20 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (12 shared connections)
- [TreeProjection](TreeProjection.md) (11 shared connections)
- [WarningType](WarningType.md) (10 shared connections)
- [HostRunState](HostRunState.md) (10 shared connections)
- [_BoundedDict](_BoundedDict.md) (9 shared connections)
- [Status](Status.md) (8 shared connections)
- [_play_start](_play_start.md) (7 shared connections)
- [runner.py](runner.py.md) (6 shared connections)
- [run_preflight](run_preflight.md) (5 shared connections)

## Source Files

- `src/ansible_aom/ansible/preflight.py`
- `src/ansible_aom/core/includes.py`
- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/parser.py`
- `src/ansible_aom/core/run_state.py`
- `src/ansible_aom/core/state_machine.py`
- `tests/unit/test_host_resolution.py`
- `tests/unit/test_include_cache.py`
- `tests/unit/test_runner_heartbeat.py`
- `tests/unit/test_warnings.py`

## Audit Trail

- EXTRACTED: 1009 (93%)
- INFERRED: 78 (7%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*