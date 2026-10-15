# Repolex Knowledge Graph of twisted/vertex

RDF knowledge graph data for [twisted/vertex](https://github.com/twisted/vertex), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/vertex
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── feb591aa1b9a3b2b8fdcf53e4962dad2a0bc38ca
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── feb591aa1b9a3b2b8fdcf53e4962dad2a0bc38ca
│           └── chunk-001.nq.gz
├── blob
│   ├── 040a91e489582bbdd69c217da3c9aaf0d3b81904.nq.gz
│   ├── 0525021e4d9d4da17255b1cd05e592bf1f0297ea.nq.gz
│   ├── 10631710928cc4f80bda749df47937aa0c852a77.nq.gz
│   ├── 170104687dd95bf0d2cbae1e8758fc23f5e2ec29.nq.gz
│   ├── 1c7000d4474d8b1bc029f68354bb8825382722c9.nq.gz
│   ├── 1d823451acf4f39ba5fb783c25fd128dec76f1a4.nq.gz
│   ├── 20def1ec955f93f02bb963e29605ad0b41038f48.nq.gz
│   ├── 212a3ba41c6151eece703c37e9f55013c731836f.nq.gz
│   ├── 243ea1f97046c8f76d100ac1740cfd1c72db89e4.nq.gz
│   ├── 260c070a890dcf7c1bff15a9d7d64570ad806e74.nq.gz
│   ├── 280986f07018d9ee8bc515134efd968dc34039d9.nq.gz
│   ├── 2f67e0f856935bd541b318704f85818cfb752307.nq.gz
│   ├── 306255517980254a6db3b48c558d8eb120a5c1f6.nq.gz
│   ├── 387d6b9c039883a56443c9b3878074f1e15120e4.nq.gz
│   ├── 3a82837287b5264b975b27f8c17bb69796b82c2e.nq.gz
│   ├── 3ac2f04ea03541de694eff97bd0ec98f4d874c99.nq.gz
│   ├── 3e5cb9af61c21639caf2af92ae4472cf6468c049.nq.gz
│   ├── 42b1c58c16e1501e7dcdc0253949d5a439f88cf6.nq.gz
│   ├── 4d928444480f338909c5646a5b236e3f632115ee.nq.gz
│   ├── 5165bf4ba0208ce2a3140cd1ce928650ac69c8ba.nq.gz
│   ├── 567a11ab11a2423f76de4cabd3c22c9297627578.nq.gz
│   ├── 61e093d44b3d91e0a3ca35761a71bd7ed537cae2.nq.gz
│   ├── 633ddb44ee730e44290e5a23c16b175864adda4b.nq.gz
│   ├── 669936348c6249b6354935499f7d1eb8b34ecdd4.nq.gz
│   ├── 69576a1e2453827b6b3496444111d95d09ffc045.nq.gz
│   ├── 6c014e35d4d1ffe30459786824f2139fe28a3b20.nq.gz
│   ├── 6c4fa73c11843f4bf26a726aeee3fc685c8dbf10.nq.gz
│   ├── 75aab93e4f794f98cb727be532ff4ad59d4f9f7c.nq.gz
│   ├── 766f0f97b475edb41c8974b74ffa9ce6641cc0cb.nq.gz
│   ├── 7b02ddb9a58e9b143be221c6dabc04fedfb83da9.nq.gz
│   ├── 7c920f29f98c6ab52ca077a09e65d493d6bf65a3.nq.gz
│   ├── 8611c4c9b754c07f15c615138b61943c0062690f.nq.gz
│   ├── 8632a5f3ffdfab50c3d8fac31a69f8acfd20ac40.nq.gz
│   ├── 8ba5db3f50b6fcb4bb1b5d7c89960b976b01764f.nq.gz
│   ├── 93c00f8f3f6d44530ef86f444c566b78240096f8.nq.gz
│   ├── 9c5099c1e0a50fea1cbf201bc67fbfe1ad068991.nq.gz
│   ├── 9d1c3b0199bb553cc1bed15f441fb064a25f4e3a.nq.gz
│   ├── 9d9cb32f46cd7d5e0fb3958235fcfa4ec70f13fd.nq.gz
│   ├── a0a6796135ee932b4845c08c26a1debf34586cba.nq.gz
│   ├── a1e869bfa71697df28690c0345f654b2c7e5f005.nq.gz
│   ├── a51d77afe3cfe0d5abd690f639e6e2a5639aae77.nq.gz
│   ├── ae06c471182d0b57501624e460f69bd92be3c224.nq.gz
│   ├── b5e5fb26af27d6eb6abed3f691ddd36126077e75.nq.gz
│   ├── bf7958ba783d1eda8a767748fc0ef7b7d9b9076c.nq.gz
│   ├── c6a372a8c4e99cb1115b75395dc731b2362d147b.nq.gz
│   ├── c7b672afb18e3bced685f70845779a5677496fa6.nq.gz
│   ├── cb6ae632691deca020971cdcd0bd8c77cb9e1eca.nq.gz
│   ├── cdbe0d75dd24e08b5126097df9a6f999a22a08a8.nq.gz
│   ├── cddfad80ba6166a73e3d77f1fb74688c5d8a2a3f.nq.gz
│   ├── ce2df963ded2dc7d7f573d8e2c6e1f55f009fb6b.nq.gz
│   ├── d4ac9c409c2162774b0650aa4b5a2b46555cede7.nq.gz
│   ├── dc458fcf9e8dbff2c3e8483dbed37a81477bc609.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7a7c7d4565eda078a34301a55463a4f33ae5884.nq.gz
│   ├── ebfdfdcc3d167805777ef490d000a78984fb083a.nq.gz
│   ├── fb404d27b123951007f97d6fc79ec8895877d467.nq.gz
│   ├── fd207aa54fc470659c1a725995b3fb89b9f0952c.nq.gz
│   └── ffbef3c311d7a6527806810dcced42f773bc68ba.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── feb591aa1b9a3b2b8fdcf53e4962dad2a0bc38ca.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 66 files
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

[twisted/vertex](https://github.com/twisted/vertex)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
