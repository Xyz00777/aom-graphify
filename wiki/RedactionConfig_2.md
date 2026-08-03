# RedactionConfig

> 68 nodes · cohesion 0.04

## Key Concepts

- **RedactionConfig** (24 connections)
- **sanitize_string()** (17 connections) — `src/ansible_aom/core/redaction.py`
- **redaction.py** (14 connections) — `src/ansible_aom/core/redaction.py`
- **should_redact()** (14 connections) — `src/ansible_aom/core/redaction.py`
- **test_redaction_layer4.py** (12 connections) — `tests/unit/test_redaction_layer4.py`
- **TestLayer2UserConfig** (8 connections) — `tests/unit/test_redaction_layer4.py`
- **TestRecurseByKeyNotValue** (8 connections) — `tests/unit/test_redaction_layer4.py`
- **TestLayer1ExactMatchKeys** (7 connections) — `tests/unit/test_redaction_layer4.py`
- **TestWhitelistStillWorks** (7 connections) — `tests/unit/test_redaction_layer4.py`
- **TestSanitizeStringLayer3Unchanged** (6 connections) — `tests/unit/test_redaction_layer4.py`
- **TestInvocationsLayer4StaysConsistent** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_exact_match_does_not_catch_suffix_or_prefix()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_exact_match_is_case_insensitive_on_lookup()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_qc002_exact_match_keys_redacted()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_custom_fields_extends_exact_match()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_custom_key_patterns_invalid_regex_skipped()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_custom_key_patterns_matches_suffix()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_custom_key_patterns_matches_token_suffix()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_layer2_does_not_rediscover_exact_match_keys()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_dict_recursion_redacts_nested_exact_match_keys()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_list_recursion_redacts_dict_items()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_recursion_depth_bounded()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_secret_in_value_under_safe_key_not_redacted()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_value_substring_password_not_redacted()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_config_whitelist_extends_defaults()** (4 connections) — `tests/unit/test_redaction_layer4.py`
- *... and 43 more nodes in this community*

## Relationships

- [RedactionConfig](RedactionConfig.md) (17 shared connections)
- [redact_event](redact_event.md) (16 shared connections)
- [redact_dict](redact_dict.md) (6 shared connections)
- [TestURLCredentialSanitization](TestURLCredentialSanitization.md) (3 shared connections)
- [View Mode Selection](View_Mode_Selection.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/redaction.py`
- `tests/unit/test_properties_redaction.py`
- `tests/unit/test_redaction_layer4.py`

## Audit Trail

- EXTRACTED: 237 (98%)
- INFERRED: 6 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*