# json.py

> 11 nodes · cohesion 0.24

## Key Concepts

- **json.py** (80 connections) — `src/ansible_aom/formats/json.py`
- **HostCounts** (8 connections) — `src/ansible_aom/formats/json.py`
- **TaskFailure** (8 connections) — `src/ansible_aom/formats/json.py`
- **.handle_completion()** (7 connections) — `src/ansible_aom/formats/json.py`
- **test_run_summary_model_has_pinned_schema()** (4 connections) — `tests/unit/test_json_renderer.py`
- **BaseModel** (3 connections)
- **JSON output renderer for AOM (F6).  Implements the Renderer Protocol but produce** (1 connections) — `src/ansible_aom/formats/json.py`
- **Build the RunSummary from accumulated RunState and print as JSON.          ``exi** (1 connections) — `src/ansible_aom/formats/json.py`
- **Per-host status counts aggregated across every task in every play.** (1 connections) — `src/ansible_aom/formats/json.py`
- **One (host, task) pair that ended in FAILED or UNREACHABLE.** (1 connections) — `src/ansible_aom/formats/json.py`
- **RunSummary captures every field the schema spec requires.** (1 connections) — `tests/unit/test_json_renderer.py`

## Relationships

- [Status](Status.md) (4 shared connections)
- [RunState](RunState.md) (4 shared connections)
- [JsonRenderer](JsonRenderer.md) (4 shared connections)
- [RunSummary](RunSummary.md) (4 shared connections)
- [JsonlEvent](JsonlEvent.md) (3 shared connections)
- [load_session](load_session.md) (3 shared connections)
- [Terminal Row Counting](Terminal_Row_Counting.md) (2 shared connections)
- [HostRunState](HostRunState.md) (2 shared connections)
- [inspect_model.py](inspect_model.py.md) (2 shared connections)
- [StreamPhase](StreamPhase.md) (2 shared connections)
- [build_run_config_key](build_run_config_key.md) (2 shared connections)
- [test_replay_determinism.py](test_replay_determinism.py.md) (2 shared connections)

## Source Files

- `src/ansible_aom/formats/json.py`
- `tests/unit/test_json_renderer.py`

## Audit Trail

- EXTRACTED: 105 (91%)
- INFERRED: 10 (9%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*