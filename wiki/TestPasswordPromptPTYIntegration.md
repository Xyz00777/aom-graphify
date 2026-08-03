# TestPasswordPromptPTYIntegration

> 34 nodes · cohesion 0.08

## Key Concepts

- **TestPasswordPromptPTYIntegration** (26 connections) — `tests/compact/test_password.py`
- **is_password_prompt()** (16 connections) — `src/ansible_aom/core/prompts.py`
- **.test_is_password_prompt_become_password()** (3 connections) — `tests/compact/test_password.py`
- **.test_is_password_prompt_become_password_defaults()** (3 connections) — `tests/compact/test_password.py`
- **.test_is_password_prompt_confirm_vault_password()** (3 connections) — `tests/compact/test_password.py`
- **.test_is_password_prompt_new_vault_password()** (3 connections) — `tests/compact/test_password.py`
- **.test_is_password_prompt_rejects_empty_string()** (3 connections) — `tests/compact/test_password.py`
- **.test_is_password_prompt_rejects_non_password()** (3 connections) — `tests/compact/test_password.py`
- **.test_is_password_prompt_rejects_partial_match_only()** (3 connections) — `tests/compact/test_password.py`
- **.test_is_password_prompt_ssh_password()** (3 connections) — `tests/compact/test_password.py`
- **.test_is_password_prompt_sudo_bracketed_password()** (3 connections) — `tests/compact/test_password.py`
- **.test_is_password_prompt_sudo_password()** (3 connections) — `tests/compact/test_password.py`
- **.test_is_password_prompt_sudo_password_for_user()** (3 connections) — `tests/compact/test_password.py`
- **.test_is_password_prompt_vault_password()** (3 connections) — `tests/compact/test_password.py`
- **.test_is_password_prompt_vault_password_with_id()** (3 connections) — `tests/compact/test_password.py`
- **.test_all_password_patterns_are_valid_regex()** (2 connections) — `tests/compact/test_password.py`
- **.test_password_patterns_count()** (2 connections) — `tests/compact/test_password.py`
- **Check if ``text`` matches any known password prompt pattern.** (1 connections) — `src/ansible_aom/core/prompts.py`
- **TC-143: Text containing but not ending with password pattern prefix still matche** (1 connections) — `tests/compact/test_password.py`
- **TC-143: All PASSWORD_PATTERNS entries compile as valid regex.** (1 connections) — `tests/compact/test_password.py`
- **TC-143: All 10 documented password patterns present.          Ansible-native (7)** (1 connections) — `tests/compact/test_password.py`
- **TC-143: Verify pexpect spawns with PTY, Ansible's getpass reads from /dev/tty.** (1 connections) — `tests/compact/test_password.py`
- **TC-143: Vault password pattern detected for PTY integration.** (1 connections) — `tests/compact/test_password.py`
- **TC-143: Vault password (vault_id variant) detected.** (1 connections) — `tests/compact/test_password.py`
- **TC-143: SSH password pattern detected for PTY integration.** (1 connections) — `tests/compact/test_password.py`
- *... and 9 more nodes in this community*

## Relationships

- [.handle_password_prompt](handle_password_prompt.md) (7 shared connections)
- [prompts.py](prompts.py.md) (2 shared connections)
- [CompactRenderer](CompactRenderer.md) (2 shared connections)
- [.test_handle_password_prompt_passes_prompt_text_to_getpass](test_handle_password_prompt_passes_prompt_text_to_getpass.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/prompts.py`
- `tests/compact/test_password.py`

## Audit Trail

- EXTRACTED: 75 (74%)
- INFERRED: 27 (26%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*