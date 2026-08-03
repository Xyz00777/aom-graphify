# StreamPhase

> 162 nodes · cohesion 0.02

## Key Concepts

- **StreamPhase** (97 connections) — `src/ansible_aom/core/parser.py`
- **JsonLineStream** (78 connections) — `src/ansible_aom/core/parser.py`
- **TestPtyStreamParserStderrLineEmission** (41 connections) — `tests/unit/test_parser.py`
- **PreParseResult** (35 connections) — `src/ansible_aom/core/parser.py`
- **TestJsonLineStreamBasics** (31 connections) — `tests/unit/test_parser.py`
- **parse_list_hosts_output()** (28 connections) — `src/ansible_aom/core/parser.py`
- **TestPtyStreamParserPhases** (25 connections) — `tests/unit/test_parser.py`
- **test_parser.py** (24 connections) — `tests/unit/test_parser.py`
- **TestListHostsEdgeCases** (23 connections) — `tests/unit/test_parser.py`
- **TestJsonLineStreamCarryBuffer** (20 connections) — `tests/unit/test_parser.py`
- **TestListHostsParser** (20 connections) — `tests/unit/test_parser.py`
- **TestPtyStreamParserJsonlEvents** (18 connections) — `tests/unit/test_parser.py`
- **TestWarningDetectionThroughAnsiPrefix** (18 connections) — `tests/unit/test_parser.py`
- **TestListHostsFallback** (17 connections) — `tests/unit/test_parser.py`
- **TestPreParsePhase** (17 connections) — `tests/unit/test_parser.py`
- **TestListTasksListHostsIntegration** (16 connections) — `tests/unit/test_parser.py`
- **TestParallelPreParse** (16 connections) — `tests/unit/test_parser.py`
- **TestPtyStreamParserPlaintextCap** (16 connections) — `tests/unit/test_parser.py`
- **TestStatusEnum** (16 connections) — `tests/unit/test_parser.py`
- **TestStreamPhaseEnum** (10 connections) — `tests/unit/test_pty_stream.py`
- **TestR6ParserAcceptsSurrogateLines** (5 connections) — `tests/integration/test_r6_encoding_roundtrip.py`
- **.test_preparse_result_assembly()** (5 connections) — `tests/unit/test_parser.py`
- **.test_list_hosts_all_inventory()** (4 connections) — `tests/unit/test_parser.py`
- **.test_parse_play_line_pattern()** (4 connections) — `tests/unit/test_parser.py`
- **.test_skip_non_host_lines()** (4 connections) — `tests/unit/test_parser.py`
- *... and 137 more nodes in this community*

## Relationships

- [PtyStreamParser](PtyStreamParser.md) (67 shared connections)
- [TaskDefinition](TaskDefinition.md) (31 shared connections)
- [HostRunState](HostRunState.md) (28 shared connections)
- [WarningType](WarningType.md) (19 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (17 shared connections)
- [Status](Status.md) (15 shared connections)
- [parse_list_tasks_output](parse_list_tasks_output.md) (14 shared connections)
- [PlayRunState](PlayRunState.md) (14 shared connections)
- [json.py](json.py.md) (12 shared connections)
- [TestJsonLineStreamSurvivesMojibake](TestJsonLineStreamSurvivesMojibake.md) (8 shared connections)
- [TestRoleGrouping](TestRoleGrouping.md) (7 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (5 shared connections)

## Source Files

- `src/ansible_aom/core/parser.py`
- `tests/integration/test_r6_encoding_roundtrip.py`
- `tests/unit/test_parser.py`
- `tests/unit/test_pty_stream.py`

## Audit Trail

- EXTRACTED: 511 (61%)
- INFERRED: 333 (39%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*