# Repolex Knowledge Graph of tartley/colorama

RDF knowledge graph data for [tartley/colorama](https://github.com/tartley/colorama), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download tartley/colorama
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 15197674cbf1b13d1ead99ef192aca1b732c0539.nq.gz
│   │   ├── 2c592416361b031e3bba00a6efd669c116645aff.nq.gz
│   │   ├── 99786beda2066a7f35d8455e115d8a8d45406cdb.nq.gz
│   │   ├── 9b5ebe9ac61822f3412277268c81e3104517b4c8.nq.gz
│   │   ├── 9f5a28369c4528502b9faa76088df965f6ac103d.nq.gz
│   │   └── d83cff271f67e756e65be9427056442858d2ec24.nq.gz
│   ├── lsp
│   │   ├── 15197674cbf1b13d1ead99ef192aca1b732c0539.nq.gz
│   │   ├── 2c592416361b031e3bba00a6efd669c116645aff.nq.gz
│   │   ├── 99786beda2066a7f35d8455e115d8a8d45406cdb.nq.gz
│   │   ├── 9b5ebe9ac61822f3412277268c81e3104517b4c8.nq.gz
│   │   ├── 9f5a28369c4528502b9faa76088df965f6ac103d.nq.gz
│   │   └── d83cff271f67e756e65be9427056442858d2ec24.nq.gz
│   └── repolex
│       ├── 15197674cbf1b13d1ead99ef192aca1b732c0539.nq.gz
│       ├── 2c592416361b031e3bba00a6efd669c116645aff.nq.gz
│       ├── 99786beda2066a7f35d8455e115d8a8d45406cdb.nq.gz
│       ├── 9b5ebe9ac61822f3412277268c81e3104517b4c8.nq.gz
│       ├── 9f5a28369c4528502b9faa76088df965f6ac103d.nq.gz
│       └── d83cff271f67e756e65be9427056442858d2ec24.nq.gz
├── blob
│   ├── 00c61112820791b84b8186cc770da97f6078c609.nq.gz
│   ├── 016aa76d1a764d037e73d2bb99c6e540c1a0a0c4.nq.gz
│   ├── 06cc8bb3107e4874b0f278698c3a0c7fe5b8aafc.nq.gz
│   ├── 07f556eea58bec325d9ee93f195ebf46742e8225.nq.gz
│   ├── 0811ff64997678114f0cb2f64d296b702e1a3602.nq.gz
│   ├── 086327cadcb61098db3615c88a0b22a3476ae004.nq.gz
│   ├── 0a20c80f882066e0e1323b0c7f61e22913c32e35.nq.gz
│   ├── 0a76fa6309b4906b805433a4231869b49c48d264.nq.gz
│   ├── 0c53846615c9bb8841d32946ca496e5d49bdcfa8.nq.gz
│   ├── 0f84e4befe550d4386d24264648abf1323e682ff.nq.gz
│   ├── 0fdb4ec4e91090876dc3fbf207049b521fa0dd73.nq.gz
│   ├── 13d5f9e23acc81da2d75e22ed985655e01cefc77.nq.gz
│   ├── 140a6ca07f2616f1ec7f86190e06980d7597b6ab.nq.gz
│   ├── 1c8c6c78a24296c88a3e65948f11c752f28887bd.nq.gz
│   ├── 1d6e6059c75812c398097c8b188aea3dcfd0dbce.nq.gz
│   ├── 1dc10be7e79c1b2ae016e6779dd9fee0ae469931.nq.gz
│   ├── 1dc20dcb284955cef1fc48d056dce40c30bd3cbe.nq.gz
│   ├── 202551b52300d169b085ad3ef4dffc037fdf650b.nq.gz
│   ├── 2a3bf471423bbf789f13755d3dcb03826f7aff36.nq.gz
│   ├── 2a9acf13daa95e85642ea255d3e3bd1ef8252804.nq.gz
│   ├── 2df28f5c52686a441bf0b4d24d18bba294e4c147.nq.gz
│   ├── 2df913c9094f74c1d20e3a9b085531a3aa17bc6a.nq.gz
│   ├── 2e9053c06e45cd65ebfe61ac591c280a1a9c6ee4.nq.gz
│   ├── 2f7384de6af6b2520daf5b6c0a8bdc95d0a43f16.nq.gz
│   ├── 30279a79cad4ca73aa583fff5c996554c87666db.nq.gz
│   ├── 3105888ec149d10cad51c11d332779e94b548661.nq.gz
│   ├── 33f25ae998c7e4155b5ed5fc3712b93a13525628.nq.gz
│   ├── 359c92be50ee3c97aafbc8d31c16e5fbf2e6d022.nq.gz
│   ├── 35aecd89a33e8efda8fb0629885c0fb9b690e6d0.nq.gz
│   ├── 3813bf44b6bb4b74507806203e51c7884a8e69c5.nq.gz
│   ├── 3d1d2f2d91867ecd8663a2870fededa15b2b9c89.nq.gz
│   ├── 3d86fe90dd1a69e7fe460e5847d6f0f56e408823.nq.gz
│   ├── 430d0668727cd0521270a52c962867907d743b34.nq.gz
│   ├── 43225c2a8971c0c880b34fa7787c3c26a35b129d.nq.gz
│   ├── 43556e60ff539882c8c398ae60f210a4d4a13679.nq.gz
│   ├── 489d82462664d4f3e14d9cf450eb6c1c943c0da6.nq.gz
│   ├── 493cfdb9aec67fb4e28521e6893a4a217c813716.nq.gz
│   ├── 4bce9f2293b657da2edc357e6dc13424242e2003.nq.gz
│   ├── 52c03a99b430f01400af2d6ca3d92792d1bfbc13.nq.gz
│   ├── 5bfc01e13eb4c892f6c2f96b05f70c8eee36933b.nq.gz
│   ├── 5f567799f395f33acd05abbc5d409dd126ce0dc8.nq.gz
│   ├── 60309d3c07aa4c1a66388d0d2530e7086d46f091.nq.gz
│   ├── 6305ed30c07eae7e4892901f0c91b6e524d5a290.nq.gz
│   ├── 655b04a261b29861e708a169e52d5571545c7592.nq.gz
│   ├── 670e6b3970b77529fd65f002a1afda6d28873cce.nq.gz
│   ├── 6d8daba2c6968a346285f9197d90e81bbac42a0f.nq.gz
│   ├── 78776588db9410924d8e4af0922fbc3960a37624.nq.gz
│   ├── 7890f3410769a2c0e675d563e650692555bf6bf0.nq.gz
│   ├── 7aa61876a34622f508a756ed7b55480e59938077.nq.gz
│   ├── 7b3fc05031e0db92d3bce0dc70a434778fc02f1d.nq.gz
│   ├── 7d56622e3fd0f40aa6a177a43247b354264f82a1.nq.gz
│   ├── 818d88c5fd7b2ac9bf8c96d983fb293a8c82f125.nq.gz
│   ├── 8262e350a68ec9982450a7227fdec7c3c6667aa2.nq.gz
│   ├── 834962a35f76f903c56bf921605b7fe3938088a4.nq.gz
│   ├── 8386a7fb91b32075fa1fc98db9d414b7464e314e.nq.gz
│   ├── 8c5661e93a205bf4fb22404d4fc50f902cc31369.nq.gz
│   ├── 8d67bba0111b1aa4c5b3a9300bbb6737e43e9e0b.nq.gz
│   ├── 8fc3f01131556fbe41a0956ae2b61b0b32ddc158.nq.gz
│   ├── 91fa10157fcb595036b2d811447de9efe47a84e1.nq.gz
│   ├── 99d896a64a2bf38c1e4aaf2e47d72d67aeb157d5.nq.gz
│   ├── 9dc6e3a4510178f54ade8de4190314ff7d2255fc.nq.gz
│   ├── a750d2ab02f3b35b702694def9a229be0a27393d.nq.gz
│   ├── af9363205528f6d2c5217d7ee18c9fd886513fb5.nq.gz
│   ├── b2dd3e1f58101d20e2bc7e911370171aa5a88523.nq.gz
│   ├── b4c1ea654713d54f57804b25e8088caf5608a8d9.nq.gz
│   ├── b7f36646e3d1d2678bea3f332c5e640bef4e203a.nq.gz
│   ├── b7ff6f2136eec3530563c0fedf226b4b00c52d9d.nq.gz
│   ├── bedd3985dee5be60bf010fccbfa617725c0af609.nq.gz
│   ├── c2d836033673993e00a02d5a3802b61cd051cf08.nq.gz
│   ├── d773531a2f7eb35a1e325f844175f8ddae1321b0.nq.gz
│   ├── da87c79a0fc68cb4e0823924c4af519efcce3683.nq.gz
│   ├── db046c4e04655cee00dcde86e25c5f56155f79c6.nq.gz
│   ├── dc03c154bdcb1e7683b2f16ba540974cb59fde25.nq.gz
│   ├── de2abf55ad9001a80c09d92055aab494c094d205.nq.gz
│   ├── e5a70dc868446b4896426046e49950863fb8cab9.nq.gz
│   ├── ea96d874616b76a38cf1138ba5d61418a777f52f.nq.gz
│   ├── ec893e104ebb2793d489df34467373e93e99bdae.nq.gz
│   ├── efe5a6085ca028e3104d2fa199e43a0c8c4cdb38.nq.gz
│   ├── f0e8f7139e4d4ce8275733d3ab1b510476f70083.nq.gz
│   ├── f351763471de5e8776c6f8a050c4dc546d97cc16.nq.gz
│   ├── f4adf4e17a5fcff5e1f199671efac219beeaad6e.nq.gz
│   ├── f4d9ce21088adbf8c1065ed83e3cead853db731d.nq.gz
│   ├── f569580236a72ba3a6ccd1aea70b4bc7bcb843aa.nq.gz
│   ├── f9cf2e90a114a3750395810fcfa5d09dd4632c52.nq.gz
│   ├── fa836c9b881722bbf59c3624403be8ead9c632e3.nq.gz
│   ├── fd97acff7a4e774cf9dba956197ee876a9feb1cf.nq.gz
│   └── fe102cc80351df998aa891995a2c192edff1a1b9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 15197674cbf1b13d1ead99ef192aca1b732c0539.nq.gz
│   ├── 2c592416361b031e3bba00a6efd669c116645aff.nq.gz
│   ├── 99786beda2066a7f35d8455e115d8a8d45406cdb.nq.gz
│   ├── 9b5ebe9ac61822f3412277268c81e3104517b4c8.nq.gz
│   ├── 9f5a28369c4528502b9faa76088df965f6ac103d.nq.gz
│   └── d83cff271f67e756e65be9427056442858d2ec24.nq.gz
├── filetree
│   ├── 15197674cbf1b13d1ead99ef192aca1b732c0539.nq.gz
│   ├── 2c592416361b031e3bba00a6efd669c116645aff.nq.gz
│   ├── 99786beda2066a7f35d8455e115d8a8d45406cdb.nq.gz
│   ├── 9b5ebe9ac61822f3412277268c81e3104517b4c8.nq.gz
│   ├── 9f5a28369c4528502b9faa76088df965f6ac103d.nq.gz
│   ├── d69f83f53c0c5aa1081d1f5eebb2dc2df6028f37.nq.gz
│   └── d83cff271f67e756e65be9427056442858d2ec24.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

## Source repository

[tartley/colorama](https://github.com/tartley/colorama)

---
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*
