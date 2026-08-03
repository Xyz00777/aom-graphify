# TestLogging

> 29 nodes · cohesion 0.07

## Key Concepts

- **TestLogging** (9 connections) — `tests/integration/test_error_handling.py`
- **TestStderrCapture** (6 connections) — `tests/integration/test_error_handling.py`
- **Path** (5 connections)
- **TestStderrHandling** (5 connections) — `tests/integration/test_error_handling.py`
- **.test_log_path_xdg_compliant()** (3 connections) — `tests/integration/test_error_handling.py`
- **.test_log_rotation_configuration()** (3 connections) — `tests/integration/test_error_handling.py`
- **.test_log_silent_during_normal_operation()** (3 connections) — `tests/integration/test_error_handling.py`
- **.test_stderr_captured_and_stored()** (3 connections) — `tests/integration/test_error_handling.py`
- **.test_stderr_file_creation()** (3 connections) — `tests/integration/test_error_handling.py`
- **.test_log_levels_present()** (2 connections) — `tests/integration/test_error_handling.py`
- **.test_verbose_flag_enables_debug()** (2 connections) — `tests/integration/test_error_handling.py`
- **.test_verbose_flag_info_level_without_flag()** (2 connections) — `tests/integration/test_error_handling.py`
- **.test_stderr_displayed_in_view()** (2 connections) — `tests/integration/test_error_handling.py`
- **.test_stderr_json_parsing_attempt()** (2 connections) — `tests/integration/test_error_handling.py`
- **.test_stderr_mixed_with_jsonl()** (2 connections) — `tests/integration/test_error_handling.py`
- **TC-455 to TC-464: Logging tests.** (1 connections) — `tests/integration/test_error_handling.py`
- **TC-455: Log file follows XDG state directory convention.** (1 connections) — `tests/integration/test_error_handling.py`
- **TC-456: Log file written but console silent during normal operation.** (1 connections) — `tests/integration/test_error_handling.py`
- **TC-457: RotatingFileHandler with 10MB/file, 5 backups.** (1 connections) — `tests/integration/test_error_handling.py`
- **TC-459 to TC-462: Log levels for different event types.** (1 connections) — `tests/integration/test_error_handling.py`
- **TC-463: --verbose flag enables DEBUG logging to file.** (1 connections) — `tests/integration/test_error_handling.py`
- **TC-463: Without --verbose, INFO level used.** (1 connections) — `tests/integration/test_error_handling.py`
- **TC-477 to TC-479: Stderr capture and handling.** (1 connections) — `tests/integration/test_error_handling.py`
- **TC-477: Stderr output stored in session directory.** (1 connections) — `tests/integration/test_error_handling.py`
- **TC-478: Stderr lines displayed in log panel.** (1 connections) — `tests/integration/test_error_handling.py`
- *... and 4 more nodes in this community*

## Relationships

- [PtyStreamParser](PtyStreamParser.md) (3 shared connections)
- [test_error_handling.py](test_error_handling.py.md) (3 shared connections)

## Source Files

- `tests/integration/test_error_handling.py`

## Audit Trail

- EXTRACTED: 63 (95%)
- INFERRED: 3 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*