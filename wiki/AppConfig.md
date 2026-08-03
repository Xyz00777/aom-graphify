# AppConfig

> 31 nodes · cohesion 0.09

## Key Concepts

- **AppConfig** (65 connections) — `src/ansible_aom/core/config.py`
- **TestAppConfig** (19 connections) — `tests/unit/test_config.py`
- **.test_app_config_custom_status_bar()** (4 connections) — `tests/unit/test_config.py`
- **.test_app_config_custom_warnings()** (4 connections) — `tests/unit/test_config.py`
- **.test_app_config_default_status_bar()** (4 connections) — `tests/unit/test_config.py`
- **.test_app_config_default_warnings()** (4 connections) — `tests/unit/test_config.py`
- **.test_app_config_independent_instances()** (4 connections) — `tests/unit/test_config.py`
- **.test_app_config_custom_log_max_lines()** (3 connections) — `tests/unit/test_config.py`
- **.test_app_config_custom_redaction()** (3 connections) — `tests/unit/test_config.py`
- **.test_app_config_custom_session_keep_count()** (3 connections) — `tests/unit/test_config.py`
- **.test_app_config_custom_session_keep_days()** (3 connections) — `tests/unit/test_config.py`
- **.test_app_config_default_log_max_lines()** (3 connections) — `tests/unit/test_config.py`
- **.test_app_config_default_redaction()** (3 connections) — `tests/unit/test_config.py`
- **.test_app_config_default_session_keep_count()** (3 connections) — `tests/unit/test_config.py`
- **.test_app_config_default_session_keep_days()** (3 connections) — `tests/unit/test_config.py`
- **BaseSettings** (1 connections)
- **Application configuration loaded from YAML and CLI.      YAML loading is handled** (1 connections) — `src/ansible_aom/core/config.py`
- **Tests for AppConfig model - TC-263 to TC-275.** (1 connections) — `tests/unit/test_config.py`
- **TC-263: AppConfig has default log_max_lines=50000.** (1 connections) — `tests/unit/test_config.py`
- **TC-264: AppConfig has default session_keep_count=100.** (1 connections) — `tests/unit/test_config.py`
- **TC-265: AppConfig has default session_keep_days=30.** (1 connections) — `tests/unit/test_config.py`
- **AppConfig has default StatusBarConfig.** (1 connections) — `tests/unit/test_config.py`
- **AppConfig has default RedactionConfig.** (1 connections) — `tests/unit/test_config.py`
- **AppConfig has default WarningsConfig.** (1 connections) — `tests/unit/test_config.py`
- **AppConfig log_max_lines can be customized.** (1 connections) — `tests/unit/test_config.py`
- *... and 6 more nodes in this community*

## Relationships

- [TestAppConfigValidation](TestAppConfigValidation.md) (10 shared connections)
- [WarningsConfig](WarningsConfig.md) (8 shared connections)
- [TestAppConfigFieldTypes](TestAppConfigFieldTypes.md) (7 shared connections)
- [TestConfigFieldValidation](TestConfigFieldValidation.md) (5 shared connections)
- [TestWarningPatternsEdgeCases](TestWarningPatternsEdgeCases.md) (5 shared connections)
- [TestConfigFromEnvironment](TestConfigFromEnvironment.md) (4 shared connections)
- [WarningType](WarningType.md) (4 shared connections)
- [load_config](load_config.md) (3 shared connections)
- [test_config.py](test_config.py.md) (3 shared connections)
- [RedactionConfig](RedactionConfig.md) (2 shared connections)
- [TestAppConfigYamlFile](TestAppConfigYamlFile.md) (2 shared connections)
- [TestConfigModelBasics](TestConfigModelBasics.md) (2 shared connections)

## Source Files

- `src/ansible_aom/core/config.py`
- `tests/unit/test_config.py`

## Audit Trail

- EXTRACTED: 64 (44%)
- INFERRED: 80 (56%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*