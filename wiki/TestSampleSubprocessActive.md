# TestSampleSubprocessActive

> 13 nodes · cohesion 0.18

## Key Concepts

- **TestSampleSubprocessActive** (7 connections) — `tests/unit/test_runner_heartbeat.py`
- **_get_psutil()** (6 connections) — `src/ansible_aom/ansible/runner.py`
- **_sample_subprocess_active()** (6 connections) — `src/ansible_aom/ansible/runner.py`
- **_probe_psutil()** (4 connections) — `src/ansible_aom/ansible/runner.py`
- **set_psutil_disabled()** (3 connections) — `src/ansible_aom/core/diagnostics.py`
- **Any** (2 connections)
- **.test_returns_bool_for_own_pid()** (2 connections) — `tests/unit/test_runner_heartbeat.py`
- **.test_returns_false_for_nonexistent_pid()** (2 connections) — `tests/unit/test_runner_heartbeat.py`
- **Subprocess-probe ``import psutil``; return ``(module, None)`` on     success or** (1 connections) — `src/ansible_aom/ansible/runner.py`
- **Return the cached psutil module, or None if probing failed.      Lazy: the first** (1 connections) — `src/ansible_aom/ansible/runner.py`
- **Return True if pid or any descendant used CPU since the last call.      Uses ``p** (1 connections) — `src/ansible_aom/ansible/runner.py`
- **Flag that psutil-based CPU sampling was disabled with ``reason``.      Set by :f** (1 connections) — `src/ansible_aom/core/diagnostics.py`
- **The CPU sampler degrades gracefully and never raises.** (1 connections) — `tests/unit/test_runner_heartbeat.py`

## Relationships

- [run_playbook](run_playbook.md) (4 shared connections)
- [diagnostics.py](diagnostics.py.md) (1 shared connections)
- [StreamPhase](StreamPhase.md) (1 shared connections)
- [PtyStreamParser](PtyStreamParser.md) (1 shared connections)
- [RunState](RunState.md) (1 shared connections)
- [_FakeSink](_FakeSink.md) (1 shared connections)

## Source Files

- `src/ansible_aom/ansible/runner.py`
- `src/ansible_aom/core/diagnostics.py`
- `tests/unit/test_runner_heartbeat.py`

## Audit Trail

- EXTRACTED: 34 (92%)
- INFERRED: 3 (8%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*