# TestSubtreeRoleCounting

> 24 nodes · cohesion 0.11

## Key Concepts

- **TestSubtreeRoleCounting** (14 connections) — `tests/unit/test_tree_projection.py`
- **TestMultiLevelInnerFooters** (11 connections) — `tests/unit/test_tree_projection.py`
- **._nested_state()** (11 connections) — `tests/unit/test_tree_projection.py`
- **._nested_truncated_state()** (7 connections) — `tests/unit/test_tree_projection.py`
- **.test_single_level_role_one_inner_footer()** (7 connections) — `tests/unit/test_tree_projection.py`
- **.test_role_total_single_role_unchanged()** (7 connections) — `tests/unit/test_tree_projection.py`
- **.test_inner_footer_per_role_ancestor_matches_role_label()** (4 connections) — `tests/unit/test_tree_projection.py`
- **.test_multi_level_inner_footers_emitted()** (4 connections) — `tests/unit/test_tree_projection.py`
- **.test_role_label_subtree_total_when_cut_inside_nested()** (4 connections) — `tests/unit/test_tree_projection.py`
- **.test_role_total_includes_nested_subtree_tasks()** (4 connections) — `tests/unit/test_tree_projection.py`
- **.test_role_visible_includes_nested_visible_tasks()** (4 connections) — `tests/unit/test_tree_projection.py`
- **.test_role_visible_single_role_unchanged()** (4 connections) — `tests/unit/test_tree_projection.py`
- **Subtree semantics for ``_build_role_total_tasks`` and     ``_count_visible_tasks** (1 connections) — `tests/unit/test_tree_projection.py`
- **Build a state with ``podman > angie_ssl_terminator`` nesting.          ``n_podma** (1 connections) — `tests/unit/test_tree_projection.py`
- **``role_total_tasks["podman"]`` must include angie's 30 tasks         as part of** (1 connections) — `tests/unit/test_tree_projection.py`
- **Regression guard: subtree and direct-children counts are         equal for a sin** (1 connections) — `tests/unit/test_tree_projection.py`
- **When only role headers + a couple tasks fit in the budget,         both ``podman** (1 connections) — `tests/unit/test_tree_projection.py`
- **Regression guard for single-role subtree == direct.** (1 connections) — `tests/unit/test_tree_projection.py`
- **With a small budget that truncates inside angie's task list,         both podman** (1 connections) — `tests/unit/test_tree_projection.py`
- **Multi-level inner footer emission for nested roles.      When the cut lands insi** (1 connections) — `tests/unit/test_tree_projection.py`
- **Build a state where the cut lands inside angie's task list.          ``podman``** (1 connections) — `tests/unit/test_tree_projection.py`
- **Cut inside ``angie_ssl_terminator`` must emit TWO inner         footers: one for** (1 connections) — `tests/unit/test_tree_projection.py`
- **For each inner footer, the count equals         ``role_total - role_visible`` fo** (1 connections) — `tests/unit/test_tree_projection.py`
- **Regression guard: a single-level role cut still emits         exactly ONE inner** (1 connections) — `tests/unit/test_tree_projection.py`

## Relationships

- [.from_run_state](from_run_state.md) (10 shared connections)
- [TaskDefinition](TaskDefinition.md) (5 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (5 shared connections)
- [PlayDefinition](PlayDefinition.md) (5 shared connections)
- [RunState](RunState.md) (4 shared connections)
- [Status](Status.md) (2 shared connections)
- [HostRunState](HostRunState.md) (2 shared connections)

## Source Files

- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 83 (89%)
- INFERRED: 10 (11%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*