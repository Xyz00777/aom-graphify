# rerun/cli.py

> 19 nodes · cohesion 0.15

## Key Concepts

- **rerun/cli.py** (22 connections) — `src/ansible_aom/rerun/cli.py`
- **main()** (12 connections) — `src/ansible_aom/rerun/cli.py`
- **_build_rerun_command()** (10 connections) — `src/ansible_aom/rerun/cli.py`
- **TestBuildRerunCommand** (7 connections) — `tests/unit/test_rerun_cli.py`
- **_strip_limit_args()** (3 connections) — `src/ansible_aom/rerun/cli.py`
- **.test_empty_host_set_raises()** (3 connections) — `tests/unit/test_rerun_cli.py`
- **.test_overrides_existing_limit_flag()** (3 connections) — `tests/unit/test_rerun_cli.py`
- **.test_overrides_limit_equals_form()** (3 connections) — `tests/unit/test_rerun_cli.py`
- **.test_overrides_short_l_flag()** (3 connections) — `tests/unit/test_rerun_cli.py`
- **.test_appends_limit_to_original_args()** (2 connections) — `tests/unit/test_rerun_cli.py`
- **.test_single_host_limit()** (2 connections) — `tests/unit/test_rerun_cli.py`
- **CLI entry point for ``aom rerun``.  Reads a recorded session, derives a host lis** (1 connections) — `src/ansible_aom/rerun/cli.py`
- **Drop any pre-existing ``--limit`` / ``-l`` from the args list.      Handles thre** (1 connections) — `src/ansible_aom/rerun/cli.py`
- **Construct the (playbook, ansible_args) pair to spawn for the rerun.      The ses** (1 connections) — `src/ansible_aom/rerun/cli.py`
- **CLI entry point for ``aom rerun``.      Args:         argv: Argument list. If No** (1 connections) — `src/ansible_aom/rerun/cli.py`
- **A pre-existing --limit in the original args is dropped in favour of ours.** (1 connections) — `tests/unit/test_rerun_cli.py`
- **``-l`` is the short form of ``--limit``; treat it the same.** (1 connections) — `tests/unit/test_rerun_cli.py`
- **``--limit=hosts`` (single arg) is also dropped.** (1 connections) — `tests/unit/test_rerun_cli.py`
- **No hosts → no rerun. Caller is expected to surface this earlier.** (1 connections) — `tests/unit/test_rerun_cli.py`

## Relationships

- [Path](Path.md) (4 shared connections)
- [load_session](load_session.md) (4 shared connections)
- [_session](_session.md) (4 shared connections)
- [diagnostics.py](diagnostics.py.md) (2 shared connections)
- [JsonRenderer](JsonRenderer.md) (2 shared connections)
- [_compose_host_set](_compose_host_set.md) (2 shared connections)
- [Exit Code Constants](Exit_Code_Constants.md) (2 shared connections)
- [Shell Completion Helpers](Shell_Completion_Helpers.md) (2 shared connections)
- [TUI Widgets Module](TUI_Widgets_Module.md) (2 shared connections)
- [ansible_aom/cli.py](ansible_aom-cli.py.md) (2 shared connections)
- [run_playbook](run_playbook.md) (1 shared connections)
- [session_id_completer](session_id_completer.md) (1 shared connections)

## Source Files

- `src/ansible_aom/rerun/cli.py`
- `tests/unit/test_rerun_cli.py`

## Audit Trail

- EXTRACTED: 78 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*