# Repolex Knowledge Graph of ionelmc/python-tblib

RDF knowledge graph data for [ionelmc/python-tblib](https://github.com/ionelmc/python-tblib), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download ionelmc/python-tblib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d88606aab343749dfeccf16a813f63cbe2dae11e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d88606aab343749dfeccf16a813f63cbe2dae11e
│           └── chunk-001.nq.gz
├── blob
│   ├── 040ea204ef0d49e641fa58edc0196cef73b5f6f2.nq.gz
│   ├── 05c828e72d831c6a1edfd510302427a047a0fcd8.nq.gz
│   ├── 0990d9dad7367c2643216fcfcf7e19dcabd9e81c.nq.gz
│   ├── 124ce115993c8fa2107f39ade54ab7890c2807d0.nq.gz
│   ├── 2cfedffa157f83925c66a1a26bfab474d5e84060.nq.gz
│   ├── 2f57449df04b2ac3b85996561a3b0972e0aadfbd.nq.gz
│   ├── 3b82d65f607e8c55c1614cc7c3af50d5b065e5bd.nq.gz
│   ├── 3c737eb63cae1d045d52a315df9862de88d427b5.nq.gz
│   ├── 43952227540f17941912030bc8d301d87aa92ce7.nq.gz
│   ├── 44723143464e70b83f5cb8be29c4659fd418e672.nq.gz
│   ├── 4915f00e628c5eed4faa908a1fb5d19ec191349e.nq.gz
│   ├── 49e39a8f77fd6d49094502737913e0a2235b5607.nq.gz
│   ├── 4ad62328695c0eee28f8a46e07c24d95e84c6451.nq.gz
│   ├── 542cbf8afb7adc82ea46055f6806f3fda5f9677c.nq.gz
│   ├── 546c3277bfcc669894c3eb8c7e2bf5a84f07122f.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 586c7367de1cff5d362be309c0a4014b0905edb1.nq.gz
│   ├── 6d01ebed6789efd1ac617e41cef7cd3731c79d48.nq.gz
│   ├── 6d7199aa5b0fa4f8fa0b066addac233cf825ff1d.nq.gz
│   ├── 6e735628abfa1c7cfd63cff5d83ab103528d22f7.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 73290d0073cf49decc874e6cead809885e3202bc.nq.gz
│   ├── 7570d459548404a82e4fcf450a98d66cb251c199.nq.gz
│   ├── 790ec7cd61e3ed5e5c388459f2f84852c255ae4c.nq.gz
│   ├── 844749acd3cc7145707ca429a7c2018580c61e03.nq.gz
│   ├── 8f8054d37b6daa5aacc507f0e5907b86d0de3d6f.nq.gz
│   ├── 9da4a9f65ffee2b0d72c169ae36a61c8c658eb97.nq.gz
│   ├── a1ace4533a23c5e392526b95209579d452e9d53d.nq.gz
│   ├── a2d480bb79405d1371da3c20e8fe0f3999995624.nq.gz
│   ├── a446914a4659bfeef32947f0d85d95920019e1ff.nq.gz
│   ├── bba6ab4a4ae82671551eec1eb2e374220d1afe46.nq.gz
│   ├── bbb5cc0ade8c4b261c1ab68fe32f8e5d31dde503.nq.gz
│   ├── be510df84176f4a753a78cb32b8806044b902c94.nq.gz
│   ├── c03e307ab39cd6807b9bc0d8f404e716707c2533.nq.gz
│   ├── c1a280731498687c7c31c989352de02af0ada697.nq.gz
│   ├── ca3d005bf36e8b03371e30c2923407b785f5f8d1.nq.gz
│   ├── d069fb52fc7f5bb5a00119116997130995ae5e97.nq.gz
│   ├── d4de49c1f438b74840cd2887e3fb2e61fc45794b.nq.gz
│   ├── da9c516dd744b6c88dd8c91f58f7bcf8f7e8341b.nq.gz
│   ├── dfff3e994ba65ba29f7642b0a22c702dca05eadf.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── ed95b83bd3079ef8e97eaa04ab4576736568c613.nq.gz
│   └── f95eb78d8a603b0fe5d17560d0dd04877d55c71c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d88606aab343749dfeccf16a813f63cbe2dae11e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[ionelmc/python-tblib](https://github.com/ionelmc/python-tblib)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
