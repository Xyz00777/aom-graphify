# TestWarningPatternsEdgeCases

> 34 nodes · cohesion 0.06

## Key Concepts

- **TestWarningPatternsEdgeCases** (14 connections) — `tests/unit/test_warnings.py`
- **TestWarningClassification** (13 connections) — `tests/unit/test_warnings.py`
- **TestWarningEntrySourceField** (11 connections) — `tests/unit/test_warnings.py`
- **.test_warning_with_deprecation_in_message_body()** (4 connections) — `tests/unit/test_warnings.py`
- **.test_source_field_empty_string_default()** (4 connections) — `tests/unit/test_warnings.py`
- **.test_deprecated_feature_classification()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_deprecation_warning_classification()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_regular_warning_classification()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_whitespace_before_bracket()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_source_field_can_be_set()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_source_field_controller_for_pty_warnings()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_empty_line_not_warning()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_json_line_not_treated_as_warning()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_mixed_warning_types()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_multiple_deprecation_warnings()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_non_warning_plaintext_added_to_plaintext_lines()** (3 connections) — `tests/unit/test_warnings.py`
- **.test_warning_in_pre_run_prompts_phase_not_captured()** (3 connections) — `tests/unit/test_warnings.py`
- **TC-502: WarningEntry source defaults to empty string if not provided.** (2 connections) — `tests/unit/test_warnings.py`
- **JSONL lines are not treated as warnings even if they contain warning text.** (2 connections) — `tests/unit/test_warnings.py`
- **TC-502: WarningEntry source field for PTY stream.** (1 connections) — `tests/unit/test_warnings.py`
- **TC-502: WarningEntry from PtyStreamParser has source='controller'.** (1 connections) — `tests/unit/test_warnings.py`
- **TC-502: WarningEntry source can be explicitly set.** (1 connections) — `tests/unit/test_warnings.py`
- **Edge cases for warning pattern matching.** (1 connections) — `tests/unit/test_warnings.py`
- **Multiple [DEPRECATION WARNING]: lines are all classified correctly.** (1 connections) — `tests/unit/test_warnings.py`
- **Mixed WARNING and DEPRECATION lines classified correctly.** (1 connections) — `tests/unit/test_warnings.py`
- *... and 9 more nodes in this community*

## Relationships

- [PtyStreamParser](PtyStreamParser.md) (15 shared connections)
- [WarningEntry](WarningEntry.md) (5 shared connections)
- [WarningsConfig](WarningsConfig.md) (3 shared connections)
- [AppConfig](AppConfig.md) (3 shared connections)
- [WarningType](WarningType.md) (3 shared connections)
- [Status](Status.md) (3 shared connections)
- [models.py](models.py.md) (3 shared connections)

## Source Files

- `tests/unit/test_warnings.py`

## Audit Trail

- EXTRACTED: 83 (82%)
- INFERRED: 18 (18%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*