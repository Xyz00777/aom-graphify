# RedactionConfig

> 80 nodes · cohesion 0.04

## Key Concepts

- **RedactionConfig** (28 connections)
- **_ansible_event_with_res()** (26 connections) — `tests/integration/test_redaction.py`
- **integration/test_redaction.py** (16 connections) — `tests/integration/test_redaction.py`
- **TestLayer3StringSanitizationOnEvents** (9 connections) — `tests/integration/test_redaction.py`
- **TestLayer2PasswordFieldsOnEvents** (8 connections) — `tests/integration/test_redaction.py`
- **TestCustomConfigOnRealisticEvents** (6 connections) — `tests/integration/test_redaction.py`
- **TestLayer1NoLogOnFullEvent** (6 connections) — `tests/integration/test_redaction.py`
- **TestLayer4InvocationModuleArgs** (6 connections) — `tests/integration/test_redaction.py`
- **.test_custom_fields_redacted_on_event()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_custom_patterns_sanitize_strings_on_event()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_custom_whitelist_extends_default()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_entire_res_replaced_with_censored_marker()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_envelope_preserved_after_no_log_censorship()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_no_log_false_passes_through_to_other_layers()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_per_item_no_log_censors_only_marked_items()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_generic_secret_fields_redacted()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_known_ansible_password_fields_redacted()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_nested_passwords_in_realistic_dict_redacted()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_password_match_regex_field_redacted()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_whitelisted_pass_fields_not_redacted()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_all_sanitized_fields_together()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_cmd_field_url_credentials_stripped()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_cmd_list_each_entry_sanitized()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_msg_field_cli_credentials_stripped()** (5 connections) — `tests/integration/test_redaction.py`
- **.test_stderr_field_cli_credentials_stripped()** (5 connections) — `tests/integration/test_redaction.py`
- *... and 55 more nodes in this community*

## Relationships

- [redact_event](redact_event.md) (25 shared connections)
- [RedactionConfig](RedactionConfig.md) (11 shared connections)

## Source Files

- `tests/integration/test_redaction.py`

## Audit Trail

- EXTRACTED: 285 (97%)
- INFERRED: 9 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*