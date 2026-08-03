# parse_list_tasks_output

> 30 nodes · cohesion 0.07

## Key Concepts

- **parse_list_tasks_output()** (31 connections) — `src/ansible_aom/core/parser.py`
- **.test_blocks_flattened()** (3 connections) — `tests/unit/test_parser.py`
- **.test_exit_code_success_output()** (3 connections) — `tests/unit/test_parser.py`
- **.test_output_no_stderr_in_parsed_content()** (3 connections) — `tests/unit/test_parser.py`
- **.test_pre_tasks_post_tasks_no_prefix()** (3 connections) — `tests/unit/test_parser.py`
- **.test_special_section_names_in_play()** (3 connections) — `tests/unit/test_parser.py`
- **.test_unnamed_task_fallback_module_name()** (3 connections) — `tests/unit/test_parser.py`
- **.test_empty_tags()** (3 connections) — `tests/unit/test_parser.py`
- **.test_include_tasks_not_expanded()** (3 connections) — `tests/unit/test_parser.py`
- **.test_no_json_output()** (3 connections) — `tests/unit/test_parser.py`
- **.test_play_indent_recognition()** (3 connections) — `tests/unit/test_parser.py`
- **.test_playbook_header_skipped()** (3 connections) — `tests/unit/test_parser.py`
- **.test_tab_separator_used()** (3 connections) — `tests/unit/test_parser.py`
- **.test_task_indent_recognition()** (3 connections) — `tests/unit/test_parser.py`
- **.test_task_tags_extraction()** (3 connections) — `tests/unit/test_parser.py`
- **Parse --list-tasks output into structured data.      Returns list of dicts with** (1 connections) — `src/ansible_aom/core/parser.py`
- **TC-115: Block tasks are flattened — no block container in output.** (1 connections) — `tests/unit/test_parser.py`
- **TC-116: pre_tasks and post_tasks appear as regular tasks.** (1 connections) — `tests/unit/test_parser.py`
- **TC-117: Unnamed tasks use their module/action as the name.** (1 connections) — `tests/unit/test_parser.py`
- **TC-116: Play names may contain special section designations.** (1 connections) — `tests/unit/test_parser.py`
- **TC-118: Parser only receives stdout content.** (1 connections) — `tests/unit/test_parser.py`
- **TC-119: Valid --list-tasks output parses correctly.** (1 connections) — `tests/unit/test_parser.py`
- **TC-108: Separator between task name and TAGS: is literal TAB.** (1 connections) — `tests/unit/test_parser.py`
- **TC-109: Play lines have exactly 2-space indent.** (1 connections) — `tests/unit/test_parser.py`
- **TC-110: Task lines have exactly 6-space indent.** (1 connections) — `tests/unit/test_parser.py`
- *... and 5 more nodes in this community*

## Relationships

- [Status](Status.md) (15 shared connections)
- [assemble_definitions](assemble_definitions.md) (2 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (1 shared connections)
- [run_preflight](run_preflight.md) (1 shared connections)
- [StreamPhase](StreamPhase.md) (1 shared connections)
- [.test_exit_code_error_output](test_exit_code_error_output.md) (1 shared connections)
- [.test_exit_code_syntax_error_output](test_exit_code_syntax_error_output.md) (1 shared connections)
- [.test_import_tasks_expanded](test_import_tasks_expanded.md) (1 shared connections)
- [.test_import_tasks_with_role_prefix](test_import_tasks_with_role_prefix.md) (1 shared connections)
- [.test_list_tasks_play_hosts_pattern_extraction](test_list_tasks_play_hosts_pattern_extraction.md) (1 shared connections)
- [.test_list_tasks_play_id_sequential](test_list_tasks_play_id_sequential.md) (1 shared connections)
- [.test_multiple_plays](test_multiple_plays.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/parser.py`
- `tests/unit/test_parser.py`

## Audit Trail

- EXTRACTED: 88 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*