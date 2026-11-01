# Public projects and repositories

**Inventory verified: November 1, 2026.** This is a curated navigation page, not a claim that every repository is a production application.

GitHub inventory: **354 total repositories** (259 public, 95 private). Public repositories: **69 active original projects**, **16 active forks**, **11 archived originals**, **163 archived forks**.

## Start here

- **[ForgeFS](https://github.com/zozo123/forgefs)** — released Rust systems tooling, with a candid performance and POSIX-boundary discussion.
- **[SWFactory](https://github.com/zozo123/ariflow-swfactory)** — alpha AI software-factory workflow with verifiable human gates and an offline replay.
- **[Cache Is King](https://github.com/zozo123/cache-is-king)** and **[Wasted Cycles](https://github.com/zozo123/wasted-cycles)** — practical tools for diagnosing build/cache/agent latency.
- **[Meta-harness on Islo](https://github.com/zozo123/meta-harness-on-islo)** — the most-starred original repository, but explicitly a scripted simulation, not a real-model benchmark.
- **[Gemma System One](https://github.com/zozo123/gemma-to-jev)** — typed, local inference research prototype with reported timings and accuracy caveats.
- **[Evidence-Aware MapReduce](https://github.com/zozo123/boltzmann-mapreduce)** — statistical reducer, traces and [arXiv paper](https://arxiv.org/abs/2607.09689).
- **[T2T vs GRCh38](https://github.com/zozo123/t2t-vs-grch38)** and **[SuperFly](https://github.com/zozo123/fly-fruit-fly)** — computational-genomics and computational-neuroscience work.

## All 69 active original public repositories

Items below are grouped by what they actually demonstrate. 'Prototype', 'simulation', 'proposal' and 'alpha' are meaningful limitations, not interchangeable with validated production integrations.

### Tools, runtimes and integrations (11)

- **[forgefs](https://github.com/zozo123/forgefs)** — Pre-1.0 Rust content-addressed workspaces; snapshot-pinned agent sessions, recorded reads and conflict-preserving forks. Released v0.4.0; not a POSIX filesystem.
- **[ariflow-swfactory](https://github.com/zozo123/ariflow-swfactory)** — Alpha Airflow-orchestrated issue-to-reviewed-PR workflow with policy and human approval gates. Bundled local replay uses scripted fixtures, not live model calls.
- **[cache-is-king](https://github.com/zozo123/cache-is-king)** — Go CLI (v0.1.0) for BuildKit cache diagnostics and Linux page-cache refaults; includes releases and local reports.
- **[wasted-cycles](https://github.com/zozo123/wasted-cycles)** — Local-first Go profiler of build/test/CI wait time in coding-agent traces and GitHub Actions.
- **[ibrowse-mcp](https://github.com/zozo123/ibrowse-mcp)** — Early read-only Go MCP server that attaches to an existing Chrome/Chromium session via CDP and records JSONL timelines.
- **[airflow-provider-sandbox](https://github.com/zozo123/airflow-provider-sandbox)** — Experimental third-party Airflow provider with SandboxOperator/SandboxExecutor and multiple sandbox backends; not Apache Airflow core.
- **[agentbox-provider-islo](https://github.com/zozo123/agentbox-provider-islo)** — Community AgentBox provider for Islo microVMs; npm 0.1.0 and newer SDK-v4 source code have different verification status.
- **[pydantic-ai-boat](https://github.com/zozo123/pydantic-ai-boat)** — Community Pydantic AI capability for executing agent commands/files inside Boat cloud sandboxes; installed from Git.
- **[rust-rover-plugin-crabbox](https://github.com/zozo123/rust-rover-plugin-crabbox)** — MVP Kotlin RustRover plugin delegating Cargo builds and tests to the Crabbox CLI.
- **[sandbox-transform-for-apache-kafka-connect](https://github.com/zozo123/sandbox-transform-for-apache-kafka-connect)** — Experimental Java/Kafka Connect transform guest layer using WebAssembly or Docker Sandboxes; not an Apache Kafka project.
- **[eass-auto-grader](https://github.com/zozo123/eass-auto-grader)** — Instructor-facing FastAPI repository grader and similarity-review helper; similarity flags require human assessment.

### Computational science, research and evaluations (10)

- **[boltzmann-mapreduce](https://github.com/zozo123/boltzmann-mapreduce)** — Evidence-aware reduction prototype and arXiv:2607.09689 paper; caller-provided evidence IDs and lineage are not a complete dependence model.
- **[threebody-closing-the-open](https://github.com/zozo123/threebody-closing-the-open)** — Three-body orbit-continuation and Floquet-stability research code and draft paper. Work in progress; completeness applies only to a bounded sampled domain.
- **[gemma-to-jev](https://github.com/zozo123/gemma-to-jev)** — Rust/Candle Gemma 3 typed-decision research prototype; measured local results and explicit warning about packed-sheet semantic interference.
- **[fly-fruit-fly](https://github.com/zozo123/fly-fruit-fly)** — SuperFly prototype: fruit-fly connectome-derived RNN controlling a Flybody simulation; selected successful flight and reported 5/10 test flights.
- **[t2t-vs-grch38](https://github.com/zozo123/t2t-vs-grch38)** — Reproducible GRCh38 vs T2T-CHM13 sequence-composition comparison. CpG-rule windows are not annotated CpG islands.
- **[genomics-sandboxes](https://github.com/zozo123/genomics-sandboxes)** — Real 24-chromosome scatter/gather demo using Islo snapshot/fork and recorded receipts. Reported speedup combines reuse and parallelism.
- **[open-physics-problems](https://github.com/zozo123/open-physics-problems)** — Catalog of 112 open physics questions with refutability and agent-tractability tags; a research-prioritization resource, not solved results.
- **[GULI-SET](https://github.com/zozo123/GULI-SET)** — Synthetic deterministic benchmark for evidence laundering/correlation neglect; baseline scores are not measurements of real LLMs.
- **[protein-lab](https://github.com/zozo123/protein-lab)** — Demonstration of peptide structure generation or loading and visualization for an Omnigent-oriented workflow.
- **[sol-exec-bench](https://github.com/zozo123/sol-exec-bench)** — Proposed reproducible GPU-kernel research campaign; explicitly not an executed benchmark.

### Sandbox experiments and agent demonstrations (21)

- **[meta-harness-on-islo](https://github.com/zozo123/meta-harness-on-islo)** — Popular five-task deterministic harness-optimization simulation (0/5 to 5/5); scripted agents and an unvalidated Islo stub, not an LLM benchmark.
- **[meta-harness-on-islo-page](https://github.com/zozo123/meta-harness-on-islo-page)** — Landing page and reproducible write-up for the deterministic meta-harness simulation.
- **[hermetic-agents-demo](https://github.com/zozo123/hermetic-agents-demo)** — Offline deterministic example of isolated scripted coder/tester roles and a hidden-oracle QA arbiter.
- **[longmem-mini-on-islo](https://github.com/zozo123/longmem-mini-on-islo)** — Three handcrafted memory questions and scripted memory strategies; not an official LongMemEval score.
- **[env-rosetta](https://github.com/zozo123/env-rosetta)** — Wordle RL-environment integration demo across four frameworks; published transcripts are scripted.
- **[env-rosetta-page](https://github.com/zozo123/env-rosetta-page)** — Project page accompanying the Wordle RL-environment demonstrations.
- **[repo2rlenv-crabbox-demo](https://github.com/zozo123/repo2rlenv-crabbox-demo)** — Demo page for a sandboxed Repo2RLEnv scoring experiment; upstream PR was closed unmerged.
- **[odysseus-crabbox-demo](https://github.com/zozo123/odysseus-crabbox-demo)** — Page showing an Odysseus workspace on disposable Islo/Crabbox compute.
- **[inferoa-demo](https://github.com/zozo123/inferoa-demo)** — Unofficial client-side token-cost simulation with receipts from real sandboxed vLLM runs.
- **[inferoa-receipts](https://github.com/zozo123/inferoa-receipts)** — Small reproducible example: agent-written fix for a timezone-naive datetime test failure.
- **[demo-evals-pydantic-islo-crabbox](https://github.com/zozo123/demo-evals-pydantic-islo-crabbox)** — Pydantic AI/Pydantic Evals triage demonstration, runnable offline or through a disposable Crabbox sandbox.
- **[gx-sandbox-demo](https://github.com/zozo123/gx-sandbox-demo)** — Minimal Great Expectations validation example with an intentionally failing check.
- **[unity-loop](https://github.com/zozo123/unity-loop)** — Claude proposes CSS scene variants, sandbox-served and scored by Claude vision; proof of concept.
- **[unity-loop-page](https://github.com/zozo123/unity-loop-page)** — Landing page for the Unity scene-variant proof of concept.
- **[pokeloop](https://github.com/zozo123/pokeloop)** — Prompt-evolution/Pokémon Crystal-style viewer demo; published results are scripted playback.
- **[wc-predict-islo-demo](https://github.com/zozo123/wc-predict-islo-demo)** — No-real-money World Cup prediction-market demo with Node microservices and LMSR pricing.
- **[islo-observability-demo](https://github.com/zozo123/islo-observability-demo)** — Synthetic-data observability POC involving Datadog, Metaplane, Databricks and Airflow.
- **[agentic-airbyte](https://github.com/zozo123/agentic-airbyte)** — Agent-driven ETL proposal with a verified 50,000-row Python worker proof; full Crabbox/Airbyte orchestration is proposed, not demonstrated.
- **[bazel-monty](https://github.com/zozo123/bazel-monty)** — Bazel 9/Pydantic Monty demonstration with reported local cold/cached timings and an Islo build.
- **[wolfram-fb0](https://github.com/zozo123/wolfram-fb0)** — Local-model NASM/Rule-30 experiment; the three reported attempts were not correct.
- **[rust-china-conf](https://github.com/zozo123/rust-china-conf)** — Rust robotics safety-gate and seeded stale-observation simulation prepared as a conference demonstration.

### Writing, talks and teaching (18)

- **[zozo123](https://github.com/zozo123/zozo123)** — This GitHub profile and its source-grounded portfolio/contributions indexes.
- **[zozo123.github.io](https://github.com/zozo123/zozo123.github.io)** — Collected interactive articles, demos and technical writing (separate from the Netlify personal site).
- **[sandboxes-why-how-when](https://github.com/zozo123/sandboxes-why-how-when)** — The Sandbox Shift: interactive guide to choosing isolation boundaries for AI-written code.
- **[sandbox-landscape](https://github.com/zozo123/sandbox-landscape)** — May 2026 snapshot of AI execution-sandbox products and trade-offs; prices should not be treated as live.
- **[gha-cache-field-guide](https://github.com/zozo123/gha-cache-field-guide)** — Field guide contrasting GitHub Actions, BuildKit and other cache mechanisms.
- **[the-living-layer](https://github.com/zozo123/the-living-layer)** — Speculative architecture essay on sandboxed compute plus governed state, with clearly bounded prototype.
- **[loop-coming-apart](https://github.com/zozo123/loop-coming-apart)** — Essay on the unbundled coding-agent inner development loop and disposable compute.
- **[how-stackoverflow-taught-ai](https://github.com/zozo123/how-stackoverflow-taught-ai)** — Sourced interactive article about Stack Overflow data and AI coding models.
- **[databases-in-the-ai-era](https://github.com/zozo123/databases-in-the-ai-era)** — Essays and AI-drafted database course material; the proposed course has not yet been taught.
- **[microservices-to-microcells](https://github.com/zozo123/microservices-to-microcells)** — Architecture proposal for bounded execution tasks and durable workflows.
- **[intel-story](https://github.com/zozo123/intel-story)** — Opinion infographic on Intel strategic decisions and execution.
- **[airflow-sandbox-townhall](https://github.com/zozo123/airflow-sandbox-townhall)** — Slides for the July 2026 Apache Airflow virtual town hall on ephemeral task sandboxes.
- **[nyc-talk](https://github.com/zozo123/nyc-talk)** — Deck, paper and lab for the October 2026 Zenity talk on sandbox non-escape failures.
- **[cam-talk-london-26](https://github.com/zozo123/cam-talk-london-26)** — LaTeX slides and references for the October 15 Cambridge Systems Research Group seminar.
- **[llmday-2026-show-visuals](https://github.com/zozo123/llmday-2026-show-visuals)** — Public presentation assets for LLMday NYC 2026; repository metadata does not include a description.
- **[free-intelligence](https://github.com/zozo123/free-intelligence)** — Film and essay about model answers versus agent harnesses, plus a Cline CLI wrapper.
- **[stochastic-cpu](https://github.com/zozo123/stochastic-cpu)** — Opinion essay about cloud infrastructure, cache hierarchy and AI-agent economics.
- **[rust-it-up](https://github.com/zozo123/rust-it-up)** — Illustrative Rust migration scorecard website; scanner is mocked, estimates not audited.

### Other public projects and interactive experiments (9)

- **[peter-gt-your-org](https://github.com/zozo123/peter-gt-your-org)** — Playful Next.js comparison of GitHub organization activity in a made-up 'Peter' unit.
- **[has-steipete-hit-1m-github-ytd](https://github.com/zozo123/has-steipete-hit-1m-github-ytd)** — Unofficial tracker of a public account's GitHub contribution activity.
- **[market-making-sandbox](https://github.com/zozo123/market-making-sandbox)** — Interactive market-microstructure explainer with 13 browser-based simulations.
- **[microprice-sandbox](https://github.com/zozo123/microprice-sandbox)** — Synthetic Avellaneda–Stoikov market-making reproduction on an Islo sandbox.
- **[kalpi-map](https://github.com/zozo123/kalpi-map)** — Hebrew polling-station and per-station results map for the 26th Knesset.
- **[milyon](https://github.com/zozo123/milyon)** — Illustrative Hebrew AI lead-response business-plan/landing-page demo; not a live commercial offer.
- **[port-folio-momo](https://github.com/zozo123/port-folio-momo)** — Public HTML repository; no description was provided in GitHub metadata.
- **[radar-0-to-60-undergrad-cs](https://github.com/zozo123/radar-0-to-60-undergrad-cs)** — Four-stage Python radar/DSP primer from FFT to range–Doppler CFAR.
- **[yossi-islo-promo](https://github.com/zozo123/yossi-islo-promo)** — Public HTML promotional artifact; no description was provided in GitHub metadata.

## Other public repositories

### Archived originals (11)

- [QC-IL](https://github.com/zozo123/QC-IL) (archived original)
- [cpython-module](https://github.com/zozo123/cpython-module) (archived original)
- [demo-eleven-labs](https://github.com/zozo123/demo-eleven-labs) (archived original)
- [docker-k8s-tf-helm](https://github.com/zozo123/docker-k8s-tf-helm) (archived original)
- [docker-without-swarm](https://github.com/zozo123/docker-without-swarm) (archived original)
- [langchain-islo](https://github.com/zozo123/langchain-islo) (archived original)
- [mirca-paper-scripts](https://github.com/zozo123/mirca-paper-scripts) (archived original)
- [spark-udf-sbx](https://github.com/zozo123/spark-udf-sbx) (archived original)
- [test-pi-harness-polymarket](https://github.com/zozo123/test-pi-harness-polymarket) (archived original)
- [verilog_final_project](https://github.com/zozo123/verilog_final_project) (archived original)
- [xor-fractal-fb0](https://github.com/zozo123/xor-fractal-fb0) (archived original)

### Active forks (16)

Forking a repository is not equivalent to authoring its upstream code. The merged contributions are tracked separately in [UPSTREAM.md](UPSTREAM.md).

- [AlgorithmVisualizer](https://github.com/zozo123/AlgorithmVisualizer) (active fork)
- [Craft](https://github.com/zozo123/Craft) (active fork)
- [airflow](https://github.com/zozo123/airflow) (active fork)
- [bazel](https://github.com/zozo123/bazel) (active fork)
- [cargo](https://github.com/zozo123/cargo) (active fork)
- [crabbox](https://github.com/zozo123/crabbox) (active fork)
- [mecatl](https://github.com/zozo123/mecatl) (active fork)
- [numpy](https://github.com/zozo123/numpy) (active fork)
- [omarchy](https://github.com/zozo123/omarchy) (active fork)
- [omnigent](https://github.com/zozo123/omnigent) (active fork)
- [openclaw](https://github.com/zozo123/openclaw) (active fork)
- [pydantic-ai](https://github.com/zozo123/pydantic-ai) (active fork)
- [spark](https://github.com/zozo123/spark) (active fork)
- [the-super-tiny-compiler](https://github.com/zozo123/the-super-tiny-compiler) (active fork)
- [transforms-for-apache-kafka-connect](https://github.com/zozo123/transforms-for-apache-kafka-connect) (active fork)
- [zed](https://github.com/zozo123/zed) (active fork)

<details>
<summary>All 163 archived public forks (expand)</summary>

These are preserved public forks, not 163 additional independently authored projects.

- [AFINES](https://github.com/zozo123/AFINES)
- [AgentENV-1](https://github.com/zozo123/AgentENV-1)
- [ClickHouse](https://github.com/zozo123/ClickHouse)
- [ColabFold](https://github.com/zozo123/ColabFold)
- [CoronAlerts](https://github.com/zozo123/CoronAlerts)
- [Diffusion-Matlab-Code](https://github.com/zozo123/Diffusion-Matlab-Code)
- [EigenVector](https://github.com/zozo123/EigenVector)
- [EuroPython2011_HighPerformanceComputing](https://github.com/zozo123/EuroPython2011_HighPerformanceComputing)
- [FARM-Intro](https://github.com/zozo123/FARM-Intro)
- [FFmpeg](https://github.com/zozo123/FFmpeg)
- [Flye](https://github.com/zozo123/Flye)
- [HiCSampler](https://github.com/zozo123/HiCSampler)
- [IBMQuantumChallenge2020](https://github.com/zozo123/IBMQuantumChallenge2020)
- [Latex-based-business-plan-template](https://github.com/zozo123/Latex-based-business-plan-template)
- [NodeBB](https://github.com/zozo123/NodeBB)
- [OpenAPI-Specification](https://github.com/zozo123/OpenAPI-Specification)
- [OpenCoder-llm](https://github.com/zozo123/OpenCoder-llm)
- [OpenFermion](https://github.com/zozo123/OpenFermion)
- [POSSUM](https://github.com/zozo123/POSSUM)
- [Programming-iOS-Book-Examples](https://github.com/zozo123/Programming-iOS-Book-Examples)
- [Repo2RLEnv](https://github.com/zozo123/Repo2RLEnv)
- [SpringerDownloader](https://github.com/zozo123/SpringerDownloader)
- [TADbit](https://github.com/zozo123/TADbit)
- [agent-skills](https://github.com/zozo123/agent-skills)
- [agentbox](https://github.com/zozo123/agentbox)
- [agnt](https://github.com/zozo123/agnt)
- [android_kernel_samsung_degas](https://github.com/zozo123/android_kernel_samsung_degas)
- [angular](https://github.com/zozo123/angular)
- [annyang](https://github.com/zozo123/annyang)
- [ansible](https://github.com/zozo123/ansible)
- [asi-django-example-project](https://github.com/zozo123/asi-django-example-project)
- [avo](https://github.com/zozo123/avo)
- [awesome-CRISPR](https://github.com/zozo123/awesome-CRISPR)
- [awesome-deep-learning-papers](https://github.com/zozo123/awesome-deep-learning-papers)
- [awesome-machine-learning](https://github.com/zozo123/awesome-machine-learning)
- [awesome-tensorflow](https://github.com/zozo123/awesome-tensorflow)
- [aws-okta](https://github.com/zozo123/aws-okta)
- [awsemmd](https://github.com/zozo123/awsemmd)
- [axios](https://github.com/zozo123/axios)
- [balena](https://github.com/zozo123/balena)
- [benchmarks](https://github.com/zozo123/benchmarks)
- [binnavi](https://github.com/zozo123/binnavi)
- [bitcoin](https://github.com/zozo123/bitcoin)
- [bktree-javascript](https://github.com/zozo123/bktree-javascript)
- [blogless](https://github.com/zozo123/blogless)
- [bootstrap](https://github.com/zozo123/bootstrap)
- [boxroom](https://github.com/zozo123/boxroom)
- [buildbot](https://github.com/zozo123/buildbot)
- [buzz](https://github.com/zozo123/buzz)
- [camel](https://github.com/zozo123/camel)
- [celery](https://github.com/zozo123/celery)
- [chip-seq-pipeline](https://github.com/zozo123/chip-seq-pipeline)
- [claude-plugins-official](https://github.com/zozo123/claude-plugins-official)
- [codex](https://github.com/zozo123/codex)
- [cognee](https://github.com/zozo123/cognee)
- [computesdk](https://github.com/zozo123/computesdk)
- [conductor](https://github.com/zozo123/conductor)
- [coursera-android](https://github.com/zozo123/coursera-android)
- [cs344](https://github.com/zozo123/cs344)
- [cuckoo](https://github.com/zozo123/cuckoo)
- [cvxopt](https://github.com/zozo123/cvxopt)
- [data-science](https://github.com/zozo123/data-science)
- [dbt-core](https://github.com/zozo123/dbt-core)
- [deepagents](https://github.com/zozo123/deepagents)
- [docker](https://github.com/zozo123/docker)
- [docker-ce](https://github.com/zozo123/docker-ce)
- [docker-cli](https://github.com/zozo123/docker-cli)
- [docker-py](https://github.com/zozo123/docker-py)
- [docs](https://github.com/zozo123/docs)
- [duckdb](https://github.com/zozo123/duckdb)
- [element-web](https://github.com/zozo123/element-web)
- [ethereum-alarm-clock](https://github.com/zozo123/ethereum-alarm-clock)
- [eve](https://github.com/zozo123/eve)
- [extensions](https://github.com/zozo123/extensions)
- [flipt](https://github.com/zozo123/flipt)
- [flue](https://github.com/zozo123/flue)
- [folly](https://github.com/zozo123/folly)
- [fuzzywuzzy](https://github.com/zozo123/fuzzywuzzy)
- [go-ethereum](https://github.com/zozo123/go-ethereum)
- [godepgraph](https://github.com/zozo123/godepgraph)
- [godot](https://github.com/zozo123/godot)
- [great_expectations](https://github.com/zozo123/great_expectations)
- [gym](https://github.com/zozo123/gym)
- [harbor](https://github.com/zozo123/harbor)
- [hermes-agent](https://github.com/zozo123/hermes-agent)
- [homebrew](https://github.com/zozo123/homebrew)
- [hugo-theme-blueberry-detox](https://github.com/zozo123/hugo-theme-blueberry-detox)
- [hugo-uno](https://github.com/zozo123/hugo-uno)
- [ibrute](https://github.com/zozo123/ibrute)
- [igv-jupyter](https://github.com/zozo123/igv-jupyter)
- [kinomajs](https://github.com/zozo123/kinomajs)
- [kubernetes](https://github.com/zozo123/kubernetes)
- [lamellipodium](https://github.com/zozo123/lamellipodium)
- [lammps](https://github.com/zozo123/lammps)
- [libfreenect](https://github.com/zozo123/libfreenect)
- [librsync-go](https://github.com/zozo123/librsync-go)
- [linux](https://github.com/zozo123/linux)
- [llama.cpp](https://github.com/zozo123/llama.cpp)
- [llvm-project](https://github.com/zozo123/llvm-project)
- [lmctfy](https://github.com/zozo123/lmctfy)
- [loopy](https://github.com/zozo123/loopy)
- [mathgen](https://github.com/zozo123/mathgen)
- [matplotlib](https://github.com/zozo123/matplotlib)
- [mininet](https://github.com/zozo123/mininet)
- [mistral-vibe](https://github.com/zozo123/mistral-vibe)
- [mojombo.github.io](https://github.com/zozo123/mojombo.github.io)
- [mongo](https://github.com/zozo123/mongo)
- [monty](https://github.com/zozo123/monty)
- [n8n](https://github.com/zozo123/n8n)
- [nanoclaw](https://github.com/zozo123/nanoclaw)
- [navidrome](https://github.com/zozo123/navidrome)
- [netdata](https://github.com/zozo123/netdata)
- [netlify-example](https://github.com/zozo123/netlify-example)
- [networkx](https://github.com/zozo123/networkx)
- [node-capstone](https://github.com/zozo123/node-capstone)
- [nushell](https://github.com/zozo123/nushell)
- [nvidia-docker](https://github.com/zozo123/nvidia-docker)
- [objectbox-java](https://github.com/zozo123/objectbox-java)
- [odysseus](https://github.com/zozo123/odysseus)
- [opencv](https://github.com/zozo123/opencv)
- [openlibrary](https://github.com/zozo123/openlibrary)
- [orioledb](https://github.com/zozo123/orioledb)
- [osqa](https://github.com/zozo123/osqa)
- [ov_ftdi](https://github.com/zozo123/ov_ftdi)
- [panopticon](https://github.com/zozo123/panopticon)
- [parallellocalypse-client](https://github.com/zozo123/parallellocalypse-client)
- [parallellocalypse-hub](https://github.com/zozo123/parallellocalypse-hub)
- [phoenix](https://github.com/zozo123/phoenix)
- [prefect](https://github.com/zozo123/prefect)
- [pulpino](https://github.com/zozo123/pulpino)
- [pydantic-ai-harness](https://github.com/zozo123/pydantic-ai-harness)
- [qira](https://github.com/zozo123/qira)
- [qrush.github.com](https://github.com/zozo123/qrush.github.com)
- [quilt](https://github.com/zozo123/quilt)
- [rapids-single-cell-examples](https://github.com/zozo123/rapids-single-cell-examples)
- [red](https://github.com/zozo123/red)
- [ruflo](https://github.com/zozo123/ruflo)
- [runc](https://github.com/zozo123/runc)
- [rust](https://github.com/zozo123/rust)
- [saleor-platform](https://github.com/zozo123/saleor-platform)
- [samples](https://github.com/zozo123/samples)
- [sandbox-sdk](https://github.com/zozo123/sandbox-sdk)
- [scriptcase-docker](https://github.com/zozo123/scriptcase-docker)
- [spec](https://github.com/zozo123/spec)
- [sqlfluff](https://github.com/zozo123/sqlfluff)
- [sqlmap](https://github.com/zozo123/sqlmap)
- [sslstrip](https://github.com/zozo123/sslstrip)
- [straw](https://github.com/zozo123/straw)
- [subsurface](https://github.com/zozo123/subsurface)
- [swarm](https://github.com/zozo123/swarm)
- [tabnet_fork](https://github.com/zozo123/tabnet_fork)
- [tcrdist3](https://github.com/zozo123/tcrdist3)
- [teleport](https://github.com/zozo123/teleport)
- [tensorflow](https://github.com/zozo123/tensorflow)
- [theZoo](https://github.com/zozo123/theZoo)
- [transformers](https://github.com/zozo123/transformers)
- [tutanota](https://github.com/zozo123/tutanota)
- [typeahead.js](https://github.com/zozo123/typeahead.js)
- [vcell-solvers](https://github.com/zozo123/vcell-solvers)
- [vitess](https://github.com/zozo123/vitess)
- [vuls](https://github.com/zozo123/vuls)
- [wikidump](https://github.com/zozo123/wikidump)
- [yochze.github.com](https://github.com/zozo123/yochze.github.com)

</details>

## How to read the evidence

Published releases, passing tests, a local replay, sandbox receipts, and paper/preprint claims are different kinds of evidence. Consult each repository's README and methodology before comparing results across projects. Snapshots, latency benchmarks and simulated agent results are not automatically production guarantees.

For merged external contributions see **[UPSTREAM.md](UPSTREAM.md)**; for a shorter overview see **[GitHub profile](README.md)**.
