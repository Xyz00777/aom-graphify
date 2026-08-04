# TestAsyncPollDoesNotLeakDictIntoLoopItem

> 8 nodes · cohesion 0.36

## Key Concepts

- **TestAsyncPollDoesNotLeakDictIntoLoopItem** (10 connections) — `tests/unit/test_inspect_model.py`
- **_make_loop_item()** (7 connections) — `src/ansible_aom/core/inspect_model.py`
- **LoopItem** (4 connections) — `src/ansible_aom/core/inspect_model.py`
- **.test_make_loop_item_async_poll_does_not_leak_dict()** (2 connections) — `tests/unit/test_inspect_model.py`
- **.test_make_loop_item_async_poll_failed_flag_set_correctly()** (2 connections) — `tests/unit/test_inspect_model.py`
- **.test_make_loop_item_normal_loop_item_unaffected()** (2 connections) — `tests/unit/test_inspect_model.py`
- **One entry from a task's loop ``results[]`` array.** (1 connections) — `src/ansible_aom/core/inspect_model.py`
- **Async-poll bookkeeping payloads must not leak the raw dict into LoopItem.label.** (1 connections) — `tests/unit/test_inspect_model.py`

## Relationships

- [StatusCounts](StatusCounts.md) (3 shared connections)
- [TaskTreeNode](TaskTreeNode.md) (3 shared connections)
- [inspect_model.py](inspect_model.py.md) (2 shared connections)
- [JsonlEvent](JsonlEvent.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/inspect_model.py`
- `tests/unit/test_inspect_model.py`

## Audit Trail

- EXTRACTED: 23 (79%)
- INFERRED: 6 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*