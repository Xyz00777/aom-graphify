# Renderer

> 55 nodes · cohesion 0.04

## Key Concepts

- **Renderer** (43 connections) — `src/ansible_aom/renderer/protocol.py`
- **renderer/protocol.py** (11 connections) — `src/ansible_aom/renderer/protocol.py`
- **factory.py** (7 connections) — `src/ansible_aom/renderer/factory.py`
- **live.py** (5 connections) — `src/ansible_aom/drivers/live.py`
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
- *... and 30 more nodes in this community*

## Relationships

- [runner.py](runner.py.md) (7 shared connections)
- [FakeRenderer](FakeRenderer.md) (6 shared connections)
- [test_cli.py](test_cli.py.md) (6 shared connections)
- [CompactRenderer](CompactRenderer.md) (5 shared connections)
- [store.py](store.py.md) (3 shared connections)
- [history.py](history.py.md) (3 shared connections)
- [run_playbook](run_playbook.md) (2 shared connections)
- [JsonRenderer](JsonRenderer.md) (2 shared connections)
- [create_renderer](create_renderer.md) (2 shared connections)
- [JsonlEvent](JsonlEvent.md) (2 shared connections)
- [event_types.py](event_types.py.md) (1 shared connections)
- [_handle_timeout_branch](_handle_timeout_branch.md) (1 shared connections)

## Source Files

- `src/ansible_aom/drivers/live.py`
- `src/ansible_aom/drivers/protocol.py`
- `src/ansible_aom/renderer/factory.py`
- `src/ansible_aom/renderer/protocol.py`
- `tests/unit/test_cli.py`
- `tests/unit/test_interactive_prompt.py`

## Audit Trail

- EXTRACTED: 132 (85%)
- INFERRED: 23 (15%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*