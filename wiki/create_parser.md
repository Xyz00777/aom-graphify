# create_parser

> 30 nodes · cohesion 0.07

## Key Concepts

- **create_parser()** (81 connections) — `src/ansible_aom/cli.py`
- **.test_inventory_flag_passed_through()** (3 connections) — `tests/unit/test_cli.py`
- **.test_limit_flag_passed_through()** (3 connections) — `tests/unit/test_cli.py`
- **.test_playbook_argument_accepted()** (3 connections) — `tests/unit/test_cli.py`
- **.test_create_parser_returns_argparse_parser()** (3 connections) — `tests/unit/test_cli.py`
- **.test_hide_state_accepts_single_value()** (3 connections) — `tests/unit/test_cli.py`
- **.test_hide_state_case_insensitive_dedup()** (3 connections) — `tests/unit/test_cli.py`
- **.test_hide_state_comma_separated()** (3 connections) — `tests/unit/test_cli.py`
- **.test_hide_state_is_repeatable()** (3 connections) — `tests/unit/test_cli.py`
- **.test_hide_state_single_comma_not_required()** (3 connections) — `tests/unit/test_cli.py`
- **.test_hide_state_typo_error_preserves_original_token()** (3 connections) — `tests/unit/test_cli.py`
- **.test_hide_state_typo_suggests_skipped()** (3 connections) — `tests/unit/test_cli.py`
- **.test_all_flags_compose_with_each_other()** (3 connections) — `tests/unit/test_cli.py`
- **.test_yes_unchanged_from_task_5_1()** (3 connections) — `tests/unit/test_cli.py`
- **.test_create_parser_calls_argcomplete_autocomplete()** (2 connections) — `tests/unit/test_cli.py`
- **.test_help_text_documents_install_completion()** (2 connections) — `tests/unit/test_cli.py`
- **Create the argument parser for the AOM CLI.      Returns:         Configured Arg** (1 connections) — `src/ansible_aom/cli.py`
- **--hide-state ok sets hide_state=["ok"].** (1 connections) — `tests/unit/test_cli.py`
- **--hide-state can be specified multiple times.** (1 connections) — `tests/unit/test_cli.py`
- **--hide-state ok,skipped splits into ["ok", "skipped"].** (1 connections) — `tests/unit/test_cli.py`
- **Single value still works without any comma.** (1 connections) — `tests/unit/test_cli.py`
- **--hide-state ok,OK stores both tokens; dedup happens downstream.** (1 connections) — `tests/unit/test_cli.py`
- **Typo 'skip' suggests 'skipped'.** (1 connections) — `tests/unit/test_cli.py`
- **Error message shows the original (un-lowered) token in quotes.** (1 connections) — `tests/unit/test_cli.py`
- **TC-002: create_parser returns ArgumentParser.** (1 connections) — `tests/unit/test_cli.py`
- *... and 5 more nodes in this community*

## Relationships

- [test_cli.py](test_cli.py.md) (15 shared connections)
- [TestYesFlag](TestYesFlag.md) (6 shared connections)
- [TestConfigPathFlag](TestConfigPathFlag.md) (5 shared connections)
- [TestFormatFlag](TestFormatFlag.md) (5 shared connections)
- [TestCaptureVerboseFlag](TestCaptureVerboseFlag.md) (4 shared connections)
- [TestNoRedactFlag](TestNoRedactFlag.md) (4 shared connections)
- [ansible_aom/cli.py](ansible_aom-cli.py.md) (3 shared connections)
- [TestCaptureSetupFlag](TestCaptureSetupFlag.md) (3 shared connections)
- [TestHideDeprecationsFlag](TestHideDeprecationsFlag.md) (3 shared connections)
- [TestHideWarningsFlag](TestHideWarningsFlag.md) (3 shared connections)
- [TestNoFailedHintFlag](TestNoFailedHintFlag.md) (3 shared connections)
- [_HideStateAction](_HideStateAction.md) (2 shared connections)

## Source Files

- `src/ansible_aom/cli.py`
- `tests/unit/test_cli.py`

## Audit Trail

- EXTRACTED: 47 (34%)
- INFERRED: 91 (66%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*