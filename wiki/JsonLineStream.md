# JsonLineStream

> 61 nodes · cohesion 0.05

## Key Concepts

- **JsonLineStream** (78 connections) — `src/ansible_aom/core/parser.py`
- **TestJsonLineStreamBasics** (31 connections) — `tests/unit/test_parser.py`
- **TestJsonLineStreamCarryBuffer** (20 connections) — `tests/unit/test_parser.py`
- **TestPreParsePhase** (17 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_event_play_start()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_event_playbook_start()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_event_runner_failed()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_event_runner_ok()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_event_runner_ok_changed()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_event_runner_skipped()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_event_runner_start()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_event_runner_unreachable()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_event_stats()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_event_task_start()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_json_without_event_field()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_parses_valid_json()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_returns_empty_for_empty_line()** (3 connections) — `tests/unit/test_parser.py`
- **.test_feed_line_returns_empty_for_non_json()** (3 connections) — `tests/unit/test_parser.py`
- **.test_invalid_json_continues_processing()** (3 connections) — `tests/unit/test_parser.py`
- **.test_non_json_handler_called()** (3 connections) — `tests/unit/test_parser.py`
- **.test_timestamp_parsing_iso8601_utc()** (3 connections) — `tests/unit/test_parser.py`
- **.test_carry_buffer_overflow_drops_without_raising()** (3 connections) — `tests/unit/test_parser.py`
- **.test_garbage_carry_does_not_swallow_next_valid_event()** (3 connections) — `tests/unit/test_parser.py`
- **.test_many_small_chunks_join()** (3 connections) — `tests/unit/test_parser.py`
- **.test_two_chunk_join_yields_full_event()** (3 connections) — `tests/unit/test_parser.py`
- *... and 36 more nodes in this community*

## Relationships

- [Status](Status.md) (27 shared connections)
- [HostRunState](HostRunState.md) (9 shared connections)
- [TaskDefinition](TaskDefinition.md) (8 shared connections)
- [test_r6_encoding_roundtrip.py](test_r6_encoding_roundtrip.py.md) (6 shared connections)
- [TestJsonLineStreamSurvivesMojibake](TestJsonLineStreamSurvivesMojibake.md) (6 shared connections)
- [StreamPhase](StreamPhase.md) (5 shared connections)
- [PlayDefinition](PlayDefinition.md) (4 shared connections)
- [PtyStreamParser](PtyStreamParser.md) (4 shared connections)
- [test_parser_orjson_swap.py](test_parser_orjson_swap.py.md) (3 shared connections)
- [Warning Pattern Detection](Warning_Pattern_Detection.md) (2 shared connections)
- [Conftest Fixture Validation](Conftest_Fixture_Validation.md) (2 shared connections)
- [Status Bar Formatting](Status_Bar_Formatting.md) (2 shared connections)

## Source Files

- `src/ansible_aom/core/parser.py`
- `tests/unit/test_parser.py`

## Audit Trail

- EXTRACTED: 183 (72%)
- INFERRED: 72 (28%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*