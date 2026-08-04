# _parse_timestamp

> 16 nodes · cohesion 0.12

## Key Concepts

- **_parse_timestamp()** (12 connections) — `src/ansible_aom/core/run_state.py`
- **.handle_event()** (4 connections) — `src/ansible_aom/core/run_state.py`
- **.test_local_timezone_preserves_instant()** (3 connections) — `tests/unit/test_event_processing.py`
- **.test_utc_timestamp_converted_to_local_timezone()** (3 connections) — `tests/unit/test_event_processing.py`
- **.test_utc_timestamp_parsed_with_timezone()** (3 connections) — `tests/unit/test_event_processing.py`
- **.test_utc_timestamp_without_z()** (3 connections) — `tests/unit/test_event_processing.py`
- **.test_utc_z_suffix_parsed_correctly()** (3 connections) — `tests/unit/test_event_processing.py`
- **.test_various_utc_timestamps()** (3 connections) — `tests/unit/test_event_processing.py`
- **Process a JSONL event and update state.** (1 connections) — `src/ansible_aom/core/run_state.py`
- **Parse timestamp from event, defaulting to current time.** (1 connections) — `src/ansible_aom/core/run_state.py`
- **TC-085: _parse_timestamp returns timezone-aware datetime from UTC string.** (1 connections) — `tests/unit/test_event_processing.py`
- **TC-085: UTC timestamp can be converted to local timezone via astimezone().** (1 connections) — `tests/unit/test_event_processing.py`
- **TC-085: 'Z' suffix in timestamps is handled as UTC.** (1 connections) — `tests/unit/test_event_processing.py`
- **TC-085: Timestamps without Z still parse as UTC if +00:00.** (1 connections) — `tests/unit/test_event_processing.py`
- **TC-085: Various UTC timestamp strings parse correctly.** (1 connections) — `tests/unit/test_event_processing.py`
- **TC-085: fromisoformat().astimezone() preserves UTC instant.** (1 connections) — `tests/unit/test_event_processing.py`

## Relationships

- [HostRunState](HostRunState.md) (6 shared connections)
- [JsonlEvent](JsonlEvent.md) (2 shared connections)
- [RunState](RunState.md) (2 shared connections)
- [run_state.py](run_state.py.md) (1 shared connections)
- [load_session](load_session.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/run_state.py`
- `tests/unit/test_event_processing.py`

## Audit Trail

- EXTRACTED: 42 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*