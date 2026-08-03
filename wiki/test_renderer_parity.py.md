# test_renderer_parity.py

> 13 nodes · cohesion 0.23

## Key Concepts

- **test_renderer_parity.py** (9 connections) — `tests/integration/test_renderer_parity.py`
- **_drive_compact()** (6 connections) — `tests/integration/test_renderer_parity.py`
- **_drive_json()** (6 connections) — `tests/integration/test_renderer_parity.py`
- **test_all_renderers_agree_on_reduced_state()** (6 connections) — `tests/integration/test_renderer_parity.py`
- **_load_events()** (4 connections) — `tests/integration/test_renderer_parity.py`
- **test_reduced_state_shape_is_stable()** (4 connections) — `tests/integration/test_renderer_parity.py`
- **CaptureFixture** (2 connections)
- **Path** (1 connections)
- **Cross-renderer parity invariant.  Feed the same recorded JSONL stream through th** (1 connections) — `tests/integration/test_renderer_parity.py`
- **Drive a CompactRenderer through every event and reduce the final state.** (1 connections) — `tests/integration/test_renderer_parity.py`
- **Drive a JsonRenderer through every event and reduce its RunState.      The rende** (1 connections) — `tests/integration/test_renderer_parity.py`
- **For each fixture, both renderers must reduce to the same dict.** (1 connections) — `tests/integration/test_renderer_parity.py`
- **Sanity check the shape on a known-good fixture.      Locks in the keys other con** (1 connections) — `tests/integration/test_renderer_parity.py`

## Relationships

- [HostRunState](HostRunState.md) (3 shared connections)
- [renderer.py](renderer.py.md) (1 shared connections)
- [json.py](json.py.md) (1 shared connections)
- [CompactRenderer](CompactRenderer.md) (1 shared connections)
- [JsonRenderer](JsonRenderer.md) (1 shared connections)

## Source Files

- `tests/integration/test_renderer_parity.py`

## Audit Trail

- EXTRACTED: 43 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*