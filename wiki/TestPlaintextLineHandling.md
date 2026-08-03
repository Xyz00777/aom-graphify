# TestPlaintextLineHandling

> 12 nodes · cohesion 0.17

## Key Concepts

- **TestPlaintextLineHandling** (10 connections) — `tests/unit/test_pty_stream.py`
- **.test_plaintext_lines_in_execution_phase()** (3 connections) — `tests/unit/test_pty_stream.py`
- **.test_plaintext_lines_not_warning()** (3 connections) — `tests/unit/test_pty_stream.py`
- **.test_plaintext_lines_order_preserved()** (3 connections) — `tests/unit/test_pty_stream.py`
- **.test_plaintext_lines_stored()** (3 connections) — `tests/unit/test_pty_stream.py`
- **.test_plaintext_vs_warning_classification()** (3 connections) — `tests/unit/test_pty_stream.py`
- **TC-142: _handle_plaintext classification.** (1 connections) — `tests/unit/test_pty_stream.py`
- **TC-142: Non-JSON, non-special lines go to plaintext_lines.** (1 connections) — `tests/unit/test_pty_stream.py`
- **Plaintext lines that aren't warnings are stored.** (1 connections) — `tests/unit/test_pty_stream.py`
- **Plaintext during EXECUTION phase collected.** (1 connections) — `tests/unit/test_pty_stream.py`
- **Lines classified correctly between warning vs plaintext.** (1 connections) — `tests/unit/test_pty_stream.py`
- **Plaintext lines maintain order.** (1 connections) — `tests/unit/test_pty_stream.py`

## Relationships

- [PtyStreamParser](PtyStreamParser.md) (6 shared connections)
- [StreamPhase](StreamPhase.md) (2 shared connections)
- [Status](Status.md) (1 shared connections)

## Source Files

- `tests/unit/test_pty_stream.py`

## Audit Trail

- EXTRACTED: 28 (90%)
- INFERRED: 3 (10%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*