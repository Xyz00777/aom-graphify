# ansible_aom/cli.py

> 33 nodes · cohesion 0.12

## Key Concepts

- **ansible_aom/cli.py** (26 connections) — `src/ansible_aom/cli.py`
- **main()** (18 connections) — `src/ansible_aom/cli.py`
- **ensure_inventory_arg()** (9 connections) — `src/ansible_aom/cli.py`
- **MonkeyPatch** (9 connections)
- **Path** (9 connections)
- **detect_default_inventory()** (7 connections) — `src/ansible_aom/cli.py`
- **_run_compact()** (6 connections) — `src/ansible_aom/cli.py`
- **TestEnsureInventoryArg** (6 connections) — `tests/unit/test_cli_inventory_autodetect.py`
- **TestDetectDefaultInventory** (5 connections) — `tests/unit/test_cli_inventory_autodetect.py`
- **.test_handles_inventory_file_long_form()** (5 connections) — `tests/unit/test_cli_inventory_autodetect.py`
- **test_cli_inventory_autodetect.py** (4 connections) — `tests/unit/test_cli_inventory_autodetect.py`
- **.test_finds_inventory_ini_in_cwd()** (4 connections) — `tests/unit/test_cli_inventory_autodetect.py`
- **.test_finds_yaml_inventory_when_only_one_present()** (4 connections) — `tests/unit/test_cli_inventory_autodetect.py`
- **.test_prefers_inventory_ini_over_hosts()** (4 connections) — `tests/unit/test_cli_inventory_autodetect.py`
- **.test_returns_none_when_no_known_file_present()** (4 connections) — `tests/unit/test_cli_inventory_autodetect.py`
- **.test_leaves_args_unchanged_when_dash_i_present()** (4 connections) — `tests/unit/test_cli_inventory_autodetect.py`
- **.test_leaves_args_unchanged_when_long_inventory_flag_present()** (4 connections) — `tests/unit/test_cli_inventory_autodetect.py`
- **.test_leaves_args_unchanged_when_no_default_present()** (4 connections) — `tests/unit/test_cli_inventory_autodetect.py`
- **.test_prepends_default_inventory_when_none_given()** (4 connections) — `tests/unit/test_cli_inventory_autodetect.py`
- **_confirm_no_redact()** (3 connections) — `src/ansible_aom/cli.py`
- **set_debug()** (3 connections) — `src/ansible_aom/core/diagnostics.py`
- **__main__.py** (3 connections) — `src/ansible_aom/__main__.py`
- **OutputFormat** (1 connections)
- **CLI entry point for AOM.  This module provides the main command-line interface f** (1 connections) — `src/ansible_aom/cli.py`
- **If no -i/--inventory flag is set, prepend one pointing at the default file.** (1 connections) — `src/ansible_aom/cli.py`
- *... and 8 more nodes in this community*

## Relationships

- [source_hash](source_hash.md) (3 shared connections)
- [State Transition Validation](State_Transition_Validation.md) (3 shared connections)
- [merge_limit_args](merge_limit_args.md) (3 shared connections)
- [diagnostics.py](diagnostics.py.md) (3 shared connections)
- [create_parser](create_parser.md) (2 shared connections)
- [completion_snippet](completion_snippet.md) (2 shared connections)
- [Auto Version Bump Hook](Auto_Version_Bump_Hook.md) (2 shared connections)
- [LiveDriver](LiveDriver.md) (2 shared connections)
- [cli_main](cli_main.md) (2 shared connections)
- [load_session](load_session.md) (2 shared connections)
- [create_renderer](create_renderer.md) (2 shared connections)
- [rerun/cli.py](rerun-cli.py.md) (2 shared connections)

## Source Files

- `src/ansible_aom/__main__.py`
- `src/ansible_aom/cli.py`
- `src/ansible_aom/core/diagnostics.py`
- `tests/unit/test_cli_inventory_autodetect.py`

## Audit Trail

- EXTRACTED: 156 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*