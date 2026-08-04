# assemble_definitions

> 36 nodes · cohesion 0.07

## Key Concepts

- **assemble_definitions()** (14 connections) — `src/ansible_aom/ansible/preflight.py`
- **test_preflight.py** (13 connections) — `tests/unit/test_preflight.py`
- **TestListHostsResolvesHostnames** (10 connections) — `tests/unit/test_host_resolution.py`
- **test_host_resolution.py** (9 connections) — `tests/unit/test_host_resolution.py`
- **_trim_stderr()** (8 connections) — `src/ansible_aom/ansible/preflight.py`
- **.test_assemble_definitions_transfers_resolved_hosts()** (5 connections) — `tests/unit/test_host_resolution.py`
- **test_assemble_definitions_combines_tasks_and_hosts()** (5 connections) — `tests/unit/test_preflight.py`
- **test_assemble_definitions_invokes_role_grouping()** (4 connections) — `tests/unit/test_preflight.py`
- **.test_assemble_definitions_with_empty_play_hosts_yields_empty()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_assemble_definitions_no_match_yields_empty_resolved_hosts()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_resolved_hosts_empty_when_list_hosts_blank()** (3 connections) — `tests/unit/test_host_resolution.py`
- **test_assemble_definitions_missing_host_data_yields_empty_resolved_hosts()** (3 connections) — `tests/unit/test_preflight.py`
- **test_preparseresult_definitions_and_errors_default_to_empty()** (3 connections) — `tests/unit/test_preflight.py`
- **test_preparseresult_has_definitions_and_errors_fields()** (3 connections) — `tests/unit/test_preflight.py`
- **test_trim_stderr_extracts_only_error_line_from_argparse_wall()** (3 connections) — `tests/unit/test_preflight.py`
- **test_trim_stderr_falls_back_to_first_lines_without_error_marker()** (3 connections) — `tests/unit/test_preflight.py`
- **test_assemble_definitions_empty_inputs_returns_empty_list()** (2 connections) — `tests/unit/test_preflight.py`
- **test_trim_stderr_empty_returns_empty()** (2 connections) — `tests/unit/test_preflight.py`
- **test_trim_stderr_handles_multiple_error_lines()** (2 connections) — `tests/unit/test_preflight.py`
- **test_trim_stderr_returns_short_message_unchanged()** (2 connections) — `tests/unit/test_preflight.py`
- **Reduce ansible-playbook stderr to the diagnostic lines worth showing.      Argpa** (1 connections) — `src/ansible_aom/ansible/preflight.py`
- **Build PlayDefinition objects from parsed --list-tasks / --list-hosts dicts.** (1 connections) — `src/ansible_aom/ansible/preflight.py`
- **Tests for host name resolution (TC-149 to TC-152).  Covers TEST_SPECIFICATION.md** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-151: --list-hosts failure → empty play_hosts → empty resolved_hosts.** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-149: --list-hosts populates PlayDefinition.resolved_hosts.** (1 connections) — `tests/unit/test_host_resolution.py`
- *... and 11 more nodes in this community*

## Relationships

- [RunState](RunState.md) (5 shared connections)
- [TaskDefinition](TaskDefinition.md) (4 shared connections)
- [Status](Status.md) (4 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (3 shared connections)
- [parse_list_hosts_output](parse_list_hosts_output.md) (3 shared connections)
- [PlayDefinition](PlayDefinition.md) (2 shared connections)
- [run_preflight](run_preflight.md) (2 shared connections)
- [StreamPhase](StreamPhase.md) (2 shared connections)
- [parse_list_tasks_output](parse_list_tasks_output.md) (2 shared connections)
- [run_state.py](run_state.py.md) (1 shared connections)

## Source Files

- `src/ansible_aom/ansible/preflight.py`
- `tests/unit/test_host_resolution.py`
- `tests/unit/test_preflight.py`

## Audit Trail

- EXTRACTED: 93 (80%)
- INFERRED: 23 (20%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*