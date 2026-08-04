# assemble_definitions

> 22 nodes · cohesion 0.10

## Key Concepts

- **assemble_definitions()** (14 connections) — `src/ansible_aom/ansible/preflight.py`
- **TestHostFallbackAfterListHostsFailure** (10 connections) — `tests/unit/test_host_resolution.py`
- **TestListHostsResolvesHostnames** (10 connections) — `tests/unit/test_host_resolution.py`
- **.test_assemble_definitions_transfers_resolved_hosts()** (5 connections) — `tests/unit/test_host_resolution.py`
- **.test_runner_event_host_not_in_resolved_hosts_still_added()** (4 connections) — `tests/unit/test_host_resolution.py`
- **test_assemble_definitions_invokes_role_grouping()** (4 connections) — `tests/unit/test_preflight.py`
- **.test_assemble_definitions_with_empty_play_hosts_yields_empty()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_runner_events_populate_hosts_incrementally()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_runstate_with_empty_definitions_resolves_to_empty()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_assemble_definitions_no_match_yields_empty_resolved_hosts()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_resolved_hosts_empty_when_list_hosts_blank()** (3 connections) — `tests/unit/test_host_resolution.py`
- **Build PlayDefinition objects from parsed --list-tasks / --list-hosts dicts.** (1 connections) — `src/ansible_aom/ansible/preflight.py`
- **TC-151: If --list-hosts fails, resolved_hosts starts empty; populated by runner** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-151: --list-hosts failure → empty play_hosts → empty resolved_hosts.** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-151: RunState.definitions=[] → _resolve_play_hosts returns [].** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-151: v2_runner_on_* events add hosts to task.hosts even without preflight.** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-151 edge: host arriving from a runner event but absent from preflight** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-149: --list-hosts populates PlayDefinition.resolved_hosts.** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-149: assemble_definitions wires parse_list_hosts_output into PlayDefinition.** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-149 edge: play with no matching --list-hosts entry gets empty resolved_hosts.** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-149: Empty --list-hosts output propagates empty resolved_hosts.** (1 connections) — `tests/unit/test_host_resolution.py`
- **5+ consecutive same-role tasks collapse into a RoleGroupDefinition.** (1 connections) — `tests/unit/test_preflight.py`

## Relationships

- [RunState](RunState.md) (5 shared connections)
- [PlayDefinition](PlayDefinition.md) (4 shared connections)
- [TaskDefinition](TaskDefinition.md) (4 shared connections)
- [test_preflight.py](test_preflight.py.md) (4 shared connections)
- [models.py](models.py.md) (3 shared connections)
- [Status](Status.md) (2 shared connections)
- [parse_list_hosts_output](parse_list_hosts_output.md) (2 shared connections)
- [run_preflight](run_preflight.md) (1 shared connections)
- [parse_list_tasks_output](parse_list_tasks_output.md) (1 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (1 shared connections)

## Source Files

- `src/ansible_aom/ansible/preflight.py`
- `tests/unit/test_host_resolution.py`
- `tests/unit/test_preflight.py`

## Audit Trail

- EXTRACTED: 59 (81%)
- INFERRED: 14 (19%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*