# ansible_aom/cli.py

> 13 nodes · cohesion 0.19

## Key Concepts

- **ansible_aom/cli.py** (26 connections) — `src/ansible_aom/cli.py`
- **main()** (18 connections) — `src/ansible_aom/cli.py`
- **_run_compact()** (6 connections) — `src/ansible_aom/cli.py`
- **_confirm_no_redact()** (3 connections) — `src/ansible_aom/cli.py`
- **__main__.py** (3 connections) — `src/ansible_aom/__main__.py`
- **test_cli_limit_merge.py** (3 connections) — `tests/unit/test_cli_limit_merge.py`
- **OutputFormat** (1 connections)
- **CLI entry point for AOM.  This module provides the main command-line interface f** (1 connections) — `src/ansible_aom/cli.py`
- **Validate ``--no-redact`` per QC-003 (Q4=B: confirm prompt).      Returns ``(proc** (1 connections) — `src/ansible_aom/cli.py`
- **Spawn the streaming renderer (compact ANSI or end-of-run JSON) via a LiveDriver.** (1 connections) — `src/ansible_aom/cli.py`
- **Main CLI entry point.      Returns:         Exit code (0 for success, non-zero f** (1 connections) — `src/ansible_aom/cli.py`
- **Entry point for running AOM as a module: python -m ansible_aom.** (1 connections) — `src/ansible_aom/__main__.py`
- **Tests for merging repeated ``-l`` / ``--limit`` flags.  ansible-playbook stores** (1 connections) — `tests/unit/test_cli_limit_merge.py`

## Relationships

- [ensure_inventory_arg](ensure_inventory_arg.md) (4 shared connections)
- [source_hash](source_hash.md) (3 shared connections)
- [State Transition Validation](State_Transition_Validation.md) (3 shared connections)
- [merge_limit_args](merge_limit_args.md) (3 shared connections)
- [runner.py](runner.py.md) (3 shared connections)
- [create_parser](create_parser.md) (2 shared connections)
- [completion_snippet](completion_snippet.md) (2 shared connections)
- [Auto Version Bump Hook](Auto_Version_Bump_Hook.md) (2 shared connections)
- [FakeRenderer](FakeRenderer.md) (2 shared connections)
- [drivers/replay.py](drivers-replay.py.md) (2 shared connections)
- [load_session](load_session.md) (2 shared connections)
- [create_renderer](create_renderer.md) (2 shared connections)

## Source Files

- `src/ansible_aom/__main__.py`
- `src/ansible_aom/cli.py`
- `tests/unit/test_cli_limit_merge.py`

## Audit Trail

- EXTRACTED: 66 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*