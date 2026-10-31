# Yossi Eliaz

**Engineering & Growth · Incredibuild / islo.dev**

AI, Genomics, Physics.

At Incredibuild / islo.dev, I work on engineering and growth for AI infrastructure. My background spans Linux kernels, computational genomics, and machine learning for autonomous driving. I have a PhD in physics and teach software engineering at HIT.

Currently teaching: [EASS Class X at HIT](https://eass-part-a-2026-x.github.io/lecture-notes/).

## Upstream contributions

[150 merged pull requests](https://github.com/search?type=pullrequests&q=author%3Azozo123+is%3Apr+is%3Amerged+-user%3Azozo123+-user%3Aislo-labs+-user%3AIncredibuild-RND+-user%3AEASS-PART-A-2026-X+-user%3AEASS-HIT-PART-B+-user%3AEASS-HIT-PART-A-2024-CLASS-V+-user%3AQuBind) in 35 open-source repositories, 112 of them in 2026 (as of October 2026).

- **[Crabbox](https://crabbox.sh/) (OpenClaw)** — [65 merged PRs](https://github.com/openclaw/crabbox/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged) since May 2026, including 18 sandbox providers (E2B, Modal, RunPod, Google Cloud Run, Azure Dynamic Sessions, Windows Sandbox and more) and a [lease heartbeat for delegated providers](https://github.com/openclaw/crabbox/pull/1707).
- **Apache Airflow** — [17 merged PRs](https://github.com/apache/airflow/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged): the [SandboxToolset](https://github.com/apache/airflow/pull/68847) for sandboxed agent shell and file access, sandbox backends for [Islo](https://github.com/apache/airflow/pull/71672), [Boat](https://github.com/apache/airflow/pull/71725), [OpenSandbox](https://github.com/apache/airflow/pull/71676) and [OpenShell](https://github.com/apache/airflow/pull/73961), and CI speedups such as [zstd-compressed image stashes](https://github.com/apache/airflow/pull/73997).
- **[Apache Spark](https://github.com/apache/spark/commit/56da062b59f8ae58faa81554c76de49937d2d232)** — external UDF dispatch routed through Spark-owned worker specifications instead of a user-supplied class hook (SPARK-59886).
- **[Omnigent](https://github.com/omnigent-ai/omnigent/pull/42)** — Islo sandbox provider and a [fix for sandbox helpers killed mid-request](https://github.com/omnigent-ai/omnigent/pull/10058).
- **[Bazel](https://github.com/bazelbuild/bazel/commit/d97111e4712b104c726fb66f7963434cb0457fcc)** — the Community Review Labeler now reads every page of a PR's reviews and fails closed on partial output.
- **Also merged** — [Zed](https://github.com/zed-industries/zed/pull/60968) (sccache cache reuse across CI checkouts), [Nushell](https://github.com/nushell/nushell/pull/18999) (a `par-each` deadlock), [axios](https://github.com/axios/axios/pull/10806), [Pydantic Monty](https://github.com/pydantic/monty/pull/147), [NetworkX](https://github.com/networkx/networkx/pull/5104), and [13 PRs in sqlfluff](https://github.com/sqlfluff/sqlfluff/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged).

## Building

- **[ForgeFS](https://github.com/zozo123/forgefs)** — isolated workspaces for concurrent coding agents; conflicting work survives as a fork.
- **[SWFactory](https://github.com/zozo123/ariflow-swfactory)** — GitHub issues to reviewed pull requests, with Airflow, coding agents, and human approval gates.
- **[T2T comparison](https://zozo123.github.io/t2t-vs-grch38/)** — a chromosome-by-chromosome comparison of human reference genomes, with results and caveats.

## Talks, 2026

- **Airflow Summit** — [Graphs of AI Coding: Orchestrating Agentic MapReduce with Airflow's New Sandboxes](https://airflowsummit.org/sessions/2026/graphs-of-ai-coding/)
- **Zenity AI Agent Security Summit, NYC** — [Your Agent Escaped Without Escaping the Sandbox](https://github.com/zozo123/nyc-talk)
- **Cambridge Systems Research Group** — [Forkable Sandboxes: The Runtime Layer for AI Software Factories](https://talks.cam.ac.uk/talk/index/273181/)

## Research

Computational genomics at Baylor College of Medicine and Rice University, and cancer transcriptomics at Harvard Medical School, with papers in Nature Communications, PNAS and Physical Review E. h-index 11 and about 800 citations on [Google Scholar](https://scholar.google.com/citations?user=NL1ZyOgAAAAJ).

[Website](https://yossieliaz.netlify.app/) · [CV (PDF)](https://yossieliaz.netlify.app/cv/Yossi-Eliaz-CV.pdf) · [Writing](https://zozo123.github.io/) · [Research](https://yossieliaz.netlify.app/research/) · [LinkedIn](https://www.linkedin.com/in/yossi-eliaz/)
