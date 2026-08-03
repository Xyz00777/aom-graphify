# JsonRenderer

> 87 nodes · cohesion 0.03

## Key Concepts

- **JsonRenderer** (76 connections) — `src/ansible_aom/formats/json.py`
- **test_json_renderer.py** (25 connections) — `tests/unit/test_json_renderer.py`
- **create_renderer()** (23 connections) — `src/ansible_aom/renderer/factory.py`
- **_state_two_hosts_one_failure()** (12 connections) — `tests/unit/test_json_renderer.py`
- **_default_runner()** (4 connections) — `src/ansible_aom/rerun/cli.py`
- **.test_factory_creates_compact_renderer_by_default()** (4 connections) — `tests/integration/test_compact_renderer.py`
- **.test_factory_forwards_failed_hint_flag_to_compact_renderer()** (4 connections) — `tests/unit/test_cli.py`
- **.test_factory_forwards_is_tty_to_compact_renderer()** (4 connections) — `tests/unit/test_cli.py`
- **.test_factory_forwards_recording_flags_to_compact_renderer()** (4 connections) — `tests/unit/test_cli.py`
- **.test_factory_forwards_warning_flags_to_compact_renderer()** (4 connections) — `tests/unit/test_cli.py`
- **test_handle_completion_aggregates_per_host_counts()** (4 connections) — `tests/unit/test_json_renderer.py`
- **test_handle_completion_emits_one_json_object()** (4 connections) — `tests/unit/test_json_renderer.py`
- **test_handle_completion_lists_failed_tasks()** (4 connections) — `tests/unit/test_json_renderer.py`
- **test_handle_completion_uses_state_timestamps()** (4 connections) — `tests/unit/test_json_renderer.py`
- **test_json_renderer_satisfies_renderer_protocol()** (4 connections) — `tests/unit/test_json_renderer.py`
- **.handle_interactive_prompt()** (3 connections) — `src/ansible_aom/formats/json.py`
- **.handle_password_prompt()** (3 connections) — `src/ansible_aom/formats/json.py`
- **.start()** (3 connections) — `src/ansible_aom/formats/json.py`
- **.update_state()** (3 connections) — `src/ansible_aom/formats/json.py`
- **.test_main_dispatches_json_renderer_when_format_json()** (3 connections) — `tests/unit/test_cli.py`
- **.test_factory_default_tui_mode_false()** (3 connections) — `tests/unit/test_cli.py`
- **.test_factory_function_exists()** (3 connections) — `tests/unit/test_cli.py`
- **.test_factory_returns_renderer_for_compact_mode()** (3 connections) — `tests/unit/test_cli.py`
- **test_factory_compact_format_explicit_returns_compact_renderer()** (3 connections) — `tests/unit/test_json_renderer.py`
- **test_factory_default_format_is_compact()** (3 connections) — `tests/unit/test_json_renderer.py`
- *... and 62 more nodes in this community*

## Relationships

- [HostRunState](HostRunState.md) (35 shared connections)
- [create_parser](create_parser.md) (8 shared connections)
- [CompactRenderer](CompactRenderer.md) (8 shared connections)
- [json.py](json.py.md) (4 shared connections)
- [Renderer](Renderer.md) (4 shared connections)
- [RunState](RunState.md) (3 shared connections)
- [JsonlEvent](JsonlEvent.md) (2 shared connections)
- [test_replay_determinism.py](test_replay_determinism.py.md) (2 shared connections)
- [TestHideStateCompactPlumbing](TestHideStateCompactPlumbing.md) (2 shared connections)
- [ansible_aom/cli.py](ansible_aom-cli.py.md) (2 shared connections)
- [rerun/cli.py](rerun-cli.py.md) (2 shared connections)
- [Status](Status.md) (1 shared connections)

## Source Files

- `src/ansible_aom/formats/json.py`
- `src/ansible_aom/renderer/factory.py`
- `src/ansible_aom/rerun/cli.py`
- `tests/integration/test_compact_renderer.py`
- `tests/unit/test_cli.py`
- `tests/unit/test_json_renderer.py`

## Audit Trail

- EXTRACTED: 197 (65%)
- INFERRED: 106 (35%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*