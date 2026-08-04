# json.py

> 18 nodes · cohesion 0.14

## Key Concepts

- **json.py** (80 connections) — `src/ansible_aom/formats/json.py`
- **HostCounts** (8 connections) — `src/ansible_aom/formats/json.py`
- **TaskFailure** (8 connections) — `src/ansible_aom/formats/json.py`
- **.handle_completion()** (7 connections) — `src/ansible_aom/formats/json.py`
- **test_rerun.py** (4 connections) — `tests/integration/test_rerun.py`
- **test_run_summary_model_has_pinned_schema()** (4 connections) — `tests/unit/test_json_renderer.py`
- **BaseModel** (3 connections)
- **test_aom_rerun_failed_spawns_with_correct_limit()** (3 connections) — `tests/integration/test_rerun.py`
- **test_aom_rerun_no_failures_exits_1_without_spawning()** (3 connections) — `tests/integration/test_rerun.py`
- **Path** (2 connections)
- **JSON output renderer for AOM (F6).  Implements the Renderer Protocol but produce** (1 connections) — `src/ansible_aom/formats/json.py`
- **Build the RunSummary from accumulated RunState and print as JSON.          ``exi** (1 connections) — `src/ansible_aom/formats/json.py`
- **Per-host status counts aggregated across every task in every play.** (1 connections) — `src/ansible_aom/formats/json.py`
- **One (host, task) pair that ended in FAILED or UNREACHABLE.** (1 connections) — `src/ansible_aom/formats/json.py`
- **End-to-end integration test for `aom rerun`.  Wires the real ``run_playbook`` ag** (1 connections) — `tests/integration/test_rerun.py`
- **`aom rerun --failed --yes` spawns ansible-playbook with --limit web2,web3.** (1 connections) — `tests/integration/test_rerun.py`
- **When the session has no failures, `--failed` exits 1 and never spawns.** (1 connections) — `tests/integration/test_rerun.py`
- **RunSummary captures every field the schema spec requires.** (1 connections) — `tests/unit/test_json_renderer.py`

## Relationships

- [RunState](RunState.md) (4 shared connections)
- [JsonRenderer](JsonRenderer.md) (4 shared connections)
- [RunSummary](RunSummary.md) (4 shared connections)
- [JsonlEvent](JsonlEvent.md) (3 shared connections)
- [Status](Status.md) (3 shared connections)
- [Terminal Row Counting](Terminal_Row_Counting.md) (2 shared connections)
- [runner.py](runner.py.md) (2 shared connections)
- [HostRunState](HostRunState.md) (2 shared connections)
- [inspect_model.py](inspect_model.py.md) (2 shared connections)
- [models.py](models.py.md) (2 shared connections)
- [store.py](store.py.md) (2 shared connections)
- [build_run_config_key](build_run_config_key.md) (2 shared connections)

## Source Files

- `src/ansible_aom/formats/json.py`
- `tests/integration/test_rerun.py`
- `tests/unit/test_json_renderer.py`

## Audit Trail

- EXTRACTED: 120 (92%)
- INFERRED: 10 (8%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*