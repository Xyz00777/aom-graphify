# _drive

> 49 nodes · cohesion 0.07

## Key Concepts

- **_drive()** (25 connections) — `src/ansible_aom/ansible/runner.py`
- **_drive()** (15 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **_SequenceChild** (14 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **_NullSink** (12 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **.test_watchdog_emits_warning_and_returns_when_no_eof()** (10 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **.test_watchdog_emits_warning_via_logger()** (10 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **.test_watchdog_path_calls_expect()** (10 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **_FakeChildIsaliveDead** (10 connections) — `tests/unit/test_runner_isalive_in_loop.py`
- **.test_clean_eof_after_stats_no_warning()** (9 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **test_runner_isalive_in_loop.py** (9 connections) — `tests/unit/test_runner_isalive_in_loop.py`
- **.test_pre_stats_timeout_does_not_trigger_watchdog()** (8 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **test_drive_exits_promptly_when_child_dead_but_pty_open()** (7 connections) — `tests/unit/test_runner_isalive_in_loop.py`
- **_start_line()** (6 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **TestWatchdogFiresAfterStats** (6 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **test_drive_isalive_check_handles_eof_exception_path()** (6 connections) — `tests/unit/test_runner_isalive_in_loop.py`
- **test_drive_isalive_check_on_timeout_branch()** (6 connections) — `tests/unit/test_runner_isalive_in_loop.py`
- **_stats_line()** (5 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **TestCleanEofAfterStats** (5 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **TestPreStatsSilenceUnchanged** (5 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **TestWatchdogUsesBoundedTimeout** (5 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **_build_parser_in_post_run_recap()** (5 connections) — `tests/unit/test_runner_isalive_in_loop.py`
- **.expect()** (2 connections) — `tests/unit/test_runner_isalive_in_loop.py`
- **Read the PTY until EOF, feeding lines to the parser/renderer.      ``diag`` is t** (1 connections) — `src/ansible_aom/ansible/runner.py`
- **.end()** (1 connections) — `tests/unit/test_runner_eof_watchdog.py`
- **.record_event()** (1 connections) — `tests/unit/test_runner_eof_watchdog.py`
- *... and 24 more nodes in this community*

## Relationships

- [RunState](RunState.md) (17 shared connections)
- [PtyStreamParser](PtyStreamParser.md) (14 shared connections)
- [json.py](json.py.md) (9 shared connections)
- [runner.py](runner.py.md) (8 shared connections)
- [test_invariants_session_roundtrip.py](test_invariants_session_roundtrip.py.md) (4 shared connections)
- [Stale Running Cleanup](Stale_Running_Cleanup.md) (2 shared connections)
- [run_playbook](run_playbook.md) (1 shared connections)
- [_handle_timeout_branch](_handle_timeout_branch.md) (1 shared connections)
- [_FakeSink](_FakeSink.md) (1 shared connections)
- [diagnostics.py](diagnostics.py.md) (1 shared connections)
- [reconstruct_pause_prompt](reconstruct_pause_prompt.md) (1 shared connections)
- [Renderer](Renderer.md) (1 shared connections)

## Source Files

- `src/ansible_aom/ansible/runner.py`
- `tests/integration/test_invariants_session_roundtrip.py`
- `tests/unit/test_runner_eof_watchdog.py`
- `tests/unit/test_runner_isalive_in_loop.py`

## Audit Trail

- EXTRACTED: 184 (85%)
- INFERRED: 33 (15%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*