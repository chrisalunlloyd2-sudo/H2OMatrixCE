# H2OMatrixCE

> H2OMatrixCE — part of the Viper RAID-0 workstation system.

*Auto-generated 2026-08-14 03:52 from source — branch `main`, 59 Python modules, 68 other files.*

## Architecture

```
  .director_payload.md
  .gitconfig
  .gitignore
  900_STEPS_SINGULARITY.md
  BUDGET_CREDITS.md
  Blueprint.md
  CHANGELOG.md
  CLIDE_SPEC.md
  ENTERPRISE_INIT.p
  GEMINI.md
  H2O_MATRIX_SOP.p
  LOGOS_PURPOSE.md
  GAME_SUBSTRATE/
    mechanics/
      AGENT_LAYER.py
      CYBER_CANVAS_TUI.py
      DETERMINISTIC_PHYSICS.py
  H2OIDE/
    Blueprint.md
    CHANGELOG.md
    DATA_FLOW.md
    ENTERPRISE_INIT.p
    GLOBAL_PEDAGOGY.md
    PEDAGOGY_LEDGER_DUMP.sql
    PROJECT_LOG.md
    PROMPT_GUIDE.md
    README.md
    README_ENTERPRISE.md
    SESSION_CHATS.jsonl
    agy
    skills/
      terminal.json
    teaching_sandbox/
      a.py
  PocketMatrix/
    build_apk/
      AndroidManifest.xml
      compiled_res.zip
      bin/
        PocketMatrix.stable.zip
        classes.dex
        debug.keystore
      obj/
      res/
      src/
    core/
      build_manifest.json
      cegcc/
        README.md
      wcecl/
    documents/
      PROJECT_GENETIC_FLOW/
        topology.json
      PROJECT_H2O/
        continue_config.json
    system/
      ce_simulator.py
      chat_harvester.py
      datacenter_sync.sh
      fault_injector.py
      google_bridge.py
      gui_bridge.py
      headless_bridge.py
      ingestion_engine.py
      positive_ping.py
      quarantine_filter.py
      telemetry_parser.py
      templates/
        desktop.html
  VIPER_SCRIPT_LIBRARY/
  agy-cli-go/
    agy-go
    go.mod
    main.go
  build_staging/
    agy
  genetic_flow/
    .aider.conf.json
    .env
    .gitignore
    __init__.py
    install_genetic_flow.sh
    runtime_loop.py
    ...
```

## Dependencies

External packages imported by this project:

`PocketMatrix`, `asyncpg`, `bs4`, `core_brain`, `dis`, `dotenv`, `email`, `flask`, `genetic_flow`, `gkeepapi`, `kqml_protocol`, `openai`, `rag_pipeline`, `requests`, `rich`, `smtplib`

## How to run

Executable entry points (have a `__main__` block):

- `python GAME_SUBSTRATE/mechanics/AGENT_LAYER.py`
- `python GAME_SUBSTRATE/mechanics/CYBER_CANVAS_TUI.py`
- `python GAME_SUBSTRATE/mechanics/DETERMINISTIC_PHYSICS.py`
- `python H2OIDE/daemon.py`
- `python H2OIDE/initialize_enterprise_project.py`
- `python H2OIDE/network_hook.py`
- `python H2OIDE/pedagogy_loop.py`
- `python PEDAGOGY_HARVESTER.py`
- `python PocketMatrix/system/ce_simulator.py`
- `python PocketMatrix/system/chat_harvester.py`
- `python PocketMatrix/system/fault_injector.py`
- `python PocketMatrix/system/google_bridge.py`

## Modules

### `GAME_SUBSTRATE/mechanics/AGENT_LAYER.py`

- `auto_configure(intent)` — Detects intent and changes system settings automatically.

### `GAME_SUBSTRATE/mechanics/DETERMINISTIC_PHYSICS.py`

- **class `StateMachine`**
  - methods: `process_input`, `update`

### `H2OIDE/daemon.py`

- `call_llm(prompt)`
- `process_batch(lines)`
- `main()`

### `H2OIDE/genetic_optimizer.py`

- `fitness(response_text, duration)`

### `H2OIDE/initialize_enterprise_project.py`

- `get_token()`
- `generate_ascii_tree(path)` — ASCII tree generator.
- `initialize()`

### `H2OIDE/network_hook.py`

- `webhook()`

### `H2OIDE/pedagogy_loop.py`

- `log_to_ledger(task, cmd)`
- `call_llm_agy(task)`
- `teach()`

### `PEDAGOGY_HARVESTER.py`

- `harvest()` — Autonomous Pedagogy Harvester

### `PocketMatrix/system/ce_simulator.py`

- **class `CESubstrateSimulator`** — Simulates a remote Windows CE device for local testing and pedagogy.
  - methods: `get_status`, `simulate_shell`

### `PocketMatrix/system/chat_harvester.py`

- `extract_todos()`

### `PocketMatrix/system/fault_injector.py`

- **class `DynamicFaultInjector`**
  - methods: `inject_fault`, `tutor_student`

### `PocketMatrix/system/google_bridge.py`

- `load_credentials()` — Loads Google credentials (Email and App Password) from config.
- `send_gmail(to_addr, subject, body, retries)` — Sends an email via Gmail SMTP using an App Password with exponential backoff.
- `sync_keep(tasks, retries)` — Syncs the local PocketMatrix ToDo database with Google Keep with backoff.

### `PocketMatrix/system/gui_bridge.py`

- `desktop()`
- `omni_chat()`
- `list_projects()`
- `list_databases()`
- `query_database()`
- `update_database()`
- `handle_notes()`
- `handle_todo()`
- `sync_todo_google()`
- `get_mail()`
- `send_mail()`
- `web_crawl()`
- `get_tasks()`
- `list_files()`
- `read_file()`

### `PocketMatrix/system/headless_bridge.py`

- **class `HeadlessBridge`**
  - methods: `translate_and_execute`

### `PocketMatrix/system/ingestion_engine.py`

- **class `IngestionEngine`**
  - methods: `clean_text`, `fetch_and_parse`, `format_for_danube`

### `PocketMatrix/system/positive_ping.py`

- `generate_ping()`

### `PocketMatrix/system/quarantine_filter.py`

- `isolate_anomalies()`

### `PocketMatrix/system/telemetry_parser.py`

- **class `TelemetryParser`**
  - methods: `generate_mock_telemetry`, `analyze_telemetry`

### `TODO_SCANNER.py`

- `scan_todos()` — High-Fidelity Todo Scanner
- `cleanup_completed()` — Removes [x] tasks from substrate to keep entropy low.
- `update_syphon(all_todos)` — Injects aggregated todos into the CHAT_SYPHON.md manifest.

### `complete_roadmap.py`

- `complete_roadmap(file_path)`

### `genetic_flow/cluster/sync_hook.py`

- `sync_bayesian_weights()` — Bridge ledger.db quantum_parameters into the genetic flow loop.
- `export_optimization_stats()` — Export genetic progress back to the main IDE ledger.

### `genetic_flow/cluster/topology_mapper.py`

- `initialize_cluster_table()`
- `update_heartbeat(node_id)` — Updates the heartbeat for a specific cluster node.
- `get_cluster_topology()` — Returns a string representation of the cluster topology for the TUI.

### `genetic_flow/core_brain/binary_engine/decompiler.py`

- **class `BinaryDecompilationEngine`** — Airgapped processor that translates Python logic into binary opcode math.
  - methods: `decompile_and_score`

### `genetic_flow/core_brain/router.py`

- **class `LocalAgentRouter`** — [PERFORMATIVE: ROUTE] Native 32-bit llama-cli Wrapper with KQML/Vector Handoff.
  - methods: `get_management_rules`, `run_generation`, `clean_code`
- `extract_clean_code(raw_stream)`

### `genetic_flow/core_brain/target_feature.py`

- `algorithm(n)`

### `genetic_flow/core_brain/test_harness.py`

- **class `StatisticalEvaluator`** — [PERFORMATIVE: EVALUATE] Evaluates microsecond trends via IQR variance algorithms (Pure Python).
  - methods: `evaluate_performance`
- `evaluate()`

### `genetic_flow/core_brain/tui_layout.py`

- `get_last_insight()`
- `generate_dashboard(gen, fitness, code_str, stuck_count, max_stuck, sprite_status)`

### `genetic_flow/core_brain/watchdog.py`

- **class `Watchdog`**
  - methods: `check_stagnation`, `get_hyperparameter_adjustment`, `trigger_cloud_escalation`

### `genetic_flow/master_logic/gemini_agent.py`

- `get_embedding(text)`
- `fetch_memory_context(goal)`
- `run_cmd(cmd)`
- `fix_step(step_data, error_output, sys_constraints, decompiler, max_retries)`
- `main(goal)`

### `genetic_flow/memory_daemon/gemini_client.py`

- `send_to_daemon(command, exit_code)`

### `genetic_flow/memory_daemon/gemini_daemon.py`

- `process_and_store(payload)` — The heavy lifting she does silently after your terminal is already free.
- `handle_connection(reader, writer)` — Instantly accepts data from your shell hook and releases it.
- `main()`

### `genetic_flow/memory_pipeline/audio_engine.py`

- **class `AudioManifestationEngine`** — [PHASE 5.2/5.3] Headless TTS & Async Streaming Engine.
  - methods: `speak`, `run_audio_feedback`

### `genetic_flow/memory_pipeline/headless_orchestrator.py`

- **class `HeadlessOrchestrator`**
  - methods: `handle_input`

### `genetic_flow/memory_pipeline/rag_interceptor.py`

- **class `SimpleEmbedder`** — Computes fixed-dimension semantic vector via hashing.
  - methods: `embed`
- **class `RAGInterceptor`**
  - methods: `pre_flight_query`, `log_event`

### `genetic_flow/pyramid/code_sprite.py`

- **class `CodeSprite`** — Autonomous Dependency Sprite: Scans for imports and manifests environment.
  - methods: `_get_installed_packages`, `scan_and_fix`

### `genetic_flow/runtime_loop.py`

- `main_loop(max_gen)`

### `genetic_flow/symbolic_brain/engine.py`

- **class `SymbolicContextEngine`** — [PERFORMATIVE: TOKENIZE] Compiles dynamic AST tree; extracts parent/child shapes.
  - methods: `get_structural_signature`, `_walk_signature`, `generate_context_hash`, `update_relational_matrix`
- **class `ProductionRuleMatcher`** — [PERFORMATIVE: MATCH] Inductive Logic Loop matching pattern variations.
  - methods: `match_rule`
- **class `MutationInjector`** — [PERFORMATIVE: INJECT] Executes physical AST block mutations.
  - methods: `apply_mutation`
- **class `WeightBackpropagator`** — [PERFORMATIVE: UPDATE] Symbolic Backprop Step.
  - methods: `backprop`

### `genetic_flow/symbolic_brain/extractor.py`

- **class `SymbolicExtractor`** — Extracts symbolic rules from successful mutations in the ledger.
  - methods: `analyze_patterns`

### `genetic_flow/symbolic_brain/parser.py`

- **class `SymbolicParser`** — [PERFORMATIVE: TOKENIZE] Compiles live files into structured AST nodes.
  - methods: `get_signature_hash`, `_get_structural_string`, `map_token_relations`

### `genetic_flow/symbolic_brain/symbolic_inference.py`

- **class `SymbolicInference`** — [PERFORMATIVE: INFER] Selects target execution transformation rules.
  - methods: `infer_optimization_directive`

### `genetic_flow/symbolic_brain/weight_backprop.py`

- **class `WeightBackprop`** — [PERFORMATIVE: UPDATE] Calculates code fitness improvements and updates rule weights.
  - methods: `update_rule_weights`

### `genetic_flow/tracking_db/writer.py`

- `get_git_hash()`
- `store_mutation(chash, gen, score, code, task, ast_depth, stagnation, latency_delta)`

### `genetic_optimizer.py`

- `fitness(response_text, duration)`

### `initialize_enterprise_project.py`

- `get_token()`
- `generate_ascii_tree(path)` — Simple ASCII tree generator.
- `initialize()`

### `predictive_wrapper.py`

- **class `PredictiveGuard`**
  - methods: `setup_db`, `get_mem_info`, `predict_fault`, `monitor_loop`, `mitigate`

### `scientific_executor.py`

- `log_scientific_step(step_num, step_desc, observation, hypothesis, experiment, result)`
- `get_next_step()`
- `mark_step_complete(step_num)`
- `run_with_limits(command)`
- `execute_step(step_num, step_desc)`

### `scientific_orchestrator.py`

- **class `ScientificOrchestrator`**
  - methods: `log_scientific_step`, `get_next_step`, `mark_step_complete`, `run_with_limits`, `orchestrate`

### `scrub_engine.py`

- `scrub_content(content)`
- `scrub_file(file_path)`

## Public API index

| Module | Function | Signature |
|--------|----------|-----------|
| `AGENT_LAYER` | `auto_configure` | `auto_configure(intent)` |
| `PEDAGOGY_HARVESTER` | `harvest` | `harvest()` |
| `TODO_SCANNER` | `cleanup_completed` | `cleanup_completed()` |
| `TODO_SCANNER` | `scan_todos` | `scan_todos()` |
| `TODO_SCANNER` | `update_syphon` | `update_syphon(all_todos)` |
| `chat_harvester` | `extract_todos` | `extract_todos()` |
| `complete_roadmap` | `complete_roadmap` | `complete_roadmap(file_path)` |
| `daemon` | `call_llm` | `call_llm(prompt)` |
| `daemon` | `main` | `main()` |
| `daemon` | `process_batch` | `process_batch(lines)` |
| `gemini_agent` | `fetch_memory_context` | `fetch_memory_context(goal)` |
| `gemini_agent` | `fix_step` | `fix_step(step_data, error_output, sys_constraints, decompiler, max_retries)` |
| `gemini_agent` | `get_embedding` | `get_embedding(text)` |
| `gemini_agent` | `main` | `main(goal)` |
| `gemini_agent` | `run_cmd` | `run_cmd(cmd)` |
| `gemini_client` | `send_to_daemon` | `send_to_daemon(command, exit_code)` |
| `gemini_daemon` | `handle_connection` | `handle_connection(reader, writer)` |
| `gemini_daemon` | `main` | `main()` |
| `gemini_daemon` | `process_and_store` | `process_and_store(payload)` |
| `genetic_optimizer` | `fitness` | `fitness(response_text, duration)` |
| `genetic_optimizer` | `fitness` | `fitness(response_text, duration)` |
| `google_bridge` | `load_credentials` | `load_credentials()` |
| `google_bridge` | `send_gmail` | `send_gmail(to_addr, subject, body, retries)` |
| `google_bridge` | `sync_keep` | `sync_keep(tasks, retries)` |
| `gui_bridge` | `desktop` | `desktop()` |
| `gui_bridge` | `get_mail` | `get_mail()` |
| `gui_bridge` | `get_tasks` | `get_tasks()` |
| `gui_bridge` | `handle_notes` | `handle_notes()` |
| `gui_bridge` | `handle_todo` | `handle_todo()` |
| `gui_bridge` | `list_databases` | `list_databases()` |
| `gui_bridge` | `list_files` | `list_files()` |
| `gui_bridge` | `list_projects` | `list_projects()` |
| `gui_bridge` | `omni_chat` | `omni_chat()` |
| `gui_bridge` | `query_database` | `query_database()` |
| `gui_bridge` | `read_file` | `read_file()` |
| `gui_bridge` | `send_mail` | `send_mail()` |
| `gui_bridge` | `sync_todo_google` | `sync_todo_google()` |
| `gui_bridge` | `update_database` | `update_database()` |
| `gui_bridge` | `web_crawl` | `web_crawl()` |
| `initialize_enterprise_project` | `generate_ascii_tree` | `generate_ascii_tree(path)` |
| `initialize_enterprise_project` | `generate_ascii_tree` | `generate_ascii_tree(path)` |
| `initialize_enterprise_project` | `get_token` | `get_token()` |
| `initialize_enterprise_project` | `get_token` | `get_token()` |
| `initialize_enterprise_project` | `initialize` | `initialize()` |
| `initialize_enterprise_project` | `initialize` | `initialize()` |
| `network_hook` | `webhook` | `webhook()` |
| `pedagogy_loop` | `call_llm_agy` | `call_llm_agy(task)` |
| `pedagogy_loop` | `log_to_ledger` | `log_to_ledger(task, cmd)` |
| `pedagogy_loop` | `teach` | `teach()` |
| `positive_ping` | `generate_ping` | `generate_ping()` |
| `quarantine_filter` | `isolate_anomalies` | `isolate_anomalies()` |
| `router` | `extract_clean_code` | `extract_clean_code(raw_stream)` |
| `runtime_loop` | `main_loop` | `main_loop(max_gen)` |
| `scientific_executor` | `execute_step` | `execute_step(step_num, step_desc)` |
| `scientific_executor` | `get_next_step` | `get_next_step()` |
| `scientific_executor` | `log_scientific_step` | `log_scientific_step(step_num, step_desc, observation, hypothesis, experiment, result)` |
| `scientific_executor` | `mark_step_complete` | `mark_step_complete(step_num)` |
| `scientific_executor` | `run_with_limits` | `run_with_limits(command)` |
| `scrub_engine` | `scrub_content` | `scrub_content(content)` |
| `scrub_engine` | `scrub_file` | `scrub_file(file_path)` |

## Status

- Branch: `main`
- Last commit: 2026-08-14 01:13:51 -0600
- File types: .md ×32, .sh ×9, .json ×6, .p ×3, .txt ×2, .go ×2, .sql ×2, .xml ×2

### Recent commits
```
75e8338 [Moe autonomous] H2OMatrixCE 2026-08-14 01:13
4d36884 [Moe autonomous] H2OMatrixCE 2026-08-13 23:22
da2d763 [Moe autonomous] H2OMatrixCE 2026-08-13 21:48
238ef5b [Moe autonomous] H2OMatrixCE 2026-08-13 20:16
def07e5 [Moe autonomous] H2OMatrixCE 2026-08-13 19:36
f13de6e [Moe autonomous] H2OMatrixCE 2026-08-13 19:02
142c999 [Moe autonomous] H2OMatrixCE 2026-08-13 17:26
1f2c38a [Moe autonomous] H2OMatrixCE 2026-08-13 16:46
```

---
*README generated by `readme_generator.py` (Viper). Deterministic — derived from source, not LLM prose.*