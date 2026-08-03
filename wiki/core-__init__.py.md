# core/__init__.py

> 25 nodes · cohesion 0.08

## Key Concepts

- **core/__init__.py** (18 connections) — `src/ansible_aom/core/__init__.py`
- **test_diagnostics.py** (15 connections) — `tests/unit/test_diagnostics.py`
- **test_render_storm.py** (9 connections) — `tests/unit/test_render_storm.py`
- **Core module for AOM - backend-agnostic shared logic.  This module contains no UI** (1 connections) — `src/ansible_aom/core/__init__.py`
- **Unit tests for core.diagnostics — opt-in observability layer.  Spec: docs/superp** (1 connections) — `tests/unit/test_diagnostics.py`
- **_reset_diagnostics()** (1 connections) — `tests/unit/test_diagnostics.py`
- **test_aom_debug_is_the_only_trace_knob()** (1 connections) — `tests/unit/test_diagnostics.py`
- **test_build_diagnostics_record_json_roundtrip()** (1 connections) — `tests/unit/test_diagnostics.py`
- **test_debug_falsy_values_disable()** (1 connections) — `tests/unit/test_diagnostics.py`
- **test_debug_sets_logger_level()** (1 connections) — `tests/unit/test_diagnostics.py`
- **test_install_enables_faulthandler()** (1 connections) — `tests/unit/test_diagnostics.py`
- **test_install_from_env_with_empty_env_is_noop()** (1 connections) — `tests/unit/test_diagnostics.py`
- **test_install_is_idempotent()** (1 connections) — `tests/unit/test_diagnostics.py`
- **test_lifecycle_mark_always_records()** (1 connections) — `tests/unit/test_diagnostics.py`
- **test_watchdog_calls_dump_traceback_later()** (1 connections) — `tests/unit/test_diagnostics.py`
- **test_watchdog_with_invalid_value_is_none()** (1 connections) — `tests/unit/test_diagnostics.py`
- **test_watchdog_zero_is_treated_as_disabled()** (1 connections) — `tests/unit/test_diagnostics.py`
- **Phase 10: render-storm self-diagnostic.  When the renderer redraws far more ofte** (1 connections) — `tests/unit/test_render_storm.py`
- **_reset()** (1 connections) — `tests/unit/test_render_storm.py`
- **test_build_diagnostics_record_includes_warnings_field()** (1 connections) — `tests/unit/test_render_storm.py`
- **test_build_diagnostics_record_warnings_empty_when_healthy()** (1 connections) — `tests/unit/test_render_storm.py`
- **test_no_warning_for_low_event_count()** (1 connections) — `tests/unit/test_render_storm.py`
- **test_no_warning_for_reasonable_ratio()** (1 connections) — `tests/unit/test_render_storm.py`
- **test_warning_for_high_ratio()** (1 connections) — `tests/unit/test_render_storm.py`
- **test_warning_when_zero_events_but_renders()** (1 connections) — `tests/unit/test_render_storm.py`

## Relationships

- [json.py](json.py.md) (2 shared connections)
- [runner.py](runner.py.md) (1 shared connections)
- [renderer.py](renderer.py.md) (1 shared connections)
- [JsonlEvent](JsonlEvent.md) (1 shared connections)
- [test_renderer_stats.py](test_renderer_stats.py.md) (1 shared connections)
- [diagnostics.py](diagnostics.py.md) (1 shared connections)
- [Secret Redaction Layers](Secret_Redaction_Layers.md) (1 shared connections)
- [Width 60-79 Truncation](Width_60-79_Truncation.md) (1 shared connections)
- [Color ASCII Fallback](Color_ASCII_Fallback.md) (1 shared connections)
- [Core Domain Architecture](Core_Domain_Architecture.md) (1 shared connections)
- [Cancellation Timer](Cancellation_Timer.md) (1 shared connections)
- [IO](IO.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/__init__.py`
- `tests/unit/test_diagnostics.py`
- `tests/unit/test_render_storm.py`

## Audit Trail

- EXTRACTED: 64 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*