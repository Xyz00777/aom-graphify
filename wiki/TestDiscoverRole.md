# TestDiscoverRole

> 12 nodes · cohesion 0.17

## Key Concepts

- **TestDiscoverRole** (11 connections) — `tests/unit/test_include_cache.py`
- **.test_discover_role_case_insensitive_cache_key()** (5 connections) — `tests/unit/test_include_cache.py`
- **.test_discover_role_dedup()** (5 connections) — `tests/unit/test_include_cache.py`
- **.test_discover_role_missing_role()** (5 connections) — `tests/unit/test_include_cache.py`
- **.test_discover_role_strips_whitespace()** (5 connections) — `tests/unit/test_include_cache.py`
- **.test_discover_role_successful()** (5 connections) — `tests/unit/test_include_cache.py`
- **Unit tests for _discover_role().** (1 connections) — `tests/unit/test_include_cache.py`
- **Successful role parsing creates and returns a RoleCacheEntry.** (1 connections) — `tests/unit/test_include_cache.py`
- **Second call returns the cached role entry.** (1 connections) — `tests/unit/test_include_cache.py`
- **Missing role directory returns None.** (1 connections) — `tests/unit/test_include_cache.py`
- **Role name is lowercased and stripped for the cache key.** (1 connections) — `tests/unit/test_include_cache.py`
- **Role name whitespace is stripped for cache key normalisation.          _discover** (1 connections) — `tests/unit/test_include_cache.py`

## Relationships

- [IncludeCacheEntry](IncludeCacheEntry.md) (6 shared connections)
- [Path](Path.md) (6 shared connections)
- [RunState](RunState.md) (5 shared connections)
- [TaskDefinition](TaskDefinition.md) (1 shared connections)
- [PlayDefinition](PlayDefinition.md) (1 shared connections)
- [RoleCacheEntry](RoleCacheEntry.md) (1 shared connections)

## Source Files

- `tests/unit/test_include_cache.py`

## Audit Trail

- EXTRACTED: 33 (79%)
- INFERRED: 9 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*