# _FakeSink

> 12 nodes · cohesion 0.20

## Key Concepts

- **_FakeSink** (21 connections) — `tests/unit/test_runner_stall_flush.py`
- **TestSentinelPreventsRefiring** (5 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_negative_stall_count_with_prior_prompt_still_skips()** (5 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_prompt_path_emits_visible_breadcrumb()** (5 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_negative_stall_count_skips_prompt_path()** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- **.end()** (1 connections) — `tests/unit/test_runner_stall_flush.py`
- **.__init__()** (1 connections) — `tests/unit/test_runner_stall_flush.py`
- **.record_event()** (1 connections) — `tests/unit/test_runner_stall_flush.py`
- **.record_stderr()** (1 connections) — `tests/unit/test_runner_stall_flush.py`
- **Once a prompt has fired, subsequent timeouts in the same window     must not re-** (1 connections) — `tests/unit/test_runner_stall_flush.py`
- **Even if the prior line is a prompt, sentinel blocks re-firing.** (1 connections) — `tests/unit/test_runner_stall_flush.py`
- **A detected prompt prints a [aom] hint so the user sees what's happening.** (1 connections) — `tests/unit/test_runner_stall_flush.py`

## Relationships

- [_FakeChild](_FakeChild.md) (7 shared connections)
- [_handle_timeout_branch](_handle_timeout_branch.md) (6 shared connections)
- [test_runner_stall_flush.py](test_runner_stall_flush.py.md) (4 shared connections)
- [.test_renderer_crash_sends_empty_line_to_avoid_hang](test_renderer_crash_sends_empty_line_to_avoid_hang.md) (2 shared connections)
- [.test_hint_only_fires_once](test_hint_only_fires_once.md) (2 shared connections)

## Source Files

- `tests/unit/test_runner_stall_flush.py`

## Audit Trail

- EXTRACTED: 47 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*