# Repolex Knowledge Graph of litestar-org/litestar-htmx

RDF knowledge graph data for [litestar-org/litestar-htmx](https://github.com/litestar-org/litestar-htmx), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/litestar-htmx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e5c4e2fcdbb53b7bad1c469f1167a5684616d360
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e5c4e2fcdbb53b7bad1c469f1167a5684616d360
│           └── chunk-001.nq.gz
├── blob
│   ├── 000b97d5aff4ef4781755324fa76851566e43a7f.nq.gz
│   ├── 0a9c313862a4ad5e30ef92a51eb6b4ab0ec5f5d3.nq.gz
│   ├── 0e7d43938eb26cfea187aeb5b787dec2cb9d109c.nq.gz
│   ├── 26472636e20c0a4abf1a835063298bdad6f5fd23.nq.gz
│   ├── 2c668ed5705ff5cf8d3072ad8663e09795187204.nq.gz
│   ├── 3254cdef6cdb0091cb0e01ef4d707906617e1323.nq.gz
│   ├── 38126d09c082a764f91c9027a8945c067f498058.nq.gz
│   ├── 425522f1fcc7ec2158accd9f1ff10172bb185a44.nq.gz
│   ├── 43d1d205976a3211c4ffda84d47625805f6e0f83.nq.gz
│   ├── 4de092008ec5bd8a6dd356708e86b4eb8b2db63b.nq.gz
│   ├── 4f248c9ea5377e250618815db93eaca47505a6a1.nq.gz
│   ├── 5b4b1af059a1f316614e0a0f7ab03f97b4665692.nq.gz
│   ├── 6273f887eea620b6e14429cdb3a11173668bd568.nq.gz
│   ├── 66be1462ebe8d2301e7063fe56b38f6891e98a40.nq.gz
│   ├── 6c2eb45b7de2aa49908a2cdb9ee4320d63097e14.nq.gz
│   ├── 6c7cd5718820a0e6cfe3eb9d75f308b6f21a6ae6.nq.gz
│   ├── 6e7c44ce8779c2363f05bd589d219bb3cf8d78c7.nq.gz
│   ├── 709733d949bfd7f9adfe140b1cbf560ced65cc73.nq.gz
│   ├── 747085e1a702c330d6cb624470d934ce49fd7c4d.nq.gz
│   ├── 784d98581057269012808bbcaa5509e39f96fcd2.nq.gz
│   ├── 79d632edb51053a51e55666d7623883eaa295799.nq.gz
│   ├── 7bca45d25f1545d15218931386ef611ae8b88467.nq.gz
│   ├── 7f0cee9e3b1e4da9e7ebd0f54da62c22a6ae211d.nq.gz
│   ├── 8425dd5c95b164a386be949a4c6bb0712f9cafee.nq.gz
│   ├── 9690daf0cc8346f95343909ab84da66cd6ffeeb8.nq.gz
│   ├── 9e59200f5007828033a6f5a96cffaa6ff0ee38de.nq.gz
│   ├── a3c95d77e24b2e9d851df2fa68a7dd35033a1076.nq.gz
│   ├── ac46473a3b576b64f71471f72fc3054127030549.nq.gz
│   ├── b4ad7b7b424205b877db1c399d6a4985a9538c13.nq.gz
│   ├── bbd440e7a11cd492aeadbc4fe999f354366866df.nq.gz
│   ├── c397a887fe6aabdcfde1241128e9c8367e3bdd59.nq.gz
│   ├── c3daf9aa2afe023231e2909e2b6333802b1ea60c.nq.gz
│   ├── c57b119eab3d77f5612dcd2ff9b38010a260c49a.nq.gz
│   ├── d28efb3d1a6b92b0147d195f5691a6ca463b4458.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d77f4c78f8037ab814f182552cb6f5cf3db67d20.nq.gz
│   ├── dae2fd2988280a6252356a33bc8859cb766af937.nq.gz
│   ├── dbcf9fc0eb54ed38e27e63dc55d4ce21f12e3cba.nq.gz
│   ├── e29316e07f415a3e7d5d678985f58f19c1e329b8.nq.gz
│   ├── e3c5e57e2814ffecdbcf0b06733f72d64804c797.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed74eb475482c43d0349d07b08f81a27abe7a606.nq.gz
│   ├── eeeabd6592ee07ad7ecf40d2bb3258fb9f46227a.nq.gz
│   ├── f4f5d1c291462ec21a7cfa9f69229d575390af94.nq.gz
│   └── f814d5183836c6c854d3c7192e02c4ac5379464c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e5c4e2fcdbb53b7bad1c469f1167a5684616d360.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[litestar-org/litestar-htmx](https://github.com/litestar-org/litestar-htmx)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
