# TestGraftIncludeChildren

> 28 nodes · cohesion 0.11

## Key Concepts

- **TestGraftIncludeChildren** (18 connections) — `tests/unit/test_include_cache.py`
- **_make_play()** (10 connections) — `tests/unit/test_include_cache.py`
- **.test_graft_preserves_existing_children()** (9 connections) — `tests/unit/test_include_cache.py`
- **_include_stub()** (8 connections) — `tests/unit/test_include_cache.py`
- **.test_block_with_include_preserves_location()** (8 connections) — `tests/unit/test_include_cache.py`
- **.test_static_include_grafts_children_into_stub()** (8 connections) — `tests/unit/test_include_cache.py`
- **.test_graft_only_targets_include_stubs()** (7 connections) — `tests/unit/test_include_cache.py`
- **.test_graft_unknown_path_leaves_stub_alone()** (7 connections) — `tests/unit/test_include_cache.py`
- **.test_nested_includes_graft_transitively()** (7 connections) — `tests/unit/test_include_cache.py`
- **._write_playbook()** (7 connections) — `tests/unit/test_include_cache.py`
- **.test_jinja_templated_include_path_is_skipped()** (4 connections) — `tests/unit/test_include_cache.py`
- **.test_role_relative_include_resolution()** (4 connections) — `tests/unit/test_include_cache.py`
- **.test_role_scan_missing_role_is_silent()** (4 connections) — `tests/unit/test_include_cache.py`
- **.test_role_scan_unparseable_role_logs_warning_once()** (4 connections) — `tests/unit/test_include_cache.py`
- **Build a single-play PlayDefinition wrapping *tasks*.** (1 connections) — `tests/unit/test_include_cache.py`
- **Build an include_tasks stub TaskDefinition like --list-tasks produces.      Real** (1 connections) — `tests/unit/test_include_cache.py`
- **Unit tests for graft_include_children() — TC-094a through TC-094e.** (1 connections) — `tests/unit/test_include_cache.py`
- **Write a one-task playbook that includes *include_target* and return its path.** (1 connections) — `tests/unit/test_include_cache.py`
- **TC-094a: A literal include_tasks stub gains children from cache.** (1 connections) — `tests/unit/test_include_cache.py`
- **TC-094b: include_tasks inside a role resolves relative to the role dir.** (1 connections) — `tests/unit/test_include_cache.py`
- **TC-094c: include_tasks: '{{ var }}.yml' does not populate cache.** (1 connections) — `tests/unit/test_include_cache.py`
- **A role listed in role_names but absent on disk does not log at WARNING/DEBUG.** (1 connections) — `tests/unit/test_include_cache.py`
- **A role with YAML PyYAML can't parse logs one WARNING, no exception.** (1 connections) — `tests/unit/test_include_cache.py`
- **TC-094d: include A includes B includes C → children at depth 2 and 3.** (1 connections) — `tests/unit/test_include_cache.py`
- **TC-094e: block: [include_tasks: foo.yml, ...] grafts under block task.** (1 connections) — `tests/unit/test_include_cache.py`
- *... and 3 more nodes in this community*

## Relationships

- [Path](Path.md) (15 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (15 shared connections)
- [TaskDefinition](TaskDefinition.md) (8 shared connections)
- [RoleCacheEntry](RoleCacheEntry.md) (1 shared connections)

## Source Files

- `tests/unit/test_include_cache.py`

## Audit Trail

- EXTRACTED: 115 (97%)
- INFERRED: 4 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*