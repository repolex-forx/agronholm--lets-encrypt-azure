# Repolex Knowledge Graph of agronholm/lets-encrypt-azure

RDF knowledge graph data for [agronholm/lets-encrypt-azure](https://github.com/agronholm/lets-encrypt-azure), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/lets-encrypt-azure
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 57aac6bf4861b89eadc67f0dc061467e715e1ae6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 57aac6bf4861b89eadc67f0dc061467e715e1ae6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0045f75d76b3df8a0d17465288d807982af4f080.nq.gz
│   ├── 014bda4834418d1c4257c6ef1a76a4aff6ae28b1.nq.gz
│   ├── 0730b556199bec491089ed5898da3cc0dfb8490a.nq.gz
│   ├── 0776576c8132a4253d9fbaa04717145030ac83fe.nq.gz
│   ├── 07d53f49cd09fb8bd55a77e64376c803d4c845ba.nq.gz
│   ├── 0a1a50ea7ebd186c43e18212b834b73b2a6da909.nq.gz
│   ├── 0b08a95d203765827caf52ae5e3ba4eade680a42.nq.gz
│   ├── 0ca42829a4ab0d3ee87747b83ef04ba8cbbbb1f6.nq.gz
│   ├── 0e190bddb436e07efa57e8743493825cba12b173.nq.gz
│   ├── 0e8dc4632ec3ff1ff9f7e2646f824ebad895ca13.nq.gz
│   ├── 12b834f6badfc821615c455f06a03c037d058da1.nq.gz
│   ├── 17ae7f23e917bcde90a219539cc66c3fe8026bd4.nq.gz
│   ├── 18e748ee9eab701ff6a2a0bdf8f19cdd4b426441.nq.gz
│   ├── 237f9f43cb0fc33646919a81c7c77676e558979c.nq.gz
│   ├── 25cc4d456d129020f9e62bc3a068a5af86984e81.nq.gz
│   ├── 270d71d38e5d64498210173b2c2889bc97d2ce6d.nq.gz
│   ├── 277c33d156760751da4bcc92b0e257ca290f3e0f.nq.gz
│   ├── 285eaf848584f016132165d46614e00480bdead8.nq.gz
│   ├── 2ff70a090adcbdea59fe9da27bbe75a603e4dff2.nq.gz
│   ├── 3a070872fb4871e88ba5416d6a19ac471b85e71c.nq.gz
│   ├── 4016f23f5d8bd367f1ff4f4bb1dedb4b1ec9a3b2.nq.gz
│   ├── 418ad45a02d643335119a1436c58fdc33fbfcdc9.nq.gz
│   ├── 42829d3da66620e35b51c181c98c8026d1775b72.nq.gz
│   ├── 453146d6de226805438b7b5a7101bdcb970ab70a.nq.gz
│   ├── 464a3d398e155db4638469d175d9f2628ecc1b83.nq.gz
│   ├── 46e4f0cbe121e1fbd0048fbac9f5c0c9a5ccf62a.nq.gz
│   ├── 55239680fd90ec7e2b48210a4a501b58a44d2f74.nq.gz
│   ├── 58b4b90c75bb47838d90be5990c7b0632b839250.nq.gz
│   ├── 5e0f7c8e464646a488ecfb8934d082b0c23234d9.nq.gz
│   ├── 5f233fd7d6f4fc26749049791ba0f913a869d422.nq.gz
│   ├── 6539cd3df1c80dd3638e59d75ac8eb1626cc3aef.nq.gz
│   ├── 66611d2774450202780a78517c80851c9c711a3a.nq.gz
│   ├── 6a4fbafcab7b2a41d14540c2d2d1b0624254ca7f.nq.gz
│   ├── 74b1ca394945697d5f03e716041cfdfa33b015c3.nq.gz
│   ├── 7540953863e6246814b33fd307a08ab6001c41c7.nq.gz
│   ├── 75d5fec938fba05165c047f42d9c1d0b443d5f4c.nq.gz
│   ├── 777fe779dd2453b5f47eb038ff6f5abab00189ae.nq.gz
│   ├── 7a1798e0bcb1a665f6fafd264f3d1af8a2001a9c.nq.gz
│   ├── 7b4c78d3a218e07ac535b1905dff4c58eef3b781.nq.gz
│   ├── 81c1d8908448e768627f59bba82fda01edda2177.nq.gz
│   ├── 851665344b1167c2a84b3ed8d7c8571031d6ce97.nq.gz
│   ├── 85c2c95b487583572e23458fe30300f2dc699b91.nq.gz
│   ├── 86094c3ec8dcd1d745da339d865976372c37bccb.nq.gz
│   ├── 8735d0b2bcb98a75c0f719388a80513306c93545.nq.gz
│   ├── 8f2b0b0c8817b6aa757cc191115396b7adcb02a3.nq.gz
│   ├── 924ecbe1d062bcf089bec2f8aed554bd9addfb46.nq.gz
│   ├── 945313e5c7f2ad743c028730155f1b16a7d2a187.nq.gz
│   ├── 95611715e30a411021689dc027dd33767c3dc25a.nq.gz
│   ├── a2d988172067e8b4579606bb63473b7c9f8a7600.nq.gz
│   ├── a3a0847924a17360d80fcf7679ad2d34cea36f05.nq.gz
│   ├── a98e382ab188231987b318470181eaa6219ed067.nq.gz
│   ├── abdd1c03f78e07cbc39b64c8bbcfa47f7cb3ed13.nq.gz
│   ├── adf1b14ae9d13fd3bbfae0dd45dd9f58262c0d36.nq.gz
│   ├── b0d20584137c03f9f02e51820532f39931ecf8b1.nq.gz
│   ├── b3fdce9acbeda25aab3dadcbaa9782a9a4998b13.nq.gz
│   ├── b6246dc4a71f8ba2386777dfea6d74ebcb2104c5.nq.gz
│   ├── b732bee797e297e05f718e12a9f4625fdfe7a256.nq.gz
│   ├── b7d45024f90ff7be8d37915c175cd990f1f9f5c2.nq.gz
│   ├── b891a2ae3bbcf1ee0cc41dc5b3473788dae8b1bc.nq.gz
│   ├── bc88c84dba8191ae34d90a2768ebad3bd7e540cb.nq.gz
│   ├── bce696a387cf1c64f207770b854bdc2f9a69259a.nq.gz
│   ├── bd8e60349abc8474e4362dddf2286e06497247cb.nq.gz
│   ├── be19055dfb13f7ce28782f17db0636681f379184.nq.gz
│   ├── bed18138840fa06c827598d63cdd55c195f73cea.nq.gz
│   ├── bf71c087cbfc76247ec52e825ceb6633bb729a39.nq.gz
│   ├── c04cdbfccc0be86d04bceaa1ec94db2db5557592.nq.gz
│   ├── c067f003e0450f1e6a55c432c989177db5fe4bea.nq.gz
│   ├── c3acd2d1304ec31c00480a5aa4280774ae4cd8f5.nq.gz
│   ├── c7087d3dcab10d17b63e223e4b5007c0f27077ee.nq.gz
│   ├── c7a3c694dc3aa38f0b85230a513a0fd9df49b3f8.nq.gz
│   ├── c7ec13e472576c77df9d9dffc6b2414adc416690.nq.gz
│   ├── c9892935ee6a9ea9c099be14c9d8696fc6484314.nq.gz
│   ├── cff3f109a57ecfc1fb8cb2522dcd74c127ba7843.nq.gz
│   ├── d1b56f4104b8b6f2d9afabf4953f9d487b573e61.nq.gz
│   ├── d315243c93d7edaec94c638e41b0b8dbc252cfa4.nq.gz
│   ├── d56badae369c03226828dac901662ecf67c27bbe.nq.gz
│   ├── d7b22e55c82e4317e27516716061ff6ca1fea63d.nq.gz
│   ├── d9f53b964ce80452cffd5d434ab34190282893b3.nq.gz
│   ├── da88b3eafa246841be9f68336cd445bfb2230fcd.nq.gz
│   ├── dc061d020bf7a7ebc576ec5b8228173c8706e5b4.nq.gz
│   ├── dd546322f81b032b0096f87f0a6159452a86ded1.nq.gz
│   ├── de822bff5ed2c587ec907f021b7feba828feddd2.nq.gz
│   ├── de94809cec23d66a31e7df078e0363bf0aeb2e64.nq.gz
│   ├── e185c20858d1bbd9c79bc7df33f6fb4972e0acda.nq.gz
│   ├── e22d0d585d271d5d1a6b5e29a5850ba9fcaba635.nq.gz
│   ├── e30438846a5b6c0a750fbee807d4895a95e00540.nq.gz
│   ├── e57ce0b691416110d7a0363aaa1baa7ab33ebb31.nq.gz
│   ├── e9d7bceca93415da29b7bd32cd5dd279da2ae4c9.nq.gz
│   ├── eb1905356d02f8dd8f118ed60fae7caa98f9ad16.nq.gz
│   ├── ebde3745885db680eb6421c5d1247d3a70921102.nq.gz
│   ├── ebfa1bac689966116ae4ca987653e3ce9220dac5.nq.gz
│   ├── ec17087abf1c1a0a49b99a8e6f677bcb35371055.nq.gz
│   ├── f1509da7f06cbc35b878b24650ffb801ed683187.nq.gz
│   ├── f2a7ce37f7b8b1139140c223c1b26068df772169.nq.gz
│   ├── f306970da4a9780365cbb334216290e2831762d8.nq.gz
│   ├── f416ede82b5e425c3ec6cfc120c22b06495ca693.nq.gz
│   ├── f49b3fd5f88328102713c91f2927ce760a091e1e.nq.gz
│   ├── f6867d416d6cc6963d90a64d8848bf5abc3b4b41.nq.gz
│   ├── f6d44bb050dd7d7350cb7ec5fa31ddd845efa3c2.nq.gz
│   ├── f782b22b9cb3cb985ec063aea8a770c849b2030c.nq.gz
│   ├── fb3e4a2d296b86ff29c8c16917adad084ff6956f.nq.gz
│   ├── fb8547c3e423e2539970c8fa3154fd092a43a1c3.nq.gz
│   └── fdf9a1bf9b43daa509b8d58e05f34141def58221.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 57aac6bf4861b89eadc67f0dc061467e715e1ae6.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 109 files
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

[agronholm/lets-encrypt-azure](https://github.com/agronholm/lets-encrypt-azure)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
