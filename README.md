# Repolex Knowledge Graph of pytest-dev/pytest-tcpclient

RDF knowledge graph data for [pytest-dev/pytest-tcpclient](https://github.com/pytest-dev/pytest-tcpclient), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pytest-tcpclient
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── aa8b88db6605d97f607f6dfb13a8b6b400b42d9b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── aa8b88db6605d97f607f6dfb13a8b6b400b42d9b
│           └── chunk-001.nq.gz
├── blob
│   ├── 021502a06bcaacf6515d025e316b691e16cfaa36.nq.gz
│   ├── 103c105e17aa23fc0c64a4001c222bfa0c7a0ad3.nq.gz
│   ├── 13bd42101d7cebf2e35aedfc8d16b3017ce487d0.nq.gz
│   ├── 192ed7770741cdb9b322499c1003b9a549cc724f.nq.gz
│   ├── 197e6d6760a7165b5537cc61c5395529fd1d175d.nq.gz
│   ├── 1f5bea0415e4738ea60d1f5c3fd0f983b201b3e8.nq.gz
│   ├── 2101180f498ad675965d6deb32b164a65d0537b0.nq.gz
│   ├── 260c63261ce9daf009eb375c8e5a4bc1a092bd43.nq.gz
│   ├── 2b19f19fb164439b9f7b84ee8fcbba0af55c55c8.nq.gz
│   ├── 2b768d5f6ac5115caf2bd0970fe6d1ba90d0158a.nq.gz
│   ├── 2c1cf0f9d8eb99b5807e056f8f0177b1d2e0f3a4.nq.gz
│   ├── 39914f9731376c374626037ea5b3f73d391522ab.nq.gz
│   ├── 3e506a54a722393e5c1484957d2b338b7b89eea6.nq.gz
│   ├── 4ffefb4a6134eb2a912fe7a941e10f34b0a5651a.nq.gz
│   ├── 51ca7cf7f485cd297ae873830202f7dbd85e9afa.nq.gz
│   ├── 52a6925b0cca0a9caf9799350363975bbee4052a.nq.gz
│   ├── 564fda854b571399091380dd6be186665f033f21.nq.gz
│   ├── 56d7c03d63de5f522b6abfd4861f1be5a8729eb6.nq.gz
│   ├── 5c3465843e4aa3f2600369c7af0e7c6c112503dd.nq.gz
│   ├── 5e4786a216b88492c5463e34efcc75c5613a1bc2.nq.gz
│   ├── 631934e1e50f8e9a257d7536e6a00951f3461aa5.nq.gz
│   ├── 649118382bfb47de411ca98340bb1067e846d813.nq.gz
│   ├── 66de749e826d4c13c327ce248ff90a10a380c20a.nq.gz
│   ├── 6928797630747958a7236bcb678223d14ad49d54.nq.gz
│   ├── 6b1ac875ac979fa009a88cdbdfa348b35f0452a7.nq.gz
│   ├── 6bd7a8a15fc67c3016da34c68dca4a36ca9dfb93.nq.gz
│   ├── 6da3f30bd564f104505ed8eea765179f48772990.nq.gz
│   ├── 73258ddd4511a520e64586897648939e88beed6c.nq.gz
│   ├── 760ecb83bfcb955fe290c99f34ac8271639bc626.nq.gz
│   ├── 7f1a1763ca9cebc7bc16576d353d3284ee5d3c7d.nq.gz
│   ├── 7ffa772434981752977d8ecb2acde78eb4faf209.nq.gz
│   ├── 81863b953d2801b121e234e9d9b13b0e3c5f564b.nq.gz
│   ├── 851b6dca1a6d2a4a564e03c3d360ca1f0201f2f3.nq.gz
│   ├── 8c0ac7ed59d1f350737970eaee556de79c190250.nq.gz
│   ├── 8dee08b419589e201a4079b644c30a2c3d4d31e4.nq.gz
│   ├── 9276757226a71c1df62baa6bfd296937c6da85c1.nq.gz
│   ├── 9a9aa7ff36c2bb50d2783d4063a97822ccd569ce.nq.gz
│   ├── a08525ab9484893f9eda6b3bc3fc6880087339b4.nq.gz
│   ├── a33e54581f7104ca9873555ff1c1123379a28bf7.nq.gz
│   ├── aae85184e266ba08a5a6236e340236e3dc56286e.nq.gz
│   ├── add1ee878912ab722868d992dba3d9f4554e74a6.nq.gz
│   ├── b00965cab9f527b9ceb00740eced566cff0ab5a6.nq.gz
│   ├── b8cd6fbfdfe0b48ae721663bf72ffbc2a49895d7.nq.gz
│   ├── c54dbd6d20b0a70b4c00d7268a795988ee47ca44.nq.gz
│   ├── c5ead2c20bc1003db65523ac85739e9d40f13042.nq.gz
│   ├── c6481d5f740462ec9fd3edcb32aa56806e316c77.nq.gz
│   ├── c76aba0760789e391e5a65423d29b7b54a825e59.nq.gz
│   ├── c90c3bd99f7532b09959509b9feca81844235466.nq.gz
│   ├── c9bac39368960f40fb3e2d0f819a2051d0ffdebe.nq.gz
│   ├── d24c9ee59de1acd056e59e0d333d49771cccbe0d.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── e34cbf69bf7fe81e8b7ab591ea601df4224a4164.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8c87699f437630888b010558a9ef79d905f8c79.nq.gz
│   ├── ea3e58d9e873c068326f6dc245990fafb9d378f6.nq.gz
│   ├── ef4c97eee727ce63e1435c313e666404c2ee3c66.nq.gz
│   ├── efa685aed3a4c004049340a8135467246dba2b57.nq.gz
│   ├── f0f0498a520fc785562ca4c79269749c9959776c.nq.gz
│   ├── f378cd537055a6b9758597916d88664014b42152.nq.gz
│   └── fc31a842cfdeeee10fd655e8090abfe14e144d5d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── aa8b88db6605d97f607f6dfb13a8b6b400b42d9b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 68 files
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

[pytest-dev/pytest-tcpclient](https://github.com/pytest-dev/pytest-tcpclient)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
