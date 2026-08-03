# json.py

> 57 nodes · cohesion 0.04

## Key Concepts

- **json.py** (80 connections) — `src/ansible_aom/formats/json.py`
- **parser.py** (43 connections) — `src/ansible_aom/core/parser.py`
- **test_session.py** (19 connections) — `tests/integration/test_session.py`
- **test_pty_stream.py** (18 connections) — `tests/unit/test_pty_stream.py`
- **test_runner_eof_watchdog.py** (14 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **test_sink_disable_and_preflight_ms.py** (11 connections) — `tests/unit/test_sink_disable_and_preflight_ms.py`
- **TestPatternRegexes** (8 connections) — `tests/unit/test_pty_stream.py`
- **test_run_state_set_caps.py** (8 connections) — `tests/unit/test_run_state_set_caps.py`
- **state_machine.py** (7 connections) — `src/ansible_aom/core/state_machine.py`
- **test_encoding_robustness.py** (6 connections) — `tests/unit/test_encoding_robustness.py`
- **test_parser_orjson_swap.py** (6 connections) — `tests/unit/test_parser_orjson_swap.py`
- **TestEofWatchdogConfig** (6 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **test_session_meta_persistence.py** (5 connections) — `tests/unit/test_session_meta_persistence.py`
- **test_perf_005_parser_byte_equal_to_stdlib()** (4 connections) — `tests/unit/test_parser_orjson_swap.py`
- **test_perf_006_carry_buffer_still_works_after_swap()** (3 connections) — `tests/unit/test_parser_orjson_swap.py`
- **test_perf_007_non_dict_json_rejected()** (3 connections) — `tests/unit/test_parser_orjson_swap.py`
- **test_grafted_role_names_capped()** (3 connections) — `tests/unit/test_run_state_set_caps.py`
- **test_grafted_uuids_capped_at_max_tasks_per_play()** (3 connections) — `tests/unit/test_run_state_set_caps.py`
- **test_play_window_counts_capped_at_max_plays()** (3 connections) — `tests/unit/test_run_state_set_caps.py`
- **test_unknown_events_keys_naturally_bounded()** (3 connections) — `tests/unit/test_run_state_set_caps.py`
- **Enum** (2 connections)
- **.test_password_patterns_match_expected_prompts()** (2 connections) — `tests/unit/test_pty_stream.py`
- **.test_recap_pattern_matches_various_formats()** (2 connections) — `tests/unit/test_pty_stream.py`
- **.test_warning_patterns_match_expected_lines()** (2 connections) — `tests/unit/test_pty_stream.py`
- **.test_watchdog_is_at_least_five_seconds()** (2 connections) — `tests/unit/test_runner_eof_watchdog.py`
- *... and 32 more nodes in this community*

## Relationships

- [SessionManager](SessionManager.md) (15 shared connections)
- [JsonlEvent](JsonlEvent.md) (12 shared connections)
- [StreamPhase](StreamPhase.md) (12 shared connections)
- [_drive](_drive.md) (9 shared connections)
- [RunState](RunState.md) (6 shared connections)
- [WarningType](WarningType.md) (4 shared connections)
- [RunSummary](RunSummary.md) (4 shared connections)
- [runner.py](runner.py.md) (3 shared connections)
- [PtyStreamParser](PtyStreamParser.md) (3 shared connections)
- [test_replay_determinism.py](test_replay_determinism.py.md) (3 shared connections)
- [test_no_eof_hang.py](test_no_eof_hang.py.md) (3 shared connections)
- [TestJsonLineStreamSurvivesMojibake](TestJsonLineStreamSurvivesMojibake.md) (3 shared connections)

## Source Files

- `src/ansible_aom/core/parser.py`
- `src/ansible_aom/core/state_machine.py`
- `src/ansible_aom/formats/json.py`
- `tests/integration/test_session.py`
- `tests/unit/test_encoding_robustness.py`
- `tests/unit/test_parser_orjson_swap.py`
- `tests/unit/test_pty_stream.py`
- `tests/unit/test_run_state_set_caps.py`
- `tests/unit/test_runner_eof_watchdog.py`
- `tests/unit/test_session_meta_persistence.py`
- `tests/unit/test_sink_disable_and_preflight_ms.py`

## Audit Trail

- EXTRACTED: 290 (98%)
- INFERRED: 5 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*