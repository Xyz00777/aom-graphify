# parity.py

> 23 nodes · cohesion 0.12

## Key Concepts

- **parity.py** (10 connections) — `src/ansible_aom/core/parity.py`
- **test_renderer_parity.py** (9 connections) — `tests/integration/test_renderer_parity.py`
- **core/exit_code.py** (8 connections) — `src/ansible_aom/core/exit_code.py`
- **reduce_state_for_parity()** (8 connections) — `src/ansible_aom/core/parity.py`
- **_drive_compact()** (6 connections) — `tests/integration/test_renderer_parity.py`
- **_drive_json()** (6 connections) — `tests/integration/test_renderer_parity.py`
- **test_all_renderers_agree_on_reduced_state()** (6 connections) — `tests/integration/test_renderer_parity.py`
- **compact/exit_code.py** (4 connections) — `src/ansible_aom/compact/exit_code.py`
- **_load_events()** (4 connections) — `tests/integration/test_renderer_parity.py`
- **test_reduced_state_shape_is_stable()** (4 connections) — `tests/integration/test_renderer_parity.py`
- **_empty_host_counts()** (2 connections) — `src/ansible_aom/core/parity.py`
- **CaptureFixture** (2 connections)
- **Backward-compat re-export shim for ``determine_exit_code``.  The canonical imple** (1 connections) — `src/ansible_aom/compact/exit_code.py`
- **Process exit-code derivation from a :class:`RunState`.  Pure: in → out, no I/O.** (1 connections) — `src/ansible_aom/core/exit_code.py`
- **Any** (1 connections)
- **Reduce a ``RunState`` into a renderer-agnostic dict.  This is the canonical "wha** (1 connections) — `src/ansible_aom/core/parity.py`
- **Project ``state`` into a renderer-agnostic dict.      Shape::          {** (1 connections) — `src/ansible_aom/core/parity.py`
- **Path** (1 connections)
- **Cross-renderer parity invariant.  Feed the same recorded JSONL stream through th** (1 connections) — `tests/integration/test_renderer_parity.py`
- **Drive a CompactRenderer through every event and reduce the final state.** (1 connections) — `tests/integration/test_renderer_parity.py`
- **Drive a JsonRenderer through every event and reduce its RunState.      The rende** (1 connections) — `tests/integration/test_renderer_parity.py`
- **For each fixture, both renderers must reduce to the same dict.** (1 connections) — `tests/integration/test_renderer_parity.py`
- **Sanity check the shape on a known-good fixture.      Locks in the keys other con** (1 connections) — `tests/integration/test_renderer_parity.py`

## Relationships

- [HostRunState](HostRunState.md) (4 shared connections)
- [models.py](models.py.md) (4 shared connections)
- [RunState](RunState.md) (3 shared connections)
- [renderer.py](renderer.py.md) (2 shared connections)
- [Status](Status.md) (2 shared connections)
- [json.py](json.py.md) (1 shared connections)
- [CompactRenderer](CompactRenderer.md) (1 shared connections)
- [JsonRenderer](JsonRenderer.md) (1 shared connections)

## Source Files

- `src/ansible_aom/compact/exit_code.py`
- `src/ansible_aom/core/exit_code.py`
- `src/ansible_aom/core/parity.py`
- `tests/integration/test_renderer_parity.py`

## Audit Trail

- EXTRACTED: 80 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*