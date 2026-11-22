# Repolex Knowledge Graph of alexcrichton/curl-rust

RDF knowledge graph data for [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust), parsed by [repolex](https://repolex.ai).

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
rlex download alexcrichton/curl-rust
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bae5dc561e0711b4982eeddda8b5dbac45d531f1
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── bae5dc561e0711b4982eeddda8b5dbac45d531f1.nq.gz
│   └── repolex
│       └── bae5dc561e0711b4982eeddda8b5dbac45d531f1
│           └── chunk-001.nq.gz
├── blob
│   ├── 00fcdcc16f092a98ae8a0e4b77a5efa6bfadcdd7.nq.gz
│   ├── 0872a4e97c8c27bc17bf7aa3e0620f036ca3b359.nq.gz
│   ├── 0b0e23a7ef8c1091536fc71bc914e1bc5574b828.nq.gz
│   ├── 103b0cf5d652a4c3f1ea7f77032e1eff46f9cf43.nq.gz
│   ├── 10bcce350665b0f34c7971b159d31640fb08e6ba.nq.gz
│   ├── 1884d6880c2801d9f99be2b4f5069c4f6747c393.nq.gz
│   ├── 1a2661a70f035b33eba5161847e89ae7f43bf389.nq.gz
│   ├── 1dc2e4f80128838e7bb093fe48c38f1f2f2a15a0.nq.gz
│   ├── 1dda47c5a0381591295c7808b85071cd46029d9d.nq.gz
│   ├── 2965e2bedca611c3e532715819e515fea4a68e03.nq.gz
│   ├── 29c6d53af30298e5213670886f83afc0fd50a59b.nq.gz
│   ├── 2c34c4817cf112eece5daa8b9a2270090e53933c.nq.gz
│   ├── 3e2db5cddaec80d051f1bb3394a2161cf7156c7b.nq.gz
│   ├── 42cffd8f062db23fc04819004546b36e34dbfe45.nq.gz
│   ├── 4338604aefae0179e2de5d9dc6c4456bd5d9fc3c.nq.gz
│   ├── 5a686108293f7563a0db164511e8f047bf9d58ed.nq.gz
│   ├── 5ae0ed8e7893accf592f241ea18792d04b73c141.nq.gz
│   ├── 5ed6338909da0b717fbedc822e5b2ba86cd667bc.nq.gz
│   ├── 5f5e4b09d57a091efc7b6430fb296b0adef6de12.nq.gz
│   ├── 625735936e4825511625ac62ffd9c618247161eb.nq.gz
│   ├── 62711d68a275f56ae3d401d283507e8e6c65b036.nq.gz
│   ├── 680d47194974195c0d5adf4eaaa04f0ee9e355f2.nq.gz
│   ├── 6a1adba0df487660d6336501576081091506e0c8.nq.gz
│   ├── 6debe8979fc3b0125160d39a34c17232e400ecee.nq.gz
│   ├── 7215fe9728f3a9f45352528007e3cc5654d536db.nq.gz
│   ├── 77ebe385cc19b256966e0caae943f42f6f1a4cd4.nq.gz
│   ├── 87eb2f9c0d62c3fc5f60c2f458303f380c087b80.nq.gz
│   ├── 88e39ae353f7293edb6e35907a71bcd261d8cde7.nq.gz
│   ├── 8ead80e2de66c4eaf83444c7c7083064576225fe.nq.gz
│   ├── 934c69516389b93c736e96260f2cb4609af9b6e1.nq.gz
│   ├── 9cc9037cd48ad6d217a6b1b1c32976127b17ff92.nq.gz
│   ├── a138f75df6f42f444704d14c522cacf547f6a60f.nq.gz
│   ├── a1899cee172cb64b1787e51712aadf2bb42d10d6.nq.gz
│   ├── a50e4f9dcaf13077a3963914e8b4d8ca60fcc408.nq.gz
│   ├── aa779a1661d19af6ee1f5dae5162a8bbc7b16a52.nq.gz
│   ├── ac671d8d2236d051f77be5c29b06ab1e3084d50f.nq.gz
│   ├── b56d44651fb75613d8f504458a3943cb99b37de0.nq.gz
│   ├── c94d2e1c638645ef3e593eaf7f82e680b17411d3.nq.gz
│   ├── cb841b65c8b0b67e1669fc628da5e3e2cb429eeb.nq.gz
│   ├── ce013625030ba8dba906f756967f9e9ca394464a.nq.gz
│   ├── d461ed8a590609203ef01ba4f653104d015ba572.nq.gz
│   ├── d770c9a127314e21a0d37b3debaf11b6d8d87070.nq.gz
│   ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
│   ├── ead762725067a39a1c69b2cb41aaac33deea0c46.nq.gz
│   ├── f6d4457d4d2f87f38e07822b1b6b6ce532c5c5cf.nq.gz
│   ├── fb13c86ff69f1e2f7e85e8e361b4538570de1a7b.nq.gz
│   └── fba1ad48d4a663b5ee08cb07e0d18a8611f73ac4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── bae5dc561e0711b4982eeddda8b5dbac45d531f1.nq.gz
├── filetree
│   └── bae5dc561e0711b4982eeddda8b5dbac45d531f1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 57 files
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

[alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
