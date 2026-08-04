# Graph Report - .  (2026-08-04)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 9469 nodes · 19097 edges · 667 communities (360 shown, 307 thin omitted)
- Extraction: 83% EXTRACTED · 17% INFERRED · 0% AMBIGUOUS · INFERRED: 3152 edges (avg confidence: 0.58)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `53d4ad26`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- HostRunState
- PtyStreamParser
- RunState
- AppConfig
- test_pty_stream.py
- StatusBarConfig
- load_session
- .from_run_state
- Display
- WarningType
- test_concurrent_inspect.py
- TaskDefinition
- CompactRenderer
- parse_list_hosts_output
- SessionManager
- _play_start
- _BoundedDict
- RedactionConfig
- parse_list_tasks_output
- create_parser
- TreeProjection
- TestJsonLineStreamSurvivesMojibake
- build_run_config_key
- OverheadStats
- Inspect CLI Commands
- StatusCounts
- TaskTreeNode
- RoleGroupDefinition
- test_task_completion.py
- InspectApp
- run_preflight
- datetime
- Error Handling Tests
- RedactionConfig
- Event Log Emission
- _play_start
- List Tasks Output Parser
- TestWarningPatternsEdgeCases
- TestPasswordPromptPTYIntegration
- store.py
- format_status_bar
- RedactionConfig
- Renderer
- _handle_timeout_branch
- runner.py
- TestTemplateVariableNameMismatch
- test_callback_env.py
- Prompt Detection Heuristics
- TestPlaintextLineHandling
- test_overhead.py
- TestUngroupedRoleTasksInTree
- TestFilterPanelHostFilter
- history.py
- App Config Model Tests
- RendererMirrorMachine
- Debug Panel Widget
- Path
- JsonlEvent
- RunDiagnostics
- Total Task Counting
- _fresh_display
- test_tree_render.py
- tests/conftest.py
- HeartbeatTracker
- ansible.posix.jsonl (parent callback)
- Playbook Run Integration Tests
- test_tree_classify_and_role_labels.py
- test_inspect_debug.py
- _session
- RedactionConfig
- TestURLCredentialSanitization
- renderer.py
- Host Result Hide Filter
- .handle_password_prompt
- Hide State Normalization
- test_full_completion_summary.py
- reconstruct_pause_prompt
- redact_dict
- Terminal Row Counting
- JsonRenderer
- is_password_prompt
- Renderer Factory Function
- Tree Projection Logic
- TestPasswordPromptPatterns
- event_types.py
- WarningsConfig
- Play Boundary State Tests
- TestHandleEventMalformedPayloads
- Preflight Definition Assembly
- TestTimestampLocalTimezone
- parse_jsonl_output
- TestEventParsing
- _AsyncEventWriter
- Mitogen Event Robustness
- _drive
- _state_with_play
- Replay CLI Subcommand
- test_r6_encoding_roundtrip.py
- analyze_overhead
- Skipped Task Collapsing
- Include Import Role Tasks
- TestPasswordPromptPatterns
- Parser Edge Cases
- RunSummary Schema Contract
- Parallel Pre-flight Runner
- Playbook Event Parsing
- Run Diagnostics Accumulator
- Main TUI Screen
- TestEdgeCases
- run_playbook
- Play Tree Projection
- sessions/conftest.py
- _row_count
- PlayDefinition
- create_renderer
- TestSubtreeRoleCounting
- State Transition Validation
- _safe_loads
- inspect/cli.py
- Path
- Pane Focus Navigation
- Log Panel Widget
- _FakeSpawn
- TestStatusBarAvailableElements
- Pydantic Model Basics
- redact_event
- format_host_rows
- Shell Completion Helpers
- Compact Display Logic
- Renderer Parity Invariant
- _FakeSpawn
- Password Prompt Patterns
- Subprocess Exit Codes
- Renderer ETA Wiring
- Auto Version Bump Hook
- test_ignore_errors_callback.py
- _make_play
- test_preflight.py
- Parser Phase Transitions
- Warning Pattern Detection
- Conftest Fixture Validation
- assemble_definitions
- TestAppConfigValidation
- WarningEntry
- TestTwoLevelTruncation
- RunSummary
- Session Roundtrip Invariants
- Version Bump Script
- TestConfigModelBasics
- Runner Heartbeat Wiring
- TestPtyStreamParserPhaseTransitions
- TestWarningPatternDetection
- parity.py
- TestRuntimeRoleTaskCount
- ansible_aom/cli.py
- test_render_storm.py
- FakeRenderer
- Color Support Detection
- View Mode Selection
- Terminal Capability Detection
- core/__init__.py
- TestProjectionLifecycle
- test_no_eof_hang.py
- Psutil Safe Probe
- ensure_inventory_arg
- TestNoRedactFlag
- Dirty Flag Throttle
- Tree Expansion Icons
- Rerun CLI Command
- test_parser_recap_cap.py
- TestPasswordTimeoutDefault
- TestPerEventLogColors
- TestConftestFixtures
- Status
- .test_record_false_does_not_touch_default_state_dir
- test_inspect_accumulator.py
- test_cli.py
- test_run_state_memory_bounds.py
- test_loop_item_count.py
- _print_session_footer
- Diagnostics CLI Wiring
- TestReEnableOnResize
- test_runner_on_start_host.py
- TestWarningVisibilityCompactPlumbing
- test_properties_state.py
- .test_skip_non_host_lines
- Stale Running Cleanup
- TestMultiLineWarningContinuation
- JSON Output Renderer
- text.py
- TestPtyStreamParserWarningsList
- test_posix_callback.py
- format_tree_block
- merge_limit_args
- .update
- _compute_mode_label
- TestVerboseDiagnostics
- TestVerboseAlwaysMsgDisplay
- _build_compact_renderer
- json.py
- Get All Actions
- Panel Toggle Keybindings
- Shift Modifier Keybindings
- unit/test_no_record.py
- Get Keybinding Function
- _FakeSink
- TestAnsiblePosixAvailability
- Ansible Core Version Check
- session_id_completer
- Profile Tracemalloc Wiring
- TestAppConfigFieldTypes
- test_invariants_session_roundtrip.py
- Password Prompt Handling
- Compact Password Passthrough
- TestPasswordPromptHandling
- cli_main
- list_sessions
- Width 60-79 Truncation
- .test_exit_code_syntax_error_output
- Warning Pattern Classification
- collect_failed_hosts
- Status Bar Formatting
- Project Architecture Overview
- Panel Refresh Snapshot
- Completion State Labels
- .test_handle_password_prompt_returns_empty_on_keyboard_interrupt
- TestCrossPlayLookupIsolation
- Tree Projection Formatters
- TestConfigFieldValidation
- TestMixedStreamHandling
- TestMultiPlayTruncationWithRoleFooters
- TestCompactModePasswordPassThrough
- CLI Framework Architecture
- TUI Widget Framework
- Rich Display Backend
- TestMultiplePlays
- TestWarnings
- TestRewindCorrectness
- Task Tree Navigation
- TestLogging
- Terminal Size Check
- Watchdog Timer
- Cancellation Timer
- TestFilterPanelTextFilter
- Ansible Args Validation
- format.py
- Keybinding Conflict Validation
- test_rerun_cli.py
- Keybinding Context Coverage
- TestV2PlaybookOnStatsCrossCheck
- test_run_state_set_caps.py
- load_config
- Monochrome Terminal Fallback
- TestTerminalSizeCheck
- Renderer Architecture
- Parser Architecture
- test_error_handling.py
- Tree Preservation On Cancel
- run_state_status_counts
- TestDeprecationWarnings
- test_diagnostics.py
- Core Tree Icons
- completion_snippet
- _make_state_with_stale_running
- Crash Recovery Stay Open
- Stderr Capture Handling
- TestAsyncPollDoesNotLeakDictIntoLoopItem
- Compact Display Sizing
- TestAppConfigYamlFile
- TestConfigFromEnvironment
- TestRedactionCustomPatterns
- .test_recap_lines_captured
- TestYesFlag
- test_prior_run_loop_totals_injection.py
- TestCaptureSetupFlag
- test_incremental_counters.py
- State Transition Validation
- TestMissingAnsiblePlaybook
- _visible_projection
- TestHideWarningsFlag
- Core Domain Architecture
- TestReplayDispatch
- TestTreeKindIncludesMore
- .on_list_view_highlighted
- TestWatchdogTimer
- Shell Completion Installation
- test_config.py
- .test_parser_detects_changed_status
- TestFormatFlag
- TestCoreModuleStructure
- .test_empty_playbook_no_plays
- Pre-commit Style Hooks
- TestNoRecordParserFlag
- test_skipped_tasks
- test_warning_color.py
- event_play_start
- Crash Recovery Notification
- .test_hide_state_rejects_unknown_value
- .test_hide_state_all_valid_values
- source_hash
- Exit Code Constants
- _compute_tree_budget
- Stderr Capture Handling
- TestConfigPathFlag
- TestRendererProtocolPasswordHandling
- .test_hide_state_does_not_appear_in_ansible_args
- .test_hide_state_mixed_append_and_comma
- .test_hide_state_rejects_unknown_in_comma_separated
- .test_hide_state_case_insensitive_ok
- post-commit-graphify
- post-commit
- .test_hide_state_case_insensitive_mixed
- TestCompactModePathUnchanged
- test_completion.py
- .test_play_names_extracted
- Host Set Collection
- Compact Renderer Module
- Exit Code Derivation
- .test_hide_state_default_is_empty
- .test_hide_state_case_insensitive_all_upper
- Secret Redaction Layers
- models.py
- TestCaptureVerboseFlag
- TestNoFailedHintFlag
- TestHideDeprecationsFlag
- Become Password Prompt
- Large Playbook Performance
- JSONL Line Stream
- _HideStateAction
- .test_hide_state_typo_suggests_failed
- .test_hide_state_random_garbage_no_suggestion
- .test_hide_state_error_includes_choices
- .test_create_parser_has_playbook_positional_arg
- .test_playbook_positional_argument_required
- .test_verbose_flag_exists
- Status Bar Duration Format
- TDD OODA Methodology
- Password Prompt Heuristics
- .test_short_v_does_not_set_aom_verbose
- .test_verbose_flag_defaults_false
- .test_help_displays_usage
- .test_help_shows_flags
- .test_unknown_args_passed_through
- Multi-Host Mixed Fixtures
- Cancellation Test Fixtures
- Core Module Purity Rule
- Pydantic App Config
- inspect_model.py
- Inspect CLI Module
- Install Hooks Script
- _build_rerun_command
- test_parser_orjson_swap.py
- test_session_store_async_write.py
- Runner Skipped Event
- rerun/cli.py
- Role Grouping Test
- Task Liveness Indicator
- All Skipped Fixture
- All Unreachable Fixture
- Dry-Run Check Fixture
- Empty Run Fixture
- Rerun Command Feature
- Shell Tab Completion
- Output Format Option
- JSON Renderer Module
- Multiple Plays Fixture
- Ansible AOM Project
- Playbook Failed Fixture
- JSONL Carry Buffer
- Core Parser Module
- Compact Display Module
- Terminal Degradation
- Single Task OK Fixture
- Status Bar Display
- Core Tree Module
- Strategy Free Tree View
- Unknown Event Fixture
- test_icons.py
- test_pause_lingering_cleanup.py
- TestClassifierRules
- DOCUMENTATION CHECKLIST (added per user question 2026-06-30)
- QC REVIEW (grumpi-qa) — 2026-06-30
- test_completion_summary.py
- format_age
- _run_cli
- test_history_loop_totals.py
- IO
- TestHostExtraction
- Q&A log
- TestClassifyEmpty
- Top-level .md files (6 to update)
- CallbackModule
- TestClassifyWarning
- Appendix: Anchor research notes
- ._render_status_panel
- TestClassifyError
- TestClassifySshDebug
- TestLevelMap
- TestFirstMatchWins
- test_replay_determinism.py
- test_password.py
- TestClassifyPrompt
- 11. CLI flags & config (answers Q33–Q36, plus Q4.2 refactor)
- core/redaction.py (secret sanitiser)
- graphify-refresh.sh
- pre-commit-wrapper.sh
- aom_jsonl callback plugin
- _format_loop_item_line
- pre-commit
- pre-push
- callbacks/__init__.py
- ansible_aom/compact/__init__.py
- log_filter.py
- drivers/__init__.py
- formats/__init__.py
- inspect/__init__.py
- renderer/__init__.py
- rerun/__init__.py
- schemas/README.md
- ansible_aom/tui/__init__.py
- screens/__init__.py
- deprecation_warning_line
- event_playbook_start
- event_runner_failed
- event_runner_failed_ignore
- event_runner_ok
- event_runner_skipped
- event_runner_start
- event_runner_unreachable
- event_stats
- event_task_start
- jsonl_line
- list_tasks_output
- password_prompt_become
- password_prompt_ssh
- password_prompt_vault
- play_definition
- task_definition
- warning_line
- recap_line
- __init__.py
- cleanup.sh
- cleanup.sh
- .test_running_has_four_animation_frames
- .test_running_color_is_cyan
- .test_completed_icon_same_as_ok
- TDD-first hard rule
- ansible/preflight.py (parallel preflight)
- ansible/runner.py (run_playbook)
- compact/renderer.py (CompactRenderer)
- cli.py composition root
- core/heartbeat.py (HeartbeatTracker)
- core/models.py (domain entities)
- core/overhead.py (OverheadStats)
- core/parity.py (renderer-agnostic dict)
- core/parser.py (PtyStreamParser)
- core/state_machine.py (ExecutionState FSM)
- core/tree.py (TreeProjection)
- drivers/protocol.py (EventSource Protocol)
- Gap refactor punch list (§7)
- formats/json.py (JsonRenderer)
- CI layering enforcement (test_layering.py)
- drivers/live.py (LiveDriver)
- Pure domain, no I/O principle
- Pure formatting separated from lifecycle
- renderer/protocol.py (Renderer Protocol)
- drivers/replay.py (ReplayDriver)
- session/store.py (SessionManager)
- session/summary.py
- TDD with strict OODA loop
- tui/app.py (AOMApp)
- Two-port architecture (Renderer + EventSource)
- Dirty-flag render throttle
- Tree height-budget pruning (clamp 5..25)
- Diagnostics lifecycle marks (preflight, spawn, first-event, etc.)
- orjson parse-path swap
- Session ID footer on run termination
- Autouse isolated_state_dir fixture
- TUI / text-mode parity enforced via core.inspect_model
- CompactRenderer
- Item event envelope schema (v2_runner_item_on_ok/failed/skipped)
- Graceful fallback to ansible.posix.jsonl
- loop_totals (task_key -> host -> item_count)
- PriorRun (with loop_totals)
- PtyStreamParser
- runner.py
- Session sink (event recorder)
- StatusCounts.add_event (ignores item events)
- _streamed_loop_items dedup set
- TaskRunState (per-host loop counter)
- TreeProjection (TUI)
- compact/renderer.py
- In-flight task credit
- Pace clamp [0.2, 5.0]
- prior_wall_total_s
- remaining_seconds display segment
- RunEstimate dataclass
- Segmented pace (fixed floor + variable)
- session/history.py
- task_wall_s (per-task wall duration map)
- Warmup gate (10% prior wall, >=2 matched tasks)
- _build_rerun_command(session, hosts)
- cli.py: aom rerun dispatcher branch (sys.argv[1]=='rerun')
- collect_failed_hosts(session) -> set[str]
- collect_unreachable_hosts(session) -> set[str]
- _compose_host_set(session, failed, unreachable, changes_only)
- _confirm(playbook, args, host_count, assume_yes, input_fn)
- src/ansible_aom/core/session.py — pure helpers
- _create_parser() — argparse builder for 'aom rerun'
- _default_runner() — lazy-import renderer + run_playbook
- main() — orchestrate resolve → load → compose → confirm → run
- _require_ansible_args(session, session_id) — schema-1.1 guard
- src/ansible_aom/rerun/cli.py
- _resolve_session_id(state_dir, session_id)
- run_playbook(playbook, ansible_args, renderer)
- _strip_limit_args(args)
- tests/unit/test_rerun_cli.py
- tests/integration/test_rerun.py
- inspect/cli.py: _build_parser() factory
- src/ansible_aom/completion.py
- completion_snippet(shell) -> str
- --install-completion <shell> CLI flag
- session_id_completer(prefix, parsed_args, state_dir, **kwargs)
- SUPPORTED_SHELLS = ('bash','zsh','fish')
- create_renderer(tui_mode, is_tty, format)
- cli.py: --format flag with --tui mutual exclusion
- HostCounts(ok, changed, failed, unreachable)
- JsonRenderer (Renderer Protocol impl)
- RenderFormat = Literal['compact','json']
- RunSummary (Pydantic schema_version=1)
- TaskFailure(host, task, msg)
- F1 Live TUI Widget Refresh Implementation Plan
- F2 Replay + F3 --no-record Implementation Plan
- F4 aom rerun Implementation Plan
- Pre-Flight --list-tasks/--list-hosts Implementation Plan
- JsonLineStream.feed_line(line) -> list[dict]
- JsonLineStream (carries partial JSONL lines)
- RunState.handle_event (unknown event fall-through pin)
- Display._degraded: bool
- Display._degraded_warning_printed: bool
- Display (compact live panel)
- Display.start/update force_size kwarg (test seam)
- MINIMUM_COLUMNS = 80
- MINIMUM_LINES = 24
- MINIMUM_SIZE = (80, 24)
- Live run data flow
- Compact refresh strategy (4 FPS)
- include_tasks dynamic expansion
- ExecutionState 8-state machine
- Exit codes (0/1/2/127/130)
- --hide-state flag (compact mode only)
- Session diff (UUID→path→name matching)
- 10 JSONL event types
- Memory bounds (MAX_PLAYS/TASKS/HOSTS)
- PASSWORD_PATTERNS list
- Parallel --list-tasks/--list-hosts preflight
- Pydantic AppConfig schema
- 4-layer secret redaction
- create_renderer factory function
- Role grouping (5+ threshold)
- Session recording to .aom artifacts
- Status enum (PENDING/RUNNING/OK/CHANGED/FAILED/SKIPPED/UNREACHABLE)
- Strategy detection (linear vs free)
- 3-phase PTY stream parsing
- Terminal 24x80 minimum + signals
- Two-level truncation footers
- WarningType enum
- ignore_errors test playbook
- Password prompt test playbooks
- Redaction test playbooks (L1-L4)
- AppConfig (Pydantic BaseSettings)
- CLI test cases (TC-001 to TC-028)
- Debug Panel
- JSONL event test cases (TC-072 to TC-081)
- Filter Panel
- handle_event Dispatcher
- _handle_v2_playbook_on_play_start
- _handle_v2_playbook_on_start
- _handle_v2_playbook_on_task_start
- _handle_v2_runner_on_ok
- _handle_v2_runner_on_skipped
- _handle_v2_runner_on_start
- _handle_v2_runner_on_unreachable
- HostRunState
- Changed Icon ◆ (yellow)
- Failed Icon ✖ (bold red)
- OK Icon ● (green)
- Pending Icon □ (dim)
- Running Icon ◐ (animated 4 FPS)
- Skipped Icon ○ (dim outline)
- Unreachable Icon ⊝ (dim red)
- Log Panel (TUI Component)
- Parser test cases (TC-107 to TC-121)
- PlayDefinition
- PlayRunState
- PtyStreamParser
- RedactionConfig
- Redaction test cases (TC-153 to TC-162)
- Renderer test cases (TC-029 to TC-066)
- RoleGroupDefinition
- RunState (Top-level State Container)
- Session Diff Command
- Session Inspect Commands
- State Machine (8 States)
- State machine test cases (TC-128 to TC-142)
- Status Enum (7 values)
- Summary Panel
- TaskDefinition (dataclass)
- TaskRunState
- Tree View (TUI Component)
- VALID_TRANSITIONS dict
- WarningEntry (dataclass)
- WarningType Enum
- WarningsConfig
- src/ansible_aom/compact/renderer.py
- format_host_rows(host_rows, width)
- format_tree_block(tree_lines, width)
- HostRow(hostname, counts, worst_status, current_task, current_elapsed_s)
- TreeProjection.from_run_state(state)
- CompactRenderer._render_status_panel (was _render_status_bar)
- RoleGroupDefinition (preflight role grouping)
- TreeProjection._task_line(task, depth)
- TreeProjection._task_role(task_name) -> str | None
- TreeLine(depth, kind, label, glyph, status, elapsed_s)
- TreeProjection._WORST_STATUS_PRIORITY

## God Nodes (most connected - your core abstractions)
1. `RunState` - 581 edges
2. `TaskDefinition` - 357 edges
3. `CompactRenderer` - 338 edges
4. `PtyStreamParser` - 338 edges
5. `PlayDefinition` - 323 edges
6. `HostRunState` - 285 edges
7. `Status` - 273 edges
8. `PlayRunState` - 252 edges
9. `TaskRunState` - 244 edges
10. `RoleGroupDefinition` - 152 edges

## Surprising Connections (you probably didn't know these)
- `test_assemble_definitions_empty_inputs_returns_empty_list()` --calls--> `assemble_definitions()`  [INFERRED]
  tests/unit/test_preflight.py → src/ansible_aom/ansible/preflight.py
- `test_format_status_bar_ascii_mode_uses_ascii_warning_glyph()` --calls--> `format_status_bar()`  [INFERRED]
  tests/compact/test_ascii_fallback.py → src/ansible_aom/compact/format.py
- `test_format_status_bar_ascii_mode_uses_pipe_separator()` --calls--> `format_status_bar()`  [INFERRED]
  tests/compact/test_ascii_fallback.py → src/ansible_aom/compact/format.py
- `test_format_status_bar_unicode_mode_keeps_unicode_glyphs()` --calls--> `format_status_bar()`  [INFERRED]
  tests/compact/test_ascii_fallback.py → src/ansible_aom/compact/format.py
- `test_format_status_bar_includes_task_progress_when_total_set()` --calls--> `format_status_bar()`  [INFERRED]
  tests/compact/test_task_progress.py → src/ansible_aom/compact/format.py

## Import Cycles
- None detected.

## Communities (667 total, 307 thin omitted)

### Community 0 - "HostRunState"
Cohesion: 0.02
Nodes (168): format_failure_recap(), Render a one-shot startup summary of plays/tasks/hosts from preflight.      Prin, Build per-failure lines naming the host and task that went wrong.      Returns o, determine_exit_code(), Determine exit code from RunState.      Traverses the RunState to determine the, HostRunState, PlayRunState, Runtime state for a task execution on a host (State class). (+160 more)

### Community 1 - "PtyStreamParser"
Cohesion: 0.02
Nodes (60): PtyStreamParser, 3-phase parser for ansible-playbook PTY output., Handle PLAY RECAP output lines., True if the most recent classified output line was plaintext.          A JSONL e, Clear pending password prompt after handling., SSH password prompt is detected., BECOME password prompt is detected., Password prompt can be cleared. (+52 more)

### Community 2 - "RunState"
Cohesion: 0.01
Nodes (139): FixtureRequest, Any, Complete execution state (State class)., Advance the private tree-shape revision counter.          TreeProjection instanc, (Re)populate the definition lookup indexes.          Called whenever ``definitio, Update the dynamic-expansion cursor for an arriving task.          Matches the r, Graft every other task of *role_name* as a sibling of the         just-grafted c, RunState (+131 more)

### Community 3 - "AppConfig"
Cohesion: 0.09
Nodes (18): AppConfig, BaseSettings, Application configuration loaded from YAML and CLI.      YAML loading is handled, Tests for AppConfig model - TC-263 to TC-275., TC-263: AppConfig has default log_max_lines=50000., TC-264: AppConfig has default session_keep_count=100., TC-265: AppConfig has default session_keep_days=30., AppConfig has default StatusBarConfig. (+10 more)

### Community 4 - "test_pty_stream.py"
Cohesion: 0.05
Nodes (26): Unit tests for PTY stream parsing.  Covers TEST_SPECIFICATION.md Sections 5.5, 5, TC-140: PLAY RECAP pattern detection., TC-140: PLAY RECAP line matches pattern., PLAY RECAP requires minimum 5 asterisks., PLAY RECAP with fewer than 5 asterisks not matched., PLAY RECAP with many asterisks matched., PLAY RECAP in PRE_RUN_PROMPTS phase routes differently., Multiple recap lines collected in POST_RUN_RECAP. (+18 more)

### Community 5 - "StatusBarConfig"
Cohesion: 0.01
Nodes (100): Status bar configuration., StatusBarConfig, Unit tests for TUI panels (Sections 7.2-7.6 of TEST_SPECIFICATION.md).  Test cas, TC-280: Regex search matches patterns., Tests for filter panel state persistence., Filter state is isolated from other instances., Filter state can be reset to show all., TC-280 edge case: Invalid regex patterns handled gracefully. (+92 more)

### Community 6 - "load_session"
Cohesion: 0.09
Nodes (56): build_index(), build_indexes(), ensure_index(), _events_path(), events_stat(), find_task_id_by_name(), index_is_fresh(), index_path() (+48 more)

### Community 7 - ".from_run_state"
Cohesion: 0.03
Nodes (48): Running spinner (◐→◓→◑→◒) animates across renders.  Previously ``format_tree_blo, Existing callers that don't pass animation_frame still render., _running_state(), test_default_frame_still_works_for_backward_compat(), test_spinner_glyph_changes_with_animation_frame(), _hostless_task_state(), Regression tests for hostless meta-task projection., test_meta_task_does_not_synthesize_fake_host_leaves() (+40 more)

### Community 8 - "Display"
Cohesion: 0.05
Nodes (26): Display, Manages the nom-style compact display.      Owns stdout for the duration of the, Initialize the display manager.          Args:             is_tty: Whether stdou, Begin owning the bottom of the terminal.          Args:             force_size:, Pipe/CI mode has its own no-op behaviour and shouldn't gain         the warning, In degraded mode update() drops the status content (we don't     flood stdout wi, No panel was ever shown, so stop() must not emit clear/show         sequences th, `force_size` is the test injection seam for the size detection     that Task 2 w (+18 more)

### Community 9 - "WarningType"
Cohesion: 0.03
Nodes (69): Enum, Warning classification type., WarningType, JsonLineStream, PreParseResult, Set handler for non-JSON lines., Result from pre-parse phase (--list-tasks + --list-hosts)., Parses JSON lines from a mixed JSON/plaintext stream.      Pexpect can split a J (+61 more)

### Community 10 - "test_concurrent_inspect.py"
Cohesion: 0.16
Nodes (18): Event, _build_session(), Any, Path, Concurrency test: writer + concurrent inspect (Phase 8 / Task 8.4).  What this t, Create ``<state_dir>/<session_id>/`` with a minimal meta.json.      Mirrors the, Append events to *events_file* at ~1000/sec until *stop* is set.      The writer, Invoke ``aom inspect --text --state-dir <state>`` and return the exit code. (+10 more)

### Community 11 - "TaskDefinition"
Cohesion: 0.02
Nodes (75): Static task info from --list-tasks (Definition class)., TaskDefinition, group_roles(), Group consecutive same-role tasks (5 or more) into RoleGroupDefinition.      Arg, Unit tests for dynamic counter accuracy (TC-310–TC-317).  Tests that ``_count_ta, Without include cache, denominator = max(preflight, runtime)., import_tasks are expanded by --list-tasks — they appear as regular     static Ta, A play with RoleGroupDefinition entries and a TaskDefinition that     has dynami (+67 more)

### Community 12 - "CompactRenderer"
Cohesion: 0.02
Nodes (98): CompactRenderer, ANSI-based compact renderer satisfying the Renderer Protocol.      Implements th, R2: cap long msg output so a runaway host doesn't stall the renderer.  A task th, Per-item ``v2_runner_item_on_failed`` messages are also capped.      A looped ta, Sub-cap messages must be passed through unchanged., R2 spec literal: 1 MB msg is logged with the truncation marker.      A host retu, test_failed_msg_truncated_above_cap(), test_item_failed_msg_truncated_above_cap() (+90 more)

### Community 13 - "parse_list_hosts_output"
Cohesion: 0.05
Nodes (22): parse_list_hosts_output(), Parse --list-hosts output into structured data.      Returns list of dicts with, TC-149: parse_list_hosts_output extracts hostnames per play., TC-087: Parallel parsing produces same results as sequential., TC-089: When --list-hosts returns empty, hosts will come from         runner eve, TC-089: Partial/corrupted output still returns any parseable plays., TC-090: Warning message when host resolution fails., TC-101: hosts: 'all' returns all inventory hosts. (+14 more)

### Community 14 - "SessionManager"
Cohesion: 0.03
Nodes (77): Any, Path, Enqueue a serialised JSONL line. Returns immediately.          Drops the line an, Manages session recording and artifact creation.      Sessions are stored during, Return the session's async writer, creating it on first use., Reason string if the session's background writer hit a disk error.          Retu, Enqueue a JSONL event for the background writer.          R16: returns immediate, Classify *line* and persist it as an ``aom_stderr_line`` event.          Phase 4 (+69 more)

### Community 15 - "_play_start"
Cohesion: 0.11
Nodes (18): _play_start(), Terminal runner events must update host state even when ids mismatch.  Real-worl, The fallback must cover every terminal handler, not just ok., An ok carrying a play.id we never saw must still land on the         task that o, Two same-named tasks in one play: the fallback must pick the         one still r, No preflight definitions (or no name match): the second         task_start under, Under strategy free, per-host runner_on_start is the start         signal; synth, A host whose latest result is UNREACHABLE or FAILED is removed         from the (+10 more)

### Community 16 - "_BoundedDict"
Cohesion: 0.15
Nodes (12): dict, JsonlHostResult, JsonlPlay, Subset of the ``play`` field on ``v2_playbook_on_play_start`` and friends., Per-host result embedded in ``hosts`` dicts on ``v2_runner_on_*``.      The shap, _BoundedDict, _BoundedSet, _parse_play_window_start() (+4 more)

### Community 17 - "RedactionConfig"
Cohesion: 0.04
Nodes (54): _ansible_event_with_res(), custom_ansible_key_pattern(), default_config(), generic_secret_key_pattern(), Any, RedactionConfig, Integration tests for the 4-layer redaction pipeline with realistic Ansible even, Layer 1 — when ``res._ansible_no_log=True`` the whole result is censored. (+46 more)

### Community 18 - "parse_list_tasks_output"
Cohesion: 0.04
Nodes (24): parse_list_tasks_output(), Parse --list-tasks output into structured data.      Returns list of dicts with, TC-114: import_tasks IS expanded — tasks appear inline in --list-tasks., TC-115: Block tasks are flattened — no block container in output., TC-116: pre_tasks and post_tasks appear as regular tasks., TC-117: Unnamed tasks use their module/action as the name., TC-116: Play names may contain special section designations., TC-118: Parser only receives stdout content. (+16 more)

### Community 19 - "create_parser"
Cohesion: 0.07
Nodes (15): create_parser(), Create the argument parser for the AOM CLI.      Returns:         Configured Arg, --hide-state ok sets hide_state=["ok"]., --hide-state can be specified multiple times., --hide-state ok,skipped splits into ["ok", "skipped"]., Single value still works without any comma., --hide-state ok,OK stores both tokens; dedup happens downstream., Typo 'skip' suggests 'skipped'. (+7 more)

### Community 20 - "TreeProjection"
Cohesion: 0.04
Nodes (82): iter_preflight_task_defs(), Yield preflight task definitions in display order with effective role path., Strip the ``"role : "`` prefix that ansible adds to task names at     runtime. P, Infer an ``include_role``-style runtime role from a task name.      Accepts simp, runtime_role_from_task_name(), strip_role_prefix(), _bump(), _collapse_role_path() (+74 more)

### Community 21 - "TestJsonLineStreamSurvivesMojibake"
Cohesion: 0.15
Nodes (11): _decode_pexpect_style(), Batch E item #10a — R6 encoding robustness.  The PTY-side decode (``pexpect.spaw, U+FFFD replacement chars in a plaintext warning line must flow         through `, Mimic pexpect's ``codec_errors='replace'`` decode., ``JsonLineStream.feed_line`` must not crash on mojibake interleaved     with rea, A UTF-8 BOM (``\\ufeff``) mid-stream must not corrupt subsequent         lines., Latin-1 bytes (``b'\\xe9\\xe8\\xea'`` for ``éèê``) interpreted         as UTF-8, A truncated UTF-8 lead byte (``b'\\xc3'``) followed by a real         JSONL even (+3 more)

### Community 22 - "build_run_config_key"
Cohesion: 0.07
Nodes (61): build_run_config_key(), Pure normalization of an ansible-playbook invocation into a hashable key.  The :, Hashable normalization of an ansible-playbook invocation.      Equality semantic, Split a comma-separated flag value, strip whitespace, drop empties, sort., Build a :class:`RunConfigKey` from a playbook path and ansible argv tail.      `, RunConfigKey, _split_csv_sorted(), find_previous_run() (+53 more)

### Community 23 - "OverheadStats"
Cohesion: 0.15
Nodes (14): OverheadStats, Per-task overhead summary.      ``None`` fields signal "insufficient data": eith, _fmt_seconds(), format_overhead_section(), Display helpers for AOM inspect output.  Houses both the overhead-stats summary, Render durations: sub-second as ms, anything else as s with one decimal., Render the per-task overhead summary.      Returns ``None`` when there's literal, Tests for the overhead-section formatter in inspect display. (+6 more)

### Community 24 - "Inspect CLI Commands"
Cohesion: 0.09
Nodes (33): _aom_jsonl_item_event(), _changed(), _failed(), _logged(), _multi_host_ok(), _ok(), _play_start(), Tests for --hide-state gating in CompactRenderer._emit_event_log.  When hide_sta (+25 more)

### Community 25 - "StatusCounts"
Cohesion: 0.05
Nodes (75): build_detail_block(), build_run_summaries(), build_run_summary(), build_task_tree(), Derive a ``RunSummary`` from a session dict (output of ``load_session``)., Map a list of session dicts to RunSummary, sorted newest-first by start_time., Aggregate status tally over (task × host) pairs.      Each ``v2_runner_on_*`` ev, Return a new StatusCounts with the bump for one runner event. (+67 more)

### Community 26 - "TaskTreeNode"
Cohesion: 0.03
Nodes (49): ComposeResult, EllipsisType, ListItem, ListView, RichLog, DetailBlock, Per-session view consumed by the Runs pane and the text-mode header., Hierarchical view of a session's tasks.      Levels: run → play → group → task → (+41 more)

### Community 27 - "RoleGroupDefinition"
Cohesion: 0.05
Nodes (51): _collect_role_group_tags(), _count_role_group_tasks(), Recursively count leaf tasks inside a ``RoleGroupDefinition``.      ``RoleGroupD, _iter_task_def_tree(), Grouped role tasks when 5+ consecutive tasks share same role.      ``parent`` ca, Yield a TaskDefinition and all nested TaskDefinition.children in order., RoleGroupDefinition, count_leaf_tasks() (+43 more)

### Community 28 - "test_task_completion.py"
Cohesion: 0.13
Nodes (29): play_dead_hosts(), _play_def_for_state(), Resolve a runtime play to its preflight PlayDefinition.      Mirrors ``TreeProje, Hosts that went FAILED/UNREACHABLE anywhere in ``play``.      Ansible drops thes, True when every live target host has finished ``task_uuid``.      "Live targets", task_complete_on_all_targets(), _failed(), _ok() (+21 more)

### Community 29 - "InspectApp"
Cohesion: 0.04
Nodes (91): App, _copy_to_clipboard(), InspectApp, Index sessions that lack a fresh index, in the background.          Runs once at, Best-effort clipboard copy from within the running TUI.      Routes through Text, Three-pane inspector app., _find_tree_node_by_kind(), _no_load_debounce() (+83 more)

### Community 30 - "run_preflight"
Cohesion: 0.17
Nodes (21): Run --list-tasks and --list-hosts in parallel; return assembled result.      Bot, run_preflight(), _make_fake_ansible(), Path, Integration tests for run_preflight against a fake ansible-playbook., ANSIBLE_NOCOLOR=1 must be set so ansible-playbook emits stderr without colours., When ansible-playbook fails with an argparse error, only the error line surfaces, Args like -i inventory.ini must reach both subprocess invocations. (+13 more)

### Community 31 - "datetime"
Cohesion: 0.08
Nodes (24): datetime, Look up preflight resolved_hosts for a runtime play.          Preflight assigns, Handle v2_playbook_on_handler_task_start event (same as task_start)., Handle v2_runner_on_start event., Handle a per-item loop event (``v2_runner_item_on_*``).          These are addit, Extract the ``task`` field as a dict.          ansible.posix.jsonl may emit ``ta, Extract the ``hosts`` field as a dict.          mitogen bulk-reconnect events ca, Carry the host's recorded start_time into a terminal HostRunState.          Term (+16 more)

### Community 32 - "Error Handling Tests"
Cohesion: 0.04
Nodes (26): TC-367: FAILED icon uses red color., TC-368: UNREACHABLE status displays dim circle with dash (⊝)., TC-368: UNREACHABLE icon is valid Unicode character., TC-368: UNREACHABLE icon uses magenta color (per spec)., TC-369: Animation frames use quadrant icons ◐ ◓ ◑ ◒., TC-369: All RUNNING frames are valid Unicode characters., TC-369: Animation cycles in correct order: ◐ → ◓ → ◑ → ◒., TC-370: PENDING status displays dim empty square (□). (+18 more)

### Community 33 - "RedactionConfig"
Cohesion: 0.04
Nodes (44): _lower_set(), Layered secret redaction system (QC-002 rewrite, Phase 2 / Task 2.1).  This modu, Decide whether a dict KEY should be redacted by Layers 1+2.      Order of checks, Sanitize credentials in a single string (Layer 3).      Applies in order:     1., sanitize_string(), should_redact(), URL of form scheme://user:SECRET@host/ has SECRET removed by sanitize_string., CLI flag of form --password=SECRET has SECRET removed by sanitize_string. (+36 more)

### Community 34 - "Event Log Emission"
Cohesion: 0.09
Nodes (38): _changed(), _failed(), _last_print_log(), _last_summary_line(), _ok(), _play_start(), Tests for task summary status counts in CompactRenderer.  When a task completes,, Task with all-ok hosts shows '(2 ok)' in the summary. (+30 more)

### Community 35 - "_play_start"
Cohesion: 0.09
Nodes (28): _play_start(), Path, Unit tests for include_tasks dynamic expansion.  TC-094 / TC-095 from TEST_SPECI, Dynamic TaskDefinition copies play_id and play_order from the parent., TC-094: Several dynamic tasks under the same include_tasks parent., A second v2_runner_on_start for the same UUID must not graft twice., A subsequent matched preflight task replaces the parent cursor., Unknown task before any preflight match is left orphan (no graft, no crash). (+20 more)

### Community 36 - "List Tasks Output Parser"
Cohesion: 0.07
Nodes (15): Path, Tests for ``scripts/verify_anchors.py``.  The anchor checker is a pre-commit hoo, The extractor pulls every anchor token from a doc, including     backtick-wrappe, Validation must report the *first* broken anchor with a clear     message and th, ``verify_doc`` returns a list of broken-anchor messages and     should short-cir, ``main`` exits 0 on a clean doc and 1 on a broken anchor, with     a clear stder, The script must be smoke-runnable from the command line so the     pre-commit ho, The anchor grammar is narrow: ``path:line`` or ``path:line-line``. (+7 more)

### Community 37 - "TestWarningPatternsEdgeCases"
Cohesion: 0.06
Nodes (20): TC-502: WarningEntry source field for PTY stream., TC-502: WarningEntry from PtyStreamParser has source='controller'., TC-502: WarningEntry source defaults to empty string if not provided., TC-502: WarningEntry source can be explicitly set., Edge cases for warning pattern matching., Multiple [DEPRECATION WARNING]: lines are all classified correctly., Mixed WARNING and DEPRECATION lines classified correctly., Warnings before EXECUTION phase may not be captured. (+12 more)

### Community 38 - "TestPasswordPromptPTYIntegration"
Cohesion: 0.09
Nodes (12): TC-143: All PASSWORD_PATTERNS entries compile as valid regex., TC-143: All 10 documented password patterns present.          Ansible-native (7), TC-143: handle_password_prompt uses getpass.getpass for PTY integration., TC-143: The prompt text is passed to getpass for display on /dev/tty., TC-143: child param exists for interface compatibility but unused in compact mod, TC-143: child param accepted for TUI interface compatibility., TC-143: Cursor positioning escape sequence written before getpass., TC-143: EOFError from getpass returns empty string (user cancelled). (+4 more)

### Community 39 - "store.py"
Cohesion: 0.08
Nodes (23): parse_iso_timestamp(), datetime, Canonical ISO 8601 timestamp parsing for ansible-playbook JSONL events.  AOM rea, Parse an ISO 8601 timestamp string, tolerating the ``Z`` UTC suffix.      Args:, _parse_timestamp(), datetime, Replay a recorded AOM session through a Renderer (F2).  Both halves of the repla, Parse an ISO 8601 ``_timestamp`` field; return None when unparseable. (+15 more)

### Community 40 - "format_status_bar"
Cohesion: 0.05
Nodes (48): format_status_bar(), Format the status bar for compact mode display.      Args:         playbook: Pat, LivenessState, Snapshot of liveness at a query instant.      ``age_s`` is whole seconds since t, TestStatusBarMode, ANSI escape bytes are zero-width on screen — they must not push     a status lin, test_row_count_ignores_ansi_escape_sequences(), ``format_status_bar(colorize=True)`` wraps semantic segments. (+40 more)

### Community 41 - "RedactionConfig"
Cohesion: 0.05
Nodes (35): custom_config(), RedactionConfig, redact_dict() recursively redacts password fields., sanitize_string() removes credentials from strings., redact_event() applies all redaction layers to event., Tests for TC-161: CLI argument credential sanitization., TC-161: CLI credentials are sanitized., TC-161 edge case: Variant CLI formats. (+27 more)

### Community 42 - "Renderer"
Cohesion: 0.04
Nodes (29): LiveDriver — :class:`EventSource` that runs a real ``ansible-playbook``.  A thin, Drive ``renderer`` to completion and return the run's exit code.          Contra, Renderer factory for compact and JSON output., Protocol, Renderer Protocol — the display-side port of the architecture.  See ``ARCHITECTU, Optional. Provide stats from the most-recent matching prior run.          **Mand, Handle a new JSONL event from ansible.          **Mandatory.** Called once per e, Surface a warning or deprecation to the user.          **Mandatory for the compa (+21 more)

### Community 43 - "_handle_timeout_branch"
Cohesion: 0.07
Nodes (30): spawn, _consume_unread(), _handle_timeout_branch(), _peek_unread(), Return the unread PTY buffer without consuming it.      pexpect's ``buffer`` pro, Read and clear the unread buffer; return whatever was there., Handle a TIMEOUT in `_drive`. Return the new ``stall_count``.      Three cases,, _FakeChild (+22 more)

### Community 44 - "runner.py"
Cohesion: 0.03
Nodes (80): Profile, _build_command(), _bundled_callback_dir(), _bundled_connection_callback_dir(), _callback_env(), _default_session_dir(), _drive(), _feed() (+72 more)

### Community 45 - "TestTemplateVariableNameMismatch"
Cohesion: 0.12
Nodes (16): _play_def(), Regression tests for Jinja2 template variable names in preflight tasks.  ansible, Host leaves must appear under a running task whose preflight         name has {{, A task with {{ variable }} in preflight must not appear twice         in the tre, A role task with {{ variable }} must match the resolved runtime         name and, A preflight task with {{ variable }} that has completed at         runtime must, Regression: preflight name `Ensure {{ user }}'s home exists` must         match, Regression: preflight name `Deploy for {{ user }}!` must match         runtime n (+8 more)

### Community 46 - "test_callback_env.py"
Cohesion: 0.25
Nodes (4): Unit tests for the runner's stdout-callback selection.  AOM prefers its bundled, Task 5.3: the new connection-tracking callback ships in     ``src/ansible_aom/ca, TestBundledCallbackDir, TestBundledConnectionCallbackDir

### Community 47 - "Prompt Detection Heuristics"
Cohesion: 0.08
Nodes (11): classify(), Classify a single stderr line into a :class:`StderrEvent`.      Tries each rule, SSH agent / connect / retry / rc lines., This one is run-level (no host) — different from the rest of ssh_info., Lock + local connection + EXEC/PUT/FETCH lines., Vault password prompts + vvvvv vault debug., Misc diagnostics: config, plays, retry, syntax, host-pattern, debug, unknown., TestClassifyConnection (+3 more)

### Community 48 - "TestPlaintextLineHandling"
Cohesion: 0.17
Nodes (7): TC-142: _handle_plaintext classification., TC-142: Non-JSON, non-special lines go to plaintext_lines., Plaintext lines that aren't warnings are stored., Plaintext during EXECUTION phase collected., Lines classified correctly between warning vs plaintext., Plaintext lines maintain order., TestPlaintextLineHandling

### Community 49 - "test_overhead.py"
Cohesion: 0.15
Nodes (17): _playbook_start(), Tests for per-task overhead analysis (core/overhead.py).  The analyzer measures, Durations: 1, 2, 3, 4, 5 seconds — P25 = 2.0., ok / failed / unreachable / skipped all measure overhead — the         fork happ, Overhead is paid once per task wall-clock (hosts parallelize).         Floor=1s,, If our estimate exceeds wall-clock (rare, but possible with         very short r, Out-of-order timestamps (clock skew, replay artifacts)         shouldn't contrib, _runner_failed() (+9 more)

### Community 50 - "TestUngroupedRoleTasksInTree"
Cohesion: 0.08
Nodes (20): _play_def(), Regression tests for ungrouped role tasks in the tree view.  Ungrouped role task, Role label for ungrouped role must show the total task count         from defini, _task_role must return the role for ungrouped TaskDefinition entries,         no, When a running task is at the end of the definition list,         the stable par, Host leaf must appear under the running task within an         ungrouped role, e, Pending plays must also show ungrouped role tasks under role headers., A pending play with bare TaskDefinition entries that have role         set must (+12 more)

### Community 51 - "TestFilterPanelHostFilter"
Cohesion: 0.07
Nodes (17): Tests for host filter - TC-303., Sample tasks with hosts., TC-303: Host filter shows tasks for specified host., TC-303: Multiple hosts in filter matches any., TC-303 edge case: Host not in inventory shows empty., TC-303 edge case: Empty host input shows all tasks., Additional tests for search logic functions., Search finds partial matches within words. (+9 more)

### Community 52 - "history.py"
Cohesion: 0.11
Nodes (33): _build_prior(), _iter_completed_sessions(), _match_loose(), _mine_and_replace(), _mine_loop_totals(), _mine_task_wall(), _parse_iso(), PriorRun (+25 more)

### Community 53 - "App Config Model Tests"
Cohesion: 0.09
Nodes (41): _logged(), Tests for error message extraction from multiple result fields.  When a task fai, Fall back to ``stdout`` when all higher-priority fields are empty., When both ``msg`` and ``module_stderr`` are present, ``msg`` wins., Missing ``msg`` key entirely — falls back to ``module_stderr``., All error fields empty — ``FAILED!`` without ``=>`` tail., Long ``module_stderr`` is subject to ``_MSG_DISPLAY_CAP`` truncation., Primary ``msg`` field shown for unreachable. (+33 more)

### Community 54 - "RendererMirrorMachine"
Cohesion: 0.08
Nodes (14): RuleBasedStateMachine, Free-strategy entry point — task_id appears via runner_on_start., Quiet-period refresh; must not perturb any counter or index., HS-2: incremental counter == authoritative full-state walk., HS-2: ``_tasks_seen`` is the renderer-side denominator floor.          The statu, Every id we counted as completed must still exist in state., A task id in ``_completed_task_ids`` must have no RUNNING hosts.          Counte, HS-3: cached ``TreeProjection``, if any, points at the live state. (+6 more)

### Community 55 - "Debug Panel Widget"
Cohesion: 0.07
Nodes (32): _ansible_collection_paths(), _has_ansible_posix(), CompletedProcess, Path, Integration tests for include/import/role task variants.  Covers TC-330 through, TC-330 / TC-331: import_tasks tree rendering and counter accuracy., TC-330: import_tasks are expanded — all task names visible., TC-331: import_tasks counter = 4 runtime tasks. (+24 more)

### Community 56 - "Path"
Cohesion: 0.07
Nodes (29): _fake_pause_prompt_command(), Path, Integration tests for runner pause/vars_prompt handling (IP1, IP3).  These tests, vars_prompt's default format is ``[name]: `` with no custom text., (yes/no) and [y/N] style prompts get the interactive treatment., Simulate exactly what ansible.builtin.pause emits in production.      ansible de, Even when the prompt text doesn't include 'Press Enter',         the bracketed t, The variant the user actually hit in production.      ``ansible.builtin.pause`` (+21 more)

### Community 57 - "JsonlEvent"
Cohesion: 0.04
Nodes (50): Cap a JSONL ``msg`` field for live display.      R6: any lone-surrogate codepoin, Return the inline body for a verbose-always ok result, or ``None``.      Mirrors, _truncate_msg(), _verbose_ok_body(), _BoundedSet, _extract_error_msg(), _first_line(), set (+42 more)

### Community 58 - "RunDiagnostics"
Cohesion: 0.11
Nodes (14): get_last_run_diagnostics(), lifecycle_mark(), Record a named timestamp (monotonic nanoseconds).      Always-on: the cost is on, Mutable per-run accumulator threaded through ``run_playbook``.      Captures the, Record total preflight elapsed time (parallel list-tasks + list-hosts)., Publish the just-finished run's diagnostics for post-hoc readers.      Phase 5 u, RunDiagnostics, set_last_run_diagnostics() (+6 more)

### Community 59 - "Total Task Counting"
Cohesion: 0.21
Nodes (15): Path, Phase 1 / Task 1.1: meta.json `_schema_version` bump.  Per `.sisyphus/plans/v1-v, End-to-end: SessionManager writes v2; load_session returns v2., ``start_session`` persists ``_schema_version: 2`` immediately.      The field is, ``end_session`` does not strip the schema field added at start., The bump is additive: every v1 field is still present and unchanged.      Guards, ``load_session`` surfaces the new field on the returned dict., A v1 legacy ``meta.json`` (no ``_schema_version`` field) loads cleanly     and r (+7 more)

### Community 60 - "_fresh_display"
Cohesion: 0.17
Nodes (9): _fresh_display(), _pin_window_closed(), Cross-event log batching — cap frame rate during event storms.  Per-event batchi, The quiet-period tick is the backstop flush: the last lines of         a burst m, Force 'a flush just happened' so subsequent print_log calls buffer., TestDrainOnOtherFrames, TestLeadingEdgeFlush, TestNonTtyUnaffected (+1 more)

### Community 61 - "test_tree_render.py"
Cohesion: 0.11
Nodes (27): _full_panel(), Snapshot tests for the compact renderer's tree + host-row block.  These pin the, Regression guard: spacing between count cells and the suffix is     two spaces (, Regression guard: when colorize=False, `_truncate_visible` must     not inject `, Regression guard: host children render WITHOUT a branch glyph,     matching the, When no task is RUNNING, the panel shows only the status bar —     no tree, no h, The status bar must be the BOTTOM line of the panel so it stays     anchored at, Helper: render the assembled panel against a fixed 80-col terminal,     24-row b (+19 more)

### Community 62 - "tests/conftest.py"
Cohesion: 0.25
Nodes (7): deprecated_removed_line(), event_runner_ok_changed(), list_hosts_output(), Shared test fixtures for AOM test suite.  CRITICAL: All fixtures are IMMUTABLE., v2_runner_on_ok event with changed=True., Ansible removed feature deprecation line., Sample --list-hosts output.

### Community 63 - "HeartbeatTracker"
Cohesion: 0.08
Nodes (33): HeartbeatTracker, Pure liveness state machine for the currently running ansible task.  Distinguish, Tests for HeartbeatTracker (core/heartbeat.py).  The tracker derives a three-lev, The real-world brew-install case: one byte at task start, then     silence. The, User-facing case: ansible-playbook is silent for >5s but its CPU     sampler sho, An ``active=False`` sample is informational ('CPU was idle') and     must not sa, CPU samples older than the live window stop counting as 'recent'.     They can s, ``reason`` annotates why the level is what it is. Backwards-compat:     existing (+25 more)

### Community 65 - "Playbook Run Integration Tests"
Cohesion: 0.15
Nodes (20): _all_text(), _aom_jsonl_item_event(), _async_poll_payload(), _item(), _item_event(), _logged(), _loop_ok(), Live per-item loop streaming in the compact log.  With the bundled ``aom_jsonl`` (+12 more)

### Community 66 - "test_tree_classify_and_role_labels.py"
Cohesion: 0.07
Nodes (20): Regression tests for tree projection bugs:  1. _classify must treat RUNNING task, Regression guard: role labels in the runtime play must show the     total task c, Build a state where one role task is completed and another is         running. T, When a role has 2 tasks and 1 is completed, the runtime role         label shows, When all role tasks are completed (none running, none pending),         the runt, Regression guard: a task with RUNNING status but no host entries yet     (e.g. b, Regression for the '(M remaining) goes UP as tasks complete' bug.          The r, TC-300: _task_role must index TaskDefinition.children (grafted     include_tasks (+12 more)

### Community 67 - "test_inspect_debug.py"
Cohesion: 0.20
Nodes (16): format_diagnostics_section(), Any, Render the ``diagnostics.json`` payload as a plain-text section.      Returns a, Path, Phase 6: ``aom inspect --debug`` prints diagnostics.json contents.  Spec: docs/s, ``--debug --json`` writes the diagnostics record as a single JSON     object for, test_format_diagnostics_recording_disabled_surfaces_reason(), test_format_diagnostics_section_with_full_record() (+8 more)

### Community 68 - "_session"
Cohesion: 0.16
Nodes (12): collect_changed_hosts(), collect_unreachable_hosts(), create_session_summary(), Any, Pure post-mortem projections of a loaded session.  These functions take a sessio, Return the set of hostnames that had at least one changed task.      Pure: scans, Create a human-readable summary of a session.      Args:         session: Sessio, Return the set of hostnames that hit ``v2_runner_on_unreachable``.      Pure: sa (+4 more)

### Community 69 - "RedactionConfig"
Cohesion: 0.04
Nodes (41): Configuration management for AOM.  This module defines Pydantic models for confi, Secret redaction configuration.      Layered model (see ``core/redaction.py``):, RedactionConfig, default_config(), Comprehensive unit tests for password/secret redaction.  This module tests the 4, Tests for TC-155: PASSWORD_MATCH regex pattern matching., TC-155: Regex matches known password field name variants., TC-155 edge case: Fields containing 'pass' that match regex but aren't passwords (+33 more)

### Community 70 - "TestURLCredentialSanitization"
Cohesion: 0.25
Nodes (5): Tests for TC-160: URL credential sanitization., TC-160: URL credentials are sanitized., TC-160 edge case: URL-encoded passwords., TC-160 edge: URLs without credentials remain unchanged., TestURLCredentialSanitization

### Community 71 - "renderer.py"
Cohesion: 0.15
Nodes (31): Compact renderer — Rich Live lifecycle and per-event log emission.  Pure formatt, add_completed(), add_in_flight(), project_remaining(), Pure run-duration projection from a prior run's per-task profile.  The "Last run, Fold a just-completed task into ``progress`` by its prior bucket.      A path ab, Top up ``progress`` with a still-running task's partial progress.      Credits `, Project remaining wall-clock seconds, or ``None`` if not estimable.      ``None` (+23 more)

### Community 73 - "Host Result Hide Filter"
Cohesion: 0.09
Nodes (13): True iff the given JSONL event type should be suppressed from the live log., should_hide_event(), Empty hide set never suppresses., Hiding only 'failed' does not affect v2_runner_on_ok., v2_runner_item_on_ok also covers changed results., v2_runner_on_start is a lifecycle event, not a result event., Empty string event type is never hidden., If any hide state matches, the event is hidden. (+5 more)

### Community 74 - ".handle_password_prompt"
Cohesion: 0.13
Nodes (11): TC-145: Verify password masked by getpass, sent to PTY.      In compact mode, th, TC-145: getpass.getpass is used which masks input (no echo)., TC-145: The prompt text (e.g., 'Vault password: ') is shown to user via getpass., TC-145: All password prompt types use the same terminal pass-through path., TC-145: Password returned as a plain string for PTY sending., TC-145: Passwords with special characters handled correctly., TC-145: Passwords with unicode characters handled correctly., TC-145: Empty password (user pressed Enter) returned as empty string. (+3 more)

### Community 75 - "Hide State Normalization"
Cohesion: 0.16
Nodes (15): Replay ``session_id`` from ``session_dir`` through ``renderer``.      Args:, replay_session(), _make_session(), Path, Unit tests for F2 replay_session.  Replay reads `events.jsonl` + `meta.json` fro, Real ansible JSONL is not strictly monotonic across threads.      A delta of -0., `handle_completion` is called with the meta.json status., Create a sessions/<id>/ directory with events.jsonl + meta.json. (+7 more)

### Community 76 - "test_full_completion_summary.py"
Cohesion: 0.33
Nodes (15): _logged(), _ok(), _play_def(), Per-task summary fires on FULL play completion, not on the next task.  Under a f, A task with zero terminal results at cancel produces no summary —     a bare ``—, A task summarised mid-run is not re-emitted at cancel/stats., A task that never completes on all hosts (run cancelled) still gets     a summar, _renderer() (+7 more)

### Community 77 - "reconstruct_pause_prompt"
Cohesion: 0.09
Nodes (19): looks_like_interactive_prompt(), Pure prompt-detection heuristics.  Two responsibilities, both pure (str in → boo, Rebuild a multi-line ``ansible.builtin.pause`` block from recent plaintext., Remove SGR escape sequences from ``text``., True if ``pending`` (unread PTY buffer) looks like a child waiting on stdin., reconstruct_pause_prompt(), _strip_ansi(), Tests for reconstruct_pause_prompt (multi-line ``|`` pause prompts).  A YAML ``| (+11 more)

### Community 78 - "redact_dict"
Cohesion: 0.09
Nodes (19): RedactionConfig, Recursively redact by KEY (Layers 1+2). Returns a new dict.      The recursion i, Redact items within a list, recursing on dict items and sanitizing strings., redact_dict(), _redact_list(), Tests for TC-158: Recursive dict/list redaction., TC-158: Exact-match secret keys at any depth are redacted.          QC-002 note:, TC-158: Password fields in list items are redacted. (+11 more)

### Community 79 - "Terminal Row Counting"
Cohesion: 0.11
Nodes (17): CallbackBase, CallbackModule, _connection_id(), _make_acquired(), _make_released(), AOM connection-tracking callback plugin.  Emits ``aom_connection_acquired`` and, Return a deterministic UUID for a (task_uuid, host) pair., Return the current UTC time as an ISO 8601 string. (+9 more)

### Community 80 - "JsonRenderer"
Cohesion: 0.04
Nodes (48): JsonRenderer, Store preflight definitions. No output., No-op — JSON mode doesn't show the prior-run hint., Drive RunState from a JSONL event. No output., No-op — warnings aren't part of the v1 schema., No-op — JSON mode produces no streaming output., No-op — no clock to refresh., No-op — JSON mode has no liveness indicator. (+40 more)

### Community 81 - "is_password_prompt"
Cohesion: 0.08
Nodes (14): is_password_prompt(), Check if ``text`` matches any known password prompt pattern., TC-143: Text containing but not ending with password pattern prefix still matche, TC-143: Vault password pattern detected for PTY integration., TC-143: Vault password (vault_id variant) detected., TC-143: SSH password pattern detected for PTY integration., TC-143: BECOME password pattern detected., TC-143: BECOME password[defaults to SSH password] pattern detected. (+6 more)

### Community 82 - "Renderer Factory Function"
Cohesion: 0.06
Nodes (32): Critical, High, Low, Medium, Meta, Open flags (pending input), Q10 — QC-009 (Medium): missing test classes (fuzz, crash-recovery, schema-boundary, concurrency), Q11 — QC-010 (Medium): `aom_` prefix policy for synthetic events (+24 more)

### Community 83 - "Tree Projection Logic"
Cohesion: 0.06
Nodes (32): Classifier: 12 source values, 30 regex rules, Connection tracking: custom JSONL callback plugin, Design revisions needed, Finding 1 — `aom_verbose_line` prefix list is one prefix, not many, Finding 2 — Inspect TUI is a static browser, Finding 3 — Config refactor is ~50 LOC, not 150-200, Finding 4 — All 5 verification tasks PASS, Implementation outline (+24 more)

### Community 84 - "TestPasswordPromptPatterns"
Cohesion: 0.11
Nodes (10): Tests for all password prompt patterns., All password prompt patterns from SPECIFICATION., Pattern matches 'Vault password: '., Pattern matches vault ID variant., Pattern matches 'SSH password: '., Pattern matches 'BECOME password: '., Pattern matches BECOME password default variant., Pattern matches 'New Vault password: '. (+2 more)

### Community 85 - "event_types.py"
Cohesion: 0.18
Nodes (11): JsonlHostStats, TypedDict for the JSONL event structure emitted by ``ansible.posix.jsonl``.  AOM, Per-host aggregate counts on ``v2_playbook_on_stats``., _event_timestamp(), iter_tree_frames(), datetime, Deterministic replay helpers for frame-by-frame tree capture.  These helpers sta, Yield a tree frame after each JSONL event.      The same ``TreeProjection`` inst (+3 more)

### Community 86 - "WarningsConfig"
Cohesion: 0.10
Nodes (17): BaseModel, Warning display configuration., WarningsConfig, Tests for WarningsConfig model - Section 8., WarningsConfig has show_warnings=True by default., WarningsConfig has show_deprecations=True by default., show_warnings can be set to False., show_deprecations can be set to False. (+9 more)

### Community 87 - "Play Boundary State Tests"
Cohesion: 0.10
Nodes (24): _make_v1_and_v2_sessions(), _make_v1_session(), _make_v2_session(), Path, Schema-boundary regression test (Phase 8 / Task 8.3).  What this test pins -----, Build a current AOM v2 session: meta.json carries ``_schema_version: 2``.      T, Build both regimes side-by-side in the same ``base`` directory.      Returning t, ``load_session`` is the branch site. Pin both sides here. (+16 more)

### Community 88 - "TestHandleEventMalformedPayloads"
Cohesion: 0.15
Nodes (11): Build a RunState with one play, one task, and one host already RUNNING.      The, TC-MITOGEN-1..6: handle_event must tolerate mitogen-distorted payloads.      The, TC-MITOGEN-1: ``task`` as a bare UUID string must be tolerated.          ansible, TC-MITOGEN-2: ``task: None`` must be tolerated.          Mitogen-shimmed actions, TC-MITOGEN-3: ``hosts`` as a list must be tolerated.          Mitogen aggregates, TC-MITOGEN-4: ``hosts: list`` on unreachable must also be tolerated., TC-MITOGEN-5: ``hosts: list`` on failed must also be tolerated., TC-MITOGEN-6: ``hosts: list`` on skipped must also be tolerated. (+3 more)

### Community 89 - "Preflight Definition Assembly"
Cohesion: 0.30
Nodes (14): _failed(), _logged(), _ok(), Per-event cost of the full-completion summary sweep must stay flat.  Regression, A host dying in one task completes OTHER tasks it was blocking:     dead hosts l, A host whose FAILED result is later overwritten by an OK (retry /     async-poll, One slow host must not make per-event completion checks sweep the     whole pend, _renderer() (+6 more)

### Community 90 - "TestTimestampLocalTimezone"
Cohesion: 0.14
Nodes (11): _parse_timestamp(), Process a JSONL event and update state., Parse timestamp from event, defaulting to current time., Tests for UTC timestamp conversion to local timezone (TC-085)., TC-085: _parse_timestamp returns timezone-aware datetime from UTC string., TC-085: UTC timestamp can be converted to local timezone via astimezone()., TC-085: 'Z' suffix in timestamps is handled as UTC., TC-085: Timestamps without Z still parse as UTC if +00:00. (+3 more)

### Community 91 - "parse_jsonl_output"
Cohesion: 0.12
Nodes (12): parse_jsonl_output(), Run ansible-playbook with JSONL callback and capture output., Parser correctly handles unreachable host., --tags install runs only install-tagged tasks., --tags configure runs only configure-tagged tasks., --tags all runs every task regardless of tag., include_tasks expands dynamic tasks at runtime., import_tasks expands static tasks before execution. (+4 more)

### Community 92 - "TestEventParsing"
Cohesion: 0.11
Nodes (14): Path, Tests using pre-recorded JSONL fixtures (no ansible-playbook needed)., Return path to tests/fixtures directory., Parse single_task_ok.jsonl fixture., Parse playbook_failed.jsonl fixture., Parse multi_host_mixed.jsonl fixture., Test parsing of specific event types from JSONL., Return path to tests/fixtures directory. (+6 more)

### Community 93 - "_AsyncEventWriter"
Cohesion: 0.12
Nodes (10): _AsyncEventWriter, Background thread that drains events onto disk.      R16: ``record_event`` enque, Cumulative count of events dropped because the queue was full., Reason string if the writer thread hit a disk error, else None.          Set onc, Wait until the queue is fully drained.          Used by tests that need to asser, Signal the writer thread to drain and exit., Consume the rest of the queue as no-ops after a disk error.          We can't wr, Drain the queue, writing each line to events.jsonl.          Any disk error (``o (+2 more)

### Community 94 - "Mitogen Event Robustness"
Cohesion: 0.16
Nodes (17): _logged(), Tests for inline + post-task duration display.  When a task completes (any of ``, No matching task_start → no duration., Hosts report without timestamps → no per-host duration shown →         the multi, Single-host tasks already show duration on the per-host line; the         summar, When multiple hosts ran the task, per-host durations may differ —         the su, First task_start has no predecessor to summarise., Renderer wired for the completion-aware summary path: preflight     target hosts (+9 more)

### Community 95 - "_drive"
Cohesion: 0.06
Nodes (33): _drive(), _NullSink, Unit tests for the EOF watchdog after ``v2_playbook_on_stats`` (R8).  R8 spec: a, Stand-in for ``_SessionSink`` — the runner treats both the same., The watchdog constant must be a positive, non-trivial number of seconds., Five seconds is the smallest "long enough to absorb a clean EOF"         but sma, When the child goes silent after the stats event, the runner must     not wait f, Synthetic EOF after a stats event in a hung child triggers a         warning vis (+25 more)

### Community 96 - "_state_with_play"
Cohesion: 0.17
Nodes (16): Tree projection with large playbooks: budget saturation and completed-task remov, With 65/100 tasks completed (still over budget), completed tasks     must NOT ap, With 90/100 tasks completed (well under budget), completed tasks     must NOT ap, Simulate progression from task-0000 running to task-0065 running.     At each st, When enough tasks complete that the unbounded tree fits under     budget, the re, With 1 host and budget=8 (minimum), completed tasks still removed., All tasks completed, no running task → tree may show just     the playbook heade, Build a RunState with one play of ``total`` preflight tasks.      First ``comple (+8 more)

### Community 97 - "Replay CLI Subcommand"
Cohesion: 0.14
Nodes (8): Tests for StatusBarConfig model - TC-260, TC-307, TC-290., TC-260: StatusBarConfig has default elements list., TC-307: StatusBarConfig can have custom elements., TC-307: elements field is a list., TC-307 edge case: Empty elements list is valid., TC-307: elements list contains strings., TC-260: Field uses default_factory for mutable default., TestStatusBarConfig

### Community 98 - "test_r6_encoding_roundtrip.py"
Cohesion: 0.11
Nodes (19): _fake_ansible_emits_jsonl_with_raw_msg(), _isolate_session_dir(), MonkeyPatch, Path, R6: encoding surrogateescape for byte-exact round-trip into ``events.jsonl``.  P, Sanity check: switching pexpect to ``surrogateescape`` must         not change b, The renderer's display path must normalise surrogate codepoints     to U+FFFD (`, ``_truncate_msg`` runs every msg field through the         encode-with-replace/d (+11 more)

### Community 99 - "analyze_overhead"
Cohesion: 0.19
Nodes (10): analyze_overhead(), _parse_iso8601(), datetime, _quantile(), Per-task overhead analysis from JSONL event streams.  Why this exists ----------, Parse the ISO-8601 timestamps emitted by ansible.posix.jsonl.      Returns ``Non, Linear-interpolation quantile (matches numpy's default).      Hand-rolled so we, Return the overhead summary for a recorded session's events.      Args: (+2 more)

### Community 100 - "Skipped Task Collapsing"
Cohesion: 0.08
Nodes (18): IntEnum, Numeric verbosity caplevel for an ``aom_stderr_line`` event.      Mirrors ansibl, StderrLevel, Unit tests for the v1 stderr classifier.  Covers ``core/stderr_classifier.py`` —, [DEPRECATION WARNING]: lines are run-level., Persistent connection reset messages (host is NOT in text)., Callback + inventory plugin setup., Inventory parse / decline diagnostics. (+10 more)

### Community 101 - "Include Import Role Tasks"
Cohesion: 0.11
Nodes (21): LogCaptureFixture, _make_partial_session(), CompletedProcess, Path, Crash-recovery regression tests (Phase 8 / Task 8.2).  What this test pins -----, Spawn a real Python subprocess that writes events, then SIGKILL it.      The sub, ``load_session`` degrades gracefully when meta.json is missing., A directory with only events.jsonl still loads (returns a dict). (+13 more)

### Community 102 - "TestPasswordPromptPatterns"
Cohesion: 0.08
Nodes (14): TC-133 to TC-139: Password pattern detection., TC-134: Vault password: pattern detected., TC-135: Vault password (id): pattern detected., TC-136: SSH password: pattern detected., TC-137: BECOME password: pattern detected., TC-138: BECOME password[defaults to SSH password]: pattern detected., TC-139: New Vault password: pattern detected., TC-139: Confirm New Vault password: pattern detected. (+6 more)

### Community 103 - "Parser Edge Cases"
Cohesion: 0.13
Nodes (5): True iff a single host's result should be suppressed from the live log.      Unl, should_hide_host_result(), Tests for should_hide_host_result — per-host hide decision., Result dict without 'changed' key is treated as ok (not changed)., TestShouldHideHostResult

### Community 104 - "RunSummary Schema Contract"
Cohesion: 0.10
Nodes (27): _events_all_skipped(), _events_all_unreachable(), _events_cancelled(), _events_dry_run_check(), _events_empty_run(), _events_multiple_plays(), _events_unknown_event_type(), _golden_path() (+19 more)

### Community 105 - "Parallel Pre-flight Runner"
Cohesion: 0.12
Nodes (23): _fake_ansible_command(), _make_capture_build_command(), _mixed_outcome_events(), Path, End-to-end round-trip for ``aom rerun`` (Item #4).  Exercises the full pipeline:, Read the captured argv lines emitted by the capture-shim.      When CPython is i, Events flagging web2/web3 as failed, web1 as changed, web4 as ok., Events flagging web5 as unreachable plus web2/web3 as failed. (+15 more)

### Community 106 - "Playbook Event Parsing"
Cohesion: 0.26
Nodes (12): _build_state(), _count_marginal_yields(), _force_render(), Per-render preflight-walk cost must not scale with renders × definitions.  The c, Warm one render, then count ``iter_preflight_task_defs`` yields over     ``n_ren, Doubling+ the pending-play task count must not increase the number of     prefli, After warmup, a steady-state re-render must not re-walk the preflight     tree., One active play (``completed`` done + 1 running + rest pending) plus     two ful (+4 more)

### Community 107 - "Run Diagnostics Accumulator"
Cohesion: 0.37
Nodes (12): Path, Prior-run observed task count + match-confidence flag.  ``preflight_task_count``, Same playbook + host count but different args -> loose fallback., A raw count of task-start events — not gated on a parseable delta., _stats(), _task_start(), test_loose_match_is_flagged_inexact(), test_missing_events_yields_zero_observed() (+4 more)

### Community 108 - "Main TUI Screen"
Cohesion: 0.11
Nodes (15): normalize_hide_states(), Lowercase, deduplicate, validate, and separate unknown inputs.      Args:, Tests for normalize_hide_states — input validation and normalisation., Empty iterable returns empty frozenset and empty unknown list., Single known value returns frozenset with that value., Mixed-case input is lowercased and matched against VALID_STATES., Duplicate values produce a single entry in the frozenset., Every entry in VALID_STATES is accepted individually. (+7 more)

### Community 109 - "TestEdgeCases"
Cohesion: 0.09
Nodes (12): Edge cases and boundary conditions., Empty lines don't crash parser., Whitespace-only lines handled gracefully., JSON without _event field returns empty., Malformed JSON doesn't crash parser., JSON with trailing newline handled., Multiple stats events handled (shouldn't happen but test)., Password prompts with extra text still match. (+4 more)

### Community 110 - "run_playbook"
Cohesion: 0.07
Nodes (33): Run a playbook through the renderer; return the subprocess exit code.      The r, run_playbook(), _fake_ansible_command(), Integration tests for the ansible-playbook runner.  The runner spawns `ansible-p, Missing ansible-playbook surfaces as exit 127 without crashing., Runner calls run_preflight before spawning and forwards its result., Build a (command, args) pair that emits `events` as JSONL then exits.      Retur, Each error → an add_warning call, even when they share a body.          The coun (+25 more)

### Community 111 - "Play Tree Projection"
Cohesion: 0.17
Nodes (8): Code of Conduct, Before You Start, Contributing to AOM, Development Workflow, Reporting a Vulnerability, Scope, Security Policy, Support

### Community 112 - "sessions/conftest.py"
Cohesion: 0.24
Nodes (10): copy_session_fixture(), load_session_dict(), Path, Loaders for curated session fixtures.  Each subdirectory under ``tests/fixtures/, Map a friendly name or raw session_id to its fixture directory., Load a curated session fixture as a dict matching load_session()., Path to the curated session fixtures directory., Return a callable that copies a curated session into tmp_path/sessions/. (+2 more)

### Community 113 - "_row_count"
Cohesion: 0.12
Nodes (24): How many terminal rows `text` occupies at the given terminal `width`.      Each, _row_count(), Tests for width-aware row counting (roadmap #12).  `_row_count` decides how many, ANSI codes are excluded from the wrap calculation; visible chars     are what co, After update() in a narrow terminal, _status_rows reflects wrapped rows.      SI, After 'abc\\n' the cursor sits on the next row but nothing is rendered there., A line exactly `width` chars long fits on one row (no wrap)., First line wraps to 2 rows, second line takes 1 row → 3 total. (+16 more)

### Community 114 - "PlayDefinition"
Cohesion: 0.03
Nodes (61): collect_tags(), _count_tasks(), format_preflight_summary(), Count leaf TaskDefinitions in a play, expanding any RoleGroupDefinition.      Dy, Unique tags across every leaf TaskDefinition, alphabetically sorted.      Used f, PlayDefinition, Static play info from --list-tasks and --list-hosts (Definition class)., Tests for format_preflight_summary — startup tree preview. (+53 more)

### Community 115 - "create_renderer"
Cohesion: 0.09
Nodes (15): RenderMode, create_renderer(), Create the renderer selected by ``mode``.      Args:         mode: ``"compact"``, _default_runner(), Real-world runner: spawn the renderer + run_playbook.      Lazy-imported so unit, Default view mode is compact., TC-005: create_renderer function exists., TC-005: create_renderer() returns CompactRenderer. (+7 more)

### Community 116 - "TestSubtreeRoleCounting"
Cohesion: 0.11
Nodes (14): Subtree semantics for ``_build_role_total_tasks`` and     ``_count_visible_tasks, Build a state with ``podman > angie_ssl_terminator`` nesting.          ``n_podma, ``role_total_tasks["podman"]`` must include angie's 30 tasks         as part of, Regression guard: subtree and direct-children counts are         equal for a sin, When only role headers + a couple tasks fit in the budget,         both ``podman, Regression guard for single-role subtree == direct., With a small budget that truncates inside angie's task list,         both podman, Multi-level inner footer emission for nested roles.      When the cut lands insi (+6 more)

### Community 117 - "State Transition Validation"
Cohesion: 0.25
Nodes (10): detect_duplicate_playbook(), True if `playbook` appears (path-normalised) in `ansible_args`.      Catches the, Tests for duplicate-playbook argument detection.  When the user types `aom site., Multiple distinct .yml files are a legitimate ansible-playbook invocation., ./site.yml and site.yml refer to the same file — flag the duplicate., test_detect_duplicate_playbook_distinguishes_different_files(), test_detect_duplicate_playbook_finds_exact_repeat(), test_detect_duplicate_playbook_handles_empty_args() (+2 more)

### Community 118 - "_safe_loads"
Cohesion: 0.08
Nodes (16): _has_surrogate_codepoint(), Any, Parse a line and return zero or more JSON events.          Returns empty list fo, Parse a line and return zero or more events., Parse JSON line and return events., Classify and handle non-JSON lines from PTY stream.          Real ansible-playbo, Update connection tracking state from a connection event.          Intercepts ``, Resolve connection_id and attribution_confidence for a stderr line.          Arg (+8 more)

### Community 119 - "inspect/cli.py"
Cohesion: 0.08
Nodes (39): _build_parser(), _default_state_dir(), inspect_debug(), inspect_prune(), inspect_text(), inspect_tui(), main(), ArgumentParser (+31 more)

### Community 120 - "Path"
Cohesion: 0.16
Nodes (13): Path, Resolve an explicit session ID, short prefix, or "most recent" intent.      Mirr, _resolve_session_id(), _make_session(), Path, Helper: create a session directory with a minimal meta.json., Helper: write a session with one failed host (web2)., Happy path: --yes --failed → run_playbook called with --limit web2. (+5 more)

### Community 121 - "Pane Focus Navigation"
Cohesion: 0.20
Nodes (16): TC-BOUNDARY-1: Duplicate play_start for the same play_id must not         destro, TC-BOUNDARY-2: Re-emitting the same play_start must preserve the         task co, TC-BOUNDARY-3: A RUNNING meta task from play 1 must be force-         completed, TC-BOUNDARY-4: The dynamic-graft cursor ``_last_matched_task_def``         must, TC-BOUNDARY-5: Under ``strategy: free`` a play_start for play N         can arri, TC-BOUNDARY-6: The free-strategy skip must NOT regress the linear         case —, TC-BOUNDARY-7: A ``v2_runner_on_*`` event that arrives WITHOUT a         ``play`, TC-BOUNDARY-8: A terminal ``v2_runner_on_ok`` event that arrives         WITHOUT (+8 more)

### Community 122 - "Log Panel Widget"
Cohesion: 0.10
Nodes (13): _execution_parser(), _fake_ansible_command(), _FakeSink, Tests for ``RunDiagnostics`` and the runner-side instrumentation.  Phase 3 of do, Backwards-compat: existing call sites that don't pass diag still work., End-to-end: a real spawn with debug on emits the standard markers., After a run, get_last_run_diagnostics() exposes the accumulator., Lifecycle marks are now always-on (phase 15); the first event mark     fires wit (+5 more)

### Community 123 - "_FakeSpawn"
Cohesion: 0.12
Nodes (14): _FakeSpawn, _patch_runner_for_fake_subprocess(), Any, MonkeyPatch, R7 — Ctrl-C race guard.  If SIGINT arrives between the child exiting cleanly and, Window #2: child already exited 0, then SIGINT fires during cleanup.      Before, The race: child exits 0, ``_drive`` returns 0, then SIGINT         fires while t, If the child exited non-zero (e.g. failed playbook) and SIGINT         arrives d (+6 more)

### Community 124 - "TestStatusBarAvailableElements"
Cohesion: 0.10
Nodes (11): Tests for available status bar elements - TC-291., TC-291: playbook_name element renders with correct data., TC-291: elapsed_time element renders HH:MM:SS., TC-291: task_progress element shows completed/total., TC-291: current_task element shows task name., TC-291: host_count element shows completed/total hosts., TC-291: subprocess_pid element shows PID when available., TC-291 edge case: PID not available shows N/A or hides. (+3 more)

### Community 125 - "Pydantic Model Basics"
Cohesion: 0.11
Nodes (14): get_status_icon_ascii(), Get ASCII fallback icon for terminals without Unicode support.      Args:, Tests for TC-377: Unicode fallback to ASCII., TC-377: OK falls back to * in ASCII mode., TC-377: CHANGED falls back to + in ASCII mode., TC-377: FAILED falls back to X in ASCII mode., TC-377: RUNNING falls back to @ in ASCII mode., TC-377: PENDING falls back to . in ASCII mode. (+6 more)

### Community 126 - "redact_event"
Cohesion: 0.06
Nodes (34): Apply all redaction layers to an event dict. Returns a new event.      Layer ord, redact_event(), _distinctive_secret(), _innocuous_key(), _password_shaped_key(), SearchStrategy, Property-based tests for the redaction layers (Batch C, family #5b).  These prop, The verbatim secret never appears in the redacted serialisation. (+26 more)

### Community 127 - "format_host_rows"
Cohesion: 0.26
Nodes (21): format_host_rows(), Render the per-host overview as a column-aligned table.      Header row + one ro, Strip SGR escapes so visible-length comparisons are accurate., _strip_sgr(), _add_results(), Per-host overview renders as a column-aligned table rather than a flat row of co, Synthesise OK/CHANGED/SKIPPED/FAILED/UNREACHABLE results for a host., Split rows on whitespace runs after stripping SGR — coarse but     enough to ass (+13 more)

### Community 128 - "Shell Completion Helpers"
Cohesion: 0.26
Nodes (4): _create_parser(), ArgumentParser, Build the argparse parser for ``aom rerun``.      Split out from ``main`` so tes, TestCreateParser

### Community 129 - "Compact Display Logic"
Cohesion: 0.47
Nodes (10): _printed(), Straggler results print under the wrong TASK header.  Log lines stream in arriva, _renderer(), _runner_failed(), _runner_ok(), _runner_start(), test_result_matching_current_header_has_no_task_suffix(), test_straggler_changed_line_carries_task_suffix() (+2 more)

### Community 130 - "Renderer Parity Invariant"
Cohesion: 0.26
Nodes (12): _all_text(), _item(), _logged(), _loop_failed(), _loop_ok(), Tests for per-item loop rendering in the streaming log.  The ``ansible.posix.jso, _renderer(), _task_start() (+4 more)

### Community 131 - "_FakeSpawn"
Cohesion: 0.14
Nodes (11): _FakeSpawn, _patch_runner_with_fake_spawn(), Any, MonkeyPatch, R9 — searchwindowsize bound on pexpect.spawn().  R9 spec: pexpect's ``searchwind, R9: searchwindowsize must exceed every pattern the runner uses.      The runner', Stand-in for pexpect.spawn() with the kwargs the runner passes., Capture every kwarg passed to pexpect.spawn() inside the runner. (+3 more)

### Community 132 - "Password Prompt Patterns"
Cohesion: 0.18
Nodes (14): TC-MITOGEN-100..107 — compact renderer's tolerance for malformed JSONL events., TC-MITOGEN-103: ``hosts: list`` must not raise on unreachable., TC-MITOGEN-104: ``hosts: list`` must not raise on failed., TC-MITOGEN-105: ``hosts: list`` must not raise on skipped., TC-MITOGEN-106: a malformed event must not poison subsequent events.          Th, TC-MITOGEN-107: a malformed event that crashes _emit_event_log         must not, TC-MITOGEN-100..105: ``update_state`` must not raise on bad events., TC-MITOGEN-100: ``task`` as a bare UUID string must not raise. (+6 more)

### Community 133 - "Subprocess Exit Codes"
Cohesion: 0.18
Nodes (7): MonkeyPatch, Tests for TC-069: ansible-core Version Check.      AOM shells out to ansible-pla, TC-069: _callback_env always returns a dict with ANSIBLE_STDOUT_CALLBACK set., TC-069: _callback_env never includes version-pin keys.          AOM doesn't pin, TC-069: _callback_env works regardless of bundled plugin state.          Both st, TC-071: _callback_env returns a fresh dict, doesn't mutate os.environ., TestAnsibleCoreVersionCheck

### Community 134 - "Renderer ETA Wiring"
Cohesion: 0.09
Nodes (11): Header + bare colon (no markers, no question mark) is still a prompt., When the header was consumed earlier and only the prompt tail         sits in th, An ordinary log line as the prior plaintext is not a signal., The heuristic used to gate the blocking-input path., Pure ``something:`` is too risky — many debug tasks end in colon., No colon, no question mark → don't treat as prompt., ansible vars_prompt without custom text uses ``[name]: ``., Defensive: don't false-positive on log lines mentioning [INFO]. (+3 more)

### Community 135 - "Auto Version Bump Hook"
Cohesion: 0.05
Nodes (58): PydanticBaseSettingsSource, AomSettings, CaptureConfig, _cli_config_path(), find_config_paths(), InspectConfig, LiveConfig, load_config_with_layers() (+50 more)

### Community 136 - "test_ignore_errors_callback.py"
Cohesion: 0.32
Nodes (4): Path, Integration: the bundled ``aom_jsonl`` callback emits ``ignore_errors``.  Ansibl, _run_playbook(), TestIgnoreErrorsCallback

### Community 137 - "_make_play"
Cohesion: 0.19
Nodes (10): _make_play(), _make_task(), _resolve_play_hosts uses _play_def_by_name dict lookup., Unknown play name → empty list, just like the linear scan returned., After definitions = [...], _task_def_index contains every leaf by name., _graft_or_match_task must NOT call _iter_leaf_task_defs.          Mock _iter_lea, Async launcher + async-status rows with the same display name stay separate., TestIndexReassignment (+2 more)

### Community 138 - "test_preflight.py"
Cohesion: 0.12
Nodes (19): Reduce ansible-playbook stderr to the diagnostic lines worth showing.      Argpa, _trim_stderr(), Tests for the pre-flight orchestrator (--list-tasks + --list-hosts)., When there's no `: error:` marker, keep the first few non-empty lines, capped., The new fields are optional with empty defaults so old call sites still work., assemble_definitions builds a PlayDefinition per play with tasks + resolved_host, When --list-hosts has no entry for a play, resolved_hosts stays empty., ansible-playbook on bad args dumps usage + error + full --help. Keep only error. (+11 more)

### Community 139 - "Parser Phase Transitions"
Cohesion: 0.25
Nodes (13): _logged(), _ok(), Tests for skipped-task collapsing.  When a task produces only ``skipped`` result, The very last task can't be flushed by a next task_start;         the stats even, ok arrives first, then skipped — those skipped land at the         next task tra, All-skipped task A followed by mixed task B: B must         flush its own skips, _renderer(), _skipped() (+5 more)

### Community 140 - "Warning Pattern Detection"
Cohesion: 0.15
Nodes (18): _ansible_collection_paths(), _find_session(), _has_ansible_posix(), _parse_jsonl_through_core(), CompletedProcess, Path, Real-ansible smoke tests.  Every other "integration" test in this suite uses a f, Return the lone session directory under ``home_dir`` or fail loudly. (+10 more)

### Community 141 - "Conftest Fixture Validation"
Cohesion: 0.15
Nodes (18): _ansible_collection_paths(), _find_session(), _has_ansible_posix(), _parse_jsonl_through_core(), CompletedProcess, Path, Real-ansible throttle awareness test (RED — TDD failing test).  This test is **i, Spawn ``python -m ansible_aom <playbook>`` against a sandboxed HOME.      The fi (+10 more)

### Community 142 - "assemble_definitions"
Cohesion: 0.10
Nodes (15): assemble_definitions(), Build PlayDefinition objects from parsed --list-tasks / --list-hosts dicts., TC-151: If --list-hosts fails, resolved_hosts starts empty; populated by runner, TC-151: --list-hosts failure → empty play_hosts → empty resolved_hosts., TC-151: RunState.definitions=[] → _resolve_play_hosts returns []., TC-151: v2_runner_on_* events add hosts to task.hosts even without preflight., TC-151 edge: host arriving from a runner event but absent from preflight, TC-149: --list-hosts populates PlayDefinition.resolved_hosts. (+7 more)

### Community 143 - "TestAppConfigValidation"
Cohesion: 0.10
Nodes (11): Tests for Pydantic field constraints - TC-316, TC-317, TC-318., TC-318: log_max_lines minimum is 1000., TC-318: log_max_lines below 1000 raises ValidationError., TC-318: log_max_lines above 100000 raises ValidationError., TC-318: session_keep_count minimum is 1., TC-318: session_keep_count below 1 raises ValidationError., TC-318: session_keep_count negative raises ValidationError., TC-318: session_keep_days minimum is 1. (+3 more)

### Community 144 - "WarningEntry"
Cohesion: 0.03
Nodes (59): A classified warning or deprecation from the PTY stream., WarningEntry, Tests for status filter checkboxes - TC-301., Create filter state for status checkboxes., TC-301: Status checkboxes filter tasks by status., TC-301: Multiple statuses create union filter., TC-301 edge case: Uncheck all shows all tasks (no filter)., TC-301 edge case: No tasks match filter shows empty tree. (+51 more)

### Community 145 - "TestTwoLevelTruncation"
Cohesion: 0.12
Nodes (12): Two-cut truncation: when the budget is exceeded, the algorithm     emits BOTH an, 1 play, 1 role, ``n_tasks`` tasks, 1 host — the simplest         tree whose budg, 2 plays, each with a single role and ``n_tasks_per_role`` tasks.         The unb, A small tree that fits the budget returns verbatim — no footers,         no has_, The classic scenario from test_tree_nested_roles.py: 1 play, 1         role, 34, When the budget cut lands inside a role's task list, both an         inner foote, When the budget cut lands cleanly on a play boundary (between         two plays), The inner footer's count must equal the number of tasks remaining         in the (+4 more)

### Community 146 - "RunSummary"
Cohesion: 0.11
Nodes (19): End-of-run summary emitted by ``JsonRenderer.handle_completion``.      Field rul, RunSummary, _canonical_schema_text(), _load_committed_schema(), Contract test for the committed ``RunSummary`` v1 JSON schema (Item #7).  Downst, Load the on-disk schema. Skipped if missing (handled in Layer 1)., Each canonical shape must validate. Catches accidental tightening., Bonus: a payload produced through the Pydantic model must validate.      Prevent (+11 more)

### Community 147 - "Session Roundtrip Invariants"
Cohesion: 0.40
Nodes (5): isolated_state_dir(), MonkeyPatch, Path, TempPathFactory, Pin AOM's state directory to a per-test tmp dir for every test.      Without thi

### Community 148 - "Version Bump Script"
Cohesion: 0.08
Nodes (25): _bump_pyproject(), _detect_bump(), main(), Path, Get the message of the just-created commit (HEAD)., Return the worktree whose Git invocation triggered this hook., Resolve a Git administrative path for the active worktree., Hook entry point.      Called as a post-commit hook (no useful argv). Reads the (+17 more)

### Community 149 - "TestConfigModelBasics"
Cohesion: 0.10
Nodes (11): Tests for Pydantic BaseModel basics - TC-316, TC-317., StatusBarConfig is a Pydantic model., RedactionConfig is a Pydantic model., WarningsConfig is a Pydantic model., AppConfig is a Pydantic Settings model., TC-316: ValidationError raised for invalid field types., TC-316: ValidationError for invalid nested types., String values in lists are preserved. (+3 more)

### Community 150 - "Runner Heartbeat Wiring"
Cohesion: 0.11
Nodes (11): _BufferedChild, _events_fixture(), _NullSink, Path, Regression tests for the multi-event PTY read bug.  Bug summary (R-INTERMITTENT-, Stand-in for the runner's session sink — records calls for assertions., Single ``expect()`` returning a multi-event blob must still record     every eve, End-to-end: a real subprocess emitting the 8-event fixture must     produce an ` (+3 more)

### Community 151 - "TestPtyStreamParserPhaseTransitions"
Cohesion: 0.11
Nodes (10): Phase stays EXECUTION without v2_playbook_on_stats., Lines in POST_RUN_RECAP phase are collected., TC-128, TC-131, TC-132: Phase transition tests., TC-128: Initial phase is PRE_RUN_PROMPTS., TC-131: v2_playbook_on_start triggers PRE_RUN_PROMPTS -> EXECUTION., TC-131: First JSONL event triggers transition to EXECUTION., TC-132: v2_playbook_on_stats triggers EXECUTION -> POST_RUN_RECAP., TC-132: PLAY RECAP line triggers EXECUTION -> POST_RUN_RECAP. (+2 more)

### Community 152 - "TestWarningPatternDetection"
Cohesion: 0.11
Nodes (10): TC-141: Warning pattern detection and classification., TC-141: [WARNING]: pattern detected., TC-141: [DEPRECATION WARNING]: pattern detected., TC-141: [DEPRECATED]: pattern detected., Multiple warnings collected separately., Warnings captured in PRE_RUN_PROMPTS phase., Warning entries have timestamp., Warning message preserved exactly. (+2 more)

### Community 153 - "parity.py"
Cohesion: 0.12
Nodes (19): Backward-compat re-export shim for ``determine_exit_code``.  The canonical imple, Process exit-code derivation from a :class:`RunState`.  Pure: in → out, no I/O., _empty_host_counts(), Any, Reduce a ``RunState`` into a renderer-agnostic dict.  This is the canonical "wha, Project ``state`` into a renderer-agnostic dict.      Shape::          {, reduce_state_for_parity(), _drive_compact() (+11 more)

### Community 154 - "TestRuntimeRoleTaskCount"
Cohesion: 0.15
Nodes (10): Regression tests for role_total_tasks counting runtime-only tasks.  When a role, A role loaded via include_role must show its runtime task count         in the r, Runtime podman tasks should appear as children of the podman         role header, When a role has tasks in BOTH preflight and runtime (same task         resolved, A task name containing ' : ' that is NOT a role prefix must not         be assig, Pure runtime role (no preflight tasks at all) must still show         the correc, role_total_tasks must include tasks from runtime that aren't in     the prefligh, Preflight has no podman tasks. At runtime, podman tasks appear         via inclu (+2 more)

### Community 155 - "ansible_aom/cli.py"
Cohesion: 0.13
Nodes (11): OutputFormat, _confirm_no_redact(), main(), CLI entry point for AOM.  This module provides the main command-line interface f, Validate ``--no-redact`` per QC-003 (Q4=B: confirm prompt).      Returns ``(proc, Spawn the streaming renderer (compact ANSI or end-of-run JSON) via a LiveDriver., Main CLI entry point.      Returns:         Exit code (0 for success, non-zero f, _run_compact() (+3 more)

### Community 157 - "FakeRenderer"
Cohesion: 0.06
Nodes (30): LiveDriver, Path, Spawns ``ansible-playbook`` and pumps its JSONL output.      Parameters mirror :, EventSource, Protocol, EventSource Protocol — the source-side port of the architecture.  See ``ARCHITEC, A producer of run events for a :class:`Renderer`.      Implementations own the f, Path (+22 more)

### Community 158 - "Color Support Detection"
Cohesion: 0.15
Nodes (6): Task 5.3: even on the ansible.posix.jsonl fallback the connection         callba, Task 5.3: if the connection-callback dir can't be resolved the         runner om, Task 5.3: when both dirs are present, ANSIBLE_CALLBACK_PLUGINS uses         the, Defensive: never inject an empty ``:`` into ANSIBLE_CALLBACK_PLUGINS         eve, Task 5.3: ANSIBLE_CALLBACK_PLUGINS includes the connection-callback dir., TestCallbackEnv

### Community 159 - "View Mode Selection"
Cohesion: 0.15
Nodes (20): _build_config(), _id_from_row(), _load_fixture(), Any, RedactionConfig, Table-driven red-team fixture test for the QC-002 redaction rewrite.  This file, Defense-in-depth: every SHOULD_REDACT row must end with the literal     ``REDACT, Sanity: the fixture loads as a list (ad-hoc debugging entry point). (+12 more)

### Community 160 - "Terminal Capability Detection"
Cohesion: 0.20
Nodes (6): Tests for TC-071: JSONL Environment Variable.      TC-071 is the contract that A, TC-071: _callback_env sets ANSIBLE_STDOUT_CALLBACK in the env dict., TC-071: A user-set ANSIBLE_STDOUT_CALLBACK in os.environ survives merging., TC-071: Bundled stdout selection includes ANSIBLE_CALLBACK_PLUGINS path., TC-071: Fallback env doesn't include ANSIBLE_CALLBACK_PLUGINS.          We rely, TestJsonlEnvironmentVariable

### Community 161 - "core/__init__.py"
Cohesion: 0.29
Nodes (5): Core module for AOM - backend-agnostic shared logic.  This module contains no UI, _drive_json(), Any, Phase 12: JsonRenderer publishes RendererStats at completion.  Spec: docs/superp, test_json_renderer_publishes_stats_on_completion()

### Community 162 - "TestProjectionLifecycle"
Cohesion: 0.23
Nodes (9): A state-shape change must refresh, not replace, the cached projection., Two ticks with no intervening state mutation reuse the same instance., A non-structural update must keep the active play visible only         while it, Build a tiny two-play state that exposes sticky row selection.      ``active`` i, _renderer(), _runner_ok(), _seed_sticky_gap_state(), _task_start() (+1 more)

### Community 163 - "test_no_eof_hang.py"
Cohesion: 0.29
Nodes (7): _fake_ansible_hangs_after_stats(), Batch E item #10c — R8 no-EOF hang protection.  A misbehaved (or hung) ansible-p, Sanity baseline: when the child cleanly exits after emitting all     events, the, Build a fake-ansible command that emits events then sleeps without     closing s, R8 regression marker: the runner must not wait indefinitely on a     hung child, test_runner_finishes_promptly_on_clean_eof(), test_runner_returns_within_bounded_time_when_child_hangs_after_stats()

### Community 164 - "Psutil Safe Probe"
Cohesion: 0.31
Nodes (8): On Ctrl-C / failure exit, the compact panel's tree + host overview must persist, Exit 130 (Ctrl-C) → tree + host snapshot lands in scrollback., Non-zero exit on a "failed" state preserves the panel too., A clean exit omits the tree snapshot — the host table still prints     for per-h, _renderer_with_running_task(), test_tree_not_duplicated_on_clean_exit(), test_tree_printed_after_cancel(), test_tree_printed_after_failure()

### Community 165 - "ensure_inventory_arg"
Cohesion: 0.23
Nodes (10): detect_default_inventory(), ensure_inventory_arg(), If no -i/--inventory flag is set, prepend one pointing at the default file., Return the first conventional inventory file found in CWD, or None., MonkeyPatch, Path, Tests for inventory auto-detection.  When the user doesn't pass `-i` / `--invent, ansible-playbook also accepts --inventory-file as a synonym. (+2 more)

### Community 166 - "TestNoRedactFlag"
Cohesion: 0.14
Nodes (6): Task 5.2: --no-redact disables redaction (with safety gates; see QC-003)., QC-003: --no-redact in non-TTY mode without --yes refuses with exit 2., QC-003: --no-redact --yes in non-TTY mode proceeds (CI escape hatch)., TTY + --yes → skip the prompt, proceed., TTY + no --yes + user answers 'n' → refuse with exit 2., TestNoRedactFlag

### Community 167 - "Dirty Flag Throttle"
Cohesion: 0.14
Nodes (12): get_status_color(), Get the ANSI color name for a given status.      Args:         status: The execu, Tests for get_status_color function., get_status_color returns green for OK., get_status_color returns yellow for CHANGED., get_status_color returns red for FAILED., get_status_color returns magenta for UNREACHABLE., get_status_color returns cyan for RUNNING. (+4 more)

### Community 168 - "Tree Expansion Icons"
Cohesion: 0.19
Nodes (14): _print_log_calls(), TC-PERF-001..002 — batched print_log per runner event.  A single runner event (`, ok event with some hosts changed=True still produces one call., 14 hosts in one ok event → exactly one print_log call., The single print_log argument carries every host line., _renderer(), _runner_failed_multi(), _runner_ok_multi() (+6 more)

### Community 170 - "test_parser_recap_cap.py"
Cohesion: 0.31
Nodes (8): R13 — cap ``PtyStreamParser._recap_lines`` at ``MAX_LOG_LINES``.  R13 spec: the, R13: recap_lines must not exceed MAX_LOG_LINES., R13: the retained tail must be the most-recent lines.      Same reasoning as R2', R13: pin the cap value at MAX_LOG_LINES (=50000)., _recap_line(), test_recap_lines_capped_at_max_log_lines(), test_recap_lines_keeps_most_recent_when_capped(), test_recap_lines_pin_against_constant_drift()

### Community 171 - "TestPasswordTimeoutDefault"
Cohesion: 0.10
Nodes (11): TC-148: Verify 60s timeout default, exception on timeout.      The DEFAULT_PASSW, TC-148: DEFAULT_PASSWORD_TIMEOUT equals 60 seconds., TC-148: DEFAULT_PASSWORD_TIMEOUT is an integer (seconds)., TC-148: DEFAULT_PASSWORD_TIMEOUT is a positive value., TC-148: Password handling respects timeout — getpass blocks until input or timeo, TC-148: CompactRenderer provides handle_password_prompt for timeout integration., TC-148: DEFAULT_PASSWORD_TIMEOUT is importable from password module., TC-148: On successful password entry, returns the password string. (+3 more)

### Community 172 - "TestPerEventLogColors"
Cohesion: 0.13
Nodes (10): _color_enabled(), True if we should emit SGR codes — TTY only, NO_COLOR honored., Tests for semantic SGR colouring in the compact status output.  Colour rules (wh, The trailing ●/✖ indicator picks its colour from the state., Per-task log lines (ok/changed/fatal/unreachable/skipping) carry     semantic co, Skipped hosts are buffered (collapsed-on-flush). Force the         mixed-task fl, The gating predicate honours both the TTY flag and ``NO_COLOR``., TestColorEnabled (+2 more)

### Community 173 - "TestConftestFixtures"
Cohesion: 0.11
Nodes (10): Verify all conftest fixtures work correctly., password_prompt_ssh fixture is valid., password_prompt_vault fixture is valid., password_prompt_become fixture is valid., deprecation_warning_line fixture is valid., deprecated_removed_line fixture is valid., warning_line fixture is valid., recap_line fixture is valid. (+2 more)

### Community 174 - "Status"
Cohesion: 0.04
Nodes (72): Task/host execution status., Status, PTY stream parsing phases., StreamPhase, Integration tests for PtyStreamParser against real ansible-playbook output.  The, Test warning pattern detection., Integration tests for 02-single-task-changed playbook., Integration tests for 03-task-failure playbook. (+64 more)

### Community 175 - ".test_record_false_does_not_touch_default_state_dir"
Cohesion: 0.36
Nodes (5): _fake_ansible_command(), Path, Integration test for F3 --no-record at the runner level.  The unit tests cover a, Even if session_dir is None, record=False must not create the default., TestNoRecordIntegration

### Community 176 - "test_inspect_accumulator.py"
Cohesion: 0.17
Nodes (19): Single-pass, constant-per-event aggregation over a session's events.      ``feed, SessionIndexAccumulator, _events(), _feed_with_refs(), _iter_task_nodes(), Unit tests for the streaming SessionIndex accumulator (core).  The accumulator i, The sqlite builder streams stderr rows straight to disk; the     accumulator mus, Tasks with no play attribution must all land under a single     '(orphan tasks)' (+11 more)

### Community 177 - "test_cli.py"
Cohesion: 0.02
Nodes (68): Unit tests for CLI interface in ansible_aom.cli.  Test cases cover: - TC-001 to, F5: argcomplete.autocomplete must be called inside create_parser., Tests for --hide-state flag., --hide-state propagates from CLI to create_renderer/run_playbook., aom --hide-state ok playbook.yml → create_renderer gets hide_states=["ok"]., --hide-state ok --hide-state skipped → hide_states=["ok", "skipped"]., No --hide-state flag → create_renderer gets hide_states=[]., --capture-verbose should reach compact renderer creation. (+60 more)

### Community 178 - "test_run_state_memory_bounds.py"
Cohesion: 0.17
Nodes (19): _play_start(), R12 — enforce MAX_PLAYS / MAX_TASKS_PER_PLAY / MAX_HOSTS_PER_TASK / MAX_TOTAL_HO, R12: a task's 10001st host is dropped., R12: the 1 000 001st HostRunState insertion is dropped.      The MAX_TOTAL_HOST_, R12: a fresh RunState has no truncations recorded., R12: each cap has its own counter, not shared., R12: pin the documented cap values so accidental edits are caught., R12: the 1001st ``v2_playbook_on_play_start`` is dropped. (+11 more)

### Community 179 - "test_loop_item_count.py"
Cohesion: 0.26
Nodes (5): _item_event(), Per-host loop item counting for the TUI task tree.  The bundled ``aom_jsonl`` ca, _running_loop_state(), TestRunStateCounter, TestTreeRendersCount

### Community 180 - "_print_session_footer"
Cohesion: 0.38
Nodes (6): _print_session_footer(), Print the end-of-run hint that points users at ``aom inspect``.      Suppressed, The runner prints a `Session …  aom inspect` footer on termination., test_footer_prints_short_id_and_inspect_hint(), test_footer_suppressed_when_no_session_id(), test_footer_suppressed_when_stderr_not_tty()

### Community 181 - "Diagnostics CLI Wiring"
Cohesion: 0.36
Nodes (5): _fake_ansible_command(), Path, Integration test: record a fake run, then replay it.  Drives ``run_playbook`` ag, A recorded failure (exit 2) writes meta.status=failed; replay         forwards t, TestRecordThenReplay

### Community 182 - "TestReEnableOnResize"
Cohesion: 0.29
Nodes (3): The 'SIGWINCH' equivalent: a previously-degraded display     re-enables its live, force_size is the test seam; production calls don't pass it.         Verify the, TestReEnableOnResize

### Community 183 - "test_runner_on_start_host.py"
Cohesion: 0.33
Nodes (4): Path, Integration: ``v2_runner_on_start`` must identify which host started.  ``ansible, _run_free_playbook(), TestRunnerOnStartCarriesHost

### Community 184 - "TestWarningVisibilityCompactPlumbing"
Cohesion: 0.18
Nodes (9): MonkeyPatch, Path, [live] show_failed_hint: false should disable compact hints., --no-failed-hint still wins when config enables hints., --hide-warnings / --hide-deprecations propagate into compact mode., TC-003: Core module file exists at expected path., TC-001: Package name is 'ansible-aom'., TC-001: CLI entry point is 'aom'. (+1 more)

### Community 185 - "test_properties_state.py"
Cohesion: 0.16
Nodes (16): _check_invariants(), event_sequences(), _make_play_start(), _make_result(), _make_stats(), _make_task_start(), DrawFn, Property-based tests for RunState invariants (Batch C, family #5c).  These tests (+8 more)

### Community 186 - ".test_skip_non_host_lines"
Cohesion: 0.33
Nodes (3): TC-141: [DEPRECATED]: pattern detected., TC-075: Task start detected for linear strategy., TC-099: Parser skips 'pattern:', 'hosts (N):', 'tasks:', and blank lines.

### Community 187 - "Stale Running Cleanup"
Cohesion: 0.16
Nodes (14): _drive_short(), Any, R11 — tighter post-stats EOF watchdog once ``end_time`` is set.  R11 spec: the 3, R11: after ``state.end_time`` is set, post-stats timeout shrinks.      The runne, R11: until stats is consumed, full ``_EOF_WATCHDOG_S`` applies.      Once the pa, R11 invariant: ``_EOF_WATCHDOG_S_QUIET`` < ``_EOF_WATCHDOG_S``.      The whole p, Fake pexpect child that records every expect() timeout and never hangs.      Aft, Run ``_drive`` with a renderer+sink that prevent pexpect errors.      The dummy (+6 more)

### Community 188 - "TestMultiLineWarningContinuation"
Cohesion: 0.15
Nodes (7): Ansible hard-wraps ``[WARNING]``/``[DEPRECATION WARNING]`` messages to     the t, Feed a real 3-line wrapped [WARNING] as ansible emits it on the PTY., A magenta line after an intervening JSON event starts a fresh         warning —, Color-based classification: a magenta stderr line with no open         warning b, Regression guard: non-coloured unrecognised lines are unaffected         and sti, Only magenta (warn/deprecate) folds. A red line after a warning         closes t, TestMultiLineWarningContinuation

### Community 189 - "JSON Output Renderer"
Cohesion: 0.11
Nodes (18): 10. Live streaming inspect (answers Q23, Q25), 12. Schema migration (answers Q29, Q31, Q9=B no version bump), 13. Test plan, 14. Documentation (answers Q37–Q39), 15. Migration / rollout, 16. Out-of-scope (explicit non-goals for v1), 17. Risks & open questions for sign-off, 1. Reframe (anchored in research) (+10 more)

### Community 190 - "text.py"
Cohesion: 0.07
Nodes (53): build_verbose_lines(), Return ``play_name -> task_id`` membership from an already-built tree.      Call, Build the verbose-panel body for one session dict and focus scope.      In-memor, task_ids_by_play(), _fmt_duration(), _host_counts_line(), _hydrate_node(), _iter_failed_tasks() (+45 more)

### Community 191 - "TestPtyStreamParserWarningsList"
Cohesion: 0.12
Nodes (10): TC-501: PtyStreamParser _warnings list type., TC-501: _warnings contains WarningEntry objects, not strings., TC-501: _warnings is empty list on initialization., TC-501: Multiple warnings are added in order received., TC-501: warnings property returns list., TC-503: WarningEntry timestamp from PTY stream., TC-503: WarningEntry captures timestamp when created., TC-503: Timestamp is either datetime or None. (+2 more)

### Community 193 - "test_posix_callback.py"
Cohesion: 0.11
Nodes (11): Ansible infrastructure: subprocess, pexpect, JSONL callback wiring.  Contains th, Tests for JSONL callback plugin configuration (TC-067 to TC-071).  Test cases co, TC-068: When bundled dir resolves, aom_jsonl wins over ansible.posix.jsonl., Tests for TC-070: ansible.posix Version Check.      AOM never imports the ansibl, TC-070: When bundled dir missing, callback name is the canonical string., TC-070: ansible.posix.jsonl parses as collection='ansible.posix', plugin='jsonl', TC-070: When bundled aom_jsonl is selected, ansible.posix isn't required., Tests for TC-068: ansible.posix Install Prompt (implicit fallback path).      AO (+3 more)

### Community 194 - "format_tree_block"
Cohesion: 0.12
Nodes (25): format_tree_block(), Render the tree block as a list of lines.      Returns an empty list when the pr, State with two plays, each with a running task on one host.      Built directly, A task under a non-last play must be indented with ``│  ``., A task under the last play must NOT carry a vertical pipe — the     parent is th, ASCII mode renders the continuation as ``|  `` (or equivalent)     rather than t, test_ascii_mode_uses_pipe_substitute(), test_last_play_children_have_plain_indent() (+17 more)

### Community 195 - "merge_limit_args"
Cohesion: 0.20
Nodes (3): merge_limit_args(), Collapse repeated ``-l`` / ``--limit`` flags into a single comma-joined one., TestMergeLimitArgs

### Community 196 - ".update"
Cohesion: 0.13
Nodes (12): Erase the status block and release the terminal., Redraw the status block with new content.          Updates within _THROTTLE_INTE, Queue a log line for printing above the status block.          Leading-edge batc, Drain any buffered log lines in one synchronized frame.          Called by the r, True when the flush window has elapsed (or never started)., Take the queued log lines (each already newline-terminated)., One synchronized frame: pending logs, then the status block., Erase the status content (but leave the display running). (+4 more)

### Community 197 - "_compute_mode_label"
Cohesion: 0.09
Nodes (12): _compute_mode_label(), Replace any lone-surrogate codepoints in ``s`` with U+FFFD.      Pexpect's ``cod, Render the status-bar mode chip(s) from ansible-playbook args.      Recording is, _replace_surrogates(), Return an immutable snapshot of this renderer's activity counters.          Call, Stop rendering and clean up resources.          Restores terminal state, flushes, Start rendering a playbook run.          Initializes the RunState, starts the Ri, Surface a pause / vars_prompt-style prompt and capture one line.          Mirror (+4 more)

### Community 198 - "TestVerboseDiagnostics"
Cohesion: 0.17
Nodes (7): Tests for TC-008: Verbose flag diagnostics., TC-008: --verbose prints resolved ansible-playbook path., TC-008: --verbose prints ANSIBLE_STDOUT_CALLBACK env override., TC-008: --verbose prints terminal capabilities when verbose., TC-008: --verbose without playbook still shows help, not crash., TC-008: --verbose includes --list-tasks summary in diagnostics., TestVerboseDiagnostics

### Community 200 - "_build_compact_renderer"
Cohesion: 0.18
Nodes (14): _build_compact_renderer(), Any, R14 — cap unbounded CompactRenderer sets.  R14 spec: the compact renderer carrie, Construct a CompactRenderer with mocks for its dependencies.      The renderer's, R14: ``_streamed_loop_items`` is bounded at 10 000 entries., R14: ``_announced_task_uuids`` is bounded at MAX_TASKS_PER_PLAY., R14: ``_completed_task_ids`` is bounded at MAX_TASKS_PER_PLAY., R14: ``_seen_warning_messages`` is bounded at 5 000 entries. (+6 more)

### Community 201 - "json.py"
Cohesion: 0.14
Nodes (15): HostCounts, BaseModel, JSON output renderer for AOM (F6).  Implements the Renderer Protocol but produce, Build the RunSummary from accumulated RunState and print as JSON.          ``exi, Per-host status counts aggregated across every task in every play., One (host, task) pair that ended in FAILED or UNREACHABLE., TaskFailure, Path (+7 more)

### Community 202 - "Get All Actions"
Cohesion: 0.20
Nodes (17): _list_tasks_event(), _play_event(), Tree correctness under incremental event replay.  Unlike synthetic-state tests t, Check if a task name appears in the rendered tree block., Replay a 100-task linear playbook event stream, checking the tree for     comple, Specifically test the window between last runner_on_ok and next     task_start:, As tasks complete during event replay, the rendered tree should     shrink once, Simulate start-of-run event with preflight task list. (+9 more)

### Community 203 - "Panel Toggle Keybindings"
Cohesion: 0.15
Nodes (12): _ansible_collection_paths(), CompletedProcess, Path, Integration: the bundled ``aom_jsonl`` callback emits per-item loop events.  ``a, Spawn ``python -m ansible_aom <playbook>`` against a sandboxed HOME.      Exerci, The full ``aom`` pipeline renders one line per loop item, once each., Search-path entries reported by ``ansible-galaxy collection list``.      A sandb, Run ansible-playbook with the bundled callback; return parsed JSONL events. (+4 more)

### Community 204 - "Shift Modifier Keybindings"
Cohesion: 0.25
Nodes (12): _complete_task(), _FakeDisplay, _prior(), Renderer wiring for the live run-duration estimate.  The renderer builds a :clas, _setup(), _task(), test_eta_appears_once_gate_opens(), test_fixed_floor_not_scaled_by_fast_variable_task() (+4 more)

### Community 205 - "unit/test_no_record.py"
Cohesion: 0.21
Nodes (7): _fake_ansible_command(), Path, Unit tests for F3 --no-record plumbing., run_playbook accepts a record=bool kwarg; default is True., `aom --no-record playbook.yml` calls run_playbook(..., record=False)., TestNoRecordCompactPlumbing, TestRunPlaybookRecordParameter

### Community 206 - "Get Keybinding Function"
Cohesion: 0.33
Nodes (5): Design, Problem, Scope, Testing, Worktree-safe version hook design

### Community 207 - "_FakeSink"
Cohesion: 0.15
Nodes (8): _FakeSink, _parser_in_execution_phase(), Return a parser advanced past the PRE_RUN_PROMPTS gate.      ``feed_line`` only, Every successful line fed to ``_feed`` bumps the heartbeat., The task_start line is itself bytes from the subprocess; it must     leave the t, ``reset_heartbeat`` is no longer called on task_start — the         line's own `, TestFeedNotesBytes, TestTaskStartCountsAsHeartbeat

### Community 208 - "TestAnsiblePosixAvailability"
Cohesion: 0.25
Nodes (5): Tests for TC-067: ansible.posix Availability Check (bundled fallback)., TC-067: The bundled aom_jsonl plugin resolves to a real path on disk.          T, TC-067: When bundled plugin file is missing, return None (force fallback)., TC-067: The bundled aom_jsonl.py file exists in the callback directory., TestAnsiblePosixAvailability

### Community 209 - "Ansible Core Version Check"
Cohesion: 0.40
Nodes (4): Gotchas, Recipe, Verifying aom at the terminal surface, What to check

### Community 210 - "session_id_completer"
Cohesion: 0.21
Nodes (10): _default_state_dir(), Any, Path, Shell-completion helpers for the AOM CLI (F5).  Two responsibilities:  1. ``sess, Resolve the default sessions directory.      Mirrors the literal used by ``inspe, Return session IDs under ``state_dir`` whose names start with ``prefix``.      T, session_id_completer(), Path (+2 more)

### Community 211 - "Profile Tracemalloc Wiring"
Cohesion: 0.14
Nodes (12): Enum, V1 stderr classifier — maps raw ansible-playbook stderr lines to typed events., Stable enum of stderr line sources (v1 contract — 12 named values).      Plus an, StderrSource, str, The StderrSource enum is the public contract — 12 named values + UNKNOWN., The enum has 12 named values (per the v1 design) plus an         UNKNOWN catch-a, Every source named in the v1 plan exists in the enum. (+4 more)

### Community 212 - "TestAppConfigFieldTypes"
Cohesion: 0.14
Nodes (8): Tests for AppConfig field types and defaults., log_max_lines is an integer., session_keep_count is an integer., session_keep_days is an integer., status_bar field is StatusBarConfig type., redaction field is RedactionConfig type., warnings field is WarningsConfig type., TestAppConfigFieldTypes

### Community 213 - "test_invariants_session_roundtrip.py"
Cohesion: 0.14
Nodes (18): event_sequences(), _make_play_start(), _make_result(), _make_task_start(), DrawFn, TempPathFactory, Stateful invariants over the session persistence round-trip.  A single sequence, Aggregate ``StatusCounts`` across every task node in the tree.      ``build_task (+10 more)

### Community 214 - "Password Prompt Handling"
Cohesion: 0.40
Nodes (4): Task 1: Pin dispatcher behavior, Task 2: Pin AOM bumper behavior, Task 3: Verify and finish, Worktree-safe Version Hook Implementation Plan

### Community 215 - "Compact Password Passthrough"
Cohesion: 0.12
Nodes (9): Each RedactionConfig instance has independent lists., custom_fields is a list., custom_patterns is a list of dicts., Tests for RedactionConfig model - TC-170, TC-312, TC-313, TC-314., TC-170: RedactionConfig whitelist defaults to empty list., TC-312: RedactionConfig can have custom whitelist., TC-313: RedactionConfig can have custom_fields., TC-314: RedactionConfig can have custom_patterns. (+1 more)

### Community 216 - "TestPasswordPromptHandling"
Cohesion: 0.17
Nodes (7): TC-143 to TC-148: Password prompt handling in PTY stream., TC-143: Password prompts set _pending_password_prompt., Password prompt state cleared after handle_password_prompt., Multiple password prompts - last one wins., Password prompt persists across phase transition., Password prompts still detected in POST_RUN_RECAP (unusual edge case)., TestPasswordPromptHandling

### Community 217 - "cli_main"
Cohesion: 0.21
Nodes (11): _build_parser(), cli_main(), ArgumentParser, Build the ``aom replay`` argument parser.      Factored out of :func:`cli_main`, Entry point for ``aom replay <session-id> [...]``.      Argparse the supplied ta, _make_session(), Path, CLI tests for the F2 `aom replay` subcommand dispatch.  Mirrors the inspect-disp (+3 more)

### Community 218 - "list_sessions"
Cohesion: 0.19
Nodes (9): list_sessions(), List all sessions in the state directory.      Returns sessions sorted by start, Section 9.1: Inspect list command., list_sessions returns empty list when no sessions., list_sessions returns all session summaries., Session UUIDs displayed as first 8 characters in list., list_sessions returns sessions sorted by start time (newest first)., list_sessions includes session status. (+1 more)

### Community 219 - "Width 60-79 Truncation"
Cohesion: 0.17
Nodes (14): _assert_installed(), MonkeyPatch, Path, Verify every CLI entry point installs the diagnostics layer.  Phase 2 of docs/su, ``aom`` with no args prints help and exits cleanly., ``aom inspect --text`` with empty state-dir prints "no sessions"., ``aom rerun --help`` exits via argparse before any rerun logic runs., ``aom replay --help`` exits via argparse before any replay runs. (+6 more)

### Community 221 - "Warning Pattern Classification"
Cohesion: 0.07
Nodes (20): get_status_icon(), Get the icon for a given status.      For RUNNING status, use the frame paramete, TC-367: get_status_icon returns correct icon for FAILED., TC-368: get_status_icon returns correct icon for UNREACHABLE., TC-369: get_status_icon returns first frame for RUNNING by default., TC-369: get_status_icon returns correct frame for RUNNING., TC-369: Frame index wraps around for RUNNING animation., TC-370: get_status_icon returns correct icon for PENDING. (+12 more)

### Community 222 - "collect_failed_hosts"
Cohesion: 0.22
Nodes (6): collect_failed_hosts(), Return the set of hostnames that hit ``v2_runner_on_failed`` in this session., collect_failed_hosts only looks at v2_runner_on_failed., A single failed event can carry multiple hosts., A meta-only session (no events.jsonl) returns an empty set., TestCollectFailedHosts

### Community 223 - "Status Bar Formatting"
Cohesion: 0.16
Nodes (15): _encode_event_line(), _hostname_strategy(), _identifier_strategy(), DrawFn, SearchStrategy, Property-based tests for the JSONL parser (Batch C, family #5a).  These tests as, Arbitrary bytes (decoded loosely) never raise from JsonLineStream.feed_line., Arbitrary bytes (decoded loosely) never raise from PtyStreamParser.feed_line. (+7 more)

### Community 225 - "Panel Refresh Snapshot"
Cohesion: 0.21
Nodes (14): MonkeyPatch, Path, Phase 5: SessionManager writes diagnostics.json next to meta.json.  Spec: docs/s, diagnostics.json write is best-effort: an OSError must not propagate     out of, end_session writes diagnostics.json containing the schema version + histogram., If the run path never published a RunDiagnostics, schema still writes     with z, A session directory without diagnostics.json (older session) is still loadable;, _start_and_end() (+6 more)

### Community 228 - "TestCrossPlayLookupIsolation"
Cohesion: 0.16
Nodes (8): Build a state where play 1 stays active and play 2 shares a task         name th, TC-CROSS-2: When play 2 has a RUNNING task, a previously completed         play, TC-CROSS-1: When handler tasks run under a different play UUID,         the hand, TC-CROSS-3: A play with its own RUNNING task renders correctly         using cro, TC-CROSS-4: ``_play_running_and_pending(play, include_cross_play=True)``, TC-CROSS: Cross-play runtime_by_name lookup must not pollute the     ``any_runni, Build a state with two plays sharing task name "Cleanup tasks".          Play 1, TestCrossPlayLookupIsolation

### Community 230 - "TestConfigFieldValidation"
Cohesion: 0.17
Nodes (7): Tests for edge cases in field validation., Boundary values for log_max_lines are valid., session_keep_count accepts large values., session_keep_days accepts large values., StatusBarConfig elements list preserves order., Multiple config instances are independent., TestConfigFieldValidation

### Community 231 - "TestMixedStreamHandling"
Cohesion: 0.17
Nodes (7): Section 5.6: JSONL events interleaved with plaintext., JSONL events and plaintext interleaved correctly., Plaintext before v2_playbook_on_start is captured., feed_line returns parsed events for JSONL., feed_line returns aom_stderr_line for plaintext., feed_line returns empty for invalid JSON., TestMixedStreamHandling

### Community 232 - "TestMultiPlayTruncationWithRoleFooters"
Cohesion: 0.22
Nodes (7): Multi-play truncation with completed tasks in earlier plays.      Reproduces the, Build the user's exact reproduction state.          Play 1 = ``podman`` (289 dir, Bug 1: the angie role (in the head, before the outer cut) has         127 remain, Bug 2: with nested roles (podman > angie) both roles in the         head have re, Bug 3: the outer footer must report the TOTAL remaining tasks         across ALL, Regression guard: when every task under a role is visible         (remaining ==, TestMultiPlayTruncationWithRoleFooters

### Community 233 - "TestCompactModePasswordPassThrough"
Cohesion: 0.17
Nodes (7): TC-144, TC-145: Compact mode password pass-through., TC-144: Password prompt sets pending state for UI handling., TC-144: All password types set correct pending state., Exact prompt text stored for UI display., Password prompts don't generate JSON events., Clearing prompt allows detecting next password prompt., TestCompactModePasswordPassThrough

### Community 238 - "TestMultiplePlays"
Cohesion: 0.18
Nodes (9): Integration tests for 04-ignore-errors playbook., Parser handles ignore_errors correctly (task fails but playbook continues)., Integration tests for 08-multiple-plays playbook., Parser correctly tracks multiple plays., Integration tests for 04-ignore-errors playbook., Parser handles ignore_errors correctly (task fails but playbook continues)., Integration tests for 08-multiple-plays playbook., TestIgnoreErrors (+1 more)

### Community 239 - "TestWarnings"
Cohesion: 0.17
Nodes (10): Integration tests for 16-warnings playbook., Parser captures [WARNING]: messages., Parser correctly handles multiple hosts with different results., Integration tests for 16-warnings playbook., Parser captures [WARNING]: messages., Parser correctly handles multiple hosts with different results., Integration tests for 16-warnings playbook., Parser captures [WARNING]: messages. (+2 more)

### Community 241 - "TestRewindCorrectness"
Cohesion: 0.25
Nodes (5): The flow that triggered the bug: status, then print_log., The status-block rewind must land on the start of the block, not above it., For a 1-row status, rewind is a carriage return, not cursor-up., For an N-row status, cursor is on the last row, so we rewind N-1 lines., TestRewindCorrectness

### Community 242 - "Task Tree Navigation"
Cohesion: 0.17
Nodes (10): _fake_ansible_command(), Batch E item #10b — R7 Ctrl-C race with completion.  SIGINT can arrive at any of, Same as above but the child failed (exit 2). The real exit         code still wi, If SIGINT arrives *after* ``handle_completion`` has fully run         (i.e. insi, SIGINT before ``playbook_on_stats`` — runner returns 130., Variant A: signal arrives mid-stream, completion never happens., Variant B: completion arrives first, then SIGINT.      R7 spec: completion wins., The run completed cleanly (exit 0). SIGINT arrives during the         ``renderer (+2 more)

### Community 243 - "TestLogging"
Cohesion: 0.07
Nodes (18): Path, TC-455 to TC-464: Logging tests., TC-455: Log file follows XDG state directory convention., TC-456: Log file written but console silent during normal operation., TC-457: RotatingFileHandler with 10MB/file, 5 backups., TC-459 to TC-462: Log levels for different event types., TC-463: --verbose flag enables DEBUG logging to file., TC-463: Without --verbose, INFO level used. (+10 more)

### Community 245 - "Terminal Size Check"
Cohesion: 0.47
Nodes (14): _prior(), Path, Mining per-task wall durations from a prior session's recorded events.  The live, _result(), _stats(), _task_start(), test_classifies_changed_tasks_as_variable(), test_failed_and_unreachable_count_as_variable() (+6 more)

### Community 247 - "Watchdog Timer"
Cohesion: 0.21
Nodes (14): _imports_in(), _iter_modules(), _module_name_for(), Path, Architecture layering enforcement (ARCHITECTURE.md §7.8).  These tests parse eve, ``renderer/protocol.py`` is the port; it must stay abstract., ``drivers/`` couples to the Renderer Protocol, not to a concrete impl.      The, Return every ansible_aom.* module name imported by ``path``.      Walks the AST (+6 more)

### Community 248 - "Cancellation Timer"
Cohesion: 0.13
Nodes (13): Tests for the psutil-safe probe in the runner.  Background: ``_sample_subprocess, If subprocess itself blows up (highly unlikely but defensive), the     helper st, If the subprocess probe exits non-zero (e.g. SIGSEGV at import),     ``_sample_s, The disable reason is surfaced via the diagnostics module so it     lands in dia, The probe is expensive (subprocess spawn). It must be cached so     repeated hea, A successful probe yields a usable psutil module; subsequent     sample calls go, Sanity: the real subprocess probe runs to completion in the test     environment, test_probe_failure_disables_psutil_in_diagnostics() (+5 more)

### Community 249 - "TestFilterPanelTextFilter"
Cohesion: 0.17
Nodes (7): Tests for text filter - TC-302., Sample tasks for filtering., TC-302: Text filter matches substring in task name., TC-302: Text filter is case-insensitive by default., TC-302: Clear filter shows all tasks., TC-302: Regex in text filter (if supported)., TestFilterPanelTextFilter

### Community 253 - "Ansible Args Validation"
Cohesion: 0.15
Nodes (9): get_tree_icon(), Get tree expansion icon.      Args:         expanded: True for expanded node (▼), Tests for TC-373 and TC-374., TC-373: Collapsed tree node displays right arrow (▶)., TC-374: Expanded tree node displays down arrow (▼)., TC-373: get_tree_icon returns correct icon for collapsed node., TC-374: get_tree_icon returns correct icon for expanded node., Tree icons are valid Unicode characters. (+1 more)

### Community 254 - "format.py"
Cohesion: 0.06
Nodes (36): _count_cell(), _format_count_cells(), format_host_summary(), Pure formatters for the compact renderer.  Every public function here takes doma, Render non-zero status count cells.      Order: ok, changed, skipped, failed, un, Format a host summary line with status icons.      Only includes non-zero counts, Right-align ``value`` in a fixed-width cell; dim zero values.      A literal zer, ``text`` wrapped in an SGR sequence, or plain ``text`` if not colorising. (+28 more)

### Community 255 - "Keybinding Conflict Validation"
Cohesion: 0.18
Nodes (10): A classified stderr line.      Carries the full info needed to emit a synthetic, StderrEvent, StderrEvent shape — used by emit code in store.py., StderrEvent is frozen so emit code can rely on it being immutable., Frozen dataclass equality on all four fields., All four fields are required (no defaults)., Real ansible-playbook wraps stderr in SGR escape sequences. The     classifier s, Sanity: clean text is classifiable. (+2 more)

### Community 256 - "test_rerun_cli.py"
Cohesion: 0.32
Nodes (6): _compose_host_set(), Combine the requested host categories into a single set.      Semantics (from th, Unit tests for the aom rerun subcommand., --unreachable is a strict superset of --failed (per spec)., _session_dict(), TestComposeHostSet

### Community 257 - "Keybinding Context Coverage"
Cohesion: 0.18
Nodes (9): generate_uuidv7(), Create a new session and return the session ID (UUIDv7).          Creates the se, Generate a UUIDv7 session ID.      UUIDv7 is time-sortable, which allows session, TC-218: Session UUIDv7 Format Validation., UUIDv7 matches expected format pattern., UUIDv7 values are time-sortable (earlier timestamps produce smaller UUIDs)., First 8 characters of UUIDv7 can be used for display., UUIDv7 embeds timestamp in first segment. (+1 more)

### Community 259 - "TestV2PlaybookOnStatsCrossCheck"
Cohesion: 0.17
Nodes (7): TC-152: Final stats event cross-checks collected hosts.      Production code: ``, TC-152: v2_playbook_on_stats with no failures transitions state to COMPLETED., TC-152: v2_playbook_on_stats with failures transitions state to FAILED., TC-152: v2_playbook_on_stats with unreachable hosts transitions to FAILED., TC-152: Hosts still marked RUNNING at stats time get finalised., TC-152 edge: stats event hosts not seen during the run still process cleanly., TestV2PlaybookOnStatsCrossCheck

### Community 260 - "test_run_state_set_caps.py"
Cohesion: 0.18
Nodes (9): R15 — cap unbounded RunState sets.  R15 spec: ``RunState`` carries several set/d, R15: ``_grafted_uuids`` does not exceed ``MAX_TASKS_PER_PLAY``., R15: ``_grafted_role_names`` is bounded (some reasonable N)., R15: ``_play_window_counts`` is bounded at ``MAX_PLAYS``., R15: ``unknown_events`` keys are bounded by event-type cardinality.      The JSO, test_grafted_role_names_capped(), test_grafted_uuids_capped_at_max_tasks_per_play(), test_play_window_counts_capped_at_max_plays() (+1 more)

### Community 261 - "load_config"
Cohesion: 0.24
Nodes (7): load_config(), Load configuration from YAML file or use defaults.      Args:         config_pat, Tests for load_config function - TC-304 to TC-306., load_config returns AppConfig instance., load_config accepts optional config_path parameter., load_config config_path is str | None., TestLoadConfig

### Community 262 - "Monochrome Terminal Fallback"
Cohesion: 0.24
Nodes (8): HS-1/HS-8: a sustained burst of state changes must not starve the         panel., HS-1/HS-8: dirty but already-rendered state waits for the 1 s         clock-adva, Two update_state calls within the throttle window → 1 panel compute.          ``, tick() with _panel_dirty=False and recent compute skips compute., Sustained log output still lets the compact panel repaint.          The log path, _renderer(), _task_start(), TestDirtyFlagGating

### Community 263 - "TestTerminalSizeCheck"
Cohesion: 0.14
Nodes (11): Tests for CompactRenderer.handle_completion() method., Each significant JSONL event must produce a log line above the panel.          W, Tests for TC-043, TC-044, TC-045: Terminal size requirements., TC-043: Minimum terminal size is 24 lines x 80 columns., Check if terminal meets minimum size., TC-043: Below minimum shows error., TC-043: Minimum size passes check., TC-043: Larger terminal passes check. (+3 more)

### Community 266 - "test_error_handling.py"
Cohesion: 0.03
Nodes (41): Integration tests for error handling (TEST_SPECIFICATION.md Section 14).  Tests, TC-452: Password Timeout - 60 Second Limit., TC-452: Password timeout defaults to 60 seconds., TC-453: Password timeout cancels with error message., TC-454: User can retry after timeout., Additional password timeout mechanism tests., Password prompts match expected patterns., TC-458: Non-blocking QueueHandler. (+33 more)

### Community 267 - "Tree Preservation On Cancel"
Cohesion: 0.25
Nodes (13): Path, Integration tests for the rebuilt `aom inspect` CLI., state_dir(), test_no_arg_invocation_falls_back_to_text_when_non_tty(), test_old_diff_subcommand_is_gone(), test_old_list_subcommand_is_gone(), test_old_show_subcommand_is_gone(), test_prune_subcommand() (+5 more)

### Community 268 - "run_state_status_counts"
Cohesion: 0.27
Nodes (8): run_state_status_counts(), Producer + consumer compose: the ignored failure lands as OK in the         stat, Unit tests for live-state status tallies (aggregate + per-host).  The compact st, A run with two hosts across three tasks, mixed outcomes.      web1: task A ok, t, _run_state(), test_aggregate_status_counts(), test_per_host_status_counts(), test_unreachable_counted()

### Community 269 - "TestDeprecationWarnings"
Cohesion: 0.22
Nodes (8): Integration tests for 17-deprecation-warnings playbook., Parser captures [DEPRECATION WARNING]: messages., Integration tests for 17-deprecation-warnings playbook., Parser captures [DEPRECATION WARNING]: messages., Parser captures PLAY RECAP lines., Integration tests for 17-deprecation-warnings playbook., Parser captures [DEPRECATION WARNING]: messages., TestDeprecationWarnings

### Community 275 - "completion_snippet"
Cohesion: 0.36
Nodes (3): completion_snippet(), Return the rc-file snippet to enable AOM tab-completion in ``shell``.      The s, TestCompletionSnippet

### Community 276 - "_make_state_with_stale_running"
Cohesion: 0.19
Nodes (9): _make_state_with_stale_running(), Regression tests for stale RUNNING hosts in the state model.  When terminal even, host_rows() should not show any host as still running after         the playbook, Cleaning up stale RUNNING hosts must not alter hosts that already         have t, TaskRunState.status should be cleared from RUNNING after         playbook comple, Build a RunState where ipa1 completed task A but is stuck as RUNNING     on task, When playbook ends, stale RUNNING hosts must be cleaned up., After v2_playbook_on_stats, hosts stuck as RUNNING must be         transitioned (+1 more)

### Community 278 - "Crash Recovery Stay Open"
Cohesion: 0.15
Nodes (13): Empirical re-verification (2026-06-30), Open flags (pending input), Q11 — Naming: `--verbose` collision, Q12 — Vault password prompts, Q13.1 — Verbose-line caplevel threshold, Q13.2 — Verbose-line classifier rules, Q13 — Capture `Display.vvvv()` plugin-loader / connection lines, Q14.1 final — Alt 1 (`V` key, context-sensitive) (+5 more)

### Community 279 - "Stderr Capture Handling"
Cohesion: 0.15
Nodes (13): FINAL RECAP, Key design decisions in the plan (locked in), Open decisions to sign off, Q10 — Size caps, Q6 — Live view: failed-task hint, Q7 — Warnings & deprecations, Q8 — Inspect view layout, Q9 — Schema versioning (+5 more)

### Community 284 - "TestAsyncPollDoesNotLeakDictIntoLoopItem"
Cohesion: 0.36
Nodes (5): LoopItem, _make_loop_item(), One entry from a task's loop ``results[]`` array., Async-poll bookkeeping payloads must not leak the raw dict into LoopItem.label., TestAsyncPollDoesNotLeakDictIntoLoopItem

### Community 286 - "TestAppConfigYamlFile"
Cohesion: 0.20
Nodes (6): Tests for Pydantic Settings YAML file integration - TC-304, TC-305, TC-306., TC-304: Default YAML file path is ~/.config/aom/config.yaml., TC-304: YAML path should be expandable to absolute path., TC-304: Config path follows XDG spec (~/.config/aom/config.yaml)., AppConfig uses SettingsConfigDict for configuration., TestAppConfigYamlFile

### Community 287 - "TestConfigFromEnvironment"
Cohesion: 0.20
Nodes (6): Tests for environment variable and YAML config loading., AppConfig can be instantiated without a config file., AppConfig uses defaults when no environment variables set., StatusBarConfig instances with same values are equal., AppConfig properly creates nested config models., TestConfigFromEnvironment

### Community 288 - "TestRedactionCustomPatterns"
Cohesion: 0.20
Nodes (6): Tests for redaction custom patterns - TC-314., Custom patterns use dict with regex and replacement., Multiple custom patterns can be defined., Custom patterns support complex regex patterns., Custom pattern dicts have regex and replacement keys., TestRedactionCustomPatterns

### Community 289 - ".test_recap_lines_captured"
Cohesion: 0.29
Nodes (5): Parser captures PLAY RECAP lines., Syntax error playbook fails before JSONL output starts., Parser captures PLAY RECAP lines., Syntax error playbook fails before JSONL output starts., Syntax error playbook fails before JSONL output starts.

### Community 290 - "TestYesFlag"
Cohesion: 0.17
Nodes (6): Tests for global --yes flag., --yes defaults to False when not provided., --yes is consumed by argparse, not forwarded to ansible-playbook., -y is consumed by argparse, not forwarded to ansible-playbook., Help text for --yes mentions the flag., TestYesFlag

### Community 291 - "test_prior_run_loop_totals_injection.py"
Cohesion: 0.40
Nodes (3): _prior_with_totals(), ``set_prior_run`` injects a prior run's loop totals into the RunState.  The tree, TestCompactInjection

### Community 293 - "test_incremental_counters.py"
Cohesion: 0.27
Nodes (9): TC-PERF-030..031 — incremental task counters on CompactRenderer.  ``count_comple, After each event the incremental counter matches count_completed_tasks., A task that arrives without preflight registration still increments., Re-arriving terminal events for the same task don't double-count., _renderer(), _runner_failed(), _runner_ok(), _task_start() (+1 more)

### Community 294 - "State Transition Validation"
Cohesion: 0.19
Nodes (6): _build_corpus(), _generate_line(), _random_text(), Deterministic fuzz test for the v1 stderr classifier.  Exercises ``classify()``, 10k stderr-like lines must not produce false positives., TestFuzzNoFalsePositives

### Community 295 - "TestMissingAnsiblePlaybook"
Cohesion: 0.20
Nodes (6): TC-465 to TC-468: Missing ansible-playbook detection., TC-465: ansible-playbook not found detected at startup., TC-466: ansible-playbook not found results in exit code 127., TC-467: Error message includes installation suggestions., TC-468: ansible.posix missing shows install command., TestMissingAnsiblePlaybook

### Community 296 - "_visible_projection"
Cohesion: 0.25
Nodes (8): Build a ``TreeProjection`` whose ``is_tree_visible()`` returns True     and whos, A ``kind="more"`` line renders with an empty branch glyph — no     ``├─`` or ``└, A line with ``has_tail_after=True`` draws ``├─`` instead of ``└─``.      Without, The ancestor of a ``has_tail_after=True`` line draws ``│  `` in     its indent c, test_ancestor_spine_continues_under_tail_after(), test_has_tail_after_demotes_last_to_mid(), test_more_kind_suppresses_branch_glyph(), _visible_projection()

### Community 298 - "Core Domain Architecture"
Cohesion: 0.17
Nodes (4): Path, Phase 7: AOM_PROFILE and AOM_TRACEMALLOC wiring.  Spec: docs/superpowers/specs/2, test_dump_profile_noop_when_off(), test_dump_profile_writes_pstats()

### Community 300 - "TestTreeKindIncludesMore"
Cohesion: 0.40
Nodes (3): Regression guard: the ``TreeKind`` Literal must include the     ``"more"`` value, Constructing a TreeLine with ``kind='more'`` is statically valid         — guard, TestTreeKindIncludesMore

### Community 302 - "TestWatchdogTimer"
Cohesion: 0.20
Nodes (6): TC-484 to TC-487: Watchdog timer tests., TC-484: No output for 60 seconds logs WARNING., TC-485: No output for 300 seconds logs ERROR., TC-486: Watchdog timer resets on any subprocess output., TC-487: Watchdog disabled during password prompt phase., TestWatchdogTimer

### Community 304 - "test_config.py"
Cohesion: 0.25
Nodes (5): Unit tests for configuration models in ansible_aom.core.config.  Test cases cove, Tests reinforcing config should not be mutated after creation., Mutating one config's elements doesn't affect others., Nested configs are independent between instances., TestConfigImmutabilityIntent

### Community 306 - "TestFormatFlag"
Cohesion: 0.20
Nodes (4): Tests for F6: --format {compact,json} flag., --format is consumed by argparse, not forwarded to ansible-playbook., `aom --format json playbook.yml` constructs a JsonRenderer., TestFormatFlag

### Community 307 - "TestCoreModuleStructure"
Cohesion: 0.20
Nodes (6): Tests for TC-003: Core Module Structure., TC-003: cli.py module exists., TC-003: __main__.py module exists., TC-003: renderer/ module exists., TC-003: core/ module exists., TestCoreModuleStructure

### Community 308 - ".test_empty_playbook_no_plays"
Cohesion: 0.50
Nodes (3): Parser handles empty playbook (no plays)., Parser handles empty playbook (no plays)., Parser handles empty playbook (no plays).

### Community 309 - "Pre-commit Style Hooks"
Cohesion: 0.40
Nodes (5): mypy type check hook, pytest hook (pre-push only), ruff check hook, ruff format hook, version bumper (not registered)

### Community 311 - "test_skipped_tasks"
Cohesion: 0.67
Nodes (3): Parser correctly identifies skipped tasks., Parser correctly identifies skipped tasks., test_skipped_tasks()

### Community 312 - "test_warning_color.py"
Cohesion: 0.44
Nodes (8): _printed(), Warnings emitted to the log must be coloured yellow and deprecations orange so t, add_warning falls through to a `[WARNING] msg` synthesis when the     raw text d, _renderer(), test_deprecation_wrapped_in_orange(), test_warning_with_synthesised_prefix_also_colored(), test_warning_without_color_when_colorize_off(), test_warning_wrapped_in_yellow()

### Community 317 - "source_hash"
Cohesion: 0.18
Nodes (8): _compute_source_hash(), AOM (Ansible Output Monitor) - nom-style terminal interface for ansible-playbook, Short stable hash of every .py source file under the package.      Companion to, Public wrapper for ``_compute_source_hash``. Cached on first call., source_hash(), ``aom --version`` prints version AND source hash., ``source_hash()`` returns a deterministic short hex digest., A source-file content change must alter the hash.          Verifies the hash act

### Community 318 - "Exit Code Constants"
Cohesion: 0.27
Nodes (4): _confirm(), Print the rerun plan + warning, then ask for Y/n confirmation.      Always print, Bare Enter (empty string) accepts the default Y., TestConfirm

### Community 319 - "_compute_tree_budget"
Cohesion: 0.40
Nodes (4): _compute_tree_budget(), Tree height budget in lines.      Baseline ~½ of terminal rows; +1 line per 3 ac, Render the current tree and host overview as static lines.          Returns a ``, test_compute_tree_budget_math()

### Community 320 - "Stderr Capture Handling"
Cohesion: 0.36
Nodes (11): _printed(), Under the free strategy ``ansible.posix.jsonl`` does not always emit ``v2_playbo, Each host fires runner_start; the header must print only once., Linear strategy fires task_start; free fires runner_start. A run     that emits, _renderer(), _runner_ok(), _runner_start(), test_new_task_after_first_gets_its_own_header() (+3 more)

### Community 321 - "TestConfigPathFlag"
Cohesion: 0.25
Nodes (3): Task 5.2: --config PATH sets the highest-precedence config layer.      The flag, The legacy argv lookup in core/config_layer.py must still find it.          Even, TestConfigPathFlag

### Community 322 - "TestRendererProtocolPasswordHandling"
Cohesion: 0.25
Nodes (5): Test password prompt handling interface for renderer integration., Parser provides interface for password prompt handling., Password prompts detected before playbook starts., Simulate full playbook workflow with parser., TestRendererProtocolPasswordHandling

### Community 330 - "TestCompactModePathUnchanged"
Cohesion: 0.40
Nodes (3): Tests for the CLI's run dispatch paths.  Compact mode uses the legacy ``run_play, The compact path must keep calling run_playbook directly., TestCompactModePathUnchanged

### Community 331 - "test_completion.py"
Cohesion: 0.17
Nodes (8): MonkeyPatch, Unit tests for shell-completion helpers (F5).  Covers: - ``session_id_completer`, F5: session-id positional on the replay parser carries the completer., F5: session-id positional on the rerun parser carries the completer., Smoke test: setting _ARGCOMPLETE causes the parser to short-circuit.      argcom, TestArgcompleteEnvHandoff, TestReplayCLICompleterWiring, TestRerunCLICompleterWiring

### Community 332 - ".test_play_names_extracted"
Cohesion: 0.40
Nodes (3): Play names are correctly extracted., Parser handles handler task events., Parser handles handler task events.

### Community 338 - "Secret Redaction Layers"
Cohesion: 0.23
Nodes (10): _populate(), Phase 13: automatic post-run diagnostics summary on AOM_DEBUG=1.  When the user, No accumulator published yet — still safe to call., set_debug(True) should have same effect as AOM_DEBUG=1 env var., set_debug(False) should suppress the summary., test_print_summary_if_debug_emits_with_debug(), test_print_summary_if_debug_handles_no_run_data(), test_print_summary_if_debug_silent_without_debug() (+2 more)

### Community 339 - "models.py"
Cohesion: 0.02
Nodes (142): _preflight_env(), Pre-flight: parallel `--list-tasks` + `--list-hosts` orchestration.  This module, Spawn a single ansible-playbook invocation; return (exit_code, stdout, stderr)., Environment for preflight subprocesses.      `ANSIBLE_NOCOLOR=1` forces ansible-, _spawn_one(), _build_name_index(), _collect_role_refs_from_tasks(), _discover_include() (+134 more)

### Community 343 - "Become Password Prompt"
Cohesion: 0.23
Nodes (13): _build_parser(), extract_anchors(), main(), parse_anchor(), ArgumentParser, Path, Return ``None`` if the anchor is valid, or a one-line error     message describi, Return a list of broken-anchor error messages for ``doc``.      The list is in c (+5 more)

### Community 344 - "Large Playbook Performance"
Cohesion: 0.18
Nodes (11): Capture & Storage, Configuration, Documentation & Onboarding, Edge Cases & Hardening, Implementation concerns, Inspect View, Live View Behavior, Open architectural (+3 more)

### Community 346 - "_HideStateAction"
Cohesion: 0.50
Nodes (3): Namespace, _HideStateAction, ArgumentParser

### Community 370 - "inspect_model.py"
Cohesion: 0.06
Nodes (55): Connection, NamedTuple, accumulate_session_events(), EventRef, _freeze_map(), _group_key(), _HostAcc, _MutCounts (+47 more)

### Community 374 - "Inspect CLI Module"
Cohesion: 0.27
Nodes (5): _final_line(), Tests for the labeled final-state line in handle_completion.  A bare ✖ told the, Exit code 130 (KeyboardInterrupt) shows 'cancelled by user'., Exit code 127 (command not found) gets its own label., TestCompletionLabel

### Community 383 - "_build_rerun_command"
Cohesion: 0.18
Nodes (9): _build_rerun_command(), Drop any pre-existing ``--limit`` / ``-l`` from the args list.      Handles thre, Construct the (playbook, ansible_args) pair to spawn for the rerun.      The ses, _strip_limit_args(), A pre-existing --limit in the original args is dropped in favour of ours., ``-l`` is the short form of ``--limit``; treat it the same., ``--limit=hosts`` (single arg) is also dropped., No hosts → no rerun. Caller is expected to surface this earlier. (+1 more)

### Community 384 - "test_parser_orjson_swap.py"
Cohesion: 0.22
Nodes (8): Path, TC-PERF-005..007 — orjson swap equivalency tests.  Pin behaviour of ``JsonLineSt, TC-PERF-005: orjson swap is byte-equivalent for real-world fixtures., TC-PERF-006: truncated JSON head is stashed and re-joined.      Equivalent behav, TC-PERF-007: top-level JSON that's not an object is rejected.      A JSON top-le, test_perf_005_parser_byte_equal_to_stdlib(), test_perf_006_carry_buffer_still_works_after_swap(), test_perf_007_non_dict_json_rejected()

### Community 385 - "test_session_store_async_write.py"
Cohesion: 0.12
Nodes (23): Total events dropped across all sessions because a queue was full., _break_events_file(), _build_1mb_event(), Path, R16 — async / non-blocking disk write in session/store.py.  R16 spec: the legacy, R16: ``end_session`` drains the writer, so every recorded event lands     on dis, R16: events and stderr lines share one writer, so their relative     order on di, Requirement: ``end_session`` flushes the writer BEFORE building the     sqlite i (+15 more)

### Community 390 - "Runner Skipped Event"
Cohesion: 0.11
Nodes (17): `aom inspect` Rebuild Implementation Plan, File structure, Plan self-review notes, Task 10: Test-leakage fix (autouse `isolated_state_dir`), Task 11: TUI screen — Runs pane (left), Task 12: TUI screen — Tasks pane (middle), Task 13: TUI screen — Detail pane (right) + R/y bindings, Task 14: Manual smoke test + suite green (+9 more)

### Community 400 - "rerun/cli.py"
Cohesion: 0.20
Nodes (8): main(), CLI entry point for ``aom rerun``.  Reads a recorded session, derives a host lis, Return the recorded ``ansible_args`` or refuse with a clear error.      Sessions, CLI entry point for ``aom rerun``.      Args:         argv: Argument list. If No, _require_ansible_args(), An explicit [] is valid — the user originally ran `aom site.yml`., A null value (rare, but possible if hand-edited) is also missing., TestRequireAnsibleArgs

### Community 402 - "Task Liveness Indicator"
Cohesion: 0.12
Nodes (16): Architecture, Byte notifications, `core/heartbeat.py`, CPU sampling, Edge cases, Goal, Implementation order, Liveness indicator for the running task (+8 more)

### Community 461 - "test_icons.py"
Cohesion: 0.20
Nodes (6): Unit tests for status icon mapping in ansible_aom.core.icons.  Test cases cover, Tests ensuring icon uniqueness (no collisions)., All status icons should be distinct (except COMPLETED=OK)., All ASCII fallback icons should be distinct (except COMPLETED=OK)., All color names should be valid Rich color names., TestStatusIconUniqueness

### Community 462 - "test_pause_lingering_cleanup.py"
Cohesion: 0.40
Nodes (6): _play_start(), Regression: a pause task that is the last task of its play must not linger as RU, Finalising a prior play must not stomp hosts that already have a         termina, _state_with_two_plays(), _task_start(), TestPauseLingerCleared

### Community 465 - "TestClassifierRules"
Cohesion: 0.20
Nodes (6): No two rules share the same first matching token (first-match-wins         would, CLASSIFIER_RULES shape and ordering — the engine of the classifier., The plan calls for 30 rules; we accept more but not fewer., Each rule is ``(source, regex, has_host)``., Each rule's regex is a pre-compiled ``re.Pattern`` (hot path)., TestClassifierRules

### Community 466 - "DOCUMENTATION CHECKLIST (added per user question 2026-06-30)"
Cohesion: 0.22
Nodes (8): Ansible Verbosity Handling in AOM: Brainstorm / Discovery Notes, DOCUMENTATION CHECKLIST (added per user question 2026-06-30), Missing docs to consider creating, Per-feature doc mapping (compact view), Source code docstrings (4 files to update), Suggested doc-update order, Summary / key decisions (running synthesis, updated as answers come in), Total scope

### Community 467 - "QC REVIEW (grumpi-qa) — 2026-06-30"
Cohesion: 0.22
Nodes (9): 1. Executive roast summary, 2. Quality scorecard, 3. Findings table, 4. Performance and scalability concerns, 5. Security and reliability concerns, 6. Testing gaps, 7. Maintainability cleanup plan, 8. Final note to the developer (+1 more)

### Community 478 - "test_completion_summary.py"
Cohesion: 0.28
Nodes (8): Tests for the host table printed by handle_completion.  After completion, the re, Build a RunState where web1 had 2 OK + 1 changed, web2 had 1 OK + 1 failed., On failure, the host table is included in the snapshot output., If no hosts ran (preflight-only failure), don't print a host table., _state_with_two_hosts(), test_completion_no_host_rows_when_no_hosts(), test_completion_prints_host_table_with_counts(), test_completion_snapshot_contains_host_rows()

### Community 479 - "format_age"
Cohesion: 0.15
Nodes (18): format_age(), format_duration_compact(), format_elapsed_hms(), datetime, Pure formatters for durations and relative ages.  These functions are used where, Render a duration as the most compact human form ("42s", "1m23s", "1h05m")., Render an elapsed time as ``M:SS`` (under an hour) or ``H:MM:SS``.      Used by, Render an absolute UTC ``end_time`` as a relative ``"Xs/m/h/d ago"`` string. (+10 more)

### Community 480 - "_run_cli"
Cohesion: 0.28
Nodes (8): CompletedProcess, Batch E item #9 — CLI matrix smoke.  Every subcommand's ``--help`` exits 0, and, Spawn ``python -m ansible_aom <argv>`` and return the completed proc., Every documented subcommand's ``--help`` exits 0 with a usage banner., Documented mutually-exclusive combos must reject with a useful message., _run_cli(), test_help_exits_zero(), test_mutex_rejected()

### Community 481 - "test_history_loop_totals.py"
Cohesion: 0.50
Nodes (8): _loop_aggregate(), _prior(), Path, Mining per-host loop totals from a prior session's recorded events.  The live ru, test_loop_totals_default_empty_without_events_file(), test_mines_loop_total_per_task_path_and_host(), test_non_loop_events_are_excluded(), _write_session_with_events()

### Community 486 - "IO"
Cohesion: 0.11
Nodes (13): IO, check_terminal_size(), Display logic for compact mode — nom-style fixed-bottom status panel.  Renders d, Check if terminal meets minimum size requirements.      Args:         lines: Num, print_summary_if_debug(), Emit a single-line ``[aom-debug] …`` post-run digest to ``file``.      Silent un, Tests for nom-style ANSI rendering in compact mode.  These tests pin the new-spe, Each Display.update() in TTY mode emits a single DEC 2026 frame. (+5 more)

### Community 487 - "TestHostExtraction"
Cohesion: 0.22
Nodes (4): Host is extracted from ``<hostname>`` prefix when present., A line without ``<...>`` prefix has no host even if rule says has_host., Even with a stale ``<...>`` in the regex, run-level sources         don't extrac, TestHostExtraction

### Community 488 - "Q&A log"
Cohesion: 0.25
Nodes (8): Q1.1 — Schema extension shape (auto-derived from Q1=B), Q1 — Mental model check (capture philosophy), Q2 — Redaction policy, Q3 — Default capture state, Q4.2 — Config-file scope, Q4.3 — Old config path compatibility, Q4 — Setup module exclusion, Q&A log

### Community 514 - "TestClassifyEmpty"
Cohesion: 0.25
Nodes (5): classify() must never crash on empty / whitespace input., Empty line → UNKNOWN source, no host, no level., Whitespace-only line → UNKNOWN., A line matching no rule → UNKNOWN, original text preserved., TestClassifyEmpty

### Community 515 - "Top-level .md files (6 to update)"
Cohesion: 0.29
Nodes (7): AGENTS.md (127 lines), ARCHITECTURE.md (562 lines), README.md (243 lines), SPECIFICATION.md (3262 lines) — heaviest changes, TEST_PLAYBOOKS.md, TEST_SPECIFICATION.md (very large), Top-level .md files (6 to update)

### Community 527 - "CallbackModule"
Cohesion: 0.24
Nodes (4): CallbackModule, Write one JSONL event for a single completed loop item.          Mirrors the par, Preserve ``ignore_errors`` in the emitted event.          Ansible calls ``v2_run, Emit the per-host start event WITH the host's name.          The parent emits ``

### Community 532 - "TestClassifyWarning"
Cohesion: 0.29
Nodes (3): [WARNING]: lines are run-level (no host)., The WorkerProcess warning is also classified as warning., TestClassifyWarning

### Community 533 - "Appendix: Anchor research notes"
Cohesion: 0.33
Nodes (6): A. JSONL event types in current AOM parser (`core/run_state.py:handler_map`), Appendix: Anchor research notes, B. Verbosity-gated content in JSONL, C. JSONL-emitted verbose fields (already in stream, just stripped on persist), D. Verbosity-gated content NOT in JSONL (lives in PTY stderr), E. Anchor files (for later implementation)

### Community 560 - "._render_status_panel"
Cohesion: 0.06
Nodes (33): count_completed_tasks(), count_total_tasks(), count_total_tasks_seen(), Sum of leaf tasks across all preflight play definitions.      Used for the statu, Running upper bound on task count for the status-bar denominator.      Preflight, Count tasks across all plays whose hosts have all reached terminal state.      T, Handle playbook completion (success/failure/crash).          Shows final status, Store preflight definitions and emit the startup summary.          Two effects: (+25 more)

### Community 575 - "TestClassifyError"
Cohesion: 0.33
Nodes (3): [ERROR]: lines and unbracketed preflight ERROR: lines., Unbracketed ``ERROR:`` from cli/__init__.py preflight path., TestClassifyError

### Community 576 - "TestClassifySshDebug"
Cohesion: 0.33
Nodes (3): ``<host> SSH:`` lines from ssh.py (caplevel 4+)., SSH: without a host prefix still classifies as ssh_debug with no host., TestClassifySshDebug

### Community 577 - "TestLevelMap"
Cohesion: 0.33
Nodes (3): LEVEL_MAP drives the 'level' field on emitted events., Lock the v1 level mapping to a public contract., TestLevelMap

### Community 578 - "TestFirstMatchWins"
Cohesion: 0.33
Nodes (4): When two rules could match, the first one in CLASSIFIER_RULES wins., ``<web1> SSH: SSH_AGENT ...`` should hit the SSH_AGENT rule,         not the gen, ``Failed to connect to the host via ssh:`` could potentially         collide wit, TestFirstMatchWins

### Community 602 - "test_replay_determinism.py"
Cohesion: 0.11
Nodes (29): _empty_preflight(), _events_same_name_concurrent_tasks_repro(), _events_serial_run_once_repro(), _fake_ansible_command(), CaptureFixture, Path, Build a (cmd, args) pair that emits ``events`` as JSONL then exits., Preflight result that contributes nothing — mirrors a fake shim where     ``--li (+21 more)

### Community 603 - "test_password.py"
Cohesion: 0.29
Nodes (5): handle_password_prompt(), Any, Password handling for compact mode.  The pure detection heuristic (:func:`is_pas, Handle password prompt using terminal pass-through for compact mode.      The ca, Tests for password prompt handling — TC-143 through TC-145, TC-148.  Covers: - T

### Community 613 - "11. CLI flags & config (answers Q33–Q36, plus Q4.2 refactor)"
Cohesion: 0.50
Nodes (4): 11. CLI flags & config (answers Q33–Q36, plus Q4.2 refactor), Capture CLI flags (locked in per Q3=B, Q4=A, Q11=A), Config schema (excerpt, `~/.config/aom/aom_config.yaml`), Multi-layer config (locked in per Q4.2=B, Q4.3, Q17)

## Knowledge Gaps
- **408 isolated node(s):** `graphify-refresh.sh script`, `GRAPHIFY_VIZ_NODE_LIMIT`, `pre-commit-wrapper.sh script`, `ansible-aom`, `install-hooks.sh script` (+403 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **307 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `RunState` connect `RunState` to `HostRunState`, `StatusBarConfig`, `.from_run_state`, `TaskDefinition`, `CompactRenderer`, `_play_start`, `_BoundedDict`, `TreeProjection`, `Inspect CLI Commands`, `RoleGroupDefinition`, `test_task_completion.py`, `datetime`, `_play_start`, `runner.py`, `TestTemplateVariableNameMismatch`, `._render_status_panel`, `TestUngroupedRoleTasksInTree`, `JsonlEvent`, `RunDiagnostics`, `test_tree_render.py`, `test_tree_classify_and_role_labels.py`, `JsonRenderer`, `event_types.py`, `TestHandleEventMalformedPayloads`, `TestTimestampLocalTimezone`, `parse_jsonl_output`, `TestEventParsing`, `_drive`, `_state_with_play`, `Playbook Event Parsing`, `run_playbook`, `PlayDefinition`, `TestSubtreeRoleCounting`, `Pane Focus Navigation`, `Log Panel Widget`, `format_host_rows`, `_make_play`, `assemble_definitions`, `TestTwoLevelTruncation`, `RunSummary`, `Runner Heartbeat Wiring`, `parity.py`, `TestRuntimeRoleTaskCount`, `TestNoRedactFlag`, `Status`, `test_cli.py`, `test_run_state_memory_bounds.py`, `test_loop_item_count.py`, `TestWarningVisibilityCompactPlumbing`, `test_properties_state.py`, `Stale Running Cleanup`, `format_tree_block`, `_compute_mode_label`, `TestVerboseDiagnostics`, `json.py`, `Get All Actions`, `_FakeSink`, `test_invariants_session_roundtrip.py`, `TestCrossPlayLookupIsolation`, `TestMultiPlayTruncationWithRoleFooters`, `TestMultiplePlays`, `TestWarnings`, `format.py`, `TestV2PlaybookOnStatsCrossCheck`, `test_run_state_set_caps.py`, `run_state_status_counts`, `TestDeprecationWarnings`, `_make_state_with_stale_running`, `TestYesFlag`, `TestCaptureSetupFlag`, `_visible_projection`, `TestHideWarningsFlag`, `TestFormatFlag`, `TestCoreModuleStructure`, `TestConfigPathFlag`, `models.py`, `TestCaptureVerboseFlag`, `TestNoFailedHintFlag`, `TestHideDeprecationsFlag`, `test_pause_lingering_cleanup.py`, `test_completion_summary.py`?**
  _High betweenness centrality (0.154) - this node is a cross-community bridge._
- **Why does `Status` connect `Status` to `HostRunState`, `PtyStreamParser`, `RunState`, `TestV2PlaybookOnStatsCrossCheck`, `StatusBarConfig`, `TestTerminalSizeCheck`, `.from_run_state`, `WarningType`, `_make_play`, `TaskDefinition`, `CompactRenderer`, `TestDeprecationWarnings`, `assemble_definitions`, `_play_start`, `_BoundedDict`, `WarningEntry`, `RunSummary`, `TestTwoLevelTruncation`, `TreeProjection`, `_make_state_with_stale_running`, `parity.py`, `TestRuntimeRoleTaskCount`, `RoleGroupDefinition`, `TestProjectionLifecycle`, `TestYesFlag`, `TestCaptureSetupFlag`, `TestNoRedactFlag`, `Dirty Flag Throttle`, `format_status_bar`, `TestHideWarningsFlag`, `TestPerEventLogColors`, `TestTemplateVariableNameMismatch`, `TestTreeKindIncludesMore`, `test_cli.py`, `TestFormatFlag`, `TestFilterPanelHostFilter`, `TestCoreModuleStructure`, `test_loop_item_count.py`, `RendererMirrorMachine`, `TestUngroupedRoleTasksInTree`, `TestWarningVisibilityCompactPlumbing`, `JsonlEvent`, `TestMultiLineWarningContinuation`, `TestConfigPathFlag`, `format_tree_block`, `test_tree_classify_and_role_labels.py`, `TestVerboseDiagnostics`, `renderer.py`, `TestVerboseAlwaysMsgDisplay`, `json.py`, `test_pause_lingering_cleanup.py`, `JsonRenderer`, `models.py`, `TestPasswordPromptPatterns`, `TestCaptureVerboseFlag`, `TestHideDeprecationsFlag`, `TestNoFailedHintFlag`, `TestHandleEventMalformedPayloads`, `TestTimestampLocalTimezone`, `TestEventParsing`, `Warning Pattern Classification`, `Pane Focus Navigation`, `TestCrossPlayLookupIsolation`, `TestMultiPlayTruncationWithRoleFooters`, `TestMultiplePlays`, `TestWarnings`, `PlayDefinition`, `TestSubtreeRoleCounting`, `TestFilterPanelTextFilter`, `TestStatusBarAvailableElements`, `Pydantic Model Basics`, `format.py`?**
  _High betweenness centrality (0.112) - this node is a cross-community bridge._
- **Why does `CompactRenderer` connect `CompactRenderer` to `HostRunState`, `Compact Display Logic`, `Renderer Parity Invariant`, `Password Prompt Patterns`, `Monochrome Terminal Fallback`, `TestTerminalSizeCheck`, `Display`, `Parser Phase Transitions`, `Inspect CLI Commands`, `StatusCounts`, `parity.py`, `Event Log Emission`, `TestProjectionLifecycle`, `Psutil Safe Probe`, `test_incremental_counters.py`, `TestPasswordPromptPTYIntegration`, `TestCaptureSetupFlag`, `format_status_bar`, `Tree Expansion Icons`, `Renderer`, `TestPasswordTimeoutDefault`, `TestPerEventLogColors`, `TestHideWarningsFlag`, `Status`, `TestNoRedactFlag`, `._render_status_panel`, `test_cli.py`, `TestFormatFlag`, `TestCoreModuleStructure`, `history.py`, `App Config Model Tests`, `TestYesFlag`, `RendererMirrorMachine`, `test_warning_color.py`, `JsonlEvent`, `TestWarningVisibilityCompactPlumbing`, `test_prior_run_loop_totals_injection.py`, `_fresh_display`, `test_tree_render.py`, `HeartbeatTracker`, `Stderr Capture Handling`, `_compute_tree_budget`, `Playbook Run Integration Tests`, `TestConfigPathFlag`, `_compute_mode_label`, `TestVerboseDiagnostics`, `renderer.py`, `TestVerboseAlwaysMsgDisplay`, `_build_compact_renderer`, `.handle_password_prompt`, `test_full_completion_summary.py`, `Shift Modifier Keybindings`, `TestPasswordPromptPatterns`, `TestCaptureVerboseFlag`, `TestHideDeprecationsFlag`, `TestNoFailedHintFlag`, `Preflight Definition Assembly`, `test_replay_determinism.py`, `test_completion_summary.py`, `Mitogen Event Robustness`, `Completion State Labels`, `RunSummary Schema Contract`, `Playbook Event Parsing`, `create_renderer`, `Inspect CLI Module`, `format.py`?**
  _High betweenness centrality (0.104) - this node is a cross-community bridge._
- **Are the 253 inferred relationships involving `RunState` (e.g. with `_NullSink` and `_SessionSink`) actually correct?**
  _`RunState` has 253 INFERRED edges - model-reasoned connections that need verification._
- **Are the 172 inferred relationships involving `TaskDefinition` (e.g. with `_count_role_group_tasks()` and `_count_tasks()`) actually correct?**
  _`TaskDefinition` has 172 INFERRED edges - model-reasoned connections that need verification._
- **Are the 181 inferred relationships involving `CompactRenderer` (e.g. with `Display` and `RunEstimate`) actually correct?**
  _`CompactRenderer` has 181 INFERRED edges - model-reasoned connections that need verification._
- **Are the 118 inferred relationships involving `PtyStreamParser` (e.g. with `_NullSink` and `_SessionSink`) actually correct?**
  _`PtyStreamParser` has 118 INFERRED edges - model-reasoned connections that need verification._