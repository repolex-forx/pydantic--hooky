# Repolex Knowledge Graph of pydantic/hooky

RDF knowledge graph data for [pydantic/hooky](https://github.com/pydantic/hooky), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/hooky
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2bd7ce0ac5d5658888806871a3db16a11150c398
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2bd7ce0ac5d5658888806871a3db16a11150c398
│           └── chunk-001.nq.gz
├── blob
│   ├── 096124fa239366ffe4731ad484ea498093c14345.nq.gz
│   ├── 0b4e0add056770d9c75f1baba98b2814bb418fe9.nq.gz
│   ├── 0d651fe6276bbe04490f47f5e7afeb016d1b43b0.nq.gz
│   ├── 0ea43a0282c44b7daa620fc9431b66175372a5a2.nq.gz
│   ├── 1b822d0f4747cb22ebf247f1a515feaca76d8b14.nq.gz
│   ├── 1fa7e4d10d31ac59589d9adfb0f6ee894f60b0f9.nq.gz
│   ├── 263a2cfc8909b3d7d23517a45eb09615c669f4ef.nq.gz
│   ├── 28bf388f1098f0adce6d01810f8b9f42ce622d86.nq.gz
│   ├── 2d758fa386d6d343d8270275f524dedc9ce669ee.nq.gz
│   ├── 37c35ca28763271496ddd5b4c4451d61813e49b1.nq.gz
│   ├── 455963f41782c79a8b56535770d474fc3decb00c.nq.gz
│   ├── 4c57b63d45b0def3b223d64e40ae8cc7674e6e95.nq.gz
│   ├── 4dac827bf2a93a2bf6fbc635cc75479ee7ca4246.nq.gz
│   ├── 5522d2b6de635a1586f06412879565546a6544c0.nq.gz
│   ├── 5cf49d452d379c6dbe20737d896a9ae28d7eb07c.nq.gz
│   ├── 610108ba53bc337a655a807f6dda92ee7376e9c7.nq.gz
│   ├── 66b230d0b1854bb09b113ade1a8eb7f17ef87b13.nq.gz
│   ├── 6731abce833764cd010c3ad24f9a53dd56fcd14e.nq.gz
│   ├── 68ec9e8dedc9772bfb854ae771b0b2d6046b0225.nq.gz
│   ├── 6d9ffb3f98817376294314b45c5bb2096007a0b8.nq.gz
│   ├── 782215f450a7909f7004ed987005da3071aca83e.nq.gz
│   ├── 7b064c139a782a7093d6ca0c6d34be2360768d55.nq.gz
│   ├── 86ebbb281a347e9d3a5f17033b1da6339315b923.nq.gz
│   ├── 998516d016aea65fcef8f7262636f179077fb5a1.nq.gz
│   ├── 9c1d0cb30bee4e14679131becf67394e585c9fc4.nq.gz
│   ├── 9c921d6d342c33589b292bcd121400d01fb053aa.nq.gz
│   ├── a98122d159aa323b108f2d7fd036360180babe3d.nq.gz
│   ├── b0f9ce4d41deda60e9789d4cca7802971844f754.nq.gz
│   ├── b1ad61327f1439a4f29d293719888234a2ebe7f8.nq.gz
│   ├── b4e86abd2ff5f8a96500bd3105f43374f7ecae15.nq.gz
│   ├── c578b8a4c1fe804352709e462d5dc0fcbe1ef1c2.nq.gz
│   ├── c59291f11afe641ab70db1fa3ccf8f005f645e0b.nq.gz
│   ├── cbe036586dec1744117322c999f6c1ee5e1c4a33.nq.gz
│   ├── d0b371a069cfcecc4357aba140398ed4e494ff3d.nq.gz
│   ├── d26cb165af0db2a9e999a48c5836773a015cd5e5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e711a8684fdc80d6537683d7e4ddb08fa71c0e12.nq.gz
│   ├── ee0959cbf5316a1cec1ab9090d9790b4fd737494.nq.gz
│   ├── ef38ba3f1f03f3008f99e65c1a35136ac15b5645.nq.gz
│   ├── f1adf0b73fcd5026a9de7aba376d90c1ee538d56.nq.gz
│   ├── f2021c6ba6b6cac450ff81f8ecf560195fc14d5c.nq.gz
│   ├── fc2d2d61762213e1b98fc1d7d771457cdef7e15a.nq.gz
│   ├── fd7332ee747b3b2343896d7bfaf9ad345649507e.nq.gz
│   └── fda4d7a53516c7d7831b812260302c5438127ca9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2bd7ce0ac5d5658888806871a3db16a11150c398.nq.gz
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

[pydantic/hooky](https://github.com/pydantic/hooky)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
