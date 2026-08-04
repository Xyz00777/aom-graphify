# json.py

> 35 nodes · cohesion 0.08

## Key Concepts

- **json.py** (80 connections) — `src/ansible_aom/formats/json.py`
- **RunSummary** (12 connections) — `src/ansible_aom/formats/json.py`
- **HostCounts** (8 connections) — `src/ansible_aom/formats/json.py`
- **TaskFailure** (8 connections) — `src/ansible_aom/formats/json.py`
- **test_run_summary_schema.py** (8 connections) — `tests/unit/test_run_summary_schema.py`
- **.handle_completion()** (7 connections) — `src/ansible_aom/formats/json.py`
- **TestSchemaVersionPin** (6 connections) — `tests/unit/test_run_summary_schema.py`
- **_load_committed_schema()** (5 connections) — `tests/unit/test_run_summary_schema.py`
- **test_run_summary_model_has_pinned_schema()** (4 connections) — `tests/unit/test_json_renderer.py`
- **test_pydantic_roundtrip_also_validates()** (4 connections) — `tests/unit/test_run_summary_schema.py`
- **TestSchemaParity** (4 connections) — `tests/unit/test_run_summary_schema.py`
- **BaseModel** (3 connections)
- **_canonical_schema_text()** (3 connections) — `tests/unit/test_run_summary_schema.py`
- **test_golden_payload_validates_against_committed_schema()** (3 connections) — `tests/unit/test_run_summary_schema.py`
- **.test_committed_schema_matches_current_model()** (3 connections) — `tests/unit/test_run_summary_schema.py`
- **.test_committed_schema_pins_schema_version_to_one()** (3 connections) — `tests/unit/test_run_summary_schema.py`
- **.test_construction_with_wrong_version_rejected()** (3 connections) — `tests/unit/test_run_summary_schema.py`
- **.test_live_model_instance_has_schema_version_one()** (3 connections) — `tests/unit/test_run_summary_schema.py`
- **JSON output renderer for AOM (F6).  Implements the Renderer Protocol but produce** (1 connections) — `src/ansible_aom/formats/json.py`
- **Build the RunSummary from accumulated RunState and print as JSON.          ``exi** (1 connections) — `src/ansible_aom/formats/json.py`
- **Per-host status counts aggregated across every task in every play.** (1 connections) — `src/ansible_aom/formats/json.py`
- **One (host, task) pair that ended in FAILED or UNREACHABLE.** (1 connections) — `src/ansible_aom/formats/json.py`
- **End-of-run summary emitted by ``JsonRenderer.handle_completion``.      Field rul** (1 connections) — `src/ansible_aom/formats/json.py`
- **RunSummary captures every field the schema spec requires.** (1 connections) — `tests/unit/test_json_renderer.py`
- **Contract test for the committed ``RunSummary`` v1 JSON schema (Item #7).  Downst** (1 connections) — `tests/unit/test_run_summary_schema.py`
- *... and 10 more nodes in this community*

## Relationships

- [Status](Status.md) (5 shared connections)
- [RunState](RunState.md) (5 shared connections)
- [JsonlEvent](JsonlEvent.md) (4 shared connections)
- [JsonRenderer](JsonRenderer.md) (4 shared connections)
- [load_session](load_session.md) (3 shared connections)
- [SessionManager](SessionManager.md) (3 shared connections)
- [Terminal Row Counting](Terminal_Row_Counting.md) (2 shared connections)
- [runner.py](runner.py.md) (2 shared connections)
- [HostRunState](HostRunState.md) (2 shared connections)
- [inspect_model.py](inspect_model.py.md) (2 shared connections)
- [StreamPhase](StreamPhase.md) (2 shared connections)
- [index.py](index.py.md) (2 shared connections)

## Source Files

- `src/ansible_aom/formats/json.py`
- `tests/unit/test_json_renderer.py`
- `tests/unit/test_run_summary_schema.py`

## Audit Trail

- EXTRACTED: 167 (91%)
- INFERRED: 17 (9%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*