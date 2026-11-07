# Repolex Knowledge Graph of scrapinghub/scrapyrt

RDF knowledge graph data for [scrapinghub/scrapyrt](https://github.com/scrapinghub/scrapyrt), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/scrapyrt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 066cdafb9dc5e864f3e1dd19cb7fafec7fefb7fe
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 066cdafb9dc5e864f3e1dd19cb7fafec7fefb7fe
│           └── chunk-001.nq.gz
├── blob
│   ├── 026bc28ff39a7986a9ed013be64c27f9e691aa96.nq.gz
│   ├── 068e89e462c56fd5d1ddd5af2e53d15f97818cd6.nq.gz
│   ├── 08d4372addbc20bbca4ff8cc730c5cf7a30f79a0.nq.gz
│   ├── 09af94445cc4642fa7d655df5e444fdb72533cd0.nq.gz
│   ├── 0b39d2d9046d40475fba4fe9369f4399ecc6c96d.nq.gz
│   ├── 0f1727880d638dc9b9dfc79969235a77a92ddf26.nq.gz
│   ├── 119b328bd0296c5ef030edf16a562ac6d1fc4bc9.nq.gz
│   ├── 1d93483af6eafd9198c5e6a9b87dd1f79db36b8e.nq.gz
│   ├── 2ad88c1e346b65e896960fce38c7a0a241756a27.nq.gz
│   ├── 2f41102db58055982ab476dbf0c47f0063dbb6cb.nq.gz
│   ├── 367ab2943d98fc7179000521e2b02fb5e4e561bf.nq.gz
│   ├── 46a61de865770bd7860ce5389e2008e2928ee088.nq.gz
│   ├── 4ef72fe723e13729fd8b31692872b8dc41604973.nq.gz
│   ├── 4f2c3260ede4613883c57d089998ed339e7e37ea.nq.gz
│   ├── 57457a257a1c29bdd4cf1947d062f13fc5e8a219.nq.gz
│   ├── 5894c56650795d76fbb16d3d37f0159050703eba.nq.gz
│   ├── 600e9142737e413d7f6bfb044ce8c9bf8186d42f.nq.gz
│   ├── 615cc9e0f81751ce0fe6d010088d7b0df81d36b1.nq.gz
│   ├── 6169b61a95c004128321861052bd687acaf85134.nq.gz
│   ├── 682de8006d914afaf7fd7be06cda5535d712135d.nq.gz
│   ├── 75a92173ac70468bd7d3e86818dfa9f88791d087.nq.gz
│   ├── 7a5f3105092f9e07a3f42dce7b31c2806a2b749b.nq.gz
│   ├── 7b5eb1c86e6cb49777cfef780b57af9cfb5b5ad7.nq.gz
│   ├── 7cd2c8b02f774b8491f47b004b944efd51abf8c9.nq.gz
│   ├── 8129f6c1febe538bc2ca7a87ca768b3d08ce290a.nq.gz
│   ├── 84b93a9598ab36b6ba9f6fd8ae844d5fbb40aa66.nq.gz
│   ├── 8b95974bd7907ee7667c005441c4db0ef20f6baf.nq.gz
│   ├── 8bbfad6d642668323488e431dafc5a762e87ca19.nq.gz
│   ├── 8ddcef6d8af6871845c89d010b21479f46e4567e.nq.gz
│   ├── 95e5036ec170f8fe4e11b3ac0c3ef5eb5397f8e9.nq.gz
│   ├── 97e7d1867e0f5f8b2f10c50cb79ed49e081f0e4d.nq.gz
│   ├── 9f1c878ffec8915dddcc89fba26f6717530de019.nq.gz
│   ├── a102b2f709667ecdeade6d9d938c6fd3f838185b.nq.gz
│   ├── a16c66b315d4b65b52e6a07eee7f0e12138ff581.nq.gz
│   ├── a64bd4c2063380a9445e1519b424444b427f49e9.nq.gz
│   ├── a73f7aaa96f6418c3dc19e990620d316f0148d2e.nq.gz
│   ├── aa0480d755b44dd149b1246d349aba29b8038db0.nq.gz
│   ├── acbb95fd89211f904f584a3cf577904b920246a1.nq.gz
│   ├── b6f9f357002681fd35c5a076e3df1ddf58de10b9.nq.gz
│   ├── bb312238cd67b271b805485584ec1feb62d4c010.nq.gz
│   ├── c22a74939a4fe41459b47ea35736d89228dca5b9.nq.gz
│   ├── c7fa3b5bf3a43ae4919bbca150883d98d1b7202d.nq.gz
│   ├── d4daa0c78ead8ce9e30b31e42a6195aad22a068c.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── da08f042c3f94b6618974679cb6b41371cf7d9b7.nq.gz
│   ├── de07c62b633e34cc7bbb736012efb332c61c0bb5.nq.gz
│   ├── de1584a03125134bf12ed359d40917471b053ae7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb891260ebd7ac9f1e1500d84f80f69f6c0cea4e.nq.gz
│   ├── ebd689ac51d69c5e1dbbe80083c2b20a39f8bb79.nq.gz
│   ├── eccbb17cf75349b2047cfb2f9278082c480ce82b.nq.gz
│   ├── f0914c61d7ae226f27c9a3a80b1e1810be9d33a2.nq.gz
│   ├── f2e7363492e47946aa5fd47892f0047711230744.nq.gz
│   ├── f50e1a23520ca3e3c5ed737ba409b13fe32581e4.nq.gz
│   ├── f5e4f26b90c439f647fb5e612107602858ebdf52.nq.gz
│   ├── f6ca84e20211bad822da86432935dfc08b8cd5fe.nq.gz
│   ├── f8142f6d3844675aefe9fa0990b6506ffafd36f0.nq.gz
│   └── ff15a4c5cd79e4e3cee3285535fe59c2c826d4ec.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 066cdafb9dc5e864f3e1dd19cb7fafec7fefb7fe.nq.gz
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

[scrapinghub/scrapyrt](https://github.com/scrapinghub/scrapyrt)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
