# test_preflight.py

> 20 nodes · cohesion 0.12

## Key Concepts

- **test_preflight.py** (13 connections) — `tests/unit/test_preflight.py`
- **_trim_stderr()** (8 connections) — `src/ansible_aom/ansible/preflight.py`
- **test_assemble_definitions_combines_tasks_and_hosts()** (5 connections) — `tests/unit/test_preflight.py`
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
- **Tests for the pre-flight orchestrator (--list-tasks + --list-hosts).** (1 connections) — `tests/unit/test_preflight.py`
- **When there's no `: error:` marker, keep the first few non-empty lines, capped.** (1 connections) — `tests/unit/test_preflight.py`
- **The new fields are optional with empty defaults so old call sites still work.** (1 connections) — `tests/unit/test_preflight.py`
- **assemble_definitions builds a PlayDefinition per play with tasks + resolved_host** (1 connections) — `tests/unit/test_preflight.py`
- **When --list-hosts has no entry for a play, resolved_hosts stays empty.** (1 connections) — `tests/unit/test_preflight.py`
- **ansible-playbook on bad args dumps usage + error + full --help. Keep only error.** (1 connections) — `tests/unit/test_preflight.py`
- **PreParseResult exposes assembled definitions plus an errors list.** (1 connections) — `tests/unit/test_preflight.py`

## Relationships

- [assemble_definitions](assemble_definitions.md) (4 shared connections)
- [models.py](models.py.md) (2 shared connections)
- [WarningType](WarningType.md) (2 shared connections)
- [run_preflight](run_preflight.md) (1 shared connections)
- [parse_list_hosts_output](parse_list_hosts_output.md) (1 shared connections)
- [parse_list_tasks_output](parse_list_tasks_output.md) (1 shared connections)

## Source Files

- `src/ansible_aom/ansible/preflight.py`
- `tests/unit/test_preflight.py`

## Audit Trail

- EXTRACTED: 44 (77%)
- INFERRED: 13 (23%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*