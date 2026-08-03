# TestAppConfigYamlFile

> 10 nodes · cohesion 0.20

## Key Concepts

- **TestAppConfigYamlFile** (10 connections) — `tests/unit/test_config.py`
- **.test_app_config_with_model_config_dict()** (3 connections) — `tests/unit/test_config.py`
- **.test_yaml_file_default_path()** (2 connections) — `tests/unit/test_config.py`
- **.test_yaml_file_expanded_path()** (2 connections) — `tests/unit/test_config.py`
- **.test_yaml_file_xdg_compliant()** (2 connections) — `tests/unit/test_config.py`
- **Tests for Pydantic Settings YAML file integration - TC-304, TC-305, TC-306.** (1 connections) — `tests/unit/test_config.py`
- **TC-304: Default YAML file path is ~/.config/aom/config.yaml.** (1 connections) — `tests/unit/test_config.py`
- **TC-304: YAML path should be expandable to absolute path.** (1 connections) — `tests/unit/test_config.py`
- **TC-304: Config path follows XDG spec (~/.config/aom/config.yaml).** (1 connections) — `tests/unit/test_config.py`
- **AppConfig uses SettingsConfigDict for configuration.** (1 connections) — `tests/unit/test_config.py`

## Relationships

- [AppConfig](AppConfig.md) (2 shared connections)
- [Status](Status.md) (1 shared connections)
- [RedactionConfig](RedactionConfig.md) (1 shared connections)
- [WarningsConfig](WarningsConfig.md) (1 shared connections)
- [test_config.py](test_config.py.md) (1 shared connections)

## Source Files

- `tests/unit/test_config.py`

## Audit Trail

- EXTRACTED: 19 (79%)
- INFERRED: 5 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*