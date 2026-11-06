# Repolex Knowledge Graph of ansible-community/antsibull-changelog

RDF knowledge graph data for [ansible-community/antsibull-changelog](https://github.com/ansible-community/antsibull-changelog), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/antsibull-changelog
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e2a251de927df6988c6ce01820affc3e3bd96030
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e2a251de927df6988c6ce01820affc3e3bd96030
│           └── chunk-001.nq.gz
├── blob
│   ├── 02f20847810036b5cae9c89459e0c53e46326105.nq.gz
│   ├── 07215d5aff19bb10111846d6f9628f60db0ef65c.nq.gz
│   ├── 08c8aa5818a5bace870de955dec7bdad756676e3.nq.gz
│   ├── 0bebc7e27ec192a2a8a0efe345c25cd2a8ab9459.nq.gz
│   ├── 100e4c845279163199ae7e2ba6308db448f0ab09.nq.gz
│   ├── 14610d102361218f7fb4be6752b01ae3de7f55b6.nq.gz
│   ├── 147f05692a6c4219701a41130c4c75c31233bac8.nq.gz
│   ├── 1850423fa4b11e280f8e8a5f8768b6913738d63d.nq.gz
│   ├── 1a8f14a0b3421a1c41289e8b6fc06f075208ed61.nq.gz
│   ├── 1ef722d4212dd4d4eff594079045eb80dff3d1bf.nq.gz
│   ├── 20c2dac1442b6fa37465bfdd84b9d8e56a04496b.nq.gz
│   ├── 21acab0252f6447f5765ca7bfee1710486e89b8f.nq.gz
│   ├── 21f83fc4406463393837c80cbe6229b7b43f2701.nq.gz
│   ├── 22183aa818301c4895ddf241dc382a5486e362f8.nq.gz
│   ├── 2384462b4e760dfe9402180366cace0c7fc51c9a.nq.gz
│   ├── 2593624b432df1e47af9bf63066aac5940b7f3e8.nq.gz
│   ├── 2af068f60ba22215cfc69c0b80871b2929e79be0.nq.gz
│   ├── 348a4d6b3a2b18543c6027dcb232e8bbc42b37c6.nq.gz
│   ├── 34a189811f5b9ef50a72abbc8330e3436171a205.nq.gz
│   ├── 358a2e9a55a3f9c21f996d8c78418ef80e2a6a11.nq.gz
│   ├── 3d93fcb6c010559a64975b4cdabe40e46d911612.nq.gz
│   ├── 3e66ee7ff4fb6ee0d11aab61852dc5d1562b54c8.nq.gz
│   ├── 4528acda93bccfc5393b664529c2e5a5a465dd95.nq.gz
│   ├── 478f90635c0b9f8394633d9d95e7f5efb1c4aa35.nq.gz
│   ├── 47ad569becede7b20f3beeaaff6f3ef3158b0383.nq.gz
│   ├── 49fb33d3a3bfa29522279a97f8fd872ce31954fb.nq.gz
│   ├── 4d56df88be233656c3105eef74080f768a854c77.nq.gz
│   ├── 4d757d861ba5affe981386371e11c7211ef6225d.nq.gz
│   ├── 4f0d042d8b65053fed27cae7f63a4eedf96078fb.nq.gz
│   ├── 4f4b65c8d05a10477c218572a9ccddcf45b165a3.nq.gz
│   ├── 50804672e0269f4e8b8d20cfc9ad7a1237607c31.nq.gz
│   ├── 52b28f75910cc81f72b38ecf81000d41cdf15ae7.nq.gz
│   ├── 55b01c5354750d0b3b9184a611d46a48d1cfd2d6.nq.gz
│   ├── 59467c01f9390cdbf2871dc1c9ac12f5ad002dab.nq.gz
│   ├── 5ee7812edbb236187b2434d8d01342f71c10b922.nq.gz
│   ├── 6010d214665e3a193b9cd5d7af7e2de913e469a0.nq.gz
│   ├── 639e61da9e640e5ade9f6a86fffe9ab5f09ef53e.nq.gz
│   ├── 648c8aa2e9fbc8a604ed3686422df8a87e857482.nq.gz
│   ├── 660a0fe69047f11e9d9b686dfff61689db203425.nq.gz
│   ├── 68d68eea3a0cfda01c88427e722990447a9db3c1.nq.gz
│   ├── 6a4ae06e8aec9a6aa85cfb83d5fe5024cd96cda6.nq.gz
│   ├── 71c7aeadcd201abc717ab135be84730524eb6bfa.nq.gz
│   ├── 71ff4a9abd81f9177adcd792058ca7b5704c990d.nq.gz
│   ├── 75bafb309863fe7c388d2fb1e67c2cfa84fd8d61.nq.gz
│   ├── 7668a87bc0adce215567922423fe68ae4bb048e0.nq.gz
│   ├── 7781073b8b4780bd55aff2db1ac6164493adab63.nq.gz
│   ├── 7923039e049acd682c7c81c5e0e799dfdd13c21f.nq.gz
│   ├── 856ec2339b39c3e92f3c874bb69ab75a3ce3e5a5.nq.gz
│   ├── 85e050b0fd4afeb8ae592cae0264e6c8d75fcc08.nq.gz
│   ├── 86547e946d69f1c0e13e25c52b9ca1ce5ea3122c.nq.gz
│   ├── 86d35e808dc30d03e3ddcbc8797f98bcec89da1d.nq.gz
│   ├── 891620b829ebd8c30c180b22020f15a46593a14e.nq.gz
│   ├── 8de84fe2f3d4e603a4a5c57d6c9bcb1c69a70134.nq.gz
│   ├── 91c1918e7f727f022e2b0b095832b7483a0e2068.nq.gz
│   ├── 92f9f98ac3bdfafc37875469e95ee306aa79fff5.nq.gz
│   ├── 951f23b02fb7101c216de6290491899c68aba91c.nq.gz
│   ├── 97c01d726ddc4372ff7e3c4a5320d9d472376acf.nq.gz
│   ├── 9a93f4baea4ee5a76eccd35282da3f422a8a9343.nq.gz
│   ├── 9cb161366aeacb04123ee2ec47a8c6cfa104e947.nq.gz
│   ├── a03b79ea3a59a1864c145a25f90ed786ee2907c2.nq.gz
│   ├── a1f6b3f6b285e02a9ea769148021c28219bc9cf8.nq.gz
│   ├── a3366ef7f428c54366eee812c62239b90fa0ba79.nq.gz
│   ├── a4170d30e2581981d1b343d713d6064dfdde1e84.nq.gz
│   ├── a50bb878e7cdbebdd7114d559188350462a19496.nq.gz
│   ├── a5d9a1c041f8cadcbd535babe74f188e45108939.nq.gz
│   ├── a8b34a32977e3ca36d991301405c3b56c67133ba.nq.gz
│   ├── b16b98ad9c5ff9dba3ec1afd4e4dc5c602b54e6c.nq.gz
│   ├── b3254a4707b78bae1af3a7a4511063f2993be83f.nq.gz
│   ├── b391dd938c7b1b26c19b38004860c3dae9457728.nq.gz
│   ├── b7739423d4997d1dbb1af6fdeaaee3d3dce8aced.nq.gz
│   ├── b89bf3040f8758e4ca217290e811c1dc88499755.nq.gz
│   ├── bd3a9fd68a38a59239700627a73ffb5ae1092c26.nq.gz
│   ├── be6957826448a537cde8c35d5b659e7c78811438.nq.gz
│   ├── c1f14a5628895555abc826bb61c8b0f46491d35f.nq.gz
│   ├── c28c9130384675eaaf650dc5e6aa37f389c9e4ea.nq.gz
│   ├── c3c37dba0ea17d8bd67b1f0b8431ff75a1d72954.nq.gz
│   ├── c4c4d9e1f71a18c351ece71eb21fb279ab2298a4.nq.gz
│   ├── c5841a29bce92a342bd3f4c10499f0b9b5f214ce.nq.gz
│   ├── c6c321e0350d06ad68e446dce627d5fe43cf2e1d.nq.gz
│   ├── ca6275597bd92a4a74b769c1d5444d5a04449608.nq.gz
│   ├── cd5389142d59ffb48ddc5dde708569d63b869f2d.nq.gz
│   ├── cf95e2d60a46b0bb707502286b9860c303ca24c8.nq.gz
│   ├── d48269260cd71de2695f9a7e73b9b387b6054b6e.nq.gz
│   ├── d8e06c8d14d2e6abf5354d9d85e91c8da60daa83.nq.gz
│   ├── e3257918ae44024f8797ac11dcf4be2c6c8fa1ff.nq.gz
│   ├── e501f3cce5ed3ba411b906687c3516999d5e2ace.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9d94fdef6bd8a8bb358c99b2aa18695c5d0b73d.nq.gz
│   ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
│   ├── eca947a89c6ed3ba5dfa041e99a8c46311946756.nq.gz
│   ├── ee9c8ea632c721ae1b600889c9863f3f2bbfc966.nq.gz
│   ├── f079ad06624a975d6cabb72feeef8466b2ebcb87.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f5f5cbff2489cb1c9096bd62efd8c3a0e41d7938.nq.gz
│   ├── f71b322d2aabd560774185ebb7c3fec99c47ef3e.nq.gz
│   ├── f7e5e9147876be2bd6474be08b739ba824058bdb.nq.gz
│   ├── f81011f9e4665cefee3a876b6798e058689596e5.nq.gz
│   ├── faed8288ec1d533ed9b9316e9167c9142235f487.nq.gz
│   ├── fc0443cf24a28d4b4d74d6890b1906e53c90b55e.nq.gz
│   └── fc5b49be83717b6293a7f0a0dd539090e9abee87.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e2a251de927df6988c6ce01820affc3e3bd96030.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 108 files
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

[ansible-community/antsibull-changelog](https://github.com/ansible-community/antsibull-changelog)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
