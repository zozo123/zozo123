# Yossi Eliaz

**Principal Engineer, AI Systems · Incredibuild / [islo.dev](https://islo.dev/)**

AI execution infrastructure · secure sandboxes · developer tooling · computational science

I build infrastructure for AI agents to execute code in isolated, reproducible environments: sandboxes, CI runners, snapshots, caching, and execution evidence. My background spans Linux and container security, autonomous-driving ML, and computational genomics. I have a PhD in physics and teach software engineering at HIT.

## Open-source contributions

**[150 merged PRs](https://github.com/search?type=pullrequests&q=author%3Azozo123+is%3Apr+is%3Amerged+-user%3Azozo123+-user%3Aislo-labs+-user%3AIncredibuild-RND+-user%3AEASS-PART-A-2026-X+-user%3AEASS-HIT-PART-B+-user%3AEASS-HIT-PART-A-2024-CLASS-V+-user%3AQuBind)** across **33 external open-source repositories**, including **115 in 2026** (verified November 1, 2026).

- **Apache Airflow — [20 merged PRs](https://github.com/apache/airflow/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged).** Built the [SandboxToolset](https://github.com/apache/airflow/pull/68847) for agent shell/file access and added [Islo](https://github.com/apache/airflow/pull/71672), [Boat](https://github.com/apache/airflow/pull/71725), [OpenSandbox](https://github.com/apache/airflow/pull/71676), and [OpenShell](https://github.com/apache/airflow/pull/73961) backends. Improved CI with [compressed image stashes](https://github.com/apache/airflow/pull/73997), [same-run snapshots](https://github.com/apache/airflow/pull/74173), and [dependency cache reuse](https://github.com/apache/airflow/pull/74466).
- **[Crabbox](https://github.com/openclaw/crabbox) (OpenClaw) — [65 merged PRs](https://github.com/openclaw/crabbox/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged).** Sandbox provider integrations including E2B, Modal, RunPod, Google Cloud Run, Azure Dynamic Sessions, and Windows Sandbox; [lease heartbeat](https://github.com/openclaw/crabbox/pull/1707) for delegated providers.
- **[Omnigent](https://github.com/omnigent-ai/omnigent/pull/42).** Islo sandbox provider and a [fix for sandbox helper processes being killed mid-request](https://github.com/omnigent-ai/omnigent/pull/10058).
- **[Apache Spark](https://github.com/apache/spark/commit/56da062b59f8ae58faa81554c76de49937d2d232) & [Bazel](https://github.com/bazelbuild/bazel/commit/d97111e4712b104c726fb66f7963434cb0457fcc).** Spark-owned external-UDF worker dispatch instead of an arbitrary class hook; Bazel review pagination that fails closed when results are partial.
- **Also merged:** [Zed](https://github.com/zed-industries/zed/pull/60968) (sccache reuse), [Nushell](https://github.com/nushell/nushell/pull/18999) (`par-each` deadlock), [Pydantic Monty](https://github.com/pydantic/monty/pull/147), [axios](https://github.com/axios/axios/pull/10806), [NetworkX](https://github.com/networkx/networkx/pull/5104), and [sqlfluff](https://github.com/sqlfluff/sqlfluff/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged).

## Projects

- **[ForgeFS](https://github.com/zozo123/forgefs)** — pre-1.0 Rust content-addressed workspaces for concurrent coding agents. Snapshot-pinned sessions, read-dependency checks, and conflict-preserving forks; [v0.4.0 release](https://github.com/zozo123/forgefs/releases).
- **[SWFactory](https://github.com/zozo123/ariflow-swfactory)** — alpha GitHub-issue-to-reviewed-PR workflow with Apache Airflow, coding agents, evidence, and human approval gates. Includes a [reproducible local replay](https://github.com/zozo123/ariflow-swfactory#quickstart) without model calls.
- **[Meta-harness on Islo](https://github.com/zozo123/meta-harness-on-islo)** — runnable, deterministic five-task harness-optimization simulation and trace viewer; a teaching/demo harness, **not** a real-LLM benchmark or validated Islo integration.
- **[T2T vs GRCh38](https://zozo123.github.io/t2t-vs-grch38/)** — chromosome-by-chromosome comparison of human reference-genome sequence composition, with source, methodology, and caveats.

## Talks, 2026

- **Airflow Summit:** [Graphs of AI Coding: Orchestrating Agentic MapReduce with Airflow's New Sandboxes](https://airflowsummit.org/sessions/2026/graphs-of-ai-coding/)
- **Cambridge Systems Research Group:** [Forkable Sandboxes: The Runtime Layer for AI Software Factories](https://talks.cam.ac.uk/talk/index/273181/)
- **Zenity AI Agent Security Summit, NYC:** [Your Agent Escaped Without Escaping the Sandbox](https://github.com/zozo123/nyc-talk)
- **LLMday NYC:** [The Sandbox Is the Agent Runtime: What Breaks When Execution Becomes Disposable](https://llmday.com/2026-nyc-q4/)

## Research & teaching

Research in computational genomics, genome architecture, physical biology, and cancer transcriptomics at Baylor College of Medicine, Rice University, and Harvard Medical School. Publications include *Nature Communications*, *PNAS*, *Physical Review E*, and *iScience*. I teach [EASS Class X at HIT](https://eass-part-a-2026-x.github.io/lecture-notes/).

[Website](https://yossieliaz.netlify.app/) · [CV (PDF)](https://yossieliaz.netlify.app/cv/Yossi-Eliaz-CV.pdf) · [Writing](https://zozo123.github.io/) · [Research](https://yossieliaz.netlify.app/research/) · [Google Scholar](https://scholar.google.com/citations?user=NL1ZyOgAAAAJ) · [LinkedIn](https://www.linkedin.com/in/yossi-eliaz/)
