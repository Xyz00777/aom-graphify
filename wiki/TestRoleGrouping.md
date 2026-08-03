# TestRoleGrouping

> 46 nodes · cohesion 0.05

## Key Concepts

- **TestRoleGrouping** (21 connections) — `tests/unit/test_parser.py`
- **assemble_definitions()** (14 connections) — `src/ansible_aom/ansible/preflight.py`
- **group_roles()** (11 connections) — `src/ansible_aom/core/parser.py`
- **TestHostFallbackAfterListHostsFailure** (10 connections) — `tests/unit/test_host_resolution.py`
- **TestListHostsResolvesHostnames** (10 connections) — `tests/unit/test_host_resolution.py`
- **test_host_resolution.py** (9 connections) — `tests/unit/test_host_resolution.py`
- **.test_assemble_definitions_transfers_resolved_hosts()** (5 connections) — `tests/unit/test_host_resolution.py`
- **.test_five_same_role_tasks_creates_group()** (5 connections) — `tests/unit/test_parser.py`
- **.test_role_group_at_end_of_list()** (5 connections) — `tests/unit/test_parser.py`
- **test_assemble_definitions_combines_tasks_and_hosts()** (5 connections) — `tests/unit/test_preflight.py`
- **.test_runner_event_host_not_in_resolved_hosts_still_added()** (4 connections) — `tests/unit/test_host_resolution.py`
- **.test_four_same_role_tasks_no_grouping()** (4 connections) — `tests/unit/test_parser.py`
- **.test_mixed_roles_no_grouping()** (4 connections) — `tests/unit/test_parser.py`
- **.test_multiple_role_groups()** (4 connections) — `tests/unit/test_parser.py`
- **.test_role_group_name_format()** (4 connections) — `tests/unit/test_parser.py`
- **.test_role_group_with_mixed_none_role()** (4 connections) — `tests/unit/test_parser.py`
- **test_assemble_definitions_invokes_role_grouping()** (4 connections) — `tests/unit/test_preflight.py`
- **.test_assemble_definitions_with_empty_play_hosts_yields_empty()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_runner_events_populate_hosts_incrementally()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_runstate_with_empty_definitions_resolves_to_empty()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_assemble_definitions_no_match_yields_empty_resolved_hosts()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_list_hosts_output_populates_resolved_hosts()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_resolved_hosts_empty_when_list_hosts_blank()** (3 connections) — `tests/unit/test_host_resolution.py`
- **Build PlayDefinition objects from parsed --list-tasks / --list-hosts dicts.** (1 connections) — `src/ansible_aom/ansible/preflight.py`
- **Group consecutive same-role tasks (5 or more) into RoleGroupDefinition.      Arg** (1 connections) — `src/ansible_aom/core/parser.py`
- *... and 21 more nodes in this community*

## Relationships

- [TaskDefinition](TaskDefinition.md) (16 shared connections)
- [RunState](RunState.md) (7 shared connections)
- [StreamPhase](StreamPhase.md) (7 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (6 shared connections)
- [run_preflight](run_preflight.md) (5 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (3 shared connections)
- [Status](Status.md) (3 shared connections)
- [json.py](json.py.md) (2 shared connections)
- [WarningType](WarningType.md) (2 shared connections)
- [parse_list_tasks_output](parse_list_tasks_output.md) (2 shared connections)
- [HostRunState](HostRunState.md) (2 shared connections)
- [JsonlEvent](JsonlEvent.md) (1 shared connections)

## Source Files

- `src/ansible_aom/ansible/preflight.py`
- `src/ansible_aom/core/parser.py`
- `tests/unit/test_host_resolution.py`
- `tests/unit/test_parser.py`
- `tests/unit/test_preflight.py`

## Audit Trail

- EXTRACTED: 131 (80%)
- INFERRED: 33 (20%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*