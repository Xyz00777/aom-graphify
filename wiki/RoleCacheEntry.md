# RoleCacheEntry

> 14 nodes · cohesion 0.16

## Key Concepts

- **RoleCacheEntry** (19 connections) — `src/ansible_aom/core/models.py`
- **TestCacheEntryProperties** (10 connections) — `tests/unit/test_include_cache.py`
- **.test_include_cache_entry_task_count()** (3 connections) — `tests/unit/test_include_cache.py`
- **.test_include_cache_entry_task_count_empty()** (3 connections) — `tests/unit/test_include_cache.py`
- **.test_role_cache_entry_task_count()** (3 connections) — `tests/unit/test_include_cache.py`
- **.test_role_cache_entry_task_count_empty()** (3 connections) — `tests/unit/test_include_cache.py`
- **.task_count()** (2 connections) — `src/ansible_aom/core/models.py`
- **Cached task list for a role discovered at runtime.      When a role is applied d** (1 connections) — `src/ansible_aom/core/models.py`
- **Pre-computed count for O(1) access in counter hot paths.** (1 connections) — `src/ansible_aom/core/models.py`
- **Unit tests for IncludeCacheEntry.task_count and RoleCacheEntry.task_count.** (1 connections) — `tests/unit/test_include_cache.py`
- **task_count property equals len(task_names).** (1 connections) — `tests/unit/test_include_cache.py`
- **Empty task_names yields task_count of 0.** (1 connections) — `tests/unit/test_include_cache.py`
- **task_count property equals len(task_names).** (1 connections) — `tests/unit/test_include_cache.py`
- **Empty task_names yields task_count of 0.** (1 connections) — `tests/unit/test_include_cache.py`

## Relationships

- [Path](Path.md) (6 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (5 shared connections)
- [run_state.py](run_state.py.md) (3 shared connections)
- [TaskDefinition](TaskDefinition.md) (2 shared connections)
- [Status](Status.md) (1 shared connections)
- [RunState](RunState.md) (1 shared connections)
- [TestGraftIncludeChildren](TestGraftIncludeChildren.md) (1 shared connections)
- [TestParseRoleTasks](TestParseRoleTasks.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/models.py`
- `tests/unit/test_include_cache.py`

## Audit Trail

- EXTRACTED: 35 (70%)
- INFERRED: 15 (30%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*