# run_playbook

> 74 nodes · cohesion 0.05

## Key Concepts

- **run_playbook()** (85 connections) — `src/ansible_aom/ansible/runner.py`
- **Path** (17 connections)
- **test_runner_interactive_prompts.py** (11 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **_fake_pause_prompt_command()** (10 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **_fake_ansible_command()** (8 connections) — `tests/integration/test_runner.py`
- **test_runner.py** (7 connections) — `tests/integration/test_runner.py`
- **TestRunnerPreflight** (6 connections) — `tests/integration/test_runner.py`
- **TestNewlineTerminatedPromptPath** (5 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **._fake_newline_terminated_prompt()** (5 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **.test_pause_prompt_answer_forwarded_to_child()** (5 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **.test_custom_pause_prompt_without_press_enter_phrasing()** (5 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **.test_default_bracketed_format_is_caught()** (5 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **.test_question_mark_prompt_is_caught()** (5 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **TestRunnerHappyPath** (5 connections) — `tests/integration/test_runner.py`
- **.test_yes_no_prompt_triggers_handler()** (4 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **TestKeyboardInterruptDuringPromptAborts** (4 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **._fake_pause_with_capture()** (4 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **.test_ctrl_c_at_prompt_returns_130_not_zero()** (4 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **TestMultilineBlockPromptColonOnOwnLine** (4 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **.test_colon_on_own_line_block_round_trip()** (4 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **.test_newline_terminated_vars_prompt_round_trip()** (4 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **.test_real_ansible_pause_newline_terminated_round_trip()** (4 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **TestNoPromptNoSpuriousInteractiveCall** (4 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **TestPausePromptDetected** (4 connections) — `tests/integration/test_runner_interactive_prompts.py`
- **.test_pause_prompt_triggers_handle_interactive_prompt()** (4 connections) — `tests/integration/test_runner_interactive_prompts.py`
- *... and 49 more nodes in this community*

## Relationships

- [runner.py](runner.py.md) (13 shared connections)
- [Status Color Mapping](Status_Color_Mapping.md) (8 shared connections)
- [_FakeSpawn](_FakeSpawn.md) (5 shared connections)
- [PlayDefinition](PlayDefinition.md) (5 shared connections)
- [Task Tree Navigation](Task_Tree_Navigation.md) (4 shared connections)
- [RunDiagnostics](RunDiagnostics.md) (3 shared connections)
- [build_run_config_key](build_run_config_key.md) (3 shared connections)
- [test_r6_encoding_roundtrip.py](test_r6_encoding_roundtrip.py.md) (3 shared connections)
- [FakeRenderer](FakeRenderer.md) (2 shared connections)
- [.test_record_false_does_not_touch_default_state_dir](test_record_false_does_not_touch_default_state_dir.md) (2 shared connections)
- [test_replay_determinism.py](test_replay_determinism.py.md) (2 shared connections)
- [Diagnostics CLI Wiring](Diagnostics_CLI_Wiring.md) (2 shared connections)

## Source Files

- `src/ansible_aom/ansible/runner.py`
- `src/ansible_aom/core/diagnostics.py`
- `tests/integration/test_runner.py`
- `tests/integration/test_runner_interactive_prompts.py`

## Audit Trail

- EXTRACTED: 241 (75%)
- INFERRED: 80 (25%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*