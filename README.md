# Repolex Knowledge Graph of block/model-ledger

RDF knowledge graph data for [block/model-ledger](https://github.com/block/model-ledger), parsed by [repolex](https://repolex.ai).

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
rlex download block/model-ledger
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 93be51a248ec70c3f8bd5cf21214ef330822147c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 93be51a248ec70c3f8bd5cf21214ef330822147c.nq.gz
│   └── repolex
│       └── 93be51a248ec70c3f8bd5cf21214ef330822147c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0020fd1a4ac39163550ecd7b71f4973081d89e7f.nq.gz
│   ├── 0475772cfb776d8bc2d01040a131fb58bc2ce9da.nq.gz
│   ├── 0617f77e4819f1a0be46f24ae8b28a2c75e81307.nq.gz
│   ├── 0793912b5f280077a82c628e16c8d11a1da7062b.nq.gz
│   ├── 086ad3096e7d19da9b27dcc5ad1e774d720ac86f.nq.gz
│   ├── 0960a021eb45bbbf277528f55aff70df7d9a863d.nq.gz
│   ├── 09e5afbff79a79bbc74253df0ff6c5dff9a4254a.nq.gz
│   ├── 0d7ccb16536ff7482f4a30a9b05a84573df6390a.nq.gz
│   ├── 0e91d80a9857e91edc443e2049203891572fd1ff.nq.gz
│   ├── 0f3ef20f8e873fcc252af39a004d20d2a4ad7ec5.nq.gz
│   ├── 10d5c474f4100aa9ecac8eb62c7225717575890c.nq.gz
│   ├── 13356d743ca6c63940263d8f1e2ea883e5e2e359.nq.gz
│   ├── 14fdc8264c2fd36465259da7e96182ca9dfa187e.nq.gz
│   ├── 19f363e6b306c8c84d6af284200e399c8a1ad94d.nq.gz
│   ├── 1caf3fd07e95071368ac8ff6fc92050b77141fce.nq.gz
│   ├── 1ddf00d2b5b6ea58aac8ea1a4de42a7fb322a2c2.nq.gz
│   ├── 1e014ce819622e21561b49aca7cb7a73b1c22071.nq.gz
│   ├── 1e5bd23ddc01cee2f2403ab139f3b5af08c0288a.nq.gz
│   ├── 201f70b0d6d1f2f7eec4e12ba3a019a712840f07.nq.gz
│   ├── 20a936adff89c0751e96b416d6790f861c24d758.nq.gz
│   ├── 20f044484f7f8e25a9c27fbe54b815c84b747dd0.nq.gz
│   ├── 22b818d2d14538ffa8e3fd874259edf4a53684f0.nq.gz
│   ├── 237c3e3d5ea4dcd2a7617f0271b3c37fee637770.nq.gz
│   ├── 24a3dbc59fe52f451eb59f9a496a36d74b5c7fa5.nq.gz
│   ├── 262624fcdbecf594e42afd9e340e26d2bd14f04f.nq.gz
│   ├── 267c344b4772cf0e3d0a6f540066b5e089313925.nq.gz
│   ├── 26e09cb3787420e76acaa587960dfedca28dbcd2.nq.gz
│   ├── 2805f6fad920ce99510c12bb40a7a8f1851d1557.nq.gz
│   ├── 2806e70f0a7b1d1b46f741f5fadb3b7b637073fc.nq.gz
│   ├── 2815f6d07642fdd937cc68066963afe075f1b51d.nq.gz
│   ├── 2b30c4a3e0f4f95efd9d5c05cd6c61cb0a192ee8.nq.gz
│   ├── 2be8f125816f396ec0f1b9f96526e954d5fb944d.nq.gz
│   ├── 2c5399a1ce8ceba74818714ada0946d3fb248084.nq.gz
│   ├── 2e7e3fa8198641f74593a0db263153c8bb9f6b37.nq.gz
│   ├── 33a66c4f71e983ba7094c7bd75f47d406f42d2cd.nq.gz
│   ├── 3478b03f024361d5f49fc89d1f48873f150299cd.nq.gz
│   ├── 34ae4fe6868e5d680182a6e7a3792c74cef71ba3.nq.gz
│   ├── 35c55999e12514e65edfe4f4cf18de6afc7ddc04.nq.gz
│   ├── 36786a4ba7a9715cf4e7972342801bca2841d820.nq.gz
│   ├── 371038a957607f85ddb54afb5442401e6b91e890.nq.gz
│   ├── 387606b7a375eafb9b5ed142d87aeab87ad39817.nq.gz
│   ├── 38de24d9dcd1dfae3cafb3d8f7b99649c0e72a4f.nq.gz
│   ├── 3982dfbe08a5b450dfeb033c3a0827fbf26f4274.nq.gz
│   ├── 3d3c915229b7da9b909a7657fbf0244375f2794a.nq.gz
│   ├── 407439f234b3b74d4e2883324f126e6d2985aae1.nq.gz
│   ├── 4097e55abfaebc5f3735b8cd4efe5b37c1926b42.nq.gz
│   ├── 40c7ca677746cd83464ffe4b3a866a0df4767c26.nq.gz
│   ├── 430e265081bbdc4b1455cdcb08e3f28489f453ba.nq.gz
│   ├── 44001f4e0dec4207c11eccae5677fed3bb632a49.nq.gz
│   ├── 44588dd1f3f08dd75f0366bfb27512dccdbcbdd9.nq.gz
│   ├── 4494a8a0c07e8ecfcf67c923a36f66264543813f.nq.gz
│   ├── 48ce61f1348f81838e5212fdcb7981035c168d7b.nq.gz
│   ├── 493861230c4cb354392e858258a0275f3cad9e40.nq.gz
│   ├── 49b8ad181e4f442e432e3ebd83c4e33529b070b6.nq.gz
│   ├── 49d6295876f33e93e509f0d8b167ad3b134cf8ad.nq.gz
│   ├── 4af3958eedafeccc3669161f3cd8bbe443dfa0f6.nq.gz
│   ├── 4b2abe8a35a343a3afe528fb752142c0ff984814.nq.gz
│   ├── 4eb6eeb520fea41283b5b1c9a5c15f946555f98a.nq.gz
│   ├── 4ffa3f47797587ae33932b428b8317a62bc1185b.nq.gz
│   ├── 52b738096f55a6787ba1d31cdd3ddb7eb0afc4a4.nq.gz
│   ├── 5463d36ae27a7cf0713b0f491931a4603373c528.nq.gz
│   ├── 558ef6fdc8e8ba046c4f7d5d34754bf5e9a3c1fc.nq.gz
│   ├── 560459d7ee602413c067ade5434ba2662b81f57b.nq.gz
│   ├── 560691b3a131153d10358fa709dac5ceba05e6b5.nq.gz
│   ├── 565fbe7a1d44a2194096d5b099f1c794b41b8f01.nq.gz
│   ├── 57041d57ae4e874dfb33c6c2f1db1e6139a54a34.nq.gz
│   ├── 57e8989d30dad21379c1c37f43a110f408bfbf75.nq.gz
│   ├── 57fac961d16d0816234f44047b6f2d36bd045ce0.nq.gz
│   ├── 5c7d4eefa5a4bd8329bc73f79439c60a4dbff599.nq.gz
│   ├── 5f7613be3caff2c81104f591dc08a2c775461620.nq.gz
│   ├── 6096d5f3bd760578933e42a2f205a4b07aef6d41.nq.gz
│   ├── 62c084d6b1cc23144c3cd0fc1eda623b887603ce.nq.gz
│   ├── 63cdbaf22d87fb9a3cdfd29178003561cc474276.nq.gz
│   ├── 656b08c491a7fa0030c0b4441fe20b15016c1c23.nq.gz
│   ├── 69b26d1b36e63cd4d55ba04525949246881163a1.nq.gz
│   ├── 6b6c2c6eb402acdeda8cbce9f379e274c2429e95.nq.gz
│   ├── 6cfd5053db5f39f9b32e888e485fc28968b2cb54.nq.gz
│   ├── 6e7992c6165009d60631cccc30664e95b3416c0b.nq.gz
│   ├── 6ebfc654ef71fe42587b8b5150f184e58168f8b4.nq.gz
│   ├── 6ef91514bfd47b899fd79804c08cdbed26fec769.nq.gz
│   ├── 6fc40c2f058108724e866776abffb7ed5d81ae9d.nq.gz
│   ├── 72039f6db2a76901e85f47fcb507a27f373d5e7c.nq.gz
│   ├── 72df97c7d80a8f6b854c1b950f70bf8b94d4999b.nq.gz
│   ├── 730de19c4b7414659ba92b2cee2168ae33340d2f.nq.gz
│   ├── 730eea81334e094b049ace9e91a287d7be8afc95.nq.gz
│   ├── 7312913b516591cdd1de0fa268d34d0716891952.nq.gz
│   ├── 74a37886cea1a1c634d077370fc24e3fc2387d86.nq.gz
│   ├── 74bf0265d8db32368dc227916fb3504071b22e60.nq.gz
│   ├── 757723f1074a754f393b0f48ed3f46f7ccdb8279.nq.gz
│   ├── 75bd1fa122efc4709d47e03afcb588ec9d29c9df.nq.gz
│   ├── 776d1f5a8b0085d11648efbd2637c6bf80f51853.nq.gz
│   ├── 78f26384230b2dd96bf06810577ae5c2cf5e98c2.nq.gz
│   ├── 7ac3bcca82138ea4eb6370bc49eb5d4901df341e.nq.gz
│   ├── 7f6c661457bb420b4989a5cc20d0d5ed193492c8.nq.gz
│   ├── 7f9a739c03e4653191176c84a5ef583ee4094d5a.nq.gz
│   ├── 803c22cf8acbdcd667b0e75055757a64f7f38849.nq.gz
│   ├── 80729ae1b76e32c0ad227212bed9dee327b538d1.nq.gz
│   ├── 81efe9c875ced9fffbae400b02125ec8c28a13a0.nq.gz
│   ├── 824decb68607790ee39ea678915d61513ca5a818.nq.gz
│   ├── 839ac465ac32bbda7efb4f3c3776da71e03728a4.nq.gz
│   ├── 8468bf83aa5d3cf1b834133a243b3839640ce614.nq.gz
│   ├── 84c57a4c67e0b4d3c02ff76cd4fee988fc7e0658.nq.gz
│   ├── 88bb045c11d3066386ac61abb1cf0766a6583367.nq.gz
│   ├── 8aa62731d9ddc3d272ce92155ae5ce75a76a2aae.nq.gz
│   ├── 8c478453a1a2fb5531f20064b6dbf9cf29ca7d7f.nq.gz
│   ├── 8e77560a5a57068ef432cc538354529211d2ed75.nq.gz
│   ├── 91d951b2a8f1360ce3648a98b2b689ddc179b38d.nq.gz
│   ├── 92eff132cbb23e903c0dd7ea5b1557148eb5449b.nq.gz
│   ├── 93de1d88383d32a5d64421444627635a111a9d25.nq.gz
│   ├── 940c61355297d0c22cd62127bd704192da939b48.nq.gz
│   ├── 9436fa76f784df92fccf7dd07970bb0d3cd154ba.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 9b541cbdd27b4180042bb247bd86d683728db0e5.nq.gz
│   ├── 9d1453962d1dcc8cf9bf4f528a998b8b9fc1fcb9.nq.gz
│   ├── 9d6016737a025986c1a61b9cc0c97fb60f551100.nq.gz
│   ├── a03cc7835c8137c417537607a6f8621b65d665a2.nq.gz
│   ├── a0f2f88036052229e0dac52d207fc4c4badbde10.nq.gz
│   ├── a1fc22466c170fb99b19853870709c03f5cc5f38.nq.gz
│   ├── a43ace4fdc963aef6a6cfead78a4376b3c43184f.nq.gz
│   ├── a46196d4fbcb43cd3b2f64a1009d2553862f5024.nq.gz
│   ├── a7a94132845fca64d56d97b31f4922a9e6d312c6.nq.gz
│   ├── a7bc9a578cbe3cd43c0ba3727ee0a2e34bd42b9b.nq.gz
│   ├── a7ca341d63f2c2c7ecd28b51c9440348d3d88bc5.nq.gz
│   ├── a874def029f92ea1484b95848ba8cb10a60ba02a.nq.gz
│   ├── ac60e3c86434376766b1ac932cfdb545afb73a2e.nq.gz
│   ├── b321e50f8d1363081532aaf6489ef3708bbd3206.nq.gz
│   ├── b3dc4a56656561120c1ac8f6d8fbcc854113b9ba.nq.gz
│   ├── b6a3bb0fb2babc89103c8139a6ceae51b4fa43b1.nq.gz
│   ├── b70ba7e0238794d8314c07247353eb1aff37b297.nq.gz
│   ├── b99926e04dba72ae6aa64f29c63f25a4a3407ea7.nq.gz
│   ├── bb9db59b42be3abe418cddcffcc0cb2cf0413c33.nq.gz
│   ├── bcf7521f31dcd4ccfb7f1550943637ba1c5ec8fa.nq.gz
│   ├── bdea3186d1ed64f786b387a9c883266b495efb4b.nq.gz
│   ├── be34b9bd7b1d0955c646a62ca7f928697c9fc560.nq.gz
│   ├── be763ca930024063cd153088493e06387184eb3d.nq.gz
│   ├── be84c4c855eca73ffb6c375c7afa08582d5f1352.nq.gz
│   ├── be984840bbed9b1db6bfb3ba644fe91cb22296c8.nq.gz
│   ├── c22a6bee027fa2fa64be1d8673fdca90854fbbbc.nq.gz
│   ├── c2bf18445d1b91f721b118e10a8667a53f7b01d4.nq.gz
│   ├── c352c08b762eb80443f52148167c018d6e7f0e58.nq.gz
│   ├── c37ec718a47755ebba4b2c835b14d134e5f46a14.nq.gz
│   ├── c38708eba0fd454df1a1283fe3bc5ee8adae757f.nq.gz
│   ├── c40ff64fb1b43d0297fc88c9ad7492ed93ca35f3.nq.gz
│   ├── c44f922e60fc8e58bd6f93616637d4d709b383f3.nq.gz
│   ├── c4bb23ce6c0c9daedf1fa65195107a579bd94775.nq.gz
│   ├── c663b889f1ab461adf7fc8dabfcdef9df11c0090.nq.gz
│   ├── c6c6987ff3e212e384e70e44b5da60d8fd962a24.nq.gz
│   ├── c6e446a199c440503791215ffdf1edec8470f80a.nq.gz
│   ├── c88738109806cc52cd70c57a375869b97edd6da0.nq.gz
│   ├── c8daeecc38528bb8d19ddc4a842bc825ef57d67a.nq.gz
│   ├── c92e1eadcbeb1de436d087577883835183f9f241.nq.gz
│   ├── c9f3757b6112317640478f867a3a8c0129fe6f96.nq.gz
│   ├── cc4b0b87421c53018e4c5422ab17ae6f180aeb16.nq.gz
│   ├── cd46b927a43b8829258b76861723985a19bd0980.nq.gz
│   ├── cd6197011ae0c75eb32fa6a7a685229b5c7b2cce.nq.gz
│   ├── cdc163921eff1160b276cfd3e1b6177f5c81cb28.nq.gz
│   ├── cf07f3b01664500c0a43ec816046a39b05acb0e8.nq.gz
│   ├── cf6ceb6418378467c0996ab5599b2617905ffd30.nq.gz
│   ├── d0591b090442e42f2b6999bbe20b057936f7866a.nq.gz
│   ├── d2bc4a7a4389eff2ed18da04cc03f543f3465419.nq.gz
│   ├── d3063ec634e1a2818c3845c2473b815c3ee8f75b.nq.gz
│   ├── d50ec3ff05a19438884e595701aa5011ed70762e.nq.gz
│   ├── d5dc25a5bb45f9d307d36a529af359bc36972065.nq.gz
│   ├── d711cea68c38fa908e58da9bd239f01579b5f2e8.nq.gz
│   ├── d8b400c870ce2deef36a75064df48baa96e7d759.nq.gz
│   ├── dba899cc29d99ba7ab088929089f7fe3e2d635c1.nq.gz
│   ├── dde0476b14386007ede44f9eef476cfca4645128.nq.gz
│   ├── de11efc4e6fa8397ce3b945c8a702e9477acddac.nq.gz
│   ├── df0b3f11b2a5764240edae5f2860d9dff556305f.nq.gz
│   ├── e0bb2867ebac5724f21e107201a95c5dea00712c.nq.gz
│   ├── e1a14e1469bd7b722ad6b613d7fe2d2fc87a187e.nq.gz
│   ├── e267ef543741800a9ed699cd0e622fd9492cd051.nq.gz
│   ├── e4728db9e4703a0a9d48e1741b3532cb97b0ee87.nq.gz
│   ├── e486471bd63a5e6bfb0e1cb7b798d7512d0c7742.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8831144673ac647f142001c214c748eef46dcc5.nq.gz
│   ├── ea7df9be2f4bca620f1f43d57354e408e081c6ea.nq.gz
│   ├── eb33cca3df54ac808310e8108cf288ef43c13a07.nq.gz
│   ├── ef4e511919c79883266c208f16a3903a68fc0807.nq.gz
│   ├── efbd0aea2d95a4dd33cc420154b724c2301f021a.nq.gz
│   ├── f18ce1a97f9fcc948af77f147766d7ca43e366db.nq.gz
│   ├── f287ba919a4111e8ad31e3106ad37d8098bb6522.nq.gz
│   ├── f3d4dd1357e2677a8ef4fd821137f7192ffae99f.nq.gz
│   ├── f787be7221c2dd5638b104edad9cf17eea90211c.nq.gz
│   ├── f9d49addc281ab65456834c26f431d120a135886.nq.gz
│   ├── fd2f5317b34b4d7d84be0544d82e209aaf58d714.nq.gz
│   ├── fdc524b439ed526092eed7e81df00a82ce4b60c6.nq.gz
│   └── fddb6737d07e0573d4c549a7fa8804ae1a606dbf.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 93be51a248ec70c3f8bd5cf21214ef330822147c.nq.gz
├── filetree
│   └── 93be51a248ec70c3f8bd5cf21214ef330822147c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 198 files
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

[block/model-ledger](https://github.com/block/model-ledger)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
