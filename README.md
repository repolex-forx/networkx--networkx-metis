# Repolex Knowledge Graph of networkx/networkx-metis

RDF knowledge graph data for [networkx/networkx-metis](https://github.com/networkx/networkx-metis), parsed by [repolex](https://repolex.ai).

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
rlex download networkx/networkx-metis
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 26a51ddad5932d843655e5b7ba1225bcfe3b8882
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 26a51ddad5932d843655e5b7ba1225bcfe3b8882
│           └── chunk-001.nq.gz
├── blob
│   ├── 00971e5de82bbab0428df952523dd72d9ab96df7.nq.gz
│   ├── 078e11434d5dbc9c707d3103f99209f6a5c580c3.nq.gz
│   ├── 0e3c6dbd2924938538b896250c2f8b87a50ffd8a.nq.gz
│   ├── 0ecd374952fcc682b3ab1d9def0a08fccedfaae5.nq.gz
│   ├── 10e8ee462de0b731c712d9fc83b2ad3b5dea7ea8.nq.gz
│   ├── 148f88d489b32964f94e69072fd391af253ecb55.nq.gz
│   ├── 165344e6ef6dceff70359191ac621344d623c46f.nq.gz
│   ├── 1884ee608dd6a4e462807c172622e75c60523854.nq.gz
│   ├── 1961178388a96af3bd01792d155c478afbe82c23.nq.gz
│   ├── 1ad4606c0c2a645c91bf158e59edff1bda6dcd60.nq.gz
│   ├── 209581865e4de099038c1612e21f17aceae5e454.nq.gz
│   ├── 25941eaec4e32b38fcccc3ca9fb375c1f37ec7f5.nq.gz
│   ├── 2a6b94f6d71b167566e714dde6f1cf5e2c5d8545.nq.gz
│   ├── 2c0fdd9683f74d269efdfc963732061bde98e87b.nq.gz
│   ├── 2de030d65ee6303f45da81d78056425e3613faed.nq.gz
│   ├── 2f6c81b7288f83b1857e803af78ebcc8fa4fb7e6.nq.gz
│   ├── 2fb8515d21a5ca0f8b017815fbf3f8bf1d345e0e.nq.gz
│   ├── 35e4b97b2916b27befb1f7f8d1d4284a597ecfa5.nq.gz
│   ├── 377c97057517d2adc83e982c825e75c275179c6d.nq.gz
│   ├── 37f7d09dc83bc9377ccb0369d90e3ed33f9f732c.nq.gz
│   ├── 38edc47a8d02d40675e5f0b2ded85ee0195c571d.nq.gz
│   ├── 3bc1ac93c042131028db0fd0e456c04a49f7915b.nq.gz
│   ├── 3c5261211232b3290b7e9aa3327e145f88482927.nq.gz
│   ├── 3d43c3ade0e3af3c714aa1c6d600822405f34b0b.nq.gz
│   ├── 3da7d26c05f2b04080c8de581738ce0ca817b8b3.nq.gz
│   ├── 3ef7bbd7bfe130666fa852ae216886fbf804bc4d.nq.gz
│   ├── 3f45902db546053163d474bf38a753ee78ca4550.nq.gz
│   ├── 3f6f7d9ed26bdebce98892cc76ebefe87c5f5031.nq.gz
│   ├── 3fb0e6e56a42bf13b2fa19b5fde4d93a3817ceff.nq.gz
│   ├── 4e78fde0b12fc867186ed138de741bfb90be9e00.nq.gz
│   ├── 51e39754c8a6b97c2b2d655c75629c1ac3ebf488.nq.gz
│   ├── 520d7f529156674f7796e18b751cdde1cc7928a1.nq.gz
│   ├── 57c119101112f816be314098e8157d9ee32ecaea.nq.gz
│   ├── 57de297dadbbf8c9c6a9270739e3aae3b4321a4a.nq.gz
│   ├── 5b8779d1f9a8f84e0f437e0cd4d5a97ea758703e.nq.gz
│   ├── 5c3ed90297fd69ce9f03f994865e33da935ca041.nq.gz
│   ├── 5efd262db91307067bbbeee849d57232d55335ed.nq.gz
│   ├── 5fc8588df6cf25b8ddc4230f58b5c76c11e6caea.nq.gz
│   ├── 603f782ad4e662b56f3796e29539798219478a8b.nq.gz
│   ├── 62b03b491b93ff98dc0ab38f0fa9c80a4791ed65.nq.gz
│   ├── 631d811bc3f85f95498c5a86b02700ed9f99f75d.nq.gz
│   ├── 634a2f0c6f3dde489f096ba46a561db78a097bb5.nq.gz
│   ├── 6442e03a9ae87cb45be1e3c5655a178437c3d242.nq.gz
│   ├── 64c94012cc700d08b28449e5d1b31f1609ee5ee7.nq.gz
│   ├── 65b5af40d0f1df524776cc3d1523522096168d1a.nq.gz
│   ├── 6945bdcd917b2aafc05db5016b5e9eb637cdeadd.nq.gz
│   ├── 6e20f556a1e3d8d719f43a49214825ec3cb0dfcc.nq.gz
│   ├── 72dae9b643a864e1405de53df4bdc817ca6c2b69.nq.gz
│   ├── 7331c33c184516dad0a32138b1e05687e4d8e176.nq.gz
│   ├── 778cc1548beeed499a95a8b4819e65dca2bc0dc4.nq.gz
│   ├── 78dc8b39e9dab0d915cc40a5cabde0762e6436ac.nq.gz
│   ├── 78e216e0e7be2aafda9650ab12147b45b9793a1d.nq.gz
│   ├── 7921bfb6fedc9f3388796c4964f126eada003d7f.nq.gz
│   ├── 7cd4391a04a30df7cf868912203b7b0a917909ef.nq.gz
│   ├── 7dd96dff27b77a174dda1c70d30284ad4cfd1f53.nq.gz
│   ├── 7e200dc6fc6938fd3caf2073850056f0a739b882.nq.gz
│   ├── 7f5ea6b013ca1a15830e1654599729da59c13c9a.nq.gz
│   ├── 7fbc46726eff2668893cea4fee6c301090001c54.nq.gz
│   ├── 84d2c7ac882e3ac8213a94e0abb536473acf0205.nq.gz
│   ├── 852634614c9a757313ff19f5c868f87da5b3d630.nq.gz
│   ├── 86dc90fbee1ee3f832602830ded9bfbf84d82afc.nq.gz
│   ├── 8976b4ba49e7c8751179c33597cce8a8eb9c756d.nq.gz
│   ├── 8f6961363204a5e6d56afae5c1ff67cb8f5a3077.nq.gz
│   ├── 93d48f01136c0affcc1a15969b5e44701279af98.nq.gz
│   ├── 99bdc599c2b123df532567500d8c9fed62c664ef.nq.gz
│   ├── 9d6e05cf1c842a19f6d2572056381fc2b7dd1f8a.nq.gz
│   ├── a092f2227d33395b1b67b25874e48eed23a75c52.nq.gz
│   ├── a19d793bdcecd7c4b8bfa2d9109475a1c31c061b.nq.gz
│   ├── a1ef6faf79d4c67c2b4ab8e8de824fdafbc8f195.nq.gz
│   ├── a2d4e8c4f0919fed4da4c2cd6aefdb5cb1902d78.nq.gz
│   ├── a474c3cb6d47fb2664496cf0fbb8dc75f379d606.nq.gz
│   ├── a47f99c2903a99d8e9e3af11b4740059b1fd017b.nq.gz
│   ├── a66d106102fa625a2580f90d34aa986a93e73780.nq.gz
│   ├── aca482bdf22e9479b1143784af5780e32f24e08d.nq.gz
│   ├── af991c60ea0126e1b23727e4ca02b75649b9410e.nq.gz
│   ├── afacd68a1e16213a93365ed00db4297cc6ef59b2.nq.gz
│   ├── b0b63b5ec4cfdd41e30803f13e4d5d5c44847923.nq.gz
│   ├── b1238ce65384177f30fa8f7d912f2e4b9b403daf.nq.gz
│   ├── b3d3c0fd02029e99403db3fa295a128ecea59711.nq.gz
│   ├── b4d222653e7133570aeddaa492f7e6e5381640fe.nq.gz
│   ├── b65cd02648720536ff6412f0b4ac3320fc865fcc.nq.gz
│   ├── bb8e1bd5f8370e5c51cdbc53f1e605bef7b073ca.nq.gz
│   ├── bc67bdaebfc3d500d39472acb1a1e17c54ebc4eb.nq.gz
│   ├── bdd543acf40099863bb99675892d0b14fda8e653.nq.gz
│   ├── bf7ac7216bd9e472ee7a66223e43423f6f1013a6.nq.gz
│   ├── c08dc2ddb092cec4ed780427ae935217734809a1.nq.gz
│   ├── c988570bea072e3205341cc9593e0747366b7072.nq.gz
│   ├── caaedcb59c03357013435a871815c0712e9a9b53.nq.gz
│   ├── cb6d1afb3d50e86eee16247719d31d09b78a324c.nq.gz
│   ├── cc089d03c9058f77e536cd31496249f8b366b232.nq.gz
│   ├── cdd00fa79ab02fcbd0eedb32f9bef303ff339f29.nq.gz
│   ├── ce805ced9eabcda2b2f7dc6836678fe1824c78a9.nq.gz
│   ├── d0565b095c56fce4fd947f9b4669747352cdd567.nq.gz
│   ├── d18e7188b16689acb38772f82f541a76404f0df5.nq.gz
│   ├── d1e288bc3d412a12f69ecceed01b70c2792fc095.nq.gz
│   ├── d32e84921fdb77e6e68e6625d7ca6667c18cac83.nq.gz
│   ├── d3e73cf8b9e9608fa9fcf5121e8963adb3246c24.nq.gz
│   ├── d4181738028aae2ae8a2870dd4cd41a989512795.nq.gz
│   ├── d4d8756e919d754a1db0b5416a62acbbd846a9ea.nq.gz
│   ├── d72472b25be307adfea84cbf2d733345fe9450f8.nq.gz
│   ├── d75e72d24b8d3a5b20ef43a30dbff977684697ef.nq.gz
│   ├── dedfd39098c40836f60f9b6ca3895e2293c89f29.nq.gz
│   ├── dfac5ca674c5dc3a97b22e0f4879b8f6361696ae.nq.gz
│   ├── e126d02a6323e26642f67b28947cc2634356a3c1.nq.gz
│   ├── e188135da57ca7b4ccbebcffb6deaee33ad971a9.nq.gz
│   ├── e1a2b9ced927d1bab94837878d14f3327a621ca0.nq.gz
│   ├── e26204b7f3d77cedf243ddc9acd4d6b536ef996d.nq.gz
│   ├── e29cf3b4042c6d163774a33d70a02d13d6b938fa.nq.gz
│   ├── e446a4db86c941fae120a68e4654568f998d6f5c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e75d68b51bbdd1010fd47fcd1a9ef04eb8d23508.nq.gz
│   ├── ed437fff1a816feb70a09ddb052580574364debc.nq.gz
│   ├── f19791b535681f6980170e7a47573420f8400352.nq.gz
│   ├── f267a3ea027853ab66c54c40e8772833cb03ed8d.nq.gz
│   ├── f48ab947233630d919929624f767c78fc24b7169.nq.gz
│   ├── f852ff59e33feecc6a9c9bb3e5c4a5f2768e3c82.nq.gz
│   ├── f952fe29791716a3559b34cdffdaa6af35e2622d.nq.gz
│   ├── fabe1ecfa8ee93807e487c08b968703ce319807e.nq.gz
│   ├── fc136ba9e065117e2a348d32a011a1576ac144f0.nq.gz
│   └── fe9f1aa570c8ac64a7fe16ccfe81616da2175333.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 26a51ddad5932d843655e5b7ba1225bcfe3b8882.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 128 files
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

[networkx/networkx-metis](https://github.com/networkx/networkx-metis)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
