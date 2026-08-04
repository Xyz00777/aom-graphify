# TestTwoLevelTruncation

> 22 nodes · cohesion 0.12

## Key Concepts

- **TestTwoLevelTruncation** (17 connections) — `tests/unit/test_tree_projection.py`
- **._single_play_single_role_state()** (11 connections) — `tests/unit/test_tree_projection.py`
- **.test_inner_footer_does_not_count_upcoming_plays_tasks()** (7 connections) — `tests/unit/test_tree_projection.py`
- **.test_outer_footer_appears_when_budget_overflow()** (7 connections) — `tests/unit/test_tree_projection.py`
- **._two_plays_state()** (7 connections) — `tests/unit/test_tree_projection.py`
- **.test_every_inner_section_line_has_tail_after()** (4 connections) — `tests/unit/test_tree_projection.py`
- **.test_inner_count_uses_role_remaining_count()** (4 connections) — `tests/unit/test_tree_projection.py`
- **.test_inner_footer_emitted_when_cut_inside_role()** (4 connections) — `tests/unit/test_tree_projection.py`
- **.test_no_inner_footer_when_cut_between_plays()** (4 connections) — `tests/unit/test_tree_projection.py`
- **.test_outer_count_uses_task_domain_count()** (4 connections) — `tests/unit/test_tree_projection.py`
- **.test_within_budget_unchanged()** (4 connections) — `tests/unit/test_tree_projection.py`
- **Two-cut truncation: when the budget is exceeded, the algorithm     emits BOTH an** (1 connections) — `tests/unit/test_tree_projection.py`
- **1 play, 1 role, ``n_tasks`` tasks, 1 host — the simplest         tree whose budg** (1 connections) — `tests/unit/test_tree_projection.py`
- **2 plays, each with a single role and ``n_tasks_per_role`` tasks.         The unb** (1 connections) — `tests/unit/test_tree_projection.py`
- **A small tree that fits the budget returns verbatim — no footers,         no has_** (1 connections) — `tests/unit/test_tree_projection.py`
- **The classic scenario from test_tree_nested_roles.py: 1 play, 1         role, 34** (1 connections) — `tests/unit/test_tree_projection.py`
- **When the budget cut lands inside a role's task list, both an         inner foote** (1 connections) — `tests/unit/test_tree_projection.py`
- **When the budget cut lands cleanly on a play boundary (between         two plays)** (1 connections) — `tests/unit/test_tree_projection.py`
- **The inner footer's count must equal the number of tasks remaining         in the** (1 connections) — `tests/unit/test_tree_projection.py`
- **The inner footer must NOT count tasks from upcoming plays.          State: 2 pla** (1 connections) — `tests/unit/test_tree_projection.py`
- **The outer footer's count uses task-domain semantics: hidden         plays, roles** (1 connections) — `tests/unit/test_tree_projection.py`
- **Every line in the inner section must carry         ``has_tail_after=True`` so th** (1 connections) — `tests/unit/test_tree_projection.py`

## Relationships

- [.from_run_state](from_run_state.md) (9 shared connections)
- [TaskDefinition](TaskDefinition.md) (5 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (5 shared connections)
- [PlayDefinition](PlayDefinition.md) (5 shared connections)
- [RunState](RunState.md) (4 shared connections)
- [Status](Status.md) (1 shared connections)
- [HostRunState](HostRunState.md) (1 shared connections)

## Source Files

- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 79 (94%)
- INFERRED: 5 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*