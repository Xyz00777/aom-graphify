# create_renderer

> 23 nodes · cohesion 0.09

## Key Concepts

- **create_renderer()** (23 connections) — `src/ansible_aom/renderer/factory.py`
- **_default_runner()** (4 connections) — `src/ansible_aom/rerun/cli.py`
- **.test_factory_creates_compact_renderer_by_default()** (4 connections) — `tests/integration/test_compact_renderer.py`
- **.test_factory_forwards_failed_hint_flag_to_compact_renderer()** (4 connections) — `tests/unit/test_cli.py`
- **.test_factory_forwards_is_tty_to_compact_renderer()** (4 connections) — `tests/unit/test_cli.py`
- **.test_factory_forwards_recording_flags_to_compact_renderer()** (4 connections) — `tests/unit/test_cli.py`
- **.test_factory_forwards_warning_flags_to_compact_renderer()** (4 connections) — `tests/unit/test_cli.py`
- **.test_factory_default_tui_mode_false()** (3 connections) — `tests/unit/test_cli.py`
- **.test_factory_function_exists()** (3 connections) — `tests/unit/test_cli.py`
- **.test_factory_returns_renderer_for_compact_mode()** (3 connections) — `tests/unit/test_cli.py`
- **test_factory_compact_format_explicit_returns_compact_renderer()** (3 connections) — `tests/unit/test_json_renderer.py`
- **test_factory_default_format_is_compact()** (3 connections) — `tests/unit/test_json_renderer.py`
- **RenderMode** (1 connections)
- **Create the renderer selected by ``mode``.      Args:         mode: ``"compact"``** (1 connections) — `src/ansible_aom/renderer/factory.py`
- **Real-world runner: spawn the renderer + run_playbook.      Lazy-imported so unit** (1 connections) — `src/ansible_aom/rerun/cli.py`
- **Default view mode is compact.** (1 connections) — `tests/integration/test_compact_renderer.py`
- **TC-005: create_renderer function exists.** (1 connections) — `tests/unit/test_cli.py`
- **TC-005: create_renderer() returns CompactRenderer.** (1 connections) — `tests/unit/test_cli.py`
- **TC-005: create_renderer() defaults to compact renderer.** (1 connections) — `tests/unit/test_cli.py`
- **create_renderer(is_tty=False) constructs a non-TTY CompactRenderer.** (1 connections) — `tests/unit/test_cli.py`
- **Compact renderer gets recording + verbose-capture state from the factory.** (1 connections) — `tests/unit/test_cli.py`
- **Compact renderer gets the failed-hint toggle from the factory.** (1 connections) — `tests/unit/test_cli.py`
- **Compact renderer gets warning visibility toggles from the factory.** (1 connections) — `tests/unit/test_cli.py`

## Relationships

- [CompactRenderer](CompactRenderer.md) (8 shared connections)
- [test_cli.py](test_cli.py.md) (7 shared connections)
- [JsonRenderer](JsonRenderer.md) (4 shared connections)
- [ansible_aom/cli.py](ansible_aom-cli.py.md) (2 shared connections)
- [Renderer](Renderer.md) (2 shared connections)
- [rerun/cli.py](rerun-cli.py.md) (2 shared connections)
- [store.py](store.py.md) (1 shared connections)
- [cli_main](cli_main.md) (1 shared connections)
- [run_playbook](run_playbook.md) (1 shared connections)
- [HostRunState](HostRunState.md) (1 shared connections)

## Source Files

- `src/ansible_aom/renderer/factory.py`
- `src/ansible_aom/rerun/cli.py`
- `tests/integration/test_compact_renderer.py`
- `tests/unit/test_cli.py`
- `tests/unit/test_json_renderer.py`

## Audit Trail

- EXTRACTED: 45 (62%)
- INFERRED: 28 (38%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*