# Repolex Knowledge Graph of klen/graphite-beacon

RDF knowledge graph data for [klen/graphite-beacon](https://github.com/klen/graphite-beacon), parsed by [repolex](https://repolex.ai).

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
rlex download klen/graphite-beacon
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c1f071e9f557693bc90f6acbc314994985dc3b77
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c1f071e9f557693bc90f6acbc314994985dc3b77
│           └── chunk-001.nq.gz
├── blob
│   ├── 010897f3d3d18475208468bbb22a8666df24a4ef.nq.gz
│   ├── 0609834e4e97cb1268d957a0d68f8345f7b0346c.nq.gz
│   ├── 0735ad97bb6e495b85fabf12beea391d1b0d3c6f.nq.gz
│   ├── 17604b5b40fcf301ad10846a354914d1481dd921.nq.gz
│   ├── 1781e2aeeb70c7b3b79aa046d43afddbfdf05f42.nq.gz
│   ├── 1c2f426e7c70b579b073509fb4226e4512554ee8.nq.gz
│   ├── 1e633cf5a78a285fd40124d42471d7c8e2ee1ccb.nq.gz
│   ├── 21eb5f937440af1f8943f5540aa70cf8faf5b865.nq.gz
│   ├── 2295344e148e6ba88db5eb072ca797e4ea2a49ef.nq.gz
│   ├── 22b9b5cfc6923d7ac7a7985902b9f1e7d9b602d6.nq.gz
│   ├── 32339a993de2981ecf202e91b78c08d3b664f2d0.nq.gz
│   ├── 33230ca58c48a809a03d4d7b483d3f5442dfcb44.nq.gz
│   ├── 363391abed06eb23b7960dd85f0cbc0d2c8b08b1.nq.gz
│   ├── 369f8836d015157240942f3800079916ee44877a.nq.gz
│   ├── 3a8b7c6f86e7c2e9b5011f360b597b71d39e86d3.nq.gz
│   ├── 3cac8e9b9cb3988f87990194996fbe1287bae6a6.nq.gz
│   ├── 3d818257bc2d8ba8122a9a98d5c9a1a65b5c989e.nq.gz
│   ├── 3edc695dcea5c89ff59d72a47fd30323fcfaa016.nq.gz
│   ├── 3f164692181611c9dd38b4cb7bb1f5935d93cc68.nq.gz
│   ├── 453a5174ca686b0fadd528a21ab8dce15da858c8.nq.gz
│   ├── 4cbb86409d3359cc753feb807657096161a8967c.nq.gz
│   ├── 56604361f56f6a20d560a0acccdd1bc3bc9061bf.nq.gz
│   ├── 5a235d4d6980b3d9cfe4ee125245e894000df49b.nq.gz
│   ├── 623082d54e85e70f08562a4f3b8434d3af498a7e.nq.gz
│   ├── 630f1fc5523e0cc7e73a113d5184b88cdebd20c9.nq.gz
│   ├── 648c2c7576c49eeb790982f61e7b86aa6985c85c.nq.gz
│   ├── 65272a254007fb99175f9a05c7dcce50b4b82d49.nq.gz
│   ├── 672e2b9345fab47f9f4f2a9eb20a36111d17afe7.nq.gz
│   ├── 677b3bcb5fd05b826b0349142c76c33fa4443657.nq.gz
│   ├── 6e24887676db22dfded12932843c6ec6ae4fc0b2.nq.gz
│   ├── 6ec4ef2782143f6b3bfda0dc1e5115f0141be974.nq.gz
│   ├── 7b5453683ba41a790ebb55d7d2f73870c8602201.nq.gz
│   ├── 7ca4ff29abcd476e8fb3fd3854f39e8c02759c88.nq.gz
│   ├── 7df89d58b245fffca79056922a52280596f57c68.nq.gz
│   ├── 7fe1cc095b82c6b292d806879bac240ea0d77d99.nq.gz
│   ├── 879732d04b5eef8604358df40f6c6386d15005f7.nq.gz
│   ├── 88600d9b38c87fbdca7f96face29485af962e95b.nq.gz
│   ├── 8a6d5bfbed68ee7f98acf9702f21ae26ec67beff.nq.gz
│   ├── 8d28d48ae1d9590c85a86d338d7b1c405380d384.nq.gz
│   ├── 8f0a730c5e89ebca845b1bef28ecb2356ef1bbb0.nq.gz
│   ├── 91d3e25ea4f161515a153efe40f43602e48de484.nq.gz
│   ├── 922c90e59b3710cb76c6b2daf7da134ac7391627.nq.gz
│   ├── 9372dce12e73021043c028252290782a876fd9ec.nq.gz
│   ├── 943c65259a00d77d4d5fbeedc46a861a96d65221.nq.gz
│   ├── 95926da5fe33538ec113791095fc3cbd7bca1701.nq.gz
│   ├── 9a5802ac1156a223e40fcfe7bb7fedb85e70db05.nq.gz
│   ├── 9f10c14465be3a96de3cffa8347925f4df4caeeb.nq.gz
│   ├── a4376243a39d04f1d36afc0261d3b2c95d9258e2.nq.gz
│   ├── a54d436db040fe5a4b089a038d8c9390a00e0d92.nq.gz
│   ├── a6f7bc8be9092df06b6604879910108d6de09254.nq.gz
│   ├── aa1ef0244842fc4c5164b1648a817fe4a438f48d.nq.gz
│   ├── ab3988a463196e07efa2c85ce016d7276ff8f4a1.nq.gz
│   ├── b5d6a128814787a5bc357c3864e82da10fe51bdf.nq.gz
│   ├── b931d6bcb57d23ef394efeafe78b82a0f13a403a.nq.gz
│   ├── c92a504d8918ca6ad5038c43d336f1f69da804f0.nq.gz
│   ├── ca000deb86f28a7d74e07ea7adbeaaa2f2db1e72.nq.gz
│   ├── cc75108d1aea35803e10b041452b853773fab759.nq.gz
│   ├── cccc6623989113a4be03ba50dbf223e03d4aea7b.nq.gz
│   ├── d37895d711b2491ad1dda8fb155adc94d51d35dd.nq.gz
│   ├── d85ad9f8f69aed53cb547a8f5196dbe86e3a7a09.nq.gz
│   ├── dd9bf4cf4f58beabb5bdcb661b3dfedd9d15e58b.nq.gz
│   ├── df2d8eb0bd6a3efb47fd9dd7822ffbddd07d1a1d.nq.gz
│   ├── e2f9d59d53932e211f727f23f7e2179548ff5af6.nq.gz
│   ├── e5ac70e2b4a660650cca476c05586212f881c7f0.nq.gz
│   ├── e6205f1a83d589cef3c6301d371d6c88ca7d2706.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7d42d57c12a8d8f194c99ee902463100e2b7cc1.nq.gz
│   ├── e87c351562b7ff795171485b3920444735dbbafc.nq.gz
│   ├── e9bd8b51fd7fb7e4757471d97bf3bd3ef36155b5.nq.gz
│   ├── ea0b7e4cd042677ca919d97fe4787e9ea1972900.nq.gz
│   ├── f57278427baf2b1e055f2a249dc2d3cfb41a9ad0.nq.gz
│   └── fe88f27eae2c710f4d47d11b46e338e8bb6f4cda.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c1f071e9f557693bc90f6acbc314994985dc3b77.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 80 files
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

[klen/graphite-beacon](https://github.com/klen/graphite-beacon)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
