# create_parser

> 42 nodes · cohesion 0.05

## Key Concepts

- **create_parser()** (81 connections) — `src/ansible_aom/cli.py`
- **TestCaptureSetupFlag** (12 connections) — `tests/unit/test_cli.py`
- **TestHideWarningsFlag** (12 connections) — `tests/unit/test_cli.py`
- **.test_inventory_flag_passed_through()** (3 connections) — `tests/unit/test_cli.py`
- **.test_limit_flag_passed_through()** (3 connections) — `tests/unit/test_cli.py`
- **.test_unknown_args_passed_through()** (3 connections) — `tests/unit/test_cli.py`
- **.test_playbook_argument_accepted()** (3 connections) — `tests/unit/test_cli.py`
- **.test_playbook_positional_argument_required()** (3 connections) — `tests/unit/test_cli.py`
- **.test_create_parser_has_playbook_positional_arg()** (3 connections) — `tests/unit/test_cli.py`
- **.test_create_parser_returns_argparse_parser()** (3 connections) — `tests/unit/test_cli.py`
- **.test_help_displays_usage()** (3 connections) — `tests/unit/test_cli.py`
- **.test_help_shows_flags()** (3 connections) — `tests/unit/test_cli.py`
- **.test_all_flags_compose_with_each_other()** (3 connections) — `tests/unit/test_cli.py`
- **.test_yes_unchanged_from_task_5_1()** (3 connections) — `tests/unit/test_cli.py`
- **.test_short_v_does_not_set_aom_verbose()** (3 connections) — `tests/unit/test_cli.py`
- **.test_verbose_flag_defaults_false()** (3 connections) — `tests/unit/test_cli.py`
- **.test_verbose_flag_exists()** (3 connections) — `tests/unit/test_cli.py`
- **.test_create_parser_calls_argcomplete_autocomplete()** (2 connections) — `tests/unit/test_cli.py`
- **.test_capture_setup_defaults_false()** (2 connections) — `tests/unit/test_cli.py`
- **.test_capture_setup_does_not_leak_to_ansible_args()** (2 connections) — `tests/unit/test_cli.py`
- **.test_capture_setup_long_form()** (2 connections) — `tests/unit/test_cli.py`
- **.test_help_text_documents_install_completion()** (2 connections) — `tests/unit/test_cli.py`
- **.test_hide_warnings_defaults_false()** (2 connections) — `tests/unit/test_cli.py`
- **.test_hide_warnings_does_not_leak_to_ansible_args()** (2 connections) — `tests/unit/test_cli.py`
- **.test_hide_warnings_long_form()** (2 connections) — `tests/unit/test_cli.py`
- *... and 17 more nodes in this community*

## Relationships

- [HostRunState](HostRunState.md) (24 shared connections)
- [TestHideStateFlag](TestHideStateFlag.md) (19 shared connections)
- [TestYesFlag](TestYesFlag.md) (6 shared connections)
- [TestConfigPathFlag](TestConfigPathFlag.md) (5 shared connections)
- [TestFormatFlag](TestFormatFlag.md) (5 shared connections)
- [TestCaptureVerboseFlag](TestCaptureVerboseFlag.md) (4 shared connections)
- [TestNoRedactFlag](TestNoRedactFlag.md) (4 shared connections)
- [TestHideDeprecationsFlag](TestHideDeprecationsFlag.md) (3 shared connections)
- [TestNoFailedHintFlag](TestNoFailedHintFlag.md) (3 shared connections)
- [ansible_aom/cli.py](ansible_aom-cli.py.md) (2 shared connections)
- [_HideStateAction](_HideStateAction.md) (2 shared connections)
- [unit/test_no_record.py](unit-test_no_record.py.md) (2 shared connections)

## Source Files

- `src/ansible_aom/cli.py`
- `tests/unit/test_cli.py`

## Audit Trail

- EXTRACTED: 68 (38%)
- INFERRED: 112 (62%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*