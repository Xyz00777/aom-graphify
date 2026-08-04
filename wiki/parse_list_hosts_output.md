# parse_list_hosts_output

> 41 nodes · cohesion 0.05

## Key Concepts

- **parse_list_hosts_output()** (28 connections) — `src/ansible_aom/core/parser.py`
- **.test_list_hosts_all_inventory()** (4 connections) — `tests/unit/test_parser.py`
- **.test_parse_play_line_pattern()** (4 connections) — `tests/unit/test_parser.py`
- **.test_parallel_parse_does_not_corrupt_data()** (4 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_output_populates_resolved_hosts()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_list_hosts_dynamic_pattern_empty_hosts()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_dynamic_pattern_fallback()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_multiple_plays_hosts()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_no_duplicate_hosts()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_pattern_filtering()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_play_number_sequential()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_with_limit()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_empty_result_fallback()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_fallback_warning_logged()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_partial_error_output()** (3 connections) — `tests/unit/test_parser.py`
- **.test_empty_output_returns_empty_list()** (3 connections) — `tests/unit/test_parser.py`
- **.test_localhost_handling()** (3 connections) — `tests/unit/test_parser.py`
- **.test_parse_hostname_extraction()** (3 connections) — `tests/unit/test_parser.py`
- **.test_playbook_header_skipped()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_stderr_not_in_result()** (3 connections) — `tests/unit/test_parser.py`
- **TC-072 to TC-086: Processing JSONL events through PTY stream.** (2 connections) — `tests/unit/test_parser.py`
- **Parse --list-hosts output into structured data.      Returns list of dicts with** (1 connections) — `src/ansible_aom/core/parser.py`
- **TC-149: parse_list_hosts_output extracts hostnames per play.** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-087: Parallel parsing produces same results as sequential.** (1 connections) — `tests/unit/test_parser.py`
- **TC-089: When --list-hosts returns empty, hosts will come from         runner eve** (1 connections) — `tests/unit/test_parser.py`
- *... and 16 more nodes in this community*

## Relationships

- [WarningType](WarningType.md) (21 shared connections)
- [models.py](models.py.md) (2 shared connections)
- [assemble_definitions](assemble_definitions.md) (2 shared connections)
- [run_preflight](run_preflight.md) (1 shared connections)
- [.test_skip_non_host_lines](test_skip_non_host_lines.md) (1 shared connections)
- [test_preflight.py](test_preflight.py.md) (1 shared connections)
- [TestMultiLineWarningContinuation](TestMultiLineWarningContinuation.md) (1 shared connections)
- [parse_list_tasks_output](parse_list_tasks_output.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/parser.py`
- `tests/unit/test_host_resolution.py`
- `tests/unit/test_parser.py`

## Audit Trail

- EXTRACTED: 110 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*