# _FakeSpawn

> 45 nodes · cohesion 0.06

## Key Concepts

- **_FakeSpawn** (13 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- **_patch_runner_for_fake_subprocess()** (9 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- **_FakeSpawn** (9 connections) — `tests/unit/test_runner_searchwindowsize.py`
- **_patch_runner_with_fake_spawn()** (7 connections) — `tests/unit/test_runner_searchwindowsize.py`
- **.test_sigint_after_failed_child_returns_child_exit_code()** (6 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- **.test_sigint_during_handle_completion_returns_child_exit_code()** (6 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- **.test_sigint_mid_run_returns_130()** (6 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- **test_runner_ctrl_c_race.py** (5 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- **test_runner_searchwindowsize.py** (5 connections) — `tests/unit/test_runner_searchwindowsize.py`
- **test_runner_searchwindow_covers_longest_pattern()** (5 connections) — `tests/unit/test_runner_searchwindowsize.py`
- **test_runner_sets_explicit_searchwindowsize()** (5 connections) — `tests/unit/test_runner_searchwindowsize.py`
- **.playbook()** (4 connections) — `src/ansible_aom/drivers/live.py`
- **MonkeyPatch** (4 connections)
- **TestCtrlCAfterChildExitedCleanly** (4 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- **TestCtrlCDuringActiveRun** (3 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- **Any** (3 connections)
- **MonkeyPatch** (3 connections)
- **.expect()** (2 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- **Any** (2 connections)
- **.expect()** (2 connections) — `tests/unit/test_runner_searchwindowsize.py`
- **.__init__()** (2 connections) — `tests/unit/test_runner_searchwindowsize.py`
- **.close()** (1 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- **.__init__()** (1 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- **.isalive()** (1 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- **.read_nonblocking()** (1 connections) — `tests/unit/test_runner_ctrl_c_race.py`
- *... and 20 more nodes in this community*

## Relationships

- [run_playbook](run_playbook.md) (5 shared connections)
- [ansible_aom/cli.py](ansible_aom-cli.py.md) (1 shared connections)
- [FakeRenderer](FakeRenderer.md) (1 shared connections)

## Source Files

- `src/ansible_aom/drivers/live.py`
- `tests/unit/test_runner_ctrl_c_race.py`
- `tests/unit/test_runner_searchwindowsize.py`

## Audit Trail

- EXTRACTED: 119 (92%)
- INFERRED: 10 (8%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*