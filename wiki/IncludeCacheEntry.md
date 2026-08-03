# IncludeCacheEntry

> 180 nodes · cohesion 0.02

## Key Concepts

- **IncludeCacheEntry** (47 connections) — `src/ansible_aom/core/models.py`
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
- **TestCacheEntryProperties** (10 connections) — `tests/unit/test_include_cache.py`
- **TestDiscoverInclude** (10 connections) — `tests/unit/test_include_cache.py`
- **_load_task_list()** (9 connections) — `src/ansible_aom/core/includes.py`
- *... and 155 more nodes in this community*

## Relationships

- [TaskDefinition](TaskDefinition.md) (37 shared connections)
- [RunState](RunState.md) (19 shared connections)
- [JsonlEvent](JsonlEvent.md) (9 shared connections)
- [run_preflight](run_preflight.md) (6 shared connections)
- [WarningType](WarningType.md) (5 shared connections)
- [StreamPhase](StreamPhase.md) (5 shared connections)
- [_play_start](_play_start.md) (5 shared connections)
- [TestRoleGrouping](TestRoleGrouping.md) (3 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (3 shared connections)
- [json.py](json.py.md) (2 shared connections)
- [TreeProjection](TreeProjection.md) (2 shared connections)
- [datetime](datetime.md) (2 shared connections)

## Source Files

- `src/ansible_aom/ansible/preflight.py`
- `src/ansible_aom/core/includes.py`
- `src/ansible_aom/core/models.py`
- `tests/unit/test_include_cache.py`

## Audit Trail

- EXTRACTED: 762 (91%)
- INFERRED: 78 (9%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*