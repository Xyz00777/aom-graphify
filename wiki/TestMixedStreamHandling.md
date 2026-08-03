# TestMixedStreamHandling

> 12 nodes · cohesion 0.17

## Key Concepts

- **TestMixedStreamHandling** (10 connections) — `tests/unit/test_pty_stream.py`
- **.test_invalid_json_returns_empty()** (3 connections) — `tests/unit/test_pty_stream.py`
- **.test_jsonl_and_plaintext_interleaved()** (3 connections) — `tests/unit/test_pty_stream.py`
- **.test_jsonl_returns_events()** (3 connections) — `tests/unit/test_pty_stream.py`
- **.test_plaintext_before_jsonl_start()** (3 connections) — `tests/unit/test_pty_stream.py`
- **.test_plaintext_returns_stderr_line()** (3 connections) — `tests/unit/test_pty_stream.py`
- **Section 5.6: JSONL events interleaved with plaintext.** (1 connections) — `tests/unit/test_pty_stream.py`
- **JSONL events and plaintext interleaved correctly.** (1 connections) — `tests/unit/test_pty_stream.py`
- **Plaintext before v2_playbook_on_start is captured.** (1 connections) — `tests/unit/test_pty_stream.py`
- **feed_line returns parsed events for JSONL.** (1 connections) — `tests/unit/test_pty_stream.py`
- **feed_line returns aom_stderr_line for plaintext.** (1 connections) — `tests/unit/test_pty_stream.py`
- **feed_line returns empty for invalid JSON.** (1 connections) — `tests/unit/test_pty_stream.py`

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