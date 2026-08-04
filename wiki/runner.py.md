# runner.py

> 101 nodes · cohesion 0.03

## Key Concepts

- **runner.py** (59 connections) — `src/ansible_aom/ansible/runner.py`
- **diagnostics.py** (38 connections) — `src/ansible_aom/core/diagnostics.py`
- **_drive()** (25 connections) — `src/ansible_aom/ansible/runner.py`
- **_SessionSink** (22 connections) — `src/ansible_aom/ansible/runner.py`
- **_feed()** (19 connections) — `src/ansible_aom/ansible/runner.py`
- **_NullSink** (18 connections) — `src/ansible_aom/ansible/runner.py`
- **_flush_pending()** (11 connections) — `src/ansible_aom/ansible/runner.py`
- **install_from_env()** (9 connections) — `src/ansible_aom/core/diagnostics.py`
- **_fire_prompt()** (8 connections) — `src/ansible_aom/ansible/runner.py`
- **TestSampleSubprocessActive** (7 connections) — `tests/unit/test_runner_heartbeat.py`
- **_get_psutil()** (6 connections) — `src/ansible_aom/ansible/runner.py`
- **_sample_subprocess_active()** (6 connections) — `src/ansible_aom/ansible/runner.py`
- **._disable()** (6 connections) — `src/ansible_aom/ansible/runner.py`
- **.record_stderr()** (6 connections) — `src/ansible_aom/ansible/runner.py`
- **_callback_env()** (5 connections) — `src/ansible_aom/ansible/runner.py`
- **Path** (5 connections)
- **build_diagnostics_record()** (5 connections) — `src/ansible_aom/core/diagnostics.py`
- **RendererStats** (5 connections) — `src/ansible_aom/core/diagnostics.py`
- **test_runner_session_meta.py** (5 connections) — `tests/unit/test_runner_session_meta.py`
- **test_state_dir_isolation.py** (5 connections) — `tests/unit/test_state_dir_isolation.py`
- **_bundled_callback_dir()** (4 connections) — `src/ansible_aom/ansible/runner.py`
- **_bundled_connection_callback_dir()** (4 connections) — `src/ansible_aom/ansible/runner.py`
- **_default_session_dir()** (4 connections) — `src/ansible_aom/ansible/runner.py`
- **_probe_psutil()** (4 connections) — `src/ansible_aom/ansible/runner.py`
- **.record_event()** (4 connections) — `src/ansible_aom/ansible/runner.py`
- *... and 76 more nodes in this community*

## Relationships

- [run_playbook](run_playbook.md) (13 shared connections)
- [_handle_timeout_branch](_handle_timeout_branch.md) (13 shared connections)
- [StreamPhase](StreamPhase.md) (10 shared connections)
- [_drive](_drive.md) (10 shared connections)
- [PtyStreamParser](PtyStreamParser.md) (7 shared connections)
- [RunState](RunState.md) (7 shared connections)
- [RunDiagnostics](RunDiagnostics.md) (7 shared connections)
- [Renderer](Renderer.md) (6 shared connections)
- [JsonlEvent](JsonlEvent.md) (5 shared connections)
- [load_session](load_session.md) (5 shared connections)
- [Status](Status.md) (4 shared connections)
- [reconstruct_pause_prompt](reconstruct_pause_prompt.md) (4 shared connections)

## Source Files

- `src/ansible_aom/ansible/runner.py`
- `src/ansible_aom/core/diagnostics.py`
- `tests/unit/test_runner_heartbeat.py`
- `tests/unit/test_runner_session_meta.py`
- `tests/unit/test_state_dir_isolation.py`

## Audit Trail

- EXTRACTED: 389 (95%)
- INFERRED: 21 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*