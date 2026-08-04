# WarningType

> 102 nodes · cohesion 0.03

## Key Concepts

- **WarningType** (95 connections) — `src/ansible_aom/core/models.py`
- **JsonLineStream** (78 connections) — `src/ansible_aom/core/parser.py`
- **TestPtyStreamParserStderrLineEmission** (41 connections) — `tests/unit/test_parser.py`
- **PreParseResult** (35 connections) — `src/ansible_aom/core/parser.py`
- **TestJsonLineStreamBasics** (31 connections) — `tests/unit/test_parser.py`
- **TestListTasksEdgeCases** (26 connections) — `tests/unit/test_parser.py`
- **TestListTasksParser** (25 connections) — `tests/unit/test_parser.py`
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
- **TestR6ParserAcceptsSurrogateLines** (5 connections) — `tests/integration/test_r6_encoding_roundtrip.py`
- **.test_preparse_result_assembly()** (5 connections) — `tests/unit/test_parser.py`
- **.test_concurrent_parse_combine_results()** (4 connections) — `tests/unit/test_parser.py`
- **Enum** (3 connections)
- **.test_mojibake_subsequent_lines_still_parse()** (3 connections) — `tests/integration/test_r6_encoding_roundtrip.py`
- **.test_feed_line_event_play_start()** (3 connections) — `tests/unit/test_parser.py`
- *... and 77 more nodes in this community*

## Relationships

- [PtyStreamParser](PtyStreamParser.md) (65 shared connections)
- [HostRunState](HostRunState.md) (51 shared connections)
- [Status](Status.md) (37 shared connections)
- [parse_list_tasks_output](parse_list_tasks_output.md) (23 shared connections)
- [parse_list_hosts_output](parse_list_hosts_output.md) (21 shared connections)
- [TaskDefinition](TaskDefinition.md) (20 shared connections)
- [StatusBarConfig](StatusBarConfig.md) (18 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (18 shared connections)
- [PlayDefinition](PlayDefinition.md) (17 shared connections)
- [WarningEntry](WarningEntry.md) (14 shared connections)
- [models.py](models.py.md) (10 shared connections)
- [TestJsonLineStreamSurvivesMojibake](TestJsonLineStreamSurvivesMojibake.md) (6 shared connections)

## Source Files

- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/parser.py`
- `tests/integration/test_r6_encoding_roundtrip.py`
- `tests/unit/test_parser.py`

## Audit Trail

- EXTRACTED: 380 (53%)
- INFERRED: 335 (47%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*