# test_posix_callback.py

> 18 nodes · cohesion 0.11

## Key Concepts

- **test_posix_callback.py** (7 connections) — `tests/unit/test_posix_callback.py`
- **TestAnsiblePosixVersionCheck** (5 connections) — `tests/unit/test_posix_callback.py`
- **ansible/__init__.py** (4 connections) — `src/ansible_aom/ansible/__init__.py`
- **TestAnsiblePosixInstallPrompt** (4 connections) — `tests/unit/test_posix_callback.py`
- **.test_bundled_preferred_over_posix_fallback()** (2 connections) — `tests/unit/test_posix_callback.py`
- **.test_fallback_selects_ansible_posix_jsonl()** (2 connections) — `tests/unit/test_posix_callback.py`
- **.test_bundled_plugin_does_not_require_ansible_posix_collection()** (2 connections) — `tests/unit/test_posix_callback.py`
- **.test_fallback_callback_name_is_ansible_posix_jsonl()** (2 connections) — `tests/unit/test_posix_callback.py`
- **.test_fallback_callback_name_split_correctly()** (2 connections) — `tests/unit/test_posix_callback.py`
- **Ansible infrastructure: subprocess, pexpect, JSONL callback wiring.  Contains th** (1 connections) — `src/ansible_aom/ansible/__init__.py`
- **Tests for JSONL callback plugin configuration (TC-067 to TC-071).  Test cases co** (1 connections) — `tests/unit/test_posix_callback.py`
- **TC-068: When bundled dir resolves, aom_jsonl wins over ansible.posix.jsonl.** (1 connections) — `tests/unit/test_posix_callback.py`
- **Tests for TC-070: ansible.posix Version Check.      AOM never imports the ansibl** (1 connections) — `tests/unit/test_posix_callback.py`
- **TC-070: When bundled dir missing, callback name is the canonical string.** (1 connections) — `tests/unit/test_posix_callback.py`
- **TC-070: ansible.posix.jsonl parses as collection='ansible.posix', plugin='jsonl'** (1 connections) — `tests/unit/test_posix_callback.py`
- **TC-070: When bundled aom_jsonl is selected, ansible.posix isn't required.** (1 connections) — `tests/unit/test_posix_callback.py`
- **Tests for TC-068: ansible.posix Install Prompt (implicit fallback path).      AO** (1 connections) — `tests/unit/test_posix_callback.py`
- **TC-068: When bundled stdout dir unavailable, env selects ansible.posix.jsonl.** (1 connections) — `tests/unit/test_posix_callback.py`

## Relationships

- [test_callback_env.py](test_callback_env.py.md) (1 shared connections)
- [Cancellation Timer](Cancellation_Timer.md) (1 shared connections)
- [Subprocess Exit Codes](Subprocess_Exit_Codes.md) (1 shared connections)
- [TestAnsiblePosixAvailability](TestAnsiblePosixAvailability.md) (1 shared connections)
- [Terminal Capability Detection](Terminal_Capability_Detection.md) (1 shared connections)

## Source Files

- `src/ansible_aom/ansible/__init__.py`
- `tests/unit/test_posix_callback.py`

## Audit Trail

- EXTRACTED: 39 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*