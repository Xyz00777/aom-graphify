# parse_list_hosts_output

> 30 nodes · cohesion 0.07

## Key Concepts

- **parse_list_hosts_output()** (28 connections) — `src/ansible_aom/core/parser.py`
- **.test_list_hosts_all_inventory()** (4 connections) — `tests/unit/test_parser.py`
- **.test_parallel_parse_does_not_corrupt_data()** (4 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_output_populates_resolved_hosts()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_list_hosts_dynamic_inventory_timeout()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_dynamic_pattern_empty_hosts()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_dynamic_pattern_fallback()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_pattern_filtering()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_with_limit()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_empty_result_fallback()** (3 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_fallback_warning_logged()** (3 connections) — `tests/unit/test_parser.py`
- **.test_empty_output_returns_empty_list()** (3 connections) — `tests/unit/test_parser.py`
- **.test_localhost_handling()** (3 connections) — `tests/unit/test_parser.py`
- **.test_parse_hostname_extraction()** (3 connections) — `tests/unit/test_parser.py`
- **.test_playbook_header_skipped()** (3 connections) — `tests/unit/test_parser.py`
- **TC-106: Slow dynamic inventory just returns hosts — parser doesn't         care** (2 connections) — `tests/unit/test_parser.py`
- **Parse --list-hosts output into structured data.      Returns list of dicts with** (1 connections) — `src/ansible_aom/core/parser.py`
- **TC-149: parse_list_hosts_output extracts hostnames per play.** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-087: Parallel parsing produces same results as sequential.** (1 connections) — `tests/unit/test_parser.py`
- **TC-089: When --list-hosts returns empty, hosts will come from         runner eve** (1 connections) — `tests/unit/test_parser.py`
- **TC-090: Warning message when host resolution fails.** (1 connections) — `tests/unit/test_parser.py`
- **TC-101: hosts: 'all' returns all inventory hosts.** (1 connections) — `tests/unit/test_parser.py`
- **TC-102: Pattern like webservers:!db_primary is preserved in hosts_pattern.** (1 connections) — `tests/unit/test_parser.py`
- **TC-103: Jinja2 pattern "{{ group }}" may fail — parser still parses         what** (1 connections) — `tests/unit/test_parser.py`
- **TC-103: When Jinja2 pattern can't resolve, hosts list is empty.** (1 connections) — `tests/unit/test_parser.py`
- *... and 5 more nodes in this community*

## Relationships

- [Status](Status.md) (15 shared connections)
- [assemble_definitions](assemble_definitions.md) (3 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (1 shared connections)
- [run_preflight](run_preflight.md) (1 shared connections)
- [StreamPhase](StreamPhase.md) (1 shared connections)
- [.test_list_hosts_multiple_plays_hosts](test_list_hosts_multiple_plays_hosts.md) (1 shared connections)
- [.test_list_hosts_no_duplicate_hosts](test_list_hosts_no_duplicate_hosts.md) (1 shared connections)
- [.test_list_hosts_play_number_sequential](test_list_hosts_play_number_sequential.md) (1 shared connections)
- [.test_list_hosts_partial_error_output](test_list_hosts_partial_error_output.md) (1 shared connections)
- [.test_parse_play_line_pattern](test_parse_play_line_pattern.md) (1 shared connections)
- [.test_skip_non_host_lines](test_skip_non_host_lines.md) (1 shared connections)
- [.test_list_hosts_stderr_not_in_result](test_list_hosts_stderr_not_in_result.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/parser.py`
- `tests/unit/test_host_resolution.py`
- `tests/unit/test_parser.py`

## Audit Trail

- EXTRACTED: 88 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*