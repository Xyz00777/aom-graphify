# Renderer

> 49 nodes · cohesion 0.04

## Key Concepts

- **Renderer** (43 connections) — `src/ansible_aom/renderer/protocol.py`
- **TestProtocol** (5 connections) — `tests/unit/test_interactive_prompt.py`
- **.test_compact_renderer_satisfies_protocol()** (4 connections) — `tests/unit/test_cli.py`
- **.drive()** (3 connections) — `src/ansible_aom/drivers/protocol.py`
- **.add_warning()** (3 connections) — `src/ansible_aom/renderer/protocol.py`
- **.test_renderer_protocol_has_handle_completion_method()** (3 connections) — `tests/unit/test_cli.py`
- **.test_renderer_protocol_has_handle_password_prompt_method()** (3 connections) — `tests/unit/test_cli.py`
- **.test_renderer_protocol_has_start_method()** (3 connections) — `tests/unit/test_cli.py`
- **.test_renderer_protocol_has_stop_method()** (3 connections) — `tests/unit/test_cli.py`
- **.test_renderer_protocol_has_update_state_method()** (3 connections) — `tests/unit/test_cli.py`
- **test_interactive_prompt.py** (3 connections) — `tests/unit/test_interactive_prompt.py`
- **.test_compact_renderer_still_satisfies_protocol()** (3 connections) — `tests/unit/test_interactive_prompt.py`
- **.handle_completion()** (2 connections) — `src/ansible_aom/renderer/protocol.py`
- **.handle_interactive_prompt()** (2 connections) — `src/ansible_aom/renderer/protocol.py`
- **.handle_password_prompt()** (2 connections) — `src/ansible_aom/renderer/protocol.py`
- **.note_pty_bytes()** (2 connections) — `src/ansible_aom/renderer/protocol.py`
- **.note_subprocess_active()** (2 connections) — `src/ansible_aom/renderer/protocol.py`
- **.print_log()** (2 connections) — `src/ansible_aom/renderer/protocol.py`
- **.set_definitions()** (2 connections) — `src/ansible_aom/renderer/protocol.py`
- **.set_prior_run()** (2 connections) — `src/ansible_aom/renderer/protocol.py`
- **.start()** (2 connections) — `src/ansible_aom/renderer/protocol.py`
- **.stop()** (2 connections) — `src/ansible_aom/renderer/protocol.py`
- **.tick()** (2 connections) — `src/ansible_aom/renderer/protocol.py`
- **.update_state()** (2 connections) — `src/ansible_aom/renderer/protocol.py`
- **.test_protocol_declares_handle_interactive_prompt()** (2 connections) — `tests/unit/test_interactive_prompt.py`
- *... and 24 more nodes in this community*

## Relationships

- [runner.py](runner.py.md) (6 shared connections)
- [HostRunState](HostRunState.md) (6 shared connections)
- [FakeRenderer](FakeRenderer.md) (5 shared connections)
- [CompactRenderer](CompactRenderer.md) (4 shared connections)
- [drivers/replay.py](drivers-replay.py.md) (3 shared connections)
- [run_playbook](run_playbook.md) (1 shared connections)
- [_handle_timeout_branch](_handle_timeout_branch.md) (1 shared connections)
- [JsonlEvent](JsonlEvent.md) (1 shared connections)
- [Hide State Normalization](Hide_State_Normalization.md) (1 shared connections)
- [create_renderer](create_renderer.md) (1 shared connections)
- [PriorRun](PriorRun.md) (1 shared connections)
- [JsonRenderer](JsonRenderer.md) (1 shared connections)

## Source Files

- `src/ansible_aom/drivers/protocol.py`
- `src/ansible_aom/renderer/protocol.py`
- `tests/unit/test_cli.py`
- `tests/unit/test_interactive_prompt.py`

## Audit Trail

- EXTRACTED: 106 (82%)
- INFERRED: 23 (18%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*