# run_preflight

> 40 nodes · cohesion 0.08

## Key Concepts

- **run_preflight()** (22 connections) — `src/ansible_aom/ansible/preflight.py`
- **test_preflight.py** (13 connections) — `tests/unit/test_preflight.py`
- **test_preflight_runner.py** (11 connections) — `tests/integration/test_preflight_runner.py`
- **Path** (10 connections)
- **_trim_stderr()** (8 connections) — `src/ansible_aom/ansible/preflight.py`
- **_make_fake_ansible()** (5 connections) — `tests/integration/test_preflight_runner.py`
- **test_run_preflight_grafts_include_children_into_definitions()** (5 connections) — `tests/integration/test_preflight_runner.py`
- **test_run_preflight_list_hosts_failure_yields_definitions_without_resolved_hosts()** (4 connections) — `tests/integration/test_preflight_runner.py`
- **test_run_preflight_passes_ansible_args()** (4 connections) — `tests/integration/test_preflight_runner.py`
- **test_run_preflight_populates_include_cache()** (4 connections) — `tests/integration/test_preflight_runner.py`
- **test_run_preflight_role_relative_include_resolves_under_role()** (4 connections) — `tests/integration/test_preflight_runner.py`
- **test_run_preflight_runs_both_commands_and_assembles_definitions()** (4 connections) — `tests/integration/test_preflight_runner.py`
- **test_run_preflight_sets_ansible_nocolor_env()** (4 connections) — `tests/integration/test_preflight_runner.py`
- **test_run_preflight_trims_argparse_help_wall_from_error()** (4 connections) — `tests/integration/test_preflight_runner.py`
- **test_run_preflight_executable_not_found_records_error()** (3 connections) — `tests/integration/test_preflight_runner.py`
- **test_assemble_definitions_missing_host_data_yields_empty_resolved_hosts()** (3 connections) — `tests/unit/test_preflight.py`
- **test_preparseresult_definitions_and_errors_default_to_empty()** (3 connections) — `tests/unit/test_preflight.py`
- **test_preparseresult_has_definitions_and_errors_fields()** (3 connections) — `tests/unit/test_preflight.py`
- **test_trim_stderr_extracts_only_error_line_from_argparse_wall()** (3 connections) — `tests/unit/test_preflight.py`
- **test_trim_stderr_falls_back_to_first_lines_without_error_marker()** (3 connections) — `tests/unit/test_preflight.py`
- **test_assemble_definitions_empty_inputs_returns_empty_list()** (2 connections) — `tests/unit/test_preflight.py`
- **test_trim_stderr_empty_returns_empty()** (2 connections) — `tests/unit/test_preflight.py`
- **test_trim_stderr_handles_multiple_error_lines()** (2 connections) — `tests/unit/test_preflight.py`
- **test_trim_stderr_returns_short_message_unchanged()** (2 connections) — `tests/unit/test_preflight.py`
- **Run --list-tasks and --list-hosts in parallel; return assembled result.      Bot** (1 connections) — `src/ansible_aom/ansible/preflight.py`
- *... and 15 more nodes in this community*

## Relationships

- [IncludeCacheEntry](IncludeCacheEntry.md) (6 shared connections)
- [TestRoleGrouping](TestRoleGrouping.md) (5 shared connections)
- [StreamPhase](StreamPhase.md) (4 shared connections)
- [parse_list_tasks_output](parse_list_tasks_output.md) (1 shared connections)
- [runner.py](runner.py.md) (1 shared connections)
- [run_playbook](run_playbook.md) (1 shared connections)
- [TaskDefinition](TaskDefinition.md) (1 shared connections)
- [json.py](json.py.md) (1 shared connections)

## Source Files

- `src/ansible_aom/ansible/preflight.py`
- `tests/integration/test_preflight_runner.py`
- `tests/unit/test_preflight.py`

## Audit Trail

- EXTRACTED: 112 (78%)
- INFERRED: 32 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*