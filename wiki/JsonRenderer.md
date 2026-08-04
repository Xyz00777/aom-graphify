# JsonRenderer

> 62 nodes · cohesion 0.04

## Key Concepts

- **JsonRenderer** (76 connections) — `src/ansible_aom/formats/json.py`
- **test_json_renderer.py** (25 connections) — `tests/unit/test_json_renderer.py`
- **_state_two_hosts_one_failure()** (12 connections) — `tests/unit/test_json_renderer.py`
- **test_handle_completion_aggregates_per_host_counts()** (4 connections) — `tests/unit/test_json_renderer.py`
- **test_handle_completion_emits_one_json_object()** (4 connections) — `tests/unit/test_json_renderer.py`
- **test_handle_completion_lists_failed_tasks()** (4 connections) — `tests/unit/test_json_renderer.py`
- **test_handle_completion_uses_state_timestamps()** (4 connections) — `tests/unit/test_json_renderer.py`
- **test_json_renderer_satisfies_renderer_protocol()** (4 connections) — `tests/unit/test_json_renderer.py`
- **.handle_interactive_prompt()** (3 connections) — `src/ansible_aom/formats/json.py`
- **.handle_password_prompt()** (3 connections) — `src/ansible_aom/formats/json.py`
- **.start()** (3 connections) — `src/ansible_aom/formats/json.py`
- **.update_state()** (3 connections) — `src/ansible_aom/formats/json.py`
- **test_factory_returns_json_renderer_for_json_format()** (3 connections) — `tests/unit/test_json_renderer.py`
- **test_handle_completion_empty_state_emits_zero_exit()** (3 connections) — `tests/unit/test_json_renderer.py`
- **test_handle_completion_records_playbook_and_exit_code()** (3 connections) — `tests/unit/test_json_renderer.py`
- **test_handle_completion_schema_version_is_one()** (3 connections) — `tests/unit/test_json_renderer.py`
- **test_interactive_prompt_refuses_to_stderr()** (3 connections) — `tests/unit/test_json_renderer.py`
- **test_json_renderer_noop_methods_emit_nothing()** (3 connections) — `tests/unit/test_json_renderer.py`
- **test_json_renderer_set_definitions_stores_them()** (3 connections) — `tests/unit/test_json_renderer.py`
- **test_json_renderer_start_records_playbook_and_args()** (3 connections) — `tests/unit/test_json_renderer.py`
- **test_json_renderer_through_full_lifecycle()** (3 connections) — `tests/unit/test_json_renderer.py`
- **test_password_prompt_refuses_to_stderr()** (3 connections) — `tests/unit/test_json_renderer.py`
- **test_prompt_refusal_does_not_corrupt_completion_json()** (3 connections) — `tests/unit/test_json_renderer.py`
- **.add_warning()** (2 connections) — `src/ansible_aom/formats/json.py`
- **.note_pty_bytes()** (2 connections) — `src/ansible_aom/formats/json.py`
- *... and 37 more nodes in this community*

## Relationships

- [test_cli.py](test_cli.py.md) (18 shared connections)
- [HostRunState](HostRunState.md) (9 shared connections)
- [json.py](json.py.md) (4 shared connections)
- [create_renderer](create_renderer.md) (4 shared connections)
- [RunState](RunState.md) (3 shared connections)
- [JsonlEvent](JsonlEvent.md) (2 shared connections)
- [Renderer](Renderer.md) (2 shared connections)
- [test_replay_determinism.py](test_replay_determinism.py.md) (2 shared connections)
- [TestFormatFlag](TestFormatFlag.md) (2 shared connections)
- [Status](Status.md) (1 shared connections)
- [parity.py](parity.py.md) (1 shared connections)
- [TestCaptureSetupFlag](TestCaptureSetupFlag.md) (1 shared connections)

## Source Files

- `src/ansible_aom/formats/json.py`
- `tests/unit/test_json_renderer.py`

## Audit Trail

- EXTRACTED: 149 (66%)
- INFERRED: 77 (34%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*