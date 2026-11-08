# Repolex Knowledge Graph of qdrant/migration

RDF knowledge graph data for [qdrant/migration](https://github.com/qdrant/migration), parsed by [repolex](https://repolex.ai).

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
rlex download qdrant/migration
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9256b2277f71345a947104be9ad25173dbb390cd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9256b2277f71345a947104be9ad25173dbb390cd
│           └── chunk-001.nq.gz
├── blob
│   ├── 03b7eda2c0bfc7ccaf9a5dacfe602e55294e0091.nq.gz
│   ├── 0451a1b4279b344bf07941e2a675d9ef7af0acdd.nq.gz
│   ├── 06faa6fe339f56da77ae1340a5327418d7764817.nq.gz
│   ├── 0e45fcdb5204db9417b1c82e844e391b3374edae.nq.gz
│   ├── 13ee8f88e8e322b60bb12fd3837a2f080294575f.nq.gz
│   ├── 1734bc07fb84a32abdcbe759411d8c1a2e341a00.nq.gz
│   ├── 1a1d87161a417bf074ef3460c6fda5f4f04cefd4.nq.gz
│   ├── 1e95cf1f250032a53b3cc27e30ec2ce6f8988765.nq.gz
│   ├── 249e5a5199f527dd5a32dd38d410f436799818f6.nq.gz
│   ├── 26000c18c79d9d16313774ed800b74095df7a2bc.nq.gz
│   ├── 26b14c9f3785d727b747fa54d20bee3a540ec52c.nq.gz
│   ├── 291f9178a36970d30f72e0637c877ece4689063c.nq.gz
│   ├── 2a5bae1a6282d1d6c0640daaed706a86ca325b28.nq.gz
│   ├── 2a6e1c0df8cb3412b8b98022f10655e7a2ff71b4.nq.gz
│   ├── 3847ea4df4f8a487eed401c876d6aa7be60ea44a.nq.gz
│   ├── 3afcc430486dd4019982740e6acc1ef08d9d39f7.nq.gz
│   ├── 3b6a1da56219c5fc46fe50a9696dfa7d3efe6002.nq.gz
│   ├── 3dcdd3a9598400248ab0551dc6a8bd182e793cd9.nq.gz
│   ├── 434bd3d959c87fddadee2bba90617f233f633f87.nq.gz
│   ├── 4a46b22d2c99faa7502f034d3131bc6c85e2b693.nq.gz
│   ├── 4a5ef21e298a451e3a8790dca3123d384a1650a7.nq.gz
│   ├── 4b09e5766d3755167a512d089cac87e54294da2e.nq.gz
│   ├── 4c85825691938fbe984e5a38d0fa9c8e91b0fb5b.nq.gz
│   ├── 585f26f8be07e99925c1213b9c320a26372b04c8.nq.gz
│   ├── 59c82ea52bc524d2da255018d9ea0d5190d31826.nq.gz
│   ├── 61dd5da0ad14f0b92998c2a3e769154d30263817.nq.gz
│   ├── 65bfd433aa8b2884e640ef0b60e9f2e85d5be84c.nq.gz
│   ├── 6657aa731e9c3ea11bfcd42386a55a9072a4e63a.nq.gz
│   ├── 6b6a9a85f199ae72992de08980f2a8c8b965d157.nq.gz
│   ├── 6dfc1bfc1f707b54966c7e5220bce06197d855f8.nq.gz
│   ├── 6fccf8e5bc3745680787a1cad4d50c4c73c73cc0.nq.gz
│   ├── 777936cb279e6d01b7b91e96cd441612ac977087.nq.gz
│   ├── 797e2798aa97f6a8d6d47906c358d358f2084dd1.nq.gz
│   ├── 79d8ef33bcb9f57af512be7a605a528e766660d2.nq.gz
│   ├── 7b1d7d44a4528e98090a542dde6677d32f086d17.nq.gz
│   ├── 8088fc6ebca027b2e6c462f0361d55cfe3017caf.nq.gz
│   ├── 85bca2eb624660059775aa04c354cd9504ef73fa.nq.gz
│   ├── 8677a8a73627a6309f542fe6f559667d72e82677.nq.gz
│   ├── 8b822f6b08378cbdc1f19a8e0ef1b9f12359ca82.nq.gz
│   ├── 8be4938bfc044124cf5161e9178a48e43bffdf29.nq.gz
│   ├── 8c9e6c1ca1be00d2b45d22041a700c773944cc80.nq.gz
│   ├── 8cf508cf04465e60aad4971ab4be2e71b7a9a9fa.nq.gz
│   ├── 8f314db69864aab46ca24f366be7d4bed280fc07.nq.gz
│   ├── 90f10fe1aa912bf9c551c4035b4eb3b123c46f62.nq.gz
│   ├── 949431788b462a81efcb850f9d1e87c4ea377c92.nq.gz
│   ├── 98b511ee1250ba34f1296935105ac454b0020336.nq.gz
│   ├── 9c2ddeeeb9fa6f96a4523ddfef62d52b9d1c63cf.nq.gz
│   ├── a202d8b6a00e70239e650142d61d24def58e4838.nq.gz
│   ├── a6ab88791425151a1432e115c1b4d8a323b05e9d.nq.gz
│   ├── aeaba359f70a7b3ee207f9341c5a9f1ee47af3b9.nq.gz
│   ├── af9cd609e0b6e542bfbb40c8c016843e83741d50.nq.gz
│   ├── b2519a2e81cda8bfdfbb9297967f3e665683a03d.nq.gz
│   ├── b2618a46e7b39ca029edc758e1a1d62345ddc6d7.nq.gz
│   ├── b5b5897ca0e360889405fe5614d82e84c7297e3f.nq.gz
│   ├── b9315f18c0e0939ad87d01783df3ca3a37ca5040.nq.gz
│   ├── bb41afbce27eea9abbc2ceff97ac2d7444ca7d22.nq.gz
│   ├── bc96e50f0628d338fbad2b3c2ea1a9b1da848006.nq.gz
│   ├── c087d7ab51c9d54beb4142e00bcc818cc83afc0c.nq.gz
│   ├── c1bb87de9a431c58df5fbca5599bf42be5008072.nq.gz
│   ├── c44ea2cb4896275356dd15514b0d7551a1a878ef.nq.gz
│   ├── cace0ebc77f39e2543450ab37b960f25ce2e25cd.nq.gz
│   ├── cfde14011419a0366b12c6697eb4fa50e336a1ab.nq.gz
│   ├── d0ea5859bfd1380c93d02b5e6be43175a5903981.nq.gz
│   ├── d27f9493a6b9197848905a6badf9ebb1318131d3.nq.gz
│   ├── d2b446972ea84e78340c595a945d644b2d831eca.nq.gz
│   ├── dc2de5a451246dcd2d74529088d113787533f65a.nq.gz
│   ├── dd61338f2e986d6f7bf410e08176d1b1f9ba2d72.nq.gz
│   ├── df27b4d9f85361dbff0d7b5e8e379d86c06d1de2.nq.gz
│   ├── e6926605004be6eb1bc09a7cc056cd211492bb67.nq.gz
│   ├── e72d58cf783b1209c0bd0a87f83b25f135fb2726.nq.gz
│   ├── f9b81452889ef5c084e89292ebe6895f07c64b13.nq.gz
│   ├── fcf6f6883cf934df17204a1b4c45696359dfa7b1.nq.gz
│   └── fe9fb57f0336bdbbc8f8d3fd8c7c7d317a72a976.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9256b2277f71345a947104be9ad25173dbb390cd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 81 files
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

[qdrant/migration](https://github.com/qdrant/migration)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
