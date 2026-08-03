# TestYesFlag

> 12 nodes · cohesion 0.17

## Key Concepts

- **TestYesFlag** (15 connections) — `tests/unit/test_cli.py`
- **.test_yes_does_not_appear_in_ansible_args()** (3 connections) — `tests/unit/test_cli.py`
- **.test_yes_flag_defaults_false()** (3 connections) — `tests/unit/test_cli.py`
- **.test_yes_help_text_mentions_yes()** (3 connections) — `tests/unit/test_cli.py`
- **.test_yes_short_does_not_appear_in_ansible_args()** (3 connections) — `tests/unit/test_cli.py`
- **.test_yes_long_form()** (2 connections) — `tests/unit/test_cli.py`
- **.test_yes_short_form()** (2 connections) — `tests/unit/test_cli.py`
- **Tests for global --yes flag.** (1 connections) — `tests/unit/test_cli.py`
- **--yes defaults to False when not provided.** (1 connections) — `tests/unit/test_cli.py`
- **--yes is consumed by argparse, not forwarded to ansible-playbook.** (1 connections) — `tests/unit/test_cli.py`
- **-y is consumed by argparse, not forwarded to ansible-playbook.** (1 connections) — `tests/unit/test_cli.py`
- **Help text for --yes mentions the flag.** (1 connections) — `tests/unit/test_cli.py`

## Relationships

- [create_parser](create_parser.md) (6 shared connections)
- [HostRunState](HostRunState.md) (4 shared connections)
- [CompactRenderer](CompactRenderer.md) (1 shared connections)
- [Status](Status.md) (1 shared connections)
- [RunState](RunState.md) (1 shared connections)
- [JsonRenderer](JsonRenderer.md) (1 shared connections)

## Source Files

- `tests/unit/test_cli.py`

## Audit Trail

- EXTRACTED: 23 (64%)
- INFERRED: 13 (36%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*