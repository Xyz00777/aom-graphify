# drivers/replay.py

> 30 nodes · cohesion 0.10

## Key Concepts

- **drivers/replay.py** (19 connections) — `src/ansible_aom/drivers/replay.py`
- **cli_main()** (13 connections) — `src/ansible_aom/drivers/replay.py`
- **renderer/protocol.py** (11 connections) — `src/ansible_aom/renderer/protocol.py`
- **factory.py** (7 connections) — `src/ansible_aom/renderer/factory.py`
- **TestReplayCLIMain** (6 connections) — `tests/unit/test_cli_replay.py`
- **_build_parser()** (5 connections) — `src/ansible_aom/drivers/replay.py`
- **_parse_timestamp()** (5 connections) — `src/ansible_aom/drivers/replay.py`
- **test_cli_replay.py** (5 connections) — `tests/unit/test_cli_replay.py`
- **_make_session()** (5 connections) — `tests/unit/test_cli_replay.py`
- **Path** (5 connections)
- **.test_cli_main_speed_zero_allowed()** (5 connections) — `tests/unit/test_cli_replay.py`
- **.test_cli_main_default_uses_compact_renderer()** (4 connections) — `tests/unit/test_cli_replay.py`
- **.test_cli_main_speed_forwarded()** (4 connections) — `tests/unit/test_cli_replay.py`
- **TestReplayDispatch** (4 connections) — `tests/unit/test_cli_replay.py`
- **.test_cli_main_returns_1_when_session_missing()** (3 connections) — `tests/unit/test_cli_replay.py`
- **datetime** (2 connections)
- **.test_replay_dispatches_to_replay_main()** (2 connections) — `tests/unit/test_cli_replay.py`
- **ArgumentParser** (1 connections)
- **Replay a recorded AOM session through a Renderer (F2).  Both halves of the repla** (1 connections) — `src/ansible_aom/drivers/replay.py`
- **Build the ``aom replay`` argument parser.      Factored out of :func:`cli_main`** (1 connections) — `src/ansible_aom/drivers/replay.py`
- **Entry point for ``aom replay <session-id> [...]``.      Argparse the supplied ta** (1 connections) — `src/ansible_aom/drivers/replay.py`
- **Parse an ISO 8601 ``_timestamp`` field; return None when unparseable.** (1 connections) — `src/ansible_aom/drivers/replay.py`
- **Renderer factory for compact and JSON output.** (1 connections) — `src/ansible_aom/renderer/factory.py`
- **Renderer Protocol — the display-side port of the architecture.  See ``ARCHITECTU** (1 connections) — `src/ansible_aom/renderer/protocol.py`
- **CLI tests for the F2 `aom replay` subcommand dispatch.  Mirrors the inspect-disp** (1 connections) — `tests/unit/test_cli_replay.py`
- *... and 5 more nodes in this community*

## Relationships

- [FakeRenderer](FakeRenderer.md) (6 shared connections)
- [load_session](load_session.md) (5 shared connections)
- [runner.py](runner.py.md) (3 shared connections)
- [create_renderer](create_renderer.md) (3 shared connections)
- [Renderer](Renderer.md) (3 shared connections)
- [session_id_completer](session_id_completer.md) (2 shared connections)
- [Hide State Normalization](Hide_State_Normalization.md) (2 shared connections)
- [ansible_aom/cli.py](ansible_aom-cli.py.md) (2 shared connections)
- [test_replay_determinism.py](test_replay_determinism.py.md) (1 shared connections)
- [CompactRenderer](CompactRenderer.md) (1 shared connections)
- [JsonRenderer](JsonRenderer.md) (1 shared connections)
- [event_types.py](event_types.py.md) (1 shared connections)

## Source Files

- `src/ansible_aom/drivers/replay.py`
- `src/ansible_aom/renderer/factory.py`
- `src/ansible_aom/renderer/protocol.py`
- `tests/unit/test_cli_replay.py`

## Audit Trail

- EXTRACTED: 109 (92%)
- INFERRED: 9 (8%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*