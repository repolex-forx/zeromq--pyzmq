# Repolex Knowledge Graph of zeromq/pyzmq

RDF knowledge graph data for [zeromq/pyzmq](https://github.com/zeromq/pyzmq), parsed by [repolex](https://repolex.ai).

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
rlex download zeromq/pyzmq
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1cbf63a7910b77483dd53265b569c1137e8a01f4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1cbf63a7910b77483dd53265b569c1137e8a01f4
│           └── chunk-001.nq.gz
└── blob
    ├── 000562239fe0c719c781d8c0e66b8ab08ff10f1b.nq.gz
    ├── 00bb32989dcfbc787760075fd6dc4801568ab0a2.nq.gz
    ├── 01f6d88c5e4c536777d40d3a649e22e3d6f6c239.nq.gz
    ├── 027d4f94e9423eca7d408ed0ec845db55de215cf.nq.gz
    ├── 02b140b8314e65101764b3df69665080d121b249.nq.gz
    ├── 0402964bd72f2a956774524b2281bf81497c2874.nq.gz
    ├── 0470081f62d5af5ee3ca932504c41d35bdf7f0ef.nq.gz
    ├── 04ee013d2c34a58db8db9d57ab6de7a856db3128.nq.gz
    ├── 059216b261a0bd72f5d17a508b0b5c6e2c1d9f62.nq.gz
    ├── 067bea81221ca30cdb196fd8476c1b39f0c954d5.nq.gz
    ├── 06eb154d0c07090c4756fe615c1cee191e06b6e4.nq.gz
    ├── 0768cdd1f0e9e92ffe52c631f29f05bf8c353eba.nq.gz
    ├── 0790e8f01dc97ee8a025bafc1737a99e29346955.nq.gz
    ├── 09850b8fd47aacd9dfc466fa782191773c35ebe0.nq.gz
    ├── 0aef770146115b4dc5699a71cabc1a4798f7f4fd.nq.gz
    ├── 0be52620830d598386d42d36a852639b39847861.nq.gz
    ├── 0cb78166ab5340d4d1ebeaedd64e1713ccc61912.nq.gz
    ├── 0e3e8e593a3962a9f4d9119898aba7afed04de69.nq.gz
    ├── 0e6cec9b1759f5d7feb0bd97c7212523605b8501.nq.gz
    ├── 0ea0f346675c2b95b7181f906274d8816cc9c382.nq.gz
    ├── 0ee584aac498a436db58b3ad630213d6c8ea90a0.nq.gz
    ├── 0f34f0ef93a8947e622b74e8ebedf79003727e0a.nq.gz
    ├── 105f2e467315b983783f21bcd41bbfaadeb21d48.nq.gz
    ├── 11356a88dff25e2f4b859eb15e2ac7dd9db60a2e.nq.gz
    ├── 128d6ee514f05447628c70d5839cf5ffec48039d.nq.gz
    ├── 147ffad1f674bf2ca4fffa0c78cc7d7bde6c6188.nq.gz
    ├── 15c4fb2ac7ccc2b691d2e00c808f46e3c4b6bb27.nq.gz
    ├── 15f696d9d3ad5275443eb3145b9c4087f1e6609f.nq.gz
    ├── 1864aa89ba65be57901b4753a9a118058b1d355d.nq.gz
    ├── 1b21bf42e808bfe9a25a654e3ed29591927c95c6.nq.gz
    ├── 1b3dbce2122bd00f04bc9deb1b32ea0e25df4d4f.nq.gz
    ├── 1bf2a0f23c89a7226438f5b23e32c8cfd6142726.nq.gz
    ├── 1bfdf845fe392e84fdfd592fc1bab3a01764bfd6.nq.gz
    ├── 1c34568dbdcda09bf02696c44a6fce1acb2ba88a.nq.gz
    ├── 1d8b6ad02681ae6c6cfbc6230ef2234a8a73f981.nq.gz
    ├── 1dc1d364c9254fb3edcf059aea62e934830b045a.nq.gz
    ├── 1e3774468806ba273fd143f5e8ae93da65d3d306.nq.gz
    ├── 1e77dfad20053f88ae5043b642e4c16dc1251549.nq.gz
    ├── 1ee797c4df4d7d4d93356f89c166c32079a28bfb.nq.gz
    ├── 2001e670a92761a5c3a10e40d93f39e2c21a3a10.nq.gz
    ├── 2071b36f58625fb8d3b16760c5053748819083c2.nq.gz
    ├── 2113a8681d6b5fd736e83e7b599d2d86b3df2e53.nq.gz
    ├── 218aa63382292583a52b24f53a79f336001ab777.nq.gz
    ├── 22121bc727b8992d9c0d7affb03f55b9958801ba.nq.gz
    ├── 222abf648085eda76502cf8f66253237cc083a25.nq.gz
    ├── 23a69ecf1d97c1353470ebec03601370b8a5eb73.nq.gz
    ├── 24c68587f3b0159845af819b9c4163d21f0f7423.nq.gz
    ├── 256a1e0498c907791da79935c7ed0f35faf90ce0.nq.gz
    ├── 257f4a9f6469dabddcc963472048169d862b81f0.nq.gz
    ├── 25aa48825daec11cf9a0880416f1a62c601d59a2.nq.gz
    ├── 2663a8477594b6fc7bf26b1ffb9edbc1ebc0a375.nq.gz
    ├── 274b736ea0f8bf3b364112c26b55230b88636520.nq.gz
    ├── 27baad46e75626d68a0691b6c89ba0fbd7c353e2.nq.gz
    ├── 27fb1b77b697f1c6a214b99f484462ab95467331.nq.gz
    ├── 2b6dc06cbe6b4a1b0ed5d4a34f7ef3a60d42ce74.nq.gz
    ├── 2e0730ac96ada562aa17c3ad1baa10d3631f28e7.nq.gz
    ├── 2e88f58ebf39ca3044668cafa663b632faf17a2c.nq.gz
    ├── 2f17ff441fea7aa89290366d2c89d4982e909602.nq.gz
    ├── 2f455676bccb97e77a86547013ccd76cd9a08143.nq.gz
    ├── 2f71edc3dd2a831a2e9e561c613fcf31123fbd7c.nq.gz
    ├── 31aa5062d0e63345b90e2de7c311a50f66a286d5.nq.gz
    ├── 3228ea151da2f00ce7d5f94a92ab7e54e33ff5db.nq.gz
    ├── 3350456e7eaf61d790e2307b801d1b36bba7c730.nq.gz
    ├── 33b03d89de15a6d0ae2dc9ae5b96f213c0abdee0.nq.gz
    ├── 3464f2074800c17276eedb7feab314b9a7301db3.nq.gz
    ├── 37b8362e2a07a77d41ff9f6d3b589364a5e00a05.nq.gz
    ├── 38242ec71ef36b1db334006e1b2b19f32eb475e8.nq.gz
    ├── 390909ac0bbab66e6109b758f53ffea52162d007.nq.gz
    ├── 39ec7e833d61ba396b3c4e32f16c5cdfcd89acb6.nq.gz
    ├── 3b92dd07e5d946e956da782e48d50ae0d4a810b0.nq.gz
    ├── 3d06115085ef40bbe0fe53ef75fa7c04b8a3bf65.nq.gz
    ├── 3dfaae8c4d2bbc2319274d04cd8dc5915be6d3da.nq.gz
    ├── 3e651af56ba8558a92c0f830c6f76e17af7627e0.nq.gz
    ├── 3f810a1f40c75e2f786638e8a0c6e6d5f7abcbde.nq.gz
    ├── 3fddcfffe7d0454e0f40470b7cf038e849f063ae.nq.gz
    ├── 3fe1bec4c24ac472fb9ab8940da43adc1de60257.nq.gz
    ├── 3ff71504cf7316197e9e8997afa9eb718c68b727.nq.gz
    ├── 40addc495baf7d832d0c59c16f02ab7856401c2d.nq.gz
    ├── 40e364af9fb0aae90fc9eb2038449987f05e6051.nq.gz
    ├── 40f3a2aca4fedb25ad860addf88204bd36688755.nq.gz
    ├── 42a255c7a44c2cd431669f06ef28d0b3efc3f6bb.nq.gz
    ├── 45b55536ba48578df80bf46f61a6d0e64b636bbb.nq.gz
    ├── 469a4ae76c7c0e9a61985f801f3f1c8e1f9fde0b.nq.gz
    ├── 48274dcddf52153ae2bb939c724f789fb49d3091.nq.gz
    ├── 491a2b5c666d2a50484404597f7cf933ffbaeb48.nq.gz
    ├── 492922d961da76b403c9bc698c301919070f48a1.nq.gz
    ├── 4a004a52e772cbe3a629d0660ba7e06b1232631a.nq.gz
    ├── 4c1b87d4d1f6fc3309447ee78f945c80dd9c3288.nq.gz
    ├── 4c4c2edc6b0e3e59a8d57b393ea8ddcd9003eddf.nq.gz
    ├── 4d5cb242544edd25ca41fb56697a0f9c38b46570.nq.gz
    ├── 4ff6f450c065e82146ac23ad385528ab49bd0f74.nq.gz
    ├── 50e9151469570311c2fbc6af9fbb8d04b2d594f4.nq.gz
    ├── 51ca3b7c1a538ae7a8aa8fd672c34687d150738c.nq.gz
    ├── 545d1ca84a525edc90d395c4b7cf5bd3f1f4ce9e.nq.gz
    ├── 5561394ddecc5a47c3767f6921cfa80df5f6a3c1.nq.gz
    ├── 55fb58ec877a08a2126cbfebd5f39174476c8290.nq.gz
    ├── 57a65c634933043406ed9e2edea85d888a476bb6.nq.gz
    ├── 57f09568223c48babf9c9d7745218f7e33290eaa.nq.gz
    ├── 599d26a26b747dde8baa3006366873f79a0ceab3.nq.gz
    ├── 59f68337f4a7c90992f45f06ed661f392ab3cdd3.nq.gz
    ├── 5bec6dc081b153d2a65f7200575f75e779d9b259.nq.gz
    ├── 5c20d144c04d29aad9630f4513e2b0554a06d47d.nq.gz
    ├── 5ce9c37ed0cec75900efc5ad2029fb98e4a8b78d.nq.gz
    ├── 5d65dfedc63a7478e912c4e87ca2098c5cedd3cd.nq.gz
    ├── 5fbb4ce97e0216cc802f6a7140d3091263eb3a6b.nq.gz
    ├── 60192deda546fbab634d26a0e31b18f32e7ec6e1.nq.gz
    ├── 615b698bbebe8ec3ec2a033ea7cf2108c07b0e37.nq.gz
    ├── 6236df3311f6a2941fc2f4fe7869b1d00c5389bd.nq.gz
    ├── 63e2763b9c57b065b963df9b0a1f86cd9fe30af0.nq.gz
    ├── 658cd0b70c18416b2dbc73de4537d45fa5da2ff6.nq.gz
    ├── 6717a5fce1d618e1e02e0edfc09f040fb64d7a9f.nq.gz
    ├── 691be3c782d3d8209dc67e12d241e749e08440cb.nq.gz
    ├── 6a47dad909a62cd28044f88a1c8eb0c7062f7ea9.nq.gz
    ├── 6b24bfdafff6083aa36e93ab19641b6f3bee95d4.nq.gz
    ├── 6c4179a80a3165e15a6f01b602d0281e64254e06.nq.gz
    ├── 6f8bbc1837450a2b3011094041105f9fa2eaa7fd.nq.gz
    ├── 72769da1a4f1a7f9bc4b233a6a74e17d1d0d7ac3.nq.gz
    ├── 72db79b375ebf8449e9e0190547d5520019d45ce.nq.gz
    ├── 732c4277cc45730d3cf09cccd192cfb899eea90d.nq.gz
    ├── 73ce62f531da4213103e0d241d6631ba6a63032a.nq.gz
    ├── 73e86f0995a2707542ec4ad4f56c99d1fc31862c.nq.gz
    ├── 743545ba68ae88abaf7c99c3fd7c04b481ff5c9d.nq.gz
    ├── 75d3e308243a16b8c2b219d1931bf6a970146e91.nq.gz
    ├── 7796e517633ff539cfd4d2d6ed2562456da07a69.nq.gz
    ├── 78c784432bc037049700de8556d75b68fcc3d12f.nq.gz
    ├── 79bd25e9c2e35963297b60602472c7f92298a9bd.nq.gz
    ├── 7aa1bedd461aac26c26978b29e6e92ec0242dbf0.nq.gz
    ├── 7af9a261be4be890aab7df2b570d59e09ff2a3e2.nq.gz
    ├── 7afb8dedfc92e58863f092f967aa44f3505e1e28.nq.gz
    ├── 7b8b84564195689cbfe2057a5579887574b57ea8.nq.gz
    ├── 7b958bc579fb322420a624c524f81e2b7dc2dd12.nq.gz
    ├── 7ba074b644f766183ee54a27864cbcb2b9b34da4.nq.gz
    ├── 7bcc5629964e3c1fb19cf042c4ec4e16444ac8aa.nq.gz
    ├── 7c5e499fb511d6d8a0a1c594a55669b932d8f3ac.nq.gz
    ├── 7e5266009c7bb1a1671e277965a77bd153c65d3a.nq.gz
    ├── 80f0158c633ccc1b52bdeacbc7494e1a05fded39.nq.gz
    ├── 811d2a84f56f1b96d98a3f4a57cfbacf50c69a08.nq.gz
    ├── 811e79d238ddc8a9520dc63067c92ff417dceb6c.nq.gz
    ├── 81b4f7b6928dcbed48216ad7a6a5c152160409ec.nq.gz
    ├── 81e656939c9fb07a42eef4e3099af252a1e6a5de.nq.gz
    ├── 827c574c48830ef1cd558cf1258bcc55400fec9b.nq.gz
    ├── 8365a3fb1a7bfcc5a5ff1ddbad2ed653ebc19d81.nq.gz
    ├── 84a010370561105e5fc202121c4b5a455c61aec3.nq.gz
    ├── 86891292bcdd144e1f0d15faae486a31c6a84911.nq.gz
    ├── 87a9fcefb62194f015273fd8200ac1f52f9eb4e1.nq.gz
    ├── 887ed925caace51b0493d9d11ae1487fd5d934c7.nq.gz
    ├── 88e755682c1096272830c01e37ef71d822ec1b05.nq.gz
    ├── 89ae9db8f88b823b6a7eabf55e203658739da122.nq.gz
    ├── 8a90241855b668733ca4aa17af186df1fb582e3a.nq.gz
    ├── 8b4915c12784538761dab70cee8e34395a1df066.nq.gz
    ├── 8d5619e2015c8c63572b9495babdc50e2fb84e59.nq.gz
    ├── 8dcc1c50d5ffa605630fa60aa157ff6e8329cabb.nq.gz
    ├── 8dcf7863d63a72fb943a01ab2980ab6d9a607c01.nq.gz
    ├── 90293e55b50c365164c850bce65f2de831e8a50c.nq.gz
    ├── 9094453b6bba12033764aa550750ba4a0e11f36a.nq.gz
    ├── 90cc18d40429a24f189b61aff67b1133521997ed.nq.gz
    ├── 9177b51af922727d0283afaaec724e8120e93c28.nq.gz
    ├── 91927ec6451814d55fd2be65866fc2df633a885d.nq.gz
    ├── 92d599830771984e889625ba47d8d2f1b649e6ca.nq.gz
    ├── 94bb8c96fc7c2a79cd0b20dda2abca5643599c4b.nq.gz
    ├── 94c7f8a3fb3b246dec15c64768147889f6593579.nq.gz
    ├── 973fdbd6e2740951969e0f071dd07837cad1d632.nq.gz
    ├── 9833a1b9d2bc5d66207e782773c2a09d8878ebcf.nq.gz
    ├── 98f7ce6208af75fa666a2e16bf25892ed2474d62.nq.gz
    ├── 9a4006a4181cdbb0b9c7b409fe0b8fd176a51d75.nq.gz
    ├── 9a762c77b67374e916bf8b3a05c8375e89464f2c.nq.gz
    ├── 9a799808a40078d965671c0c3daa29f29fd3a2ea.nq.gz
    ├── 9ad31412115b26b9640efaf29d6ac708c20df40f.nq.gz
    ├── 9c6f90088602e71f4583a886b929a73026bbe509.nq.gz
    ├── 9ca12f580b8e79515ffe8c5d611937c82951a40f.nq.gz
    ├── 9d63cce44c7ffe9a8eda5b8aa0a5771101c1e4d1.nq.gz
    ├── 9fb2241ee103e06e4c022e2dff3dcc0b3816dbf5.nq.gz
    ├── 9fd6956ad35a1ff951ff5fe2a5048056c442b928.nq.gz
    ├── a11ba79d109f310b9de26067e852262ee55e2a12.nq.gz
    ├── a20ae45d783e1bfb0aadedec9cbf9f09b112da25.nq.gz
    ├── a30314d8dab231af3037fc5661ce455356b3b5ee.nq.gz
    ├── a3967cb3cfa4f0712a3685138c3847f6c789253e.nq.gz
    ├── a40068461aa61a99a23f80d54b9098d705570494.nq.gz
    ├── a45ec00bfac66f89afe213a328bf039fe8e46099.nq.gz
    ├── a5d2d347ad61bc6955500957aca2b8f32d6a0308.nq.gz
    ├── a75e890baab0b163006d4ba0184c1a2bfdde2348.nq.gz
    ├── a7e4f244294c6d954fb8989bb161dd25dcb36a6f.nq.gz
    ├── a906be6e8709ce1e16ffedd231d2aff872978ba2.nq.gz
    ├── a96c3f67a1d4f283de9365cae259c7860c94c40a.nq.gz
    ├── a99e143ccf3035db55cb5a34caa13e98ba793e9a.nq.gz
    ├── a9cd40e495928a11ebb3373f95b6eeee17a58c10.nq.gz
    ├── ab0326be0b64dc82b37d383fc6dd5687b6219eb7.nq.gz
    ├── ac66cd3e904775306341b74809ea078a4e55a4d6.nq.gz
    ├── acdf8572bab032c77aff90544a5463ed8d117aae.nq.gz
    ├── ad5daa5163b7f6b39beb9cc7f1ae1b9928b788ac.nq.gz
    ├── ae10c786f20bb7c941828c872655b4cf20576067.nq.gz
    ├── ae3c3357a7cc033d94397c95cca9fc66c7db197a.nq.gz
    ├── ae9b63316f962c8f8d1f213af9a0482e9bbc0472.nq.gz
    ├── afb8d5671551b8ca824e33b068b8ad71be09ed9c.nq.gz
    ├── b0ef0272c4e93a6f7a9955e9ac16f9a6ddf148e2.nq.gz
    ├── b169a30b0759a56bca074cfa59129bfa1d69d73f.nq.gz
    ├── b1a571a01fd3fe0c5112cab5d415d18812afc29e.nq.gz
    └── b25d2d4974b63503d9984c2835d96904356f24ec.nq.gz

7 directories, 200 files
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

[zeromq/pyzmq](https://github.com/zeromq/pyzmq)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
