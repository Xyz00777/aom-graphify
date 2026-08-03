# redact_event

> 44 nodes · cohesion 0.06

## Key Concepts

- **redact_event()** (69 connections) — `src/ansible_aom/core/redaction.py`
- **test_properties_redaction.py** (15 connections) — `tests/unit/test_properties_redaction.py`
- **TestLayer1AnsibleNoLog** (7 connections) — `tests/unit/test_redaction.py`
- **TestInvocationModuleArgs** (6 connections) — `tests/unit/test_redaction.py`
- **TestNoLogLayer0StillWorks** (5 connections) — `tests/unit/test_redaction_layer4.py`
- **SearchStrategy** (4 connections)
- **.test_deeply_nested_args()** (4 connections) — `tests/unit/test_redaction.py`
- **.test_module_args_list_values()** (4 connections) — `tests/unit/test_redaction.py`
- **.test_module_args_recursive_redaction()** (4 connections) — `tests/unit/test_redaction.py`
- **.test_no_log_censors_result_field()** (4 connections) — `tests/unit/test_redaction.py`
- **.test_no_log_loop_items_individually_censored()** (4 connections) — `tests/unit/test_redaction.py`
- **.test_no_log_mixed_loop_items()** (4 connections) — `tests/unit/test_redaction.py`
- **.test_no_log_replaces_entire_result()** (4 connections) — `tests/unit/test_redaction.py`
- **_distinctive_secret()** (3 connections) — `tests/unit/test_properties_redaction.py`
- **_innocuous_key()** (3 connections) — `tests/unit/test_properties_redaction.py`
- **_password_shaped_key()** (3 connections) — `tests/unit/test_properties_redaction.py`
- **test_no_log_at_top_level_censors_everything()** (3 connections) — `tests/unit/test_properties_redaction.py`
- **test_no_log_in_loop_items_censors_that_item()** (3 connections) — `tests/unit/test_properties_redaction.py`
- **test_password_redaction_works_through_nested_dicts()** (3 connections) — `tests/unit/test_properties_redaction.py`
- **test_password_shaped_keys_are_redacted()** (3 connections) — `tests/unit/test_properties_redaction.py`
- **test_whitelisted_keys_pass_through()** (3 connections) — `tests/unit/test_properties_redaction.py`
- **.test_no_log_loop_item_censored()** (3 connections) — `tests/unit/test_redaction_layer4.py`
- **.test_no_log_replaces_entire_result()** (3 connections) — `tests/unit/test_redaction_layer4.py`
- **_whitelisted_key()** (2 connections) — `tests/unit/test_properties_redaction.py`
- **Apply all redaction layers to an event dict. Returns a new event.      Layer ord** (1 connections) — `src/ansible_aom/core/redaction.py`
- *... and 19 more nodes in this community*

## Relationships

- [RedactionConfig](RedactionConfig.md) (68 shared connections)
- [redact_dict](redact_dict.md) (3 shared connections)
- [View Mode Selection](View_Mode_Selection.md) (2 shared connections)
- [json.py](json.py.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/redaction.py`
- `tests/unit/test_properties_redaction.py`
- `tests/unit/test_redaction.py`
- `tests/unit/test_redaction_layer4.py`

## Audit Trail

- EXTRACTED: 183 (98%)
- INFERRED: 3 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*