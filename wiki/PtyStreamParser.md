# PtyStreamParser

> 129 nodes · cohesion 0.02

## Key Concepts

- **PtyStreamParser** (338 connections) — `src/ansible_aom/core/parser.py`
- **TestPtyStreamParserLatestOutputIsPlaintext** (15 connections) — `tests/unit/test_parser.py`
- **.test_become_password_prompt_detected()** (3 connections) — `tests/integration/test_playbook_parser.py`
- **.test_clear_password_prompt()** (3 connections) — `tests/integration/test_playbook_parser.py`
- **.test_ssh_password_prompt_detected()** (3 connections) — `tests/integration/test_playbook_parser.py`
- **.test_vault_password_prompt_detected()** (3 connections) — `tests/integration/test_playbook_parser.py`
- **.test_execution_to_post_run_on_stats_event()** (3 connections) — `tests/integration/test_playbook_parser.py`
- **.test_initial_phase_is_pre_run_prompts()** (3 connections) — `tests/integration/test_playbook_parser.py`
- **.test_non_json_lines_handled_during_execution()** (3 connections) — `tests/integration/test_playbook_parser.py`
- **.test_pre_run_to_execution_on_start_event()** (3 connections) — `tests/integration/test_playbook_parser.py`
- **.test_deprecated_pattern()** (3 connections) — `tests/integration/test_playbook_parser.py`
- **.test_deprecation_warning_pattern()** (3 connections) — `tests/integration/test_playbook_parser.py`
- **.test_warning_pattern()** (3 connections) — `tests/integration/test_playbook_parser.py`
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
- *... and 104 more nodes in this community*

## Relationships

- [WarningType](WarningType.md) (65 shared connections)
- [Status](Status.md) (39 shared connections)
- [TestWarningPatternsEdgeCases](TestWarningPatternsEdgeCases.md) (15 shared connections)
- [test_error_handling.py](test_error_handling.py.md) (14 shared connections)
- [_drive](_drive.md) (14 shared connections)
- [TestPasswordPromptPatterns](TestPasswordPromptPatterns.md) (13 shared connections)
- [test_pty_stream.py](test_pty_stream.py.md) (13 shared connections)
- [TestEdgeCases](TestEdgeCases.md) (11 shared connections)
- [_safe_loads](_safe_loads.md) (10 shared connections)
- [TestEventParsing](TestEventParsing.md) (9 shared connections)
- [TestConftestFixtures](TestConftestFixtures.md) (9 shared connections)
- [TestPtyStreamParserPhaseTransitions](TestPtyStreamParserPhaseTransitions.md) (9 shared connections)

## Source Files

- `src/ansible_aom/core/parser.py`
- `tests/integration/test_playbook_parser.py`
- `tests/unit/test_parser.py`

## Audit Trail

- EXTRACTED: 472 (79%)
- INFERRED: 126 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*