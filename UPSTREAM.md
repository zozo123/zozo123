# Upstream open-source contributions

**Verified November 1, 2026** from the connected GitHub search results. These are authored pull requests **merged into other repositories**, excluding the personal account and a defined set of employer/teaching organizations; they are not a count of all submitted PRs or all commits.

- **150 merged authored PRs** across **33 external repositories**; **115 merged in 2026**.
- **17 open PRs** across external repositories at this snapshot; open work is not counted as merged.
- The author-PR search misses some authored commits integrated via maintainer-owned PRs or mirrors; important verified examples are documented below.

## Representative landed work

- **Apache Airflow:** [SandboxToolset #68847](https://github.com/apache/airflow/pull/68847) for agent shell/file tools; [Islo #71672](https://github.com/apache/airflow/pull/71672), [Boat #71725](https://github.com/apache/airflow/pull/71725), [OpenSandbox #71676](https://github.com/apache/airflow/pull/71676), and [OpenShell #73961](https://github.com/apache/airflow/pull/73961) backends; [zstd image stash #73997](https://github.com/apache/airflow/pull/73997), [snapshot materialization #74173](https://github.com/apache/airflow/pull/74173), and [dependency reuse #74466](https://github.com/apache/airflow/pull/74466) for CI.
- **OpenClaw Crabbox:** provider integrations, lifecycle and broker controls; representative [delegated lease heartbeat #1707](https://github.com/openclaw/crabbox/pull/1707), [OAuth/session identity binding #1158](https://github.com/openclaw/crabbox/pull/1158), [parallel shard cap #2935](https://github.com/openclaw/crabbox/pull/2935), and [Cloud Run provider #1160](https://github.com/openclaw/crabbox/pull/1160).
- **OpenClaw core:** [SSRF/pinned-dispatch HTTP/2 mitigation #61777](https://github.com/openclaw/openclaw/pull/61777), [Docker apt-GPG key pinning #74254](https://github.com/openclaw/openclaw/pull/74254), [Slack thread-context fix #63840](https://github.com/openclaw/openclaw/pull/63840), and [Ollama provider base URL fix #61776](https://github.com/openclaw/openclaw/pull/61776).
- **Omnigent:** [Islo provider #42](https://github.com/omnigent-ai/omnigent/pull/42), [bubblewrap helper lifetime fix #10058](https://github.com/omnigent-ai/omnigent/pull/10058), [hermetic Databricks e2e #10843](https://github.com/omnigent-ai/omnigent/pull/10843).
- **SQLFluff:** [13 merged PRs](https://github.com/sqlfluff/sqlfluff/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged) across Databricks, Snowflake, DuckDB, StarRocks, Greenplum, Oracle, and rules/CI behavior.
- **Historical systems and genomics:** [balena-engine](https://github.com/balena-os/balena-engine/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged) Docker/runc and integration test work; [straw](https://github.com/aidenlab/straw/pulls?q=is%3Apr+author%3Azozo123+is%3Amerged) Python/MATLAB Hi-C interfaces and packaging.

### Authored commits merged through a different PR flow

- **[Apache Spark](https://github.com/apache/spark/commit/56da062b59f8ae58faa81554c76de49937d2d232):** authored SPARK-59886 patch for Spark-controlled UDF worker dispatch, committed upstream by a maintainer. This is an authored landed commit, not a separately counted author-owned merged PR.
- **[Bazel](https://github.com/bazelbuild/bazel/commit/d97111e4712b104c726fb66f7963434cb0457fcc):** authored fix for paginated PR review retrieval and fail-closed behavior, integrated through the upstream project workflow. Not separately counted in the 150 author-owned merged PRs.

## All external repositories with merged authored PRs (33)

| Repository | Merged PRs |
| --- | ---: |
| [openclaw/crabbox](https://github.com/openclaw/crabbox/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 65 |
| [apache/airflow](https://github.com/apache/airflow/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 20 |
| [sqlfluff/sqlfluff](https://github.com/sqlfluff/sqlfluff/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 13 |
| [balena-os/balena-engine](https://github.com/balena-os/balena-engine/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 11 |
| [aidenlab/straw](https://github.com/aidenlab/straw/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 5 |
| [openclaw/openclaw](https://github.com/openclaw/openclaw/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 4 |
| [omnigent-ai/omnigent](https://github.com/omnigent-ai/omnigent/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 3 |
| [balena-io-modules/network-manager](https://github.com/balena-io-modules/network-manager/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 2 |
| [balena-os/balena-libnetwork](https://github.com/balena-os/balena-libnetwork/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 2 |
| [nushell/nushell](https://github.com/nushell/nushell/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 2 |
| [axios/axios](https://github.com/axios/axios/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [balena-os/balena-raspberrypi](https://github.com/balena-os/balena-raspberrypi/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [balena-os/balena-supervisor](https://github.com/balena-os/balena-supervisor/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [davidliwei/awesome-CRISPR](https://github.com/davidliwei/awesome-CRISPR/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [fivetran/great_expectations](https://github.com/fivetran/great_expectations/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [fredrikloch/hugo-uno](https://github.com/fredrikloch/hugo-uno/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [fungiboletus/bktree-javascript](https://github.com/fungiboletus/bktree-javascript/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [hussius/tabnet_fork](https://github.com/hussius/tabnet_fork/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [kmayerb/tcrdist3](https://github.com/kmayerb/tcrdist3/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [lammps/lammps](https://github.com/lammps/lammps/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [langchain-ai/docs](https://github.com/langchain-ai/docs/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [networkx/networkx](https://github.com/networkx/networkx/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [nrgene/simppl](https://github.com/nrgene/simppl/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [pydantic/monty](https://github.com/pydantic/monty/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [segmentio/aws-okta](https://github.com/segmentio/aws-okta/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [sheindyfr/CoronAlerts](https://github.com/sheindyfr/CoronAlerts/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [sokrypton/ColabFold](https://github.com/sokrypton/ColabFold/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [SuperInstance/quilt](https://github.com/SuperInstance/quilt/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [topoteretes/cognee](https://github.com/topoteretes/cognee/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [twistlock/authz](https://github.com/twistlock/authz/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [vitessio/vitess](https://github.com/vitessio/vitess/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [withastro/flue](https://github.com/withastro/flue/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |
| [zed-industries/zed](https://github.com/zed-industries/zed/pulls?q=is%3Apr%20author%3Azozo123%20is%3Amerged) | 1 |

<details>
<summary>All 150 merged pull requests, grouped by upstream repository</summary>

### openclaw/crabbox — 65 merged

- [#2935: feat(shard): cap parallel shards with --concurrency](https://github.com/openclaw/crabbox/pull/2935)
- [#2303: provider(ascii-box): support the Boat rebrand end to end](https://github.com/openclaw/crabbox/pull/2303)
- [#2292: fix(external): reclaim abandoned Windows slug reservation locks](https://github.com/openclaw/crabbox/pull/2292)
- [#1707: feat: let delegated providers keep a lease alive](https://github.com/openclaw/crabbox/pull/1707)
- [#2275: docs: redesign README with task-first structure and SVG banner](https://github.com/openclaw/crabbox/pull/2275)
- [#2274: docs: document coordinator runtimes in agent guidance](https://github.com/openclaw/crabbox/pull/2274)
- [#1706: feat(islo): add opt-in idle pausing](https://github.com/openclaw/crabbox/pull/1706)
- [#1911: feat: publish Crabbox sandbox quickstart for skills.sh](https://github.com/openclaw/crabbox/pull/1911)
- [#1708: fix(islo): validate sandbox identity before status and cleanup](https://github.com/openclaw/crabbox/pull/1708)
- [#1705: docs: record why the islo provider stays delegated-run](https://github.com/openclaw/crabbox/pull/1705)
- [#1189: docs: clarify use cases, costs, and runtime boundaries](https://github.com/openclaw/crabbox/pull/1189)
- [#1174: docs: add pi coding agent to the Agent Skills compatibility catalog](https://github.com/openclaw/crabbox/pull/1174)
- [#1162: fix(cp): prefer secluded rsync args for resolved SSH copies](https://github.com/openclaw/crabbox/pull/1162)
- [#1160: feat: add Google Cloud Run sandbox provider](https://github.com/openclaw/crabbox/pull/1160)
- [#1158: fix(auth): bind OAuth and sessions to immutable identity](https://github.com/openclaw/crabbox/pull/1158)
- [#1155: feat: publish integrations and Crabbox Agent Skill discovery](https://github.com/openclaw/crabbox/pull/1155)
- [#1142: feat(zed): add Crabbox provider-layer extension](https://github.com/openclaw/crabbox/pull/1142)
- [#1136: feat(cli): improve editor handoffs for agents and humans](https://github.com/openclaw/crabbox/pull/1136)
- [#1141: fix(docs): make all sidebar counts reflect content pages](https://github.com/openclaw/crabbox/pull/1141)
- [#1083: feat: add Herdr plugin](https://github.com/openclaw/crabbox/pull/1083)
- [#1062: docs: add Features capability explorer](https://github.com/openclaw/crabbox/pull/1062)
- [#1051: docs: make providers first-class in the docs experience](https://github.com/openclaw/crabbox/pull/1051)
- [#458: feat: add Orgo provider](https://github.com/openclaw/crabbox/pull/458)
- [#986: feat(provider): add Unikraft Cloud service provider](https://github.com/openclaw/crabbox/pull/986)
- [#1021: docs: add hermetic agent evidence pattern](https://github.com/openclaw/crabbox/pull/1021)
- [#1019: feat: add sync-plan json output](https://github.com/openclaw/crabbox/pull/1019)
- [#1018: fix: keep crabbox runtime state out of sync](https://github.com/openclaw/crabbox/pull/1018)
- [#1004: feat(provider): add CubeSandbox provider](https://github.com/openclaw/crabbox/pull/1004)
- [#980: fix: declare archive-sync feature for daytona provider](https://github.com/openclaw/crabbox/pull/980)
- [#979: docs: define islo gateway profile and document live smoke env vars](https://github.com/openclaw/crabbox/pull/979)
- [#981: ci: add hermetic end-to-end connector smoke workflow](https://github.com/openclaw/crabbox/pull/981)
- [#978: docs: fix coordinator API methods, backend-kind labels, and cli command map](https://github.com/openclaw/crabbox/pull/978)
- [#345: docs: add Slurm academic sandbox plan and adapter](https://github.com/openclaw/crabbox/pull/345)
- [#346: docs: add Station profiles security roadmap](https://github.com/openclaw/crabbox/pull/346)
- [#326: feat: add marketplace credits gateway skeleton](https://github.com/openclaw/crabbox/pull/326)
- [#531: \[codex\] add FastAPI Cloud service-control provider](https://github.com/openclaw/crabbox/pull/531)
- [#428: Fix Islo provider default create payload](https://github.com/openclaw/crabbox/pull/428)
- [#352: feat(cloudflare): advertise FeatureRunSession + return run-session handle](https://github.com/openclaw/crabbox/pull/352)
- [#238: feat: add Windows Sandbox provider](https://github.com/openclaw/crabbox/pull/238)
- [#220: feat: add smolvm provider (Smol Machines / smolfleet)](https://github.com/openclaw/crabbox/pull/220)
- [#281: feat(islo): expose direct SSH hostnames](https://github.com/openclaw/crabbox/pull/281)
- [#148: feat: add freestyle.sh delegated-run provider](https://github.com/openclaw/crabbox/pull/148)
- [#199: feat: pause/resume commands via optional PausableBackend (islo first)](https://github.com/openclaw/crabbox/pull/199)
- [#205: feat(islo): add Tailscale plane to the islo provider](https://github.com/openclaw/crabbox/pull/205)
- [#236: feat(provider): add OpenComputer sandbox provider (REST API)](https://github.com/openclaw/crabbox/pull/236)
- [#226: Require evidence artifacts for run proofs](https://github.com/openclaw/crabbox/pull/226)
- [#198: islo: align provider with current Islo API status/SSE contract](https://github.com/openclaw/crabbox/pull/198)
- [#203: fix: restrict lease metadata writes](https://github.com/openclaw/crabbox/pull/203)
- [#195: \[codex\] docs: use reliable release badge](https://github.com/openclaw/crabbox/pull/195)
- [#192: feat: add apple-container local development provider](https://github.com/openclaw/crabbox/pull/192)
- [#191: docs: scope README Release badge to push events](https://github.com/openclaw/crabbox/pull/191)
- [#157: feat: add ASCII Box provider](https://github.com/openclaw/crabbox/pull/157)
- [#181: feat(islo): implement Crabbox run session handles](https://github.com/openclaw/crabbox/pull/181)
- [#129: feat: introduce pond (peer discovery + bridge + ssh-mesh)](https://github.com/openclaw/crabbox/pull/129)
- [#177: Add Azure Dynamic Sessions provider](https://github.com/openclaw/crabbox/pull/177)
- [#173: feat(init): detect repo checks during onboarding](https://github.com/openclaw/crabbox/pull/173)
- [#132: feat(wandb): native gRPC sandbox provider](https://github.com/openclaw/crabbox/pull/132)
- [#133: feat: add runpod provider](https://github.com/openclaw/crabbox/pull/133)
- [#119: feat: add railway sandbox provider](https://github.com/openclaw/crabbox/pull/119)
- [#72: Add Actions-first failure capsules](https://github.com/openclaw/crabbox/pull/72)
- [#85: feat: add Modal delegated-run provider](https://github.com/openclaw/crabbox/pull/85)
- [#74: feat: add Tensorlake delegated-run provider](https://github.com/openclaw/crabbox/pull/74)
- [#75: docs(islo): document ssh access via islo ssh --setup](https://github.com/openclaw/crabbox/pull/75)
- [#41: Add E2B provider](https://github.com/openclaw/crabbox/pull/41)
- [#32: fix: reject daytona resource override flags](https://github.com/openclaw/crabbox/pull/32)

### apache/airflow — 20 merged

- [#74173: Accelerate CI image materialization with same-run snapshots](https://github.com/apache/airflow/pull/74173)
- [#74311: Run dependency explanations separately from main AMD canaries](https://github.com/apache/airflow/pull/74311)
- [#74466: Reuse locked CI dependencies across workspace source changes](https://github.com/apache/airflow/pull/74466)
- [#73961: Add OpenShell backend for sandbox tools](https://github.com/apache/airflow/pull/73961)
- [#71672: Add Islo backend for sandbox tools](https://github.com/apache/airflow/pull/71672)
- [#71725: Add Boat backend for sandbox tools](https://github.com/apache/airflow/pull/71725)
- [#74504: Require dns+nft egress mode for OpenSandbox network policies](https://github.com/apache/airflow/pull/74504)
- [#74191: Notify downstream Dags when COPY INTO writes a Unity (Databricks) table](https://github.com/apache/airflow/pull/74191)
- [#74172: Fail provider DB test jobs when their tests fail](https://github.com/apache/airflow/pull/74172)
- [#74055: Run only the tests that import a changed test helper](https://github.com/apache/airflow/pull/74055)
- [#74076: Shrink the CI image by skipping unused Rust docs and the Go archive](https://github.com/apache/airflow/pull/74076)
- [#74052: Stop wiping the uv cache before every CI image build](https://github.com/apache/airflow/pull/74052)
- [#73997: Speed up CI image restores with zstd-compressed stashes](https://github.com/apache/airflow/pull/73997)
- [#71676: Add OpenSandbox backend for sandbox tools](https://github.com/apache/airflow/pull/71676)
- [#73184: Optimize CI disk cleanup](https://github.com/apache/airflow/pull/73184)
- [#73182: Republish repaired prek caches and keep unrelated host caches](https://github.com/apache/airflow/pull/73182)
- [#73183: Optimize UI and Playwright dependency caching](https://github.com/apache/airflow/pull/73183)
- [#73185: Run migration tests once per backend instead of in every core test shard](https://github.com/apache/airflow/pull/73185)
- [#68847: Add SandboxToolset for sandboxed agent shell and file access](https://github.com/apache/airflow/pull/68847)
- [#70096: Validate common AI tool-call arguments to enable pydantic-ai retries](https://github.com/apache/airflow/pull/70096)

### sqlfluff/sqlfluff — 13 merged

- [#7731: feat: Add option for non-zero exit on large_file_skip](https://github.com/sqlfluff/sqlfluff/pull/7731)
- [#7735: fix(databricks): RF03 should not flag STRUCT function aliases](https://github.com/sqlfluff/sqlfluff/pull/7735)
- [#7729: fix(LT09): Consistent single/multi target newline behavior](https://github.com/sqlfluff/sqlfluff/pull/7729)
- [#7726: refactor(oracle): Move keywords to separate file](https://github.com/sqlfluff/sqlfluff/pull/7726)
- [#7732: fix(databricks): Allow _metadata column references](https://github.com/sqlfluff/sqlfluff/pull/7732)
- [#7738: fix(LT02): Don't force FROM/VALUES separation when values are inline](https://github.com/sqlfluff/sqlfluff/pull/7738)
- [#7728: fix(sparksql): Add regression tests for struct field access alignment (#6913)](https://github.com/sqlfluff/sqlfluff/pull/7728)
- [#7727: fix: Apply warning-level fixes even when no errors present](https://github.com/sqlfluff/sqlfluff/pull/7727)
- [#7725: fix(greenplum): Add support for CREATE/DROP EXTERNAL TABLE](https://github.com/sqlfluff/sqlfluff/pull/7725)
- [#7724: fix(snowflake): Exclude NEXTVAL/CURRVAL sequences from references.from checks](https://github.com/sqlfluff/sqlfluff/pull/7724)
- [#7717: feat(starrocks): Add support for ARRAY, MAP, and STRUCT types](https://github.com/sqlfluff/sqlfluff/pull/7717)
- [#7718: fix(snowflake): Support multiple statements in EXCEPTION WHEN handlers](https://github.com/sqlfluff/sqlfluff/pull/7718)
- [#7694: \[codex\] Fix DuckDB double-quoted struct keys](https://github.com/sqlfluff/sqlfluff/pull/7694)

### balena-os/balena-engine — 11 merged

- [#61: balena additional naming fixes ](https://github.com/balena-os/balena-engine/pull/61)
- [#53: Updated github hooks for balena](https://github.com/balena-os/balena-engine/pull/53)
- [#50: updated the mock of xfer to pass unit test](https://github.com/balena-os/balena-engine/pull/50)
- [#49: Adjusting makefile for balena](https://github.com/balena-os/balena-engine/pull/49)
- [#36: Fixing integration tests](https://github.com/balena-os/balena-engine/pull/36)
- [#22: Fixed runc version](https://github.com/balena-os/balena-engine/pull/22)
- [#21: integration: Skip plugin tests](https://github.com/balena-os/balena-engine/pull/21)
- [#18: Stabilized and adjusted tests for rce-docker 17.06](https://github.com/balena-os/balena-engine/pull/18)
- [#6: Changed rce target name](https://github.com/balena-os/balena-engine/pull/6)
- [#5: renamed rce target to rce-docker](https://github.com/balena-os/balena-engine/pull/5)
- [#3: Boxed docker 17.03 and reduced bin size](https://github.com/balena-os/balena-engine/pull/3)

### aidenlab/straw — 5 merged

- [#41: Updated pypi version](https://github.com/aidenlab/straw/pull/41)
- [#40: Updated pypi version](https://github.com/aidenlab/straw/pull/40)
- [#29: hic-straw: published the PyPi lib](https://github.com/aidenlab/straw/pull/29)
- [#28: Straw: Allowed loading the python module to MATLAB](https://github.com/aidenlab/straw/pull/28)
- [#27: Block map adapting for Python3](https://github.com/aidenlab/straw/pull/27)

### openclaw/openclaw — 4 merged

- [#63840: fix(slack): preserve thread context for Agents & Assistants DM root messages](https://github.com/openclaw/openclaw/pull/63840)
- [#74254: fix(docker): require single primary key before Docker apt GPG pin](https://github.com/openclaw/openclaw/pull/74254)
- [#61777: fix(ssrf): disable HTTP/2 for pinned dispatchers (undici 8.0)](https://github.com/openclaw/openclaw/pull/61777)
- [#61776: fix(ollama): resolve per-provider baseUrl in createStreamFn](https://github.com/openclaw/openclaw/pull/61776)

### omnigent-ai/omnigent — 3 merged

- [#10843: test(e2e): make the exported-base-url Databricks e2e hermetic (into #10069)](https://github.com/omnigent-ai/omnigent/pull/10843)
- [#10058: fix(os-env): spawn the bwrap helper from a thread that outlives requests](https://github.com/omnigent-ai/omnigent/pull/10058)
- [#42: \[codex\] add islo sandbox provider](https://github.com/omnigent-ai/omnigent/pull/42)

### balena-io-modules/network-manager — 2 merged

- [#37: Added support to retrieve wifi ssid from environment ](https://github.com/balena-io-modules/network-manager/pull/37)
- [#22: Added a netwrok manager status function](https://github.com/balena-io-modules/network-manager/pull/22)

### balena-os/balena-libnetwork — 2 merged

- [#3: proxy: renamed docker-proxy to balena-proxy](https://github.com/balena-os/balena-libnetwork/pull/3)
- [#2: Enabled remote to support network create -d](https://github.com/balena-os/balena-libnetwork/pull/2)

### nushell/nushell — 2 merged

- [#18999: Fix par-each deadlock when chaining same-size thread pools](https://github.com/nushell/nushell/pull/18999)
- [#18810: Test Incredibuild self-hosted runner in CI](https://github.com/nushell/nushell/pull/18810)

### axios/axios — 1 merged

- [#10806: fix(fetch): preserve abort reasons in fetch adapter](https://github.com/axios/axios/pull/10806)

### balena-os/balena-raspberrypi — 1 merged

- [#130: rpi: set always overcommit policy on](https://github.com/balena-os/balena-raspberrypi/pull/130)

### balena-os/balena-supervisor — 1 merged

- [#319: Makefile: removed the deprecated force flag](https://github.com/balena-os/balena-supervisor/pull/319)

### davidliwei/awesome-CRISPR — 1 merged

- [#19: Added CRISPR-SURF to list](https://github.com/davidliwei/awesome-CRISPR/pull/19)

### fivetran/great_expectations — 1 merged

- [#11920: \[DOCS\] Fix typos in the Run a Validation Definition guide](https://github.com/fivetran/great_expectations/pull/11920)

### fredrikloch/hugo-uno — 1 merged

- [#28: Update README.md](https://github.com/fredrikloch/hugo-uno/pull/28)

### fungiboletus/bktree-javascript — 1 merged

- [#1: LICENSE](https://github.com/fungiboletus/bktree-javascript/pull/1)

### hussius/tabnet_fork — 1 merged

- [#4: Update README.md](https://github.com/hussius/tabnet_fork/pull/4)

### kmayerb/tcrdist3 — 1 merged

- [#58: Added a missing argument when calling _synthesize_vj_matched_background](https://github.com/kmayerb/tcrdist3/pull/58)

### lammps/lammps — 1 merged

- [#838: Tools/Matlab: Allow to read LAMMPS output fields](https://github.com/lammps/lammps/pull/838)

### langchain-ai/docs — 1 merged

- [#4345: docs: add Islo sandbox integration](https://github.com/langchain-ai/docs/pull/4345)

### networkx/networkx — 1 merged

- [#5104: vertex-cover: Added support for self-loop edges and improved performance](https://github.com/networkx/networkx/pull/5104)

### nrgene/simppl — 1 merged

- [#7: Update setup.py](https://github.com/nrgene/simppl/pull/7)

### pydantic/monty — 1 merged

- [#147: handle i64::MIN division overflow in //, %, and divmod()](https://github.com/pydantic/monty/pull/147)

### segmentio/aws-okta — 1 merged

- [#304: Added Ubuntu 2020 (Focal) to Makefile.release](https://github.com/segmentio/aws-okta/pull/304)

### sheindyfr/CoronAlerts — 1 merged

- [#1: Update README.md](https://github.com/sheindyfr/CoronAlerts/pull/1)

### sokrypton/ColabFold — 1 merged

- [#153: Update README.md](https://github.com/sokrypton/ColabFold/pull/153)

### SuperInstance/quilt — 1 merged

- [#6: ci: run workflows on Incredibuild runners](https://github.com/SuperInstance/quilt/pull/6)

### topoteretes/cognee — 1 merged

- [#4082: feat(deploy): add Islo SDK sandbox deployment](https://github.com/topoteretes/cognee/pull/4082)

### twistlock/authz — 1 merged

- [#10: AuthZ: Added .gitignore and make gofmt satisfied](https://github.com/twistlock/authz/pull/10)

### vitessio/vitess — 1 merged

- [#1627: Added go report card](https://github.com/vitessio/vitess/pull/1627)

### withastro/flue — 1 merged

- [#75: Add islo sandbox connector](https://github.com/withastro/flue/pull/75)

### zed-industries/zed — 1 merged

- [#60968: Improve sccache cache reuse](https://github.com/zed-industries/zed/pull/60968)

</details>

## Open external pull requests at this snapshot (17)

These are under upstream review and **not** included in the merged totals. [Live GitHub search](https://github.com/pulls?q=author%3Azozo123+is%3Apr+is%3Aopen) may show a broader set, including repositories outside this page's exclusions.

- **openclaw/openclaw** — [#155634: feat(provider): add Databricks Unity Gateway](https://github.com/openclaw/openclaw/pull/155634)
- **openclaw/crabbox** — [#2992: docs: fix stale README facts and smooth the local quick start](https://github.com/openclaw/crabbox/pull/2992)
- **apache/airflow** — [#76156: Databricks: add Delta table version producer for externally written tables (#74195)](https://github.com/apache/airflow/pull/76156)
- **omnigent-ai/omnigent** — [#12429: feat(sdk): make omnigent-client installable without the omnigent server](https://github.com/omnigent-ai/omnigent/pull/12429)
- **openclaw/openclaw** — [#155442: feat(swarm): add bounded launch contract for exact candidate verification](https://github.com/openclaw/openclaw/pull/155442)
- **apache/airflow** — [#76157: Add a resumable deferrable Databricks Genie operator](https://github.com/apache/airflow/pull/76157)
- **zed-industries/zed** — [#66360: remote: Accept shell-quoted ssh executable in SSH command lines](https://github.com/zed-industries/zed/pull/66360)
- **omnigent-ai/omnigent** — [#10716: fix(databricks): run the SDK token fallback with omnigent's interpreter](https://github.com/omnigent-ai/omnigent/pull/10716)
- **omnigent-ai/omnigent** — [#10845: fix(claude-sdk): exit non-zero when the apiKeyHelper mints no token](https://github.com/omnigent-ai/omnigent/pull/10845)
- **omnigent-ai/omnigent** — [#9944: feat(cli): add omnigent speculate to race agents and keep verified code](https://github.com/omnigent-ai/omnigent/pull/9944)
- **omnigent-ai/omnigent** — [#9873: Add Boat.dev managed sandbox provider](https://github.com/omnigent-ai/omnigent/pull/9873)
- **apache/spark** — [#59231: \[SPARK-59083\]\[UDF\] Run scalar external UDFs in a CPython worker](https://github.com/apache/spark/pull/59231)
- **bazelbuild/bazel** — [#31993: Reuse a scratch buffer for Merkle tree directory digests under BlobPolicy.DISCARD](https://github.com/bazelbuild/bazel/pull/31993)
- **apache/spark** — [#59230: \[SPARK-57214\]\[UDF\] Ship the direct UDF dispatcher in a shaded runtime jar](https://github.com/apache/spark/pull/59230)
- **apache/spark** — [#59232: \[SPARK-55278\]\[UDF\] Document and test direct worker launcher commands](https://github.com/apache/spark/pull/59232)
- **Aiven-Open/transforms-for-apache-kafka-connect** — [#207: Add the Sandbox transformation with wasm and sbx runtimes](https://github.com/Aiven-Open/transforms-for-apache-kafka-connect/pull/207)
- **gvago/incredibuild-qodo-demo** — [#5: Demo: CI as the control loop — Qodo × Islo × Incredibuild](https://github.com/gvago/incredibuild-qodo-demo/pull/5)

## Counting convention

The exact GitHub query excludes PRs under `zozo123`, `islo-labs`, `Incredibuild-RND`, and selected HIT teaching organizations. This prevents counting personal, employer-internal and course PRs as external upstream work. It does not establish how much effort each PR required, and a merged PR does not by itself demonstrate a particular performance or security outcome.

[All public projects](PROJECTS.md) · [Profile summary](README.md)
