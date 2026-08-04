# TestMultiLineWarningContinuation

> 15 nodes · cohesion 0.15

## Key Concepts

- **TestMultiLineWarningContinuation** (18 connections) — `tests/unit/test_parser.py`
- **._feed_wrapped_warning()** (4 connections) — `tests/unit/test_parser.py`
- **.test_continuation_lines_emit_no_stderr_event()** (3 connections) — `tests/unit/test_parser.py`
- **.test_json_event_closes_warning_block()** (3 connections) — `tests/unit/test_parser.py`
- **.test_non_magenta_unknown_line_still_unknown()** (3 connections) — `tests/unit/test_parser.py`
- **.test_orphan_magenta_line_classified_as_warning_not_unknown()** (3 connections) — `tests/unit/test_parser.py`
- **.test_red_colored_line_does_not_fold_into_warning()** (3 connections) — `tests/unit/test_parser.py`
- **.test_warning_message_reassembled_from_all_lines()** (3 connections) — `tests/unit/test_parser.py`
- **Regression guard: non-coloured unrecognised lines are unaffected         and sti** (2 connections) — `tests/unit/test_parser.py`
- **.test_deprecation_continuation_keeps_deprecation_type()** (2 connections) — `tests/unit/test_parser.py`
- **Ansible hard-wraps ``[WARNING]``/``[DEPRECATION WARNING]`` messages to     the t** (1 connections) — `tests/unit/test_parser.py`
- **Feed a real 3-line wrapped [WARNING] as ansible emits it on the PTY.** (1 connections) — `tests/unit/test_parser.py`
- **A magenta line after an intervening JSON event starts a fresh         warning —** (1 connections) — `tests/unit/test_parser.py`
- **Color-based classification: a magenta stderr line with no open         warning b** (1 connections) — `tests/unit/test_parser.py`
- **Only magenta (warn/deprecate) folds. A red line after a warning         closes t** (1 connections) — `tests/unit/test_parser.py`

## Relationships

- [PtyStreamParser](PtyStreamParser.md) (8 shared connections)
- [Status](Status.md) (4 shared connections)
- [TaskDefinition](TaskDefinition.md) (2 shared connections)
- [parse_list_hosts_output](parse_list_hosts_output.md) (1 shared connections)
- [StreamPhase](StreamPhase.md) (1 shared connections)
- [JsonLineStream](JsonLineStream.md) (1 shared connections)

## Source Files

- `tests/unit/test_parser.py`

## Audit Trail

- EXTRACTED: 41 (84%)
- INFERRED: 8 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*