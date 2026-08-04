# rerun/cli.py

> 14 nodes · cohesion 0.20

## Key Concepts

- **rerun/cli.py** (22 connections) — `src/ansible_aom/rerun/cli.py`
- **main()** (12 connections) — `src/ansible_aom/rerun/cli.py`
- **_require_ansible_args()** (8 connections) — `src/ansible_aom/rerun/cli.py`
- **TestRequireAnsibleArgs** (6 connections) — `tests/unit/test_rerun_cli.py`
- **.test_none_value_treated_as_missing()** (3 connections) — `tests/unit/test_rerun_cli.py`
- **.test_session_with_empty_args_returns_empty_list()** (3 connections) — `tests/unit/test_rerun_cli.py`
- **.test_missing_field_error_message_explains_schema()** (2 connections) — `tests/unit/test_rerun_cli.py`
- **.test_missing_field_raises_with_clear_error()** (2 connections) — `tests/unit/test_rerun_cli.py`
- **.test_session_with_args_returns_them()** (2 connections) — `tests/unit/test_rerun_cli.py`
- **CLI entry point for ``aom rerun``.  Reads a recorded session, derives a host lis** (1 connections) — `src/ansible_aom/rerun/cli.py`
- **Return the recorded ``ansible_args`` or refuse with a clear error.      Sessions** (1 connections) — `src/ansible_aom/rerun/cli.py`
- **CLI entry point for ``aom rerun``.      Args:         argv: Argument list. If No** (1 connections) — `src/ansible_aom/rerun/cli.py`
- **An explicit [] is valid — the user originally ran `aom site.yml`.** (1 connections) — `tests/unit/test_rerun_cli.py`
- **A null value (rare, but possible if hand-edited) is also missing.** (1 connections) — `tests/unit/test_rerun_cli.py`

## Relationships

- [test_rerun_cli.py](test_rerun_cli.py.md) (4 shared connections)
- [_build_rerun_command](_build_rerun_command.md) (3 shared connections)
- [_session](_session.md) (3 shared connections)
- [runner.py](runner.py.md) (2 shared connections)
- [create_renderer](create_renderer.md) (2 shared connections)
- [Exit Code Constants](Exit_Code_Constants.md) (2 shared connections)
- [Shell Completion Helpers](Shell_Completion_Helpers.md) (2 shared connections)
- [Path](Path.md) (2 shared connections)
- [load_session](load_session.md) (2 shared connections)
- [ansible_aom/cli.py](ansible_aom-cli.py.md) (2 shared connections)
- [run_playbook](run_playbook.md) (1 shared connections)
- [session_id_completer](session_id_completer.md) (1 shared connections)

## Source Files

- `src/ansible_aom/rerun/cli.py`
- `tests/unit/test_rerun_cli.py`

## Audit Trail

- EXTRACTED: 65 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*