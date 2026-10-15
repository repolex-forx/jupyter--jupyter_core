# Repolex Knowledge Graph of jupyter/jupyter_core

RDF knowledge graph data for [jupyter/jupyter_core](https://github.com/jupyter/jupyter_core), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter/jupyter_core
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4c4f526adab04ae6bf7821f65a5adbd011aa27ac
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4c4f526adab04ae6bf7821f65a5adbd011aa27ac
│           └── chunk-001.nq.gz
├── blob
│   ├── 05aa9ae20d419005d6b9283b4363344878f49625.nq.gz
│   ├── 0bff3baaa3358df987836c0bf5e91773084cd3fb.nq.gz
│   ├── 0f46386d91d04f1d28abe4ecfeb409c3c7183e28.nq.gz
│   ├── 0fe4d750e00c9d145d6ce7ee60daad46c2069cdd.nq.gz
│   ├── 15ea12d94c3d3712afc13e3f64db2b9823d98bd4.nq.gz
│   ├── 167925d433216da6b571b09083d15e7af3a85712.nq.gz
│   ├── 1becf2e92a19a6aa4b7edd4604fffe298bc3aedc.nq.gz
│   ├── 27370e396b6ecebe399cf1283c4b6d90bf41dc3d.nq.gz
│   ├── 27459871deebc03ca9d5cc1b50a63697fcde6fce.nq.gz
│   ├── 2d074e9c9ece8661c8d2064a0629538cb61eb0bd.nq.gz
│   ├── 32993401b461639c90980ae9f276977b0c80577d.nq.gz
│   ├── 39192bf30c3252ec007cc4794b57113877b67743.nq.gz
│   ├── 396330bb9729d2ec595617aef79fb28600d86bd7.nq.gz
│   ├── 3db6604a425a669db88784c2d03d0bbd92733835.nq.gz
│   ├── 46fb9bf2f5f25fd5aa25346d558d943fe431918d.nq.gz
│   ├── 4b74781b1f19b45f90f9b1e947f5b9a31f67e4ed.nq.gz
│   ├── 4c04297c6eb760584fb879006879e70c4ac04a73.nq.gz
│   ├── 5e43214046a5dd01eb6bc92e81e0cbd2486d0fbc.nq.gz
│   ├── 5e868478132262172efd0e8c4caadf826ec0834f.nq.gz
│   ├── 5f104320122476e375331592d4618efbd8fdff09.nq.gz
│   ├── 5fffd9148a7f6f48314ad6b6a05c1106d856ff5a.nq.gz
│   ├── 67180b40ec77944e0d7d6691b2cd0b63979d5f97.nq.gz
│   ├── 6775c08d75be1faa536c722a42c335b4b823d9fd.nq.gz
│   ├── 6dcaa1311004dc172defa1e32d02dd836f8e7641.nq.gz
│   ├── 725feab5ce652dc39f3f2c77b9fd3c90bf049c65.nq.gz
│   ├── 73c4e1bc1f3b9169d13a0df4d8f43ec8d2c5e4e8.nq.gz
│   ├── 778675b70d9bfe3d8c92f56d3cc9c0dd939bb732.nq.gz
│   ├── 7d0ad2f89aadea8b2c984c648f4e11f638807db4.nq.gz
│   ├── 7f7c4881214ee53749a088c1a2615423f40e96fa.nq.gz
│   ├── 87945fb83947b896b61630f5f67a5ac47a05543a.nq.gz
│   ├── 9292666ffb30ead93e12e5aaf252da605df18528.nq.gz
│   ├── 9551778d615c01ff05b737efc9c90676a2193473.nq.gz
│   ├── 9a38574c8e3ea400d239d81751dc85798e725720.nq.gz
│   ├── 9afe31d6078623b6d6a0eba64b06aad773c2dee9.nq.gz
│   ├── a44e199a8af58e5922f8ebb696218312c317dedc.nq.gz
│   ├── ab0f3543736178a9e0ed03c296b338a0b6bf3ea4.nq.gz
│   ├── adb22cb1a3be386c0828fa5caaff05eddf1fce56.nq.gz
│   ├── af5374d6cad06aceb2deedde057dd5f58b65b2bc.nq.gz
│   ├── b6a3876462981b2c17114a28b5f35ed3f0cdce1a.nq.gz
│   ├── b775e5529fbd61f854dc5712c5e419e40f1931bb.nq.gz
│   ├── bbfeb7869dbee70ac438bbdd414109d6c865206f.nq.gz
│   ├── c576a54877c836891c83f5d6d0e1e817581d22c6.nq.gz
│   ├── cc2bf05c7185b1e3a576c403b2550d45602048db.nq.gz
│   ├── d16837e12413034fbfa4dc9bb066e786aec1c6ca.nq.gz
│   ├── d921b49589ffaa2481e6c068548cd6faee761304.nq.gz
│   ├── db376da4ad9c5e36ff9d773a6a301f6c0d022576.nq.gz
│   ├── dc22f365ba89a9a5598f990016f44b027bf34e35.nq.gz
│   ├── deb395da43c31ec78e2b2c28e0b3789840a63d39.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7659263d00c96dc5c3545aeeb79f361b2e6e3ec.nq.gz
│   ├── e7addad0771ca29a3469722cdd7b74bf0bd3116d.nq.gz
│   ├── ea20c856473bceb1220bc6c1f70073614ed5551d.nq.gz
│   ├── f144b94abd9d17f470d435d79060dc046070308d.nq.gz
│   ├── f3f9dee833f7a8015fe627bee67a54f026fd2e1c.nq.gz
│   ├── f6743a9bf2cdf500e843de3e1f6b3077d172161f.nq.gz
│   ├── f7e8d6d0d87fd908f42f4c79380146a25451d576.nq.gz
│   └── fcdd3e88b66ec9b10362685146ef2a36088e54f3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4c4f526adab04ae6bf7821f65a5adbd011aa27ac.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 65 files
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

[jupyter/jupyter_core](https://github.com/jupyter/jupyter_core)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
