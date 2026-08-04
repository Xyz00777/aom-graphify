# TestProjectionLifecycle

> 13 nodes · cohesion 0.23

## Key Concepts

- **TestProjectionLifecycle** (11 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **_seed_sticky_gap_state()** (9 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **test_tree_projection_lifecycle.py** (8 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **.test_perf_020_event_keeps_projection_alive_and_refreshes_cache()** (7 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **.test_perf_022_update_state_keeps_sticky_active_play_on_gap_frame()** (6 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **_renderer()** (5 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **.test_perf_021_consecutive_ticks_reuse_projection()** (4 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **_runner_ok()** (2 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **_task_start()** (2 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **A state-shape change must refresh, not replace, the cached projection.** (1 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **Two ticks with no intervening state mutation reuse the same instance.** (1 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **A non-structural update must keep the active play visible only         while it** (1 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **Build a tiny two-play state that exposes sticky row selection.      ``active`` i** (1 connections) — `tests/compact/test_tree_projection_lifecycle.py`

## Relationships

- [HostRunState](HostRunState.md) (6 shared connections)
- [TreeProjection](TreeProjection.md) (4 shared connections)
- [CompactRenderer](CompactRenderer.md) (3 shared connections)
- [TaskDefinition](TaskDefinition.md) (3 shared connections)
- [PlayDefinition](PlayDefinition.md) (3 shared connections)
- [Status](Status.md) (2 shared connections)
- [renderer.py](renderer.py.md) (1 shared connections)

## Source Files

- `tests/compact/test_tree_projection_lifecycle.py`

## Audit Trail

- EXTRACTED: 48 (83%)
- INFERRED: 10 (17%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*