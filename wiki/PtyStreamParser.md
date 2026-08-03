# PtyStreamParser

> 107 nodes · cohesion 0.02

## Key Concepts

- **PtyStreamParser** (338 connections) — `src/ansible_aom/core/parser.py`
- **TestPtyStreamParserLatestOutputIsPlaintext** (15 connections) — `tests/unit/test_parser.py`
- **.test_process_play_start_creates_play_state()** (3 connections) — `tests/unit/test_parser.py`
- **.test_process_playbook_start_sets_start_time()** (3 connections) — `tests/unit/test_parser.py`
- **.test_process_runner_start_free_strategy()** (3 connections) — `tests/unit/test_parser.py`
- **.test_clear_password_prompt()** (3 connections) — `tests/unit/test_parser.py`
- **.test_deprecation_warning_pattern()** (3 connections) — `tests/unit/test_parser.py`
- **.test_initial_phase_pre_run_prompts()** (3 connections) — `tests/unit/test_parser.py`
- **.test_password_pattern_become()** (3 connections) — `tests/unit/test_parser.py`
- **.test_password_pattern_ssh()** (3 connections) — `tests/unit/test_parser.py`
- **.test_password_pattern_vault()** (3 connections) — `tests/unit/test_parser.py`
- **.test_play_recap_detection()** (3 connections) — `tests/unit/test_parser.py`
- **.test_transition_to_execution_on_start_event()** (3 connections) — `tests/unit/test_parser.py`
- **.test_transition_to_post_run_on_stats_event()** (3 connections) — `tests/unit/test_parser.py`
- **.test_warning_pattern_detection()** (3 connections) — `tests/unit/test_parser.py`
- **.test_plaintext_lines_60000_input_retains_exactly_50000()** (3 connections) — `tests/unit/test_parser.py`
- **.test_ansi_stripped_before_classification()** (3 connections) — `tests/unit/test_parser.py`
- **.test_connection_acquire_adds_to_active()** (3 connections) — `tests/unit/test_parser.py`
- **.test_connection_acquire_different_hosts()** (3 connections) — `tests/unit/test_parser.py`
- **.test_connection_acquire_multiple_for_same_host()** (3 connections) — `tests/unit/test_parser.py`
- **.test_connection_release_removes_from_active()** (3 connections) — `tests/unit/test_parser.py`
- **.test_connection_release_unknown_conn_id_noop()** (3 connections) — `tests/unit/test_parser.py`
- **.test_deprecation_does_not_emit_stderr_line()** (3 connections) — `tests/unit/test_parser.py`
- **.test_non_warning_plaintext_emits_stderr_line()** (3 connections) — `tests/unit/test_parser.py`
- **.test_password_prompt_does_not_emit_stderr_line()** (3 connections) — `tests/unit/test_parser.py`
- *... and 82 more nodes in this community*

## Relationships

- [StreamPhase](StreamPhase.md) (67 shared connections)
- [TestWarningPatternsEdgeCases](TestWarningPatternsEdgeCases.md) (23 shared connections)
- [_drive](_drive.md) (14 shared connections)
- [test_error_handling.py](test_error_handling.py.md) (13 shared connections)
- [TestPasswordPromptPatterns](TestPasswordPromptPatterns.md) (13 shared connections)
- [TestEdgeCases](TestEdgeCases.md) (11 shared connections)
- [_safe_loads](_safe_loads.md) (10 shared connections)
- [TestEventParsing](TestEventParsing.md) (9 shared connections)
- [TestConftestFixtures](TestConftestFixtures.md) (9 shared connections)
- [TestPtyStreamParserPhaseTransitions](TestPtyStreamParserPhaseTransitions.md) (9 shared connections)
- [TestWarningPatternDetection](TestWarningPatternDetection.md) (9 shared connections)
- [TestMultiLineWarningContinuation](TestMultiLineWarningContinuation.md) (8 shared connections)

## Source Files

- `src/ansible_aom/core/parser.py`
- `tests/unit/test_parser.py`

## Audit Trail

- EXTRACTED: 428 (77%)
- INFERRED: 126 (23%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*