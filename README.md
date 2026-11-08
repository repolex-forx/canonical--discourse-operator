# Repolex Knowledge Graph of canonical/discourse-operator

RDF knowledge graph data for [canonical/discourse-operator](https://github.com/canonical/discourse-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/discourse-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d351212f17645e74658aac28ab40a18bf7050c75
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d351212f17645e74658aac28ab40a18bf7050c75
│           └── chunk-001.nq.gz
├── blob
│   ├── 00fb4a306ad594ba726fa0400c6dd727a4b43140.nq.gz
│   ├── 0107bbce542c97514be68c08c016c379830e4208.nq.gz
│   ├── 0297205acdc346d9903882d704acacce5e11d14e.nq.gz
│   ├── 048bf14b30d66085cb76dbd387216e2ef93568a3.nq.gz
│   ├── 0552d35ebc61186ac2b05e60f689ec29ca634f6f.nq.gz
│   ├── 07952403a085b4a1a93fb9a1f3afc120ab8d3087.nq.gz
│   ├── 07e0b48cbd1569fbf0e610fa77b6a4e96330574f.nq.gz
│   ├── 07f437e0f2bab25fa6f3d12c5fcb26e1289b71cb.nq.gz
│   ├── 09de764ae8e27594b8a9521cd0ce0e24dd1d8600.nq.gz
│   ├── 0d849605a4690a5c33a08cf63e2b6f49c8b80440.nq.gz
│   ├── 1285d0f20c6a582c833f74a1c914e0fe1fa2592d.nq.gz
│   ├── 1652342ff670823078fa1384b7c74f985f290db8.nq.gz
│   ├── 17b5e6c699f1498a743bc9ed7c7970fb22cce6ed.nq.gz
│   ├── 18460b65c8375e4a5b1d3b0962e9cfa537dd1834.nq.gz
│   ├── 19bcfdd0251136d37cfc9684f0b6eecb2412a90b.nq.gz
│   ├── 1b741a638b6ecfd344f69285568a32c283099e29.nq.gz
│   ├── 1bd9f14a238d5d94e7382df225c593a7d2d5e84b.nq.gz
│   ├── 2032f0ebb040d8d4a7a0536247e7faa9c7b38893.nq.gz
│   ├── 20c303717e6906903724085e9f5bf8af6ae253c1.nq.gz
│   ├── 2181fb71c16c4a380c9327e0d9fc517828d33e82.nq.gz
│   ├── 21d86552fa5661b5981668bf5eef6e9f5e69e5ee.nq.gz
│   ├── 2289d439ce48766a9cbe9a069f209f92679c4008.nq.gz
│   ├── 2668e37797c83804d4f72871fcf6d22aef24bc87.nq.gz
│   ├── 26b0b77ea53ca7c4bcc87a011ae0f5e28f5ad2be.nq.gz
│   ├── 272df9017dd2f62373ffadda4888f887dbb2f314.nq.gz
│   ├── 273c57e4e910576a73cc52cce3d7b2ad26c6d199.nq.gz
│   ├── 28b808c88154e25c9bd10ea556f7a373dddeff53.nq.gz
│   ├── 29d45c2ecef1155c5eeb129f7afa2d55a01162cd.nq.gz
│   ├── 29ede242ff455a64fa253000d80487a0bb723248.nq.gz
│   ├── 2a034ef9598e478d2aaeb8b8f7d9cc40fc896b35.nq.gz
│   ├── 2cf495dc99cd48b645642dc14e9b90497bd721dc.nq.gz
│   ├── 2e4f591fd3a3d77255e1e7544b48059b001881be.nq.gz
│   ├── 2e57f6998236295919e7f109b37d0f1e815ae94d.nq.gz
│   ├── 3006f13e199b573708dde2114878ca4fa8071aeb.nq.gz
│   ├── 3014a84f49e5da629a320e61b44bb11e73fea385.nq.gz
│   ├── 3372cdf832ee05e9662c2b38bd09673703f18820.nq.gz
│   ├── 3561e99ffb8c6654466d5b7a3df57531385aee5d.nq.gz
│   ├── 37473f2c122b3669ee891f608c9f5e0920b29b1e.nq.gz
│   ├── 3acd483c62cb3c43f5cd96888033aa968f7dea74.nq.gz
│   ├── 3e81c2b46a83b823938f762374244582b371a65e.nq.gz
│   ├── 4036c82187b951211aa0f9da7dd27795b793d74a.nq.gz
│   ├── 433a20b9fae46944ea3056789dbd3e490d38bb98.nq.gz
│   ├── 43b3cd2088024e1f35412da6be72fb40f60012fe.nq.gz
│   ├── 46486cb8b067308f8e9ce614e1d97facc26ea66e.nq.gz
│   ├── 46eb82a6ae17db1b363c99c3229f39e074307ece.nq.gz
│   ├── 473385ba34955ef7f9facd633acac329a0236bf8.nq.gz
│   ├── 47410c4eaf45036d119125038f6f44243848d5c7.nq.gz
│   ├── 47932c046a96659f81a4bc0fdc914b7231ad9669.nq.gz
│   ├── 4876c8651a05b8520ca53381dc9c08812b0bdfc2.nq.gz
│   ├── 4a9b47492cc42c59868cc8f0c91c05b76946a9c8.nq.gz
│   ├── 4c3ee53b9383fc7fd416ff159fe281591c15756e.nq.gz
│   ├── 4ee206acc01b26687fac8473e533f4a899c57c2a.nq.gz
│   ├── 501d932de7af80622aaa44fb52d85b9e9bbbe841.nq.gz
│   ├── 50e07740db92606e932722ca9c004403437a73c3.nq.gz
│   ├── 50e827767dfedab365cece6b219d7f2bb02477ee.nq.gz
│   ├── 52f1279bf9926fc3c07ed0cc74885348e6d733fa.nq.gz
│   ├── 549bf1c2966e9b3405f76dec0ef89bbf5b093e83.nq.gz
│   ├── 55969d643048afbcfabdfa8a3314e271294fff2f.nq.gz
│   ├── 57c8dfb9d9f3253da3f36dbdf3e82839e8b0b117.nq.gz
│   ├── 5d8e402c6bfe52b26bea61ad46771b16dbeac345.nq.gz
│   ├── 60c6f60a7a1d5a1658375cb3ccded55a7e98385e.nq.gz
│   ├── 62f61fdc3b380eab9c82eb397e10c531af8b60f3.nq.gz
│   ├── 654b145c313ce9f564bf142ae5443e87a2c35e7f.nq.gz
│   ├── 676e4483e60c782a4f472dfa0353ec8d03a06626.nq.gz
│   ├── 683bb8f15d56cc3126ce0bb797090959a86cef09.nq.gz
│   ├── 692c56f4812f42d08342d8a17dbcd577a1aa9d59.nq.gz
│   ├── 6c66a500075530d42aa60378821f35bc979154cb.nq.gz
│   ├── 6ded0cb89f3030f164e640f885fe774e3905287e.nq.gz
│   ├── 6f94cded4fec60283aa42d48789f2f779e32bb9a.nq.gz
│   ├── 71a5e573e5ccc058764eb47f5e45d2367fceb56e.nq.gz
│   ├── 728aaeda33fd462f0c22c434fdacf547d50fdc55.nq.gz
│   ├── 741cae38a3340055c8b764f021908e4e62041d0e.nq.gz
│   ├── 747a41f4107637941372097412b0e8f28c3eea38.nq.gz
│   ├── 76c5d2ad905cea370df195d06cbc391806b4085f.nq.gz
│   ├── 7c4a762177fda41726a88b0746cdb74b1d65f0cb.nq.gz
│   ├── 7d9a94ed6159a96ddce31408b4d2c4d77ec18773.nq.gz
│   ├── 8005711124e9fbe4abc6f74746d89d1f003d63c2.nq.gz
│   ├── 816c8e8bd3f0b68846bf0e16509f2e4efee56823.nq.gz
│   ├── 85a8bb9774f4ddaa5548304339ccbad6eeae9df4.nq.gz
│   ├── 86bc59f3ed321b9587b92bbd247e353c2f513226.nq.gz
│   ├── 8ac991d0ad5bb0614ace36482ee020a0dd0445e8.nq.gz
│   ├── 8d6dee6d69f73f9180c1c113c6c00d84804446ec.nq.gz
│   ├── 8f724a9ce3107ba208523a5aaa8e143fab163b64.nq.gz
│   ├── 90037962745add1ec638f1cf6080d413d0a28460.nq.gz
│   ├── 911d0f1d3239d34fca23742fb816b37be24d5668.nq.gz
│   ├── 92544b6d117bffa68a28bcd4a12222c20b53294f.nq.gz
│   ├── 929d59b7102686e923b70b64c95887f44b2a4de9.nq.gz
│   ├── 92eee7aef218a5f38c6cd0c5d234fd09cb26c00b.nq.gz
│   ├── 94c36227f86308a2bb33708930f51a2811749dec.nq.gz
│   ├── 96f1c9485ad9fd492d8dab46a7ab7cdc7c4e9ada.nq.gz
│   ├── 980fcb044e7b4cf53ff57f3d75d70e386b5915ca.nq.gz
│   ├── 9961dfcc90f0ddc998f8da17c77eecd6def9d220.nq.gz
│   ├── 999d79ac770f8f2b47a971f817436f65ade33faf.nq.gz
│   ├── 9d66e595abadf8f7e41b50d723f51a5571c20371.nq.gz
│   ├── a041d387000a2304bdc26ca2b2ac7cbb599ef76e.nq.gz
│   ├── a23f3ed30b633f98a94831e4292e57967dc56f87.nq.gz
│   ├── a2ec38ec4d1f71c31a803e808131bcb1c49095f8.nq.gz
│   ├── a36edceecb92ee280f1f4afb3bb493b11e2239b6.nq.gz
│   ├── a4144fa9d0681e2d5db5ffa011a676cf12b08415.nq.gz
│   ├── a43ad1c6dcb8d74eb24922d35bd3d89238238244.nq.gz
│   ├── a57a160604b95947a6afd3f932b97e6a9f0171d0.nq.gz
│   ├── a8a30a4d6c6a12bdb389839297a0ab3a01873844.nq.gz
│   ├── a8bb9aba9a7191bf7f945d6ffab2744021d25958.nq.gz
│   ├── a990a83bf38818a5742d21f3327fd1d25c4728dd.nq.gz
│   ├── aa51245755f6f3bbf0fd994138c70271e6d6e762.nq.gz
│   ├── abb5775c5db5d499d2093a971dc113beb01e7e15.nq.gz
│   ├── b09404ae6f93e66ea326ea68268b6c34c7a62fa8.nq.gz
│   ├── b7238f428373603affbe0074d0a76a90fca2a013.nq.gz
│   ├── b7e8994b89924481f9624f9a74d9f6bccb170ffd.nq.gz
│   ├── b7f78fbe33918cfd0d3f9327ffcc5a63cbcf3ffb.nq.gz
│   ├── bc27101088878049d58ec9dbece98f9a29e08b02.nq.gz
│   ├── c35eeef6edb2b5b31c6e6cb2616e3eb3ce89bcd5.nq.gz
│   ├── caf695b79046dc4bccce8105a5370a0891238b2e.nq.gz
│   ├── cd15e463382e13c09e0c589b7183986396d93193.nq.gz
│   ├── ce39142525ddbfd8146fc6d149b15ad8cb5f61e9.nq.gz
│   ├── d18b22661c4d49059b0cab8fff1d8b66261dcad3.nq.gz
│   ├── d2857fb4988d1021af72d6de32817c485de77071.nq.gz
│   ├── d2de37a0b67564255b2865d2e3d7e30965234017.nq.gz
│   ├── d3ed02fcdbaecbe70c51d1ab02b077542455944e.nq.gz
│   ├── d44ed887dc669651e82505b3b4f8114238862eee.nq.gz
│   ├── d46710a200c0acdb20ee739d74c0998120e358cd.nq.gz
│   ├── d5511061ecfa84b7dbc6513d177338883547b984.nq.gz
│   ├── d9ca2d90a8ba7e9d75b72adcff9cc52b47a1489f.nq.gz
│   ├── dde1871e7c4c590d979d42aed8703979ac623f87.nq.gz
│   ├── df541556b4c8b8d1d2040a3acdf1aa8872e9c1a7.nq.gz
│   ├── e28b14c2de9526b516aefaed241cc29d2a8c7bfc.nq.gz
│   ├── e4282b3e2d275311e613d13cddcd5e508d560d2b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e86264935dc72ace2ca8daf115442b875a4f1940.nq.gz
│   ├── e998ac001be06e6c5111459f34f0b9875c78ab6d.nq.gz
│   ├── ea10dfc152d56abbc8e880573969fbf0ea37bf1a.nq.gz
│   ├── ec26cd6741bbb64e3e4f5fcbb4b5e71903a197f4.nq.gz
│   ├── f03208f6bfbdd165c536129f1080a97e0c872481.nq.gz
│   ├── f14e636fae6ac409b427d8e77c8b0950e4d63d9a.nq.gz
│   ├── f15c9a5f5c7c688cb333ec1993992d8f1132ea47.nq.gz
│   ├── f2e77e2a27b3d352933bd70808a82437d2f18a74.nq.gz
│   ├── f3725536bfddec7d52254598205c3f52e03a3aa4.nq.gz
│   ├── f4a65fdd7c0714cb6e6d8696295f9c0110a5e870.nq.gz
│   ├── f4e30c56a97efe41bb7baa39ac822b3e4b4d694c.nq.gz
│   ├── f55165852a059c152540beb18231ee0cb151ab60.nq.gz
│   ├── f581a6d8536dbd702d1df1ddc7b572245ee05446.nq.gz
│   ├── fa89e9d7f0a34f12feec51eb28b9208c96d0494e.nq.gz
│   ├── fa941fe014095eb02d8509cfd16f8bcd3df62955.nq.gz
│   ├── fc6e00c56c3485255f7bcc300562c8f65072199b.nq.gz
│   ├── fe6468e8d0a1957aba024423c38b9eac57f996f6.nq.gz
│   ├── fe85c67c73e71c2b333cf3e4b5186199e5cefcfc.nq.gz
│   ├── feaa5b73b3d58ed87bf00e8001dcab3164005ff3.nq.gz
│   └── ff1997cf5bd6bcd40a7c067c27a5b604e4012ba2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d351212f17645e74658aac28ab40a18bf7050c75.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 156 files
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

[canonical/discourse-operator](https://github.com/canonical/discourse-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
