# cli_main

> 13 nodes · cohesion 0.28

## Key Concepts

- **cli_main()** (13 connections) — `src/ansible_aom/drivers/replay.py`
- **TestReplayCLIMain** (6 connections) — `tests/unit/test_cli_replay.py`
- **test_cli_replay.py** (5 connections) — `tests/unit/test_cli_replay.py`
- **_make_session()** (5 connections) — `tests/unit/test_cli_replay.py`
- **Path** (5 connections)
- **.test_cli_main_speed_zero_allowed()** (5 connections) — `tests/unit/test_cli_replay.py`
- **.test_cli_main_default_uses_compact_renderer()** (4 connections) — `tests/unit/test_cli_replay.py`
- **.test_cli_main_speed_forwarded()** (4 connections) — `tests/unit/test_cli_replay.py`
- **.test_cli_main_returns_1_when_session_missing()** (3 connections) — `tests/unit/test_cli_replay.py`
- **Entry point for ``aom replay <session-id> [...]``.      Argparse the supplied ta** (1 connections) — `src/ansible_aom/drivers/replay.py`
- **CLI tests for the F2 `aom replay` subcommand dispatch.  Mirrors the inspect-disp** (1 connections) — `tests/unit/test_cli_replay.py`
- **`--speed 0` is the documented "fast as possible" sentinel.** (1 connections) — `tests/unit/test_cli_replay.py`
- **`replay.cli_main` parses argv, builds a renderer, calls replay_session.** (1 connections) — `tests/unit/test_cli_replay.py`

## Relationships

- [ansible_aom/cli.py](ansible_aom-cli.py.md) (2 shared connections)
- [ReplayDriver](ReplayDriver.md) (2 shared connections)
- [diagnostics.py](diagnostics.py.md) (1 shared connections)
- [JsonlEvent](JsonlEvent.md) (1 shared connections)
- [Ansible Posix Availability](Ansible_Posix_Availability.md) (1 shared connections)
- [create_renderer](create_renderer.md) (1 shared connections)
- [json.py](json.py.md) (1 shared connections)
- [TestReplayDispatch](TestReplayDispatch.md) (1 shared connections)

## Source Files

- `src/ansible_aom/drivers/replay.py`
- `tests/unit/test_cli_replay.py`

## Audit Trail

- EXTRACTED: 46 (85%)
- INFERRED: 8 (15%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*