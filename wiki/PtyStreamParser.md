# PtyStreamParser

> 143 nodes · cohesion 0.02

## Key Concepts

- **PtyStreamParser** (338 connections) — `src/ansible_aom/core/parser.py`
- **TestPasswordPromptPatterns** (17 connections) — `tests/unit/test_pty_stream.py`
- **TestPtyStreamParserLatestOutputIsPlaintext** (15 connections) — `tests/unit/test_parser.py`
- **TestGracefulDegradationJSONLParseFailure** (5 connections) — `tests/integration/test_error_handling.py`
- **TestPasswordTimeoutMechanisn** (4 connections) — `tests/integration/test_error_handling.py`
- **.test_malformed_jsonl_does_not_crash()** (3 connections) — `tests/integration/test_error_handling.py`
- **.test_valid_json_following_malformed_still_parsed()** (3 connections) — `tests/integration/test_error_handling.py`
- **.test_password_prompt_detected_patterns()** (3 connections) — `tests/integration/test_error_handling.py`
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
- *... and 118 more nodes in this community*

## Relationships

- [Status](Status.md) (66 shared connections)
- [TestWarningPatternsEdgeCases](TestWarningPatternsEdgeCases.md) (23 shared connections)
- [test_playbook_parser.py](test_playbook_parser.py.md) (22 shared connections)
- [StreamPhase](StreamPhase.md) (17 shared connections)
- [_drive](_drive.md) (14 shared connections)
- [TestEdgeCases](TestEdgeCases.md) (11 shared connections)
- [_safe_loads](_safe_loads.md) (10 shared connections)
- [TestEventParsing](TestEventParsing.md) (9 shared connections)
- [TestConftestFixtures](TestConftestFixtures.md) (9 shared connections)
- [TestPtyStreamParserPhaseTransitions](TestPtyStreamParserPhaseTransitions.md) (9 shared connections)
- [TestWarningPatternDetection](TestWarningPatternDetection.md) (9 shared connections)
- [TestPasswordPromptHandling](TestPasswordPromptHandling.md) (8 shared connections)

## Source Files

- `src/ansible_aom/core/parser.py`
- `tests/integration/test_error_handling.py`
- `tests/unit/test_parser.py`
- `tests/unit/test_pty_stream.py`

## Audit Trail

- EXTRACTED: 509 (79%)
- INFERRED: 134 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*