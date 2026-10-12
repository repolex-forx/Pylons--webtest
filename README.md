# Repolex Knowledge Graph of Pylons/webtest

RDF knowledge graph data for [Pylons/webtest](https://github.com/Pylons/webtest), parsed by [repolex](https://repolex.ai).

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
rlex download Pylons/webtest
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 938524c6162aeee147cf0bf5ab1b6b929e2cc21d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 938524c6162aeee147cf0bf5ab1b6b929e2cc21d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a2153dc6ac3eb7afe20a29e2927a96118432ac9.nq.gz
│   ├── 0a46755fdb12d8507db3b228c4d01e9cf17d75c4.nq.gz
│   ├── 10c175d19c6e9269fb2dec78b7d7aebfdf0e0d5d.nq.gz
│   ├── 142b6ca357fee89f09803fc9ad7ff676500c37cf.nq.gz
│   ├── 1b3c3613893a657ad8c630e89b2115477e8dce70.nq.gz
│   ├── 1e3114d98bc3078ac6bd1292cdd525d3cde9697b.nq.gz
│   ├── 22497bf630461576bdbe02ea6f92ab8087ca92f6.nq.gz
│   ├── 228a45d35d551182c6ed12eebf56d5f85852962a.nq.gz
│   ├── 24293877869fa0166d7eb54cbcffeccbde65f279.nq.gz
│   ├── 2958d35a5c09fc5581349b5d0c1a7f856ccc7d86.nq.gz
│   ├── 2c565a3f1b62e170638381e55b2afc48dc9562fe.nq.gz
│   ├── 2f5a9c3317abb9bc05371a7122e31bb561308702.nq.gz
│   ├── 35fe381a3c94544795f035f9b1f0150910189107.nq.gz
│   ├── 4b1eb68625911d250dc50c05eefd1a075ba16947.nq.gz
│   ├── 4ce32efb0010134d213a503c7056a21ced1a8bbd.nq.gz
│   ├── 60fc5dfacceb68c301f9077ff5d289b132364c07.nq.gz
│   ├── 67414754570bdd5662d43fcc6db7d9cf9cc851f8.nq.gz
│   ├── 67bbd614f8702a5d02d8deb342db2148c793b2ca.nq.gz
│   ├── 687792173dfd2c5104bf7c0fdc5c2f20b01103b9.nq.gz
│   ├── 6a230a8dbde0a81575905c798cf4e729e2e3e03e.nq.gz
│   ├── 6ab109a7f90c2269882c8b1143f2861aed2022ef.nq.gz
│   ├── 75b85d9f7aa3b4f219c4af5ee0595adedb412783.nq.gz
│   ├── 792d6005489ebee62cde02066f19c5521e620451.nq.gz
│   ├── 8264626d0002b248ddd0168a6140174b2f589eac.nq.gz
│   ├── 8335cff7bb7c5dc2cda5aef41d75ff892ef88789.nq.gz
│   ├── 93042880c11ec2e721a69e4e5461e35e0e6f1d03.nq.gz
│   ├── 94213d006fc9e46187665364ff32227a91817668.nq.gz
│   ├── 99a99eacba045f80d4534df961bd4f1cf32d393c.nq.gz
│   ├── 9daf4ca0216ed543b2062ee465990b2c857de31d.nq.gz
│   ├── a24cc5638e3f179cea26620bdc369a7174dcec0a.nq.gz
│   ├── a4c37733b237b7298d207eb24219e9bbac1e139e.nq.gz
│   ├── a769df940c8447e72467be403f7852c6a75cf740.nq.gz
│   ├── aa6e26db05e4fc863f18af2c06793ab085e2d937.nq.gz
│   ├── b5b2ecd5b3e43725075e02f24a55b358ba3ce9da.nq.gz
│   ├── b6c565bf84a69a9f6089bfde94acd7d1401383fb.nq.gz
│   ├── b98c53f4cadf556665f1751e65ad7867bdd5fe6c.nq.gz
│   ├── bbea0ec8c734c5af47d656243fc350088048e160.nq.gz
│   ├── c42d537a53453940b593aa7183f3367160a97f47.nq.gz
│   ├── c9ea82c4765b032ebb70438b52bfb5353e65c25a.nq.gz
│   ├── d336b1e658b90b403c2845f2ec0c3a9266942409.nq.gz
│   ├── e22698baf7ce3f3290d2a6744ff21e4699a8e8ba.nq.gz
│   ├── e28ae31ecf1ecb2a1ca4b4bd13f15b72b4cc8af6.nq.gz
│   ├── e6e9d9e1ffe83a925435a2a62cc2764c3a38d495.nq.gz
│   ├── e8d3b47aa8f43a323cf60c4249a636b21703276b.nq.gz
│   ├── f0d5544588a33680e6cb041470db56e86165ebb9.nq.gz
│   ├── f3a28878f2f511cc31528da98e2a8724c5a32fbb.nq.gz
│   ├── f57a051b08930bac4281b5fd6bb4583c4a12e763.nq.gz
│   ├── f84b01f36dc487225c9382e7fb854bb944a55755.nq.gz
│   └── f92db703e7f92cb48258202be9fc3cf66bfc2d7c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 938524c6162aeee147cf0bf5ab1b6b929e2cc21d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[Pylons/webtest](https://github.com/Pylons/webtest)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
