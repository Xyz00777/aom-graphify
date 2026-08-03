# _FakeSink

> 46 nodes · cohesion 0.07

## Key Concepts

- **_FakeSink** (21 connections) — `tests/unit/test_runner_stall_flush.py`
- **_FakeChild** (20 connections) — `tests/unit/test_runner_stall_flush.py`
- **test_runner_stall_flush.py** (11 connections) — `tests/unit/test_runner_stall_flush.py`
- **TestStallFlushDoesNotBlock** (6 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_renderer_crash_sends_empty_line_to_avoid_hang()** (5 connections) — `tests/unit/test_runner_stall_flush.py`
- **TestMultilinePauseBlock** (5 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_no_block_and_bare_colon_prior_does_not_fire()** (5 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_prior_non_prompt_does_not_fire()** (5 connections) — `tests/unit/test_runner_stall_flush.py`
- **TestSentinelPreventsRefiring** (5 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_negative_stall_count_with_prior_prompt_still_skips()** (5 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_prompt_path_emits_visible_breadcrumb()** (5 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_quiet_child_just_ticks()** (5 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_hint_only_fires_once()** (5 connections) — `tests/unit/test_runner_stall_flush.py`
- **TestHighConfidencePromptPath** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_known_prompt_drains_buffer_and_calls_handler()** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_reconstructed_block_fires_prompt()** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_sentinel_blocks_reconstructed_block_refiring()** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- **TestPriorPlaintextPromptPath** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_prior_prompt_with_empty_buffer_fires()** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_negative_stall_count_skips_prompt_path()** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_at_threshold_flushes_buffer_as_log()** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_below_threshold_does_nothing_to_buffer()** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_flush_records_to_session_sink()** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- **TestStallHintBeforeFlush** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- **.test_hint_fires_at_hint_threshold()** (4 connections) — `tests/unit/test_runner_stall_flush.py`
- *... and 21 more nodes in this community*

## Relationships

- [run_playbook](run_playbook.md) (17 shared connections)
- [Renderer ETA Wiring](Renderer_ETA_Wiring.md) (1 shared connections)

## Source Files

- `tests/unit/test_runner_stall_flush.py`

## Audit Trail

- EXTRACTED: 172 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*