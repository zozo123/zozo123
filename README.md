# Yossi Eliaz

**Principal Engineer, AI Systems · [Incredibuild](https://incredibuild.com/)**

[incredibuild.com](https://incredibuild.com/) · [islo.dev](https://islo.dev/) · [zozo123.github.io](https://zozo123.github.io/)

*Secure agent execution · sandboxes and snapshots · CI/build performance · computational science*

I work on execution infrastructure for AI coding and research agents: isolated environments, reusable snapshots, build and dependency caches, evidence, and recovery. Earlier work spans Linux/container systems, autonomous-driving ML, and computational genomics. I hold a PhD in physics and teach software engineering at HIT.

## Open source contributions

**162 merged authored PRs** across **36 external repositories**, **127 in 2026** (verified November 11, 2026): [155 found by GitHub search](https://github.com/search?type=pullrequests&q=author%3Azozo123+is%3Apr+is%3Amerged+-user%3Azozo123+-user%3Aislo-labs+-user%3AIncredibuild-RND+-user%3AEASS-PART-A-2026-X+-user%3AEASS-HIT-PART-B+-user%3AEASS-HIT-PART-A-2024-CLASS-V+-user%3AQuBind) plus [7 Bazel PRs](UPSTREAM.md#bazelbuildbazel--7-landed-via-copybara) that landed through Bazel's Copybara import, which closes PRs instead of marking them merged. [Full upstream catalog, all PRs and open work](UPSTREAM.md).

- **[Apache Airflow — 20 merged PRs](https://github.com/apache/airflow/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged).** [SandboxToolset](https://github.com/apache/airflow/pull/68847) for agent shell/file tools; [Islo](https://github.com/apache/airflow/pull/71672), [Boat](https://github.com/apache/airflow/pull/71725), [OpenSandbox](https://github.com/apache/airflow/pull/71676) and [OpenShell](https://github.com/apache/airflow/pull/73961) backends; CI work on [compressed image stashes](https://github.com/apache/airflow/pull/73997), [snapshots](https://github.com/apache/airflow/pull/74173) and [dependency cache reuse](https://github.com/apache/airflow/pull/74466).
- **[OpenClaw Crabbox — 66 merged PRs](https://github.com/openclaw/crabbox/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged).** Sandbox providers, delegated-run lifecycle, [lease heartbeats](https://github.com/openclaw/crabbox/pull/1707), [identity binding](https://github.com/openclaw/crabbox/pull/1158) and [bounded parallel shards](https://github.com/openclaw/crabbox/pull/2935).
- **[OpenClaw core — 4 merged PRs](https://github.com/openclaw/openclaw/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged).** Including an [SSRF mitigation for pinned dispatchers](https://github.com/openclaw/openclaw/pull/61777) and [Docker apt key-pinning fix](https://github.com/openclaw/openclaw/pull/74254).
- **[Bazel — 7 landed PRs](UPSTREAM.md#bazelbuildbazel--7-landed-via-copybara).** [Merkle digest scratch buffer for remote execution](https://github.com/bazelbuild/bazel/pull/31993), [paginated, fail-closed community review labeling](https://github.com/bazelbuild/bazel/pull/30359), [locale-independent SSL monitor](https://github.com/bazelbuild/bazel/pull/30363) and a [reproducible distfile](https://github.com/bazelbuild/bazel/pull/30365).
- **Also upstream:** [SQLFluff (13)](https://github.com/sqlfluff/sqlfluff/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged), [balena-engine (11)](https://github.com/balena-os/balena-engine/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged), [straw (5)](https://github.com/aidenlab/straw/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged), [Omnigent (3)](https://github.com/omnigent-ai/omnigent/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged), [Zed (2)](https://github.com/zed-industries/zed/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged), [Nushell](https://github.com/nushell/nushell/pull/18999), [Pydantic Monty](https://github.com/pydantic/monty/pull/147), and more.
- **Author-attributed commit integrated through another PR flow:** [Apache Spark UDF worker dispatch](https://github.com/apache/spark/commit/56da062b59f8ae58faa81554c76de49937d2d232). Not included in the total above.

## Playing around

- **[ForgeFS](https://github.com/zozo123/forgefs)** — pre-1.0 Rust content-addressed workspaces for concurrent agents. Snapshot-pinned sessions, read-dependency checks, conflict-preserving forks, and auditable release seals. [v0.4.0 released](https://github.com/zozo123/forgefs/releases); not POSIX/FUSE or a Git replacement.
- **[SWFactory](https://github.com/zozo123/ariflow-swfactory)** — alpha Airflow + agents pipeline from GitHub issues to evidence-bearing, reviewed PRs with human gates. Includes a repeatable offline fixture replay; deployed end-to-end model integration is not claimed.
- **[Cache Is King](https://github.com/zozo123/cache-is-king)** and **[Wasted Cycles](https://github.com/zozo123/wasted-cycles)** — Go tooling to inspect Docker/CI cache misses, page refaults, and machine time lost during coding-agent work.
- **[Meta-harness on Islo](https://github.com/zozo123/meta-harness-on-islo)** — deterministic five-task harness-improvement simulation with trace visualization. Scripted agents and an Islo adapter stub; not a real-LLM benchmark.
- **[Gemma System One](https://github.com/zozo123/gemma-to-jev)** — Rust/Candle local typed-decision inference prototype with measured hardware-specific results and a documented semantic-isolation caveat.
- **[GULI-SET](https://github.com/zozo123/GULI-SET)** — synthetic, deterministic benchmark for distinguishing independent evidence from repeated claims; not yet an LLM evaluation result.

## Scientific computing experiments

- **[Evidence-Aware MapReduce for Forkable Compute](https://arxiv.org/abs/2607.09689)** — 2026 preprint and [open implementation](https://github.com/zozo123/boltzmann-mapreduce) on lineage, evidence identity and statistical reduction.
- **[Three-Body Orbit Atlas](https://github.com/zozo123/threebody-closing-the-open)** — numerical continuation and Floquet-stability research; in progress, with explicitly bounded completeness.
- **[SuperFly](https://github.com/zozo123/fly-fruit-fly)** — connectome-informed RNN controller for simulated fruit-fly flight; research prototype.
- **[T2T vs GRCh38](https://zozo123.github.io/t2t-vs-grch38/)** — reproducible chromosome-level sequence-composition comparisons, not functional CpG-island annotation.

[Explore all 69 active original projects and all public forks/archives](PROJECTS.md).

## Talks, 2026

- **[Airflow Town Hall](https://zozo123.github.io/airflow-sandbox-townhall/)** — A Sandbox Provider for Apache Airflow ([recording](https://www.youtube.com/watch?v=cznc1tFYnMI))
- **[Airflow Summit](https://airflowsummit.org/sessions/2026/graphs-of-ai-coding/)** — Graphs of AI Coding: Orchestrating Agentic MapReduce with Airflow's New Sandboxes ([recording](https://www.youtube.com/watch?v=54Cfk91HNp8), [slides](https://airflowsummit.org/slides/2026/graphs-of-ai-coding.pdf))
- **[Cambridge Systems Research Group](https://www.cst.cam.ac.uk/seminars/list/273181)** — Forkable Sandboxes: The Runtime Layer for AI Software Factories
- **[Zenity AI Agent Security Summit, NYC](https://github.com/zozo123/nyc-talk)** — Your Agent Escaped Without Escaping the Sandbox
- **[LLMday NYC](https://llmday.com/2026-nyc-q4/)** — The Sandbox Is the Agent Runtime: What Breaks When Execution Becomes Disposable

[All seven 2026 talks, with recordings and slides](https://zozo123.github.io/#talks).

## Research & teaching

Computational genomics and physical biology research with Baylor College of Medicine, Rice University, and Harvard Medical School. I teach [EASS Class X at HIT](https://eass-part-a-2026-x.github.io/lecture-notes/). See [publications on Google Scholar](https://scholar.google.com/citations?user=NL1ZyOgAAAAJ).

[Website](https://yossieliaz.netlify.app/) · [CV (PDF)](https://yossieliaz.netlify.app/cv/Yossi-Eliaz-CV.pdf) · [Writing & demos](https://zozo123.github.io/) · [Research](https://yossieliaz.netlify.app/research/) · [LinkedIn](https://www.linkedin.com/in/yossi-eliaz/)
