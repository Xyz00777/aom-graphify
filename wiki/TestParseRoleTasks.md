# TestParseRoleTasks

> 12 nodes · cohesion 0.17

## Key Concepts

- **TestParseRoleTasks** (11 connections) — `tests/unit/test_include_cache.py`
- **.test_parse_role_tasks_malformed_yaml()** (4 connections) — `tests/unit/test_include_cache.py`
- **.test_parse_role_tasks_missing_dir()** (4 connections) — `tests/unit/test_include_cache.py`
- **.test_parse_role_tasks_no_name_keys()** (4 connections) — `tests/unit/test_include_cache.py`
- **.test_parse_role_tasks_strips_prefix()** (4 connections) — `tests/unit/test_include_cache.py`
- **.test_parse_role_tasks_valid()** (4 connections) — `tests/unit/test_include_cache.py`
- **Unit tests for parse_role_tasks().** (1 connections) — `tests/unit/test_include_cache.py`
- **Valid role directory with tasks/main.yml returns task names.** (1 connections) — `tests/unit/test_include_cache.py`
- **Missing role directory returns empty list.** (1 connections) — `tests/unit/test_include_cache.py`
- **Role prefix 'role : ' is stripped from task names.** (1 connections) — `tests/unit/test_include_cache.py`
- **Tasks without 'name' key are skipped in role parsing.** (1 connections) — `tests/unit/test_include_cache.py`
- **Malformed YAML in tasks/main.yml returns empty list.** (1 connections) — `tests/unit/test_include_cache.py`

## Relationships

- [IncludeCacheEntry](IncludeCacheEntry.md) (6 shared connections)
- [Path](Path.md) (6 shared connections)
- [TaskDefinition](TaskDefinition.md) (2 shared connections)
- [RoleCacheEntry](RoleCacheEntry.md) (1 shared connections)

## Source Files

- `tests/unit/test_include_cache.py`

## Audit Trail

- EXTRACTED: 33 (89%)
- INFERRED: 4 (11%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*