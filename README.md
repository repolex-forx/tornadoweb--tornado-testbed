# Repolex Knowledge Graph of tornadoweb/tornado-testbed

RDF knowledge graph data for [tornadoweb/tornado-testbed](https://github.com/tornadoweb/tornado-testbed), parsed by [repolex](https://repolex.ai).

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
rlex download tornadoweb/tornado-testbed
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ba2cc54671dbd03d1229d19903ea8a1bb0ab2e26
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ba2cc54671dbd03d1229d19903ea8a1bb0ab2e26
│           └── chunk-001.nq.gz
├── blob
│   ├── 0341151ef378a07aacdaed51fab56fadba0dee7d.nq.gz
│   ├── 06247246118a2e71b001e89a43968b934fc6e7fd.nq.gz
│   ├── 0643572615fe25421f4ad2c4c814a817c6c07406.nq.gz
│   ├── 0ae618c35af1e7534382af6696f279220772539c.nq.gz
│   ├── 0c9b0da819e7170aab810225f944860adf6de871.nq.gz
│   ├── 0d2bd48cdb8ab2b6ade60baece0e2f4752a1e47f.nq.gz
│   ├── 113f1910409a4a4006636fa43cfea7d26fed7de9.nq.gz
│   ├── 12f7b4a291e8a4fe06f2401e2940712b64567a2c.nq.gz
│   ├── 187937ae453b95397dc8b02c5eceb6b1e54ce845.nq.gz
│   ├── 1ae734e63e384a5ed0a8e05a03a9e1045878d508.nq.gz
│   ├── 1f044b917fd2f4bf66f5ea6fd920187704c676e7.nq.gz
│   ├── 228d4f17de41396d8baa7b91e36294ac51d6ddd5.nq.gz
│   ├── 29a907d9edd0165d1be55d48526d50609ad0bffc.nq.gz
│   ├── 2a3925ad4b628685faaaca467068c7a5e1cc4b0e.nq.gz
│   ├── 2e11d982dd9c52018104ec49436771c0c8ff38cf.nq.gz
│   ├── 356e46c279fdf74cec7671dac56f66943d482e2c.nq.gz
│   ├── 35fb4a7fa723b9aa73a4782aeba46dd0c9eb465b.nq.gz
│   ├── 379a8f86e97379d76889fe5ca8b9b4e752faf59f.nq.gz
│   ├── 3886932832341a399b4e152d7c28e2b5b9d7623b.nq.gz
│   ├── 3b118f979a8e5c9509629d8614d8d9832f3cb9d3.nq.gz
│   ├── 3b616f13b843562840928f73b92ec238eaca0aee.nq.gz
│   ├── 4161e1aabb58d5aa21e93b11c2af04d47a947fdf.nq.gz
│   ├── 4246c7bd5c9c87ffd18ff3cb6e986425b8f62108.nq.gz
│   ├── 45bfe17b4e265b20d53680388d12be9e135b6e7c.nq.gz
│   ├── 496f4ce0582b2956df5b4c1fe19ff78ff0e5fb38.nq.gz
│   ├── 5655d71dfd6f05c84953ed586ddac79a3bec6301.nq.gz
│   ├── 56b4122f718bd7da4dbd5010e73b4e4186e41329.nq.gz
│   ├── 56bb24f36195080145db3c53c4b561a16dd2f574.nq.gz
│   ├── 56d987f3c6050101283e224dd323b5f6e1ff4af1.nq.gz
│   ├── 5890ed22db463e47f674adaaaa119d313e8e8ff0.nq.gz
│   ├── 59deed1ac86330f8d268cb96e2152d2c3614c356.nq.gz
│   ├── 59fb42a25c1949ca90c9d8198db3e2c404d0a657.nq.gz
│   ├── 615d41c1d329a3394b38f2e0ca4d6e0efab9f5a2.nq.gz
│   ├── 6512988f98720a229ad80aec2f11e3b530bde6be.nq.gz
│   ├── 765bcdb554b9cc46ab9747c46574438f90f46265.nq.gz
│   ├── 7b1aa4de9b0dfeac5fde0e6ea98c895a8fc1867b.nq.gz
│   ├── 7c1e7dc0f70f10581cb39b1e13a2a06b834da240.nq.gz
│   ├── 897d943e152e60047c88d4c3edcddf881d514bbd.nq.gz
│   ├── 8df22aa9069d20b05019c152f9e0a21605839a14.nq.gz
│   ├── 905c333d7571acd7ec2ebe2ff8a2d3946b143fdc.nq.gz
│   ├── 9aa0d96cc8e7916d572fb707a627e2b638f778dd.nq.gz
│   ├── 9d2c792ec20bc8124dbfe5431f6fede6bf9ec8c0.nq.gz
│   ├── 9db83369511ab75d38676d3d7890a8cf7620971e.nq.gz
│   ├── 9f024de8dd9d46417291a643f04d37c10a7e92c0.nq.gz
│   ├── 9f323081654c0a2fc653e9c40a6bedb5fe7940c1.nq.gz
│   ├── a06e6ad8f34c411a3b0ea0235e0c19c373042471.nq.gz
│   ├── a0c323e03365d30a11b9003f1f73845c72d35ab0.nq.gz
│   ├── a0f5d0c0b1c4ec53c7ac9dac36f1e48d0fcf3489.nq.gz
│   ├── a82aeaa0354da403165a313818ff1fb8d7ad96e9.nq.gz
│   ├── a8fc8cd7b8a69115c0dd116a02e8003e954f3edb.nq.gz
│   ├── aa806d7ae66e03c9af41c218f10e0df5de1ce497.nq.gz
│   ├── ae18698bf5181517f8f3e67346bb0efb435ae2d8.nq.gz
│   ├── b30c0b3a6bac000886de3fb977a3cd1a6b0b2931.nq.gz
│   ├── b4cc496b9c49b540b1054455eff954535682d98b.nq.gz
│   ├── b9244f13adf5f2564e52fbf3357fd2fb2d9ae0d1.nq.gz
│   ├── ba84bee0f20e8601c817fa65bc44af5a1ad8b326.nq.gz
│   ├── bc5ad626ed992303414bf85d03bcc55dd4b9299c.nq.gz
│   ├── be0b6632b45c1c5cf78490cb92ed97b2ba289570.nq.gz
│   ├── c89debd144ebb31bbf744420ae3ec8f41bab746d.nq.gz
│   ├── ca2f49f39f14ffbdc5d143bcb009d82e8cbcee08.nq.gz
│   ├── cdd76a3cb78c365a66df6160529ce68975f79bed.nq.gz
│   ├── ce68e858dcb69d687df6a924e6fa9e61283b99b3.nq.gz
│   ├── d1762a4ff69eb8cb912adbe4bf32e0425915a957.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── db2c7fa7e80cfb0eb881ce2cb9d1880ce5b95972.nq.gz
│   ├── dd86b8908df28478047129bfbc3ed473b25815e6.nq.gz
│   ├── de9a66b425f2358463cfd7d0b4a16f5d2e61a0ae.nq.gz
│   ├── deff5c534a7574d539ff5149dfafdb9b58967be5.nq.gz
│   ├── df4d753b589c5ec4e316e9200dfb2712d1bc0ff7.nq.gz
│   ├── e255c5706489e8037fbcee2e4e074cd0e4b68b6b.nq.gz
│   ├── e530a0127647d1a708e975d42419e1d2ac39b63d.nq.gz
│   ├── e567a1ac5ef3963df0fdacb4743a918e561cf0f2.nq.gz
│   ├── e5dd3ff85939eb3b25f14743085cca47c6b64c82.nq.gz
│   ├── f7f17df522d94bb7345f085124a7375cde960fc6.nq.gz
│   ├── f928bcf9c6cc58bcc9984df968550c7223eba889.nq.gz
│   ├── fa13f548d005756ececc3d4e470c52dbd3a71ce4.nq.gz
│   ├── fb9d6fd824aef6153eb4702394017ca5ca881473.nq.gz
│   └── ff167e576a43218c1aec34873fd7185f94747598.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ba2cc54671dbd03d1229d19903ea8a1bb0ab2e26.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 85 files
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

[tornadoweb/tornado-testbed](https://github.com/tornadoweb/tornado-testbed)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
