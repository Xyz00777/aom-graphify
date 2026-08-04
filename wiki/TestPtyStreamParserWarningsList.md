# TestPtyStreamParserWarningsList

> 16 nodes · cohesion 0.12

## Key Concepts

- **TestPtyStreamParserWarningsList** (13 connections) — `tests/unit/test_warnings.py`
- **TestWarningEntryTimestamp** (10 connections) — `tests/unit/test_warnings.py`
- **.test_warnings_list_contains_warning_entry_objects()** (4 connections) — `tests/unit/test_warnings.py`
- **.test_multiple_warnings_preserve_order()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_warnings_list_empty_initially()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_warnings_property_returns_list()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_timestamp_captured_on_creation()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_timestamp_is_datetime_or_none()** (3 connections) — `tests/unit/test_warnings.py`
- **TC-503: Timestamp is either datetime or None.** (2 connections) — `tests/unit/test_warnings.py`
- **TC-501: PtyStreamParser _warnings list type.** (1 connections) — `tests/unit/test_warnings.py`
- **TC-501: _warnings contains WarningEntry objects, not strings.** (1 connections) — `tests/unit/test_warnings.py`
- **TC-501: _warnings is empty list on initialization.** (1 connections) — `tests/unit/test_warnings.py`
- **TC-501: Multiple warnings are added in order received.** (1 connections) — `tests/unit/test_warnings.py`
- **TC-501: warnings property returns list.** (1 connections) — `tests/unit/test_warnings.py`
- **TC-503: WarningEntry timestamp from PTY stream.** (1 connections) — `tests/unit/test_warnings.py`
- **TC-503: WarningEntry captures timestamp when created.** (1 connections) — `tests/unit/test_warnings.py`

## Relationships

- [PtyStreamParser](PtyStreamParser.md) (8 shared connections)
- [WarningEntry](WarningEntry.md) (3 shared connections)
- [WarningsConfig](WarningsConfig.md) (2 shared connections)
- [AppConfig](AppConfig.md) (2 shared connections)
- [WarningType](WarningType.md) (2 shared connections)
- [Status](Status.md) (2 shared connections)
- [models.py](models.py.md) (2 shared connections)

## Source Files

- `tests/unit/test_warnings.py`

## Audit Trail

- EXTRACTED: 38 (75%)
- INFERRED: 13 (25%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*