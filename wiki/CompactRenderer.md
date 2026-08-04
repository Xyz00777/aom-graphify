# CompactRenderer

> 150 nodes · cohesion 0.02

## Key Concepts

- **CompactRenderer** (338 connections) — `src/ansible_aom/compact/renderer.py`
- **test_renderer_set_definitions.py** (11 connections) — `tests/compact/test_renderer_set_definitions.py`
- **test_renderer_stats.py** (11 connections) — `tests/compact/test_renderer_stats.py`
- **TestCompactModePasswordFlow** (10 connections) — `tests/compact/test_password.py`
- **TestCompactRendererInteractivePrompt** (9 connections) — `tests/unit/test_interactive_prompt.py`
- **test_warning_visibility.py** (8 connections) — `tests/compact/test_warning_visibility.py`
- **TestPauseSecondsLogged** (8 connections) — `tests/unit/test_compact_pause_visibility.py`
- **test_long_output_cap.py** (7 connections) — `tests/compact/test_long_output_cap.py`
- **_build_definitions()** (7 connections) — `tests/compact/test_renderer_set_definitions.py`
- **test_unknown_event_hint.py** (7 connections) — `tests/compact/test_unknown_event_hint.py`
- **test_unmatched_event_hint.py** (6 connections) — `tests/compact/test_unmatched_event_hint.py`
- **_pause_task_event()** (5 connections) — `tests/unit/test_compact_pause_visibility.py`
- **test_set_definitions_called_before_start_is_safe()** (4 connections) — `tests/compact/test_renderer_set_definitions.py`
- **test_set_definitions_prints_summary_above_status_panel()** (4 connections) — `tests/compact/test_renderer_set_definitions.py`
- **test_set_definitions_unions_hosts_across_plays()** (4 connections) — `tests/compact/test_renderer_set_definitions.py`
- **test_set_definitions_updates_initial_hosts_total_in_status_bar()** (4 connections) — `tests/compact/test_renderer_set_definitions.py`
- **_ok_event()** (4 connections) — `tests/compact/test_renderer_stats.py`
- **_empty_state()** (4 connections) — `tests/compact/test_unknown_event_hint.py`
- **test_completion_no_hint_when_all_known()** (4 connections) — `tests/compact/test_unknown_event_hint.py`
- **_empty_state()** (4 connections) — `tests/compact/test_unmatched_event_hint.py`
- **.test_tick_refreshes_status_bar_without_an_event()** (4 connections) — `tests/integration/test_compact_renderer.py`
- **.test_handle_password_prompt_returns_string()** (4 connections) — `tests/integration/test_compact_renderer.py`
- **.test_pause_short_action_name_also_caught()** (4 connections) — `tests/unit/test_compact_pause_visibility.py`
- **.test_pause_with_string_seconds_handled()** (4 connections) — `tests/unit/test_compact_pause_visibility.py`
- **.test_pause_without_seconds_does_not_emit_sleeping_line()** (4 connections) — `tests/unit/test_compact_pause_visibility.py`
- *... and 125 more nodes in this community*

## Relationships

- [HostRunState](HostRunState.md) (43 shared connections)
- [JsonlEvent](JsonlEvent.md) (31 shared connections)
- [test_cli.py](test_cli.py.md) (18 shared connections)
- [Inspect CLI Commands](Inspect_CLI_Commands.md) (14 shared connections)
- [Event Log Emission](Event_Log_Emission.md) (14 shared connections)
- [renderer.py](renderer.py.md) (9 shared connections)
- [._render_status_panel](_render_status_panel.md) (9 shared connections)
- [create_renderer](create_renderer.md) (8 shared connections)
- [Playbook Run Integration Tests](Playbook_Run_Integration_Tests.md) (8 shared connections)
- [Renderer Parity Invariant](Renderer_Parity_Invariant.md) (7 shared connections)
- [TestTerminalSizeCheck](TestTerminalSizeCheck.md) (7 shared connections)
- [Tree Expansion Icons](Tree_Expansion_Icons.md) (6 shared connections)

## Source Files

- `src/ansible_aom/compact/renderer.py`
- `tests/compact/test_long_output_cap.py`
- `tests/compact/test_password.py`
- `tests/compact/test_renderer_set_definitions.py`
- `tests/compact/test_renderer_stats.py`
- `tests/compact/test_unknown_event_hint.py`
- `tests/compact/test_unmatched_event_hint.py`
- `tests/compact/test_warning_visibility.py`
- `tests/integration/test_compact_renderer.py`
- `tests/unit/test_compact_pause_visibility.py`
- `tests/unit/test_interactive_prompt.py`

## Audit Trail

- EXTRACTED: 497 (70%)
- INFERRED: 218 (30%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*