# CompactRenderer

> 131 nodes · cohesion 0.02

## Key Concepts

- **CompactRenderer** (338 connections) — `src/ansible_aom/compact/renderer.py`
- **test_renderer_set_definitions.py** (11 connections) — `tests/compact/test_renderer_set_definitions.py`
- **TestCompactModePasswordFlow** (10 connections) — `tests/compact/test_password.py`
- **TestCompactRendererInteractivePrompt** (9 connections) — `tests/unit/test_interactive_prompt.py`
- **test_warning_visibility.py** (8 connections) — `tests/compact/test_warning_visibility.py`
- **test_long_output_cap.py** (7 connections) — `tests/compact/test_long_output_cap.py`
- **test_password.py** (7 connections) — `tests/compact/test_password.py`
- **_build_definitions()** (7 connections) — `tests/compact/test_renderer_set_definitions.py`
- **test_unmatched_event_hint.py** (6 connections) — `tests/compact/test_unmatched_event_hint.py`
- **test_prior_run_loop_totals_injection.py** (5 connections) — `tests/unit/test_prior_run_loop_totals_injection.py`
- **TestCompactInjection** (5 connections) — `tests/unit/test_prior_run_loop_totals_injection.py`
- **test_set_definitions_called_before_start_is_safe()** (4 connections) — `tests/compact/test_renderer_set_definitions.py`
- **test_set_definitions_prints_summary_above_status_panel()** (4 connections) — `tests/compact/test_renderer_set_definitions.py`
- **test_set_definitions_unions_hosts_across_plays()** (4 connections) — `tests/compact/test_renderer_set_definitions.py`
- **test_set_definitions_updates_initial_hosts_total_in_status_bar()** (4 connections) — `tests/compact/test_renderer_set_definitions.py`
- **test_renderer_status_bar_reflects_outcome_tally()** (4 connections) — `tests/compact/test_status_tally_bar.py`
- **_empty_state()** (4 connections) — `tests/compact/test_unmatched_event_hint.py`
- **.test_tick_refreshes_status_bar_without_an_event()** (4 connections) — `tests/integration/test_compact_renderer.py`
- **.test_handle_password_prompt_returns_string()** (4 connections) — `tests/integration/test_compact_renderer.py`
- **test_item_failed_msg_truncated_above_cap()** (3 connections) — `tests/compact/test_long_output_cap.py`
- **test_one_megabyte_failed_msg_truncated()** (3 connections) — `tests/compact/test_long_output_cap.py`
- **test_short_msg_not_truncated()** (3 connections) — `tests/compact/test_long_output_cap.py`
- **.test_render_handle_password_prompt_returns_empty_on_cancel()** (3 connections) — `tests/compact/test_password.py`
- **.test_render_handle_password_prompt_returns_password()** (3 connections) — `tests/compact/test_password.py`
- **.test_render_handle_password_prompt_starts_display_after_input()** (3 connections) — `tests/compact/test_password.py`
- *... and 106 more nodes in this community*

## Relationships

- [Status](Status.md) (54 shared connections)
- [._emit_event_log](_emit_event_log.md) (22 shared connections)
- [renderer.py](renderer.py.md) (15 shared connections)
- [Inspect CLI Commands](Inspect_CLI_Commands.md) (14 shared connections)
- [Event Log Emission](Event_Log_Emission.md) (14 shared connections)
- [JsonlEvent](JsonlEvent.md) (9 shared connections)
- [create_renderer](create_renderer.md) (8 shared connections)
- [Playbook Run Integration Tests](Playbook_Run_Integration_Tests.md) (8 shared connections)
- [create_parser](create_parser.md) (8 shared connections)
- [history.py](history.py.md) (7 shared connections)
- [Renderer Parity Invariant](Renderer_Parity_Invariant.md) (7 shared connections)
- [format_failure_recap](format_failure_recap.md) (6 shared connections)

## Source Files

- `src/ansible_aom/compact/renderer.py`
- `tests/compact/test_long_output_cap.py`
- `tests/compact/test_password.py`
- `tests/compact/test_renderer_set_definitions.py`
- `tests/compact/test_status_tally_bar.py`
- `tests/compact/test_unmatched_event_hint.py`
- `tests/compact/test_warning_visibility.py`
- `tests/integration/test_compact_renderer.py`
- `tests/unit/test_interactive_prompt.py`
- `tests/unit/test_prior_run_loop_totals_injection.py`

## Audit Trail

- EXTRACTED: 442 (67%)
- INFERRED: 216 (33%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*