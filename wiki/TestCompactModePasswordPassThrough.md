# TestCompactModePasswordPassThrough

> 12 nodes · cohesion 0.17

## Key Concepts

- **TestCompactModePasswordPassThrough** (10 connections) — `tests/unit/test_pty_stream.py`
- **.test_clear_password_prompt_allows_next_detection()** (3 connections) — `tests/unit/test_pty_stream.py`
- **.test_password_prompt_exact_text_stored()** (3 connections) — `tests/unit/test_pty_stream.py`
- **.test_password_prompt_multiple_types()** (3 connections) — `tests/unit/test_pty_stream.py`
- **.test_password_prompt_not_json_event()** (3 connections) — `tests/unit/test_pty_stream.py`
- **.test_password_prompt_sets_pending_state()** (3 connections) — `tests/unit/test_pty_stream.py`
- **TC-144, TC-145: Compact mode password pass-through.** (1 connections) — `tests/unit/test_pty_stream.py`
- **TC-144: Password prompt sets pending state for UI handling.** (1 connections) — `tests/unit/test_pty_stream.py`
- **TC-144: All password types set correct pending state.** (1 connections) — `tests/unit/test_pty_stream.py`
- **Exact prompt text stored for UI display.** (1 connections) — `tests/unit/test_pty_stream.py`
- **Password prompts don't generate JSON events.** (1 connections) — `tests/unit/test_pty_stream.py`
- **Clearing prompt allows detecting next password prompt.** (1 connections) — `tests/unit/test_pty_stream.py`

## Relationships

- [PtyStreamParser](PtyStreamParser.md) (6 shared connections)
- [WarningType](WarningType.md) (1 shared connections)
- [Status](Status.md) (1 shared connections)
- [test_pty_stream.py](test_pty_stream.py.md) (1 shared connections)

## Source Files

- `tests/unit/test_pty_stream.py`

## Audit Trail

- EXTRACTED: 28 (90%)
- INFERRED: 3 (10%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*