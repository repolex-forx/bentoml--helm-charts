# Repolex Knowledge Graph of bentoml/helm-charts

RDF knowledge graph data for [bentoml/helm-charts](https://github.com/bentoml/helm-charts), parsed by [repolex](https://repolex.ai).

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
rlex download bentoml/helm-charts
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 34abbcb4e548b17f67df717e88796459e8159b55
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 34abbcb4e548b17f67df717e88796459e8159b55
│           └── chunk-001.nq.gz
└── blob
    ├── 001769b8e3392942e981790baae0e6a0e8619b30.nq.gz
    ├── 010e2e598a46e540051bf2617ece994f879ae779.nq.gz
    ├── 014b266813f966b28f63654b9f7242178b36ef9f.nq.gz
    ├── 0206f73f80a796d6233df8951a1520b62b5469cb.nq.gz
    ├── 022a02516ec1f9cc7a82598c1fe3a382d0ba2ade.nq.gz
    ├── 022f9e03eaeae40908e4fe7d8d471b203db5dbe1.nq.gz
    ├── 024db923d3af83dcd592d3dd1021b2ea98b44479.nq.gz
    ├── 02fc28abb97dee18766332f6f51f97c9667c21a6.nq.gz
    ├── 03091860e32253dd70613ea6527276947c29531b.nq.gz
    ├── 042bec04e6d4644368a90cd4a350355c5a595510.nq.gz
    ├── 05e47cddc4c1de972d1f36658b6910ed21cd7353.nq.gz
    ├── 06268a7292feb07bc269bd6c7dd1dd3dd2b2efb6.nq.gz
    ├── 06fe4a2d8e060d9cf99a0b9722712e2659f80e7c.nq.gz
    ├── 07cd126cd3f58a863ffbd229e2fd7458c7742608.nq.gz
    ├── 081bbd266d6851f759cd6a0aba1357a23a5aab14.nq.gz
    ├── 0845bce0e368a2cafd5ca34f307175411c4b1416.nq.gz
    ├── 0880b1c8afbab7038295eab44d79be1be1638adf.nq.gz
    ├── 088f5051f95f12fd9582cfda677728cfc929eedc.nq.gz
    ├── 09216f5e0a4427333061dd06a2fe11dbfcb5422e.nq.gz
    ├── 093cd633bfc8a09a4dcce997cdb7a084760bc1c8.nq.gz
    ├── 09ad03de7a60982ab6188d84c054ff80874e9474.nq.gz
    ├── 09f98cc0a8dbea66c5d17607739c7fd855d2c5ba.nq.gz
    ├── 0a4dc1cdbd482a4f3aef6e23db455edce3cf724c.nq.gz
    ├── 0a6657ab487d6162987d5119bdc8a0261370da93.nq.gz
    ├── 0a87c23fbdf5e028f0b108f12672dd62a5ed9ca9.nq.gz
    ├── 0b14b32d5431bf95108cb52aecd7812b0f3ddc84.nq.gz
    ├── 0b311e93c7c1726fc655b9a6d7a108ff61a2df20.nq.gz
    ├── 0b31a5a94552aefc1513db53b862420a43139c72.nq.gz
    ├── 0b9282a16b3d0057fded94b3c526c62497057872.nq.gz
    ├── 0d0bfa2b7619033a5254196a7f1ec89fdcdaaf34.nq.gz
    ├── 0d3ddd58d9b4f5bbd3ee667c4b9907c56d8fb543.nq.gz
    ├── 0d8fe3a8aa0142cb8191c34b108cb238726825d8.nq.gz
    ├── 0da1aaf37020279978ea76ad5ec40dd260e9446a.nq.gz
    ├── 0ea0df1420bb5d4a2c049c98a2b83ddbb40f9144.nq.gz
    ├── 0f64dbf861e68b493ac30369996667b3da1daf8d.nq.gz
    ├── 0f92d7ba1dba966985ba07340a04f6f9f3b13600.nq.gz
    ├── 0fdd3abb2bebf3046be40a19e8211f227e7a26b7.nq.gz
    ├── 0fff35d0af7144c3704039836b05a200c6c00112.nq.gz
    ├── 10563a725a2e5aaefecfa7b7b82a74a2e6f62a7d.nq.gz
    ├── 113cf352adf5672ccda13169992581f3a1f5288d.nq.gz
    ├── 119837d1c808f5cf2db0cf6c400be2707c307982.nq.gz
    ├── 11c603ceacc9f5b2f9f1d0407b27a146901ee982.nq.gz
    ├── 1324530a011f396b11d462489c3775407683903f.nq.gz
    ├── 1371a69566285580fc7c8bf8b763fe0f867fba41.nq.gz
    ├── 145e615c539af866e5e9f8931fa7143e89ee4c5d.nq.gz
    ├── 14a6508f8022affd85dcfa4d40ffcf57cba918c9.nq.gz
    ├── 150de5ecf917e0299b847c59687480582a20a1a0.nq.gz
    ├── 151ea92046f9a3f812b1c3f72c0ce1a52983672f.nq.gz
    ├── 1591b1b5b61911bf51ba49214cc611fa4dccc594.nq.gz
    ├── 15a29b020e79fad32268e1a203ecab8f2fa294e7.nq.gz
    ├── 16f9574f069ac5a20e81a4436186769bb3816bd8.nq.gz
    ├── 18080b77920bdec59c33eae1e8a90d4bec58c273.nq.gz
    ├── 18bef4850a5af832d804b2703cd847ead4c68cc5.nq.gz
    ├── 198b65af5e2624e64269e1fbf12d71c94b94f8b3.nq.gz
    ├── 1af2f5e76be8a61b0679cbf7d8e31f8b1c97dbe6.nq.gz
    ├── 1b242d19539006f280322bafd9e1e315d4739cdd.nq.gz
    ├── 1e6c4ec789d03a82af743db84d9303dfb4e374e1.nq.gz
    ├── 1e7cdd6daba8099ba34ec16cc5cdd3f796553521.nq.gz
    ├── 1f79db890b6fac05ec9583d9fcba81800c061f30.nq.gz
    ├── 1f8f1b97df785853e4a9ff7f93315fd7058a5e8c.nq.gz
    ├── 1fdc6fe8470eae2378ef156a550c876d523a9c77.nq.gz
    ├── 20575b31663f994b2f743207a4f67572daafb7f4.nq.gz
    ├── 20d48b7f6def62b00567eb87298308b04ca04caf.nq.gz
    ├── 21dcdd822fe6c44b1f1fe349132147be6ec49d8e.nq.gz
    ├── 228238aca450f2e64c8dcef601dd8d3ad68715c0.nq.gz
    ├── 22d8de4f64712da0d2aa8ea454b02595c9247957.nq.gz
    ├── 2382b1137d9272b6215f776915b341436d104b30.nq.gz
    ├── 23905e18b405f60570a091de4d412a70faecd16a.nq.gz
    ├── 23aee4a7f4b0978b908b8d3db414830246d1cfaf.nq.gz
    ├── 24fd5f24628ed4b45ea033edd579e4970cf91f22.nq.gz
    ├── 2512cb1a1c798d96c465549e19bfc96dc6ed08ff.nq.gz
    ├── 2626db2e60a63d961207d027fd5e13c9362dc275.nq.gz
    ├── 2737ed3619f55ef2cca34e3fd742fcc4b619b609.nq.gz
    ├── 273ab20d1c398de64f994a9e808d75c2d98dddf1.nq.gz
    ├── 2784a17654843f8b5cfb8d2b0ebe34f4a7978a30.nq.gz
    ├── 27f59843c03de6e1d290588a351b674756783e5d.nq.gz
    ├── 281e0b5e29b397dd18b16e096358fdfeaf2fec0e.nq.gz
    ├── 28b3b386c70f3175d9964ba101db532e386b795c.nq.gz
    ├── 29579d1f088172c056248875d1186a48325bf5db.nq.gz
    ├── 2aeeb2717036773243e691b209b0c6207c6aa183.nq.gz
    ├── 2b7f202f71995c702bd6114bf8f9122806dcec43.nq.gz
    ├── 2be3ad95f863051bdd55ad040642d6525afca3ad.nq.gz
    ├── 2ca59d599ef75983e15d94bf97f2d9f4c8ea0b0d.nq.gz
    ├── 2cb3540ca8b62a93577f2ba2de24c23ce20628f0.nq.gz
    ├── 2d09f7cee2252fcbeb3ae76c2f976256a9218d4f.nq.gz
    ├── 2d1c7536eae112aef61a52a5eb13a4aef91fa1e0.nq.gz
    ├── 2d55295e1640619e9b9c582b450793d7c7ab6eab.nq.gz
    ├── 2dcf9225beb221a73a035222b867485beb35ef68.nq.gz
    ├── 2e6357cee3530adc20cfdfc0c5e03f6e8e608e41.nq.gz
    ├── 2fafe618554baf7696c4b2c6df0cb848ac8784f0.nq.gz
    ├── 31ccc4393780c6674d3b90a36a4001bf3459167d.nq.gz
    ├── 321bbd75c16d39a599c61cd89d3fefeed9cf2abb.nq.gz
    ├── 3225a1791bb031f192df4b411c9cd3b817f1bf9e.nq.gz
    ├── 33b3d85f5cad3f73bc1776f092ab415aa1fd9f91.nq.gz
    ├── 33e6afbee0cb9581a737f8e6e5d78a33d2b1f7e7.nq.gz
    ├── 33fcd2b8d1577cbe74c1081fc564ef49e25c84f7.nq.gz
    ├── 35472b5dece15fdce474d03a87ab82e91bfeea71.nq.gz
    ├── 36287b07ec1906eec35001d121611b02708e37f7.nq.gz
    ├── 3652f79c7b6e910d592a38dbb68f86464e871a18.nq.gz
    ├── 36a9b95e0daf1a8abfb0f5b5b3459e742a447223.nq.gz
    ├── 3749012b575ac60ee9fc4fc45c17220446f752be.nq.gz
    ├── 384777dcc4ad64b716270e5ddc265af033bc19ea.nq.gz
    ├── 38d78f9014e70b5323ae7eeb4519ebba40d8d93f.nq.gz
    ├── 3958bf1db753180d29720ca0b4d5e2fe27589f94.nq.gz
    ├── 396b0b0cf578fb83813629fe97ded59ae5445dce.nq.gz
    ├── 39bb06370e83f718e63a213440a9f781602cd6a9.nq.gz
    ├── 39d90ebf07a22d2b8e38bb6fe054d1460278fe96.nq.gz
    ├── 3a869cb5a610f551c57c4a8e3092446bd168c2d8.nq.gz
    ├── 3c17ada7f5112a20097d643d344a267b4280dfbf.nq.gz
    ├── 3c2a4401c8d447b67f2589a7400902de7bef07a5.nq.gz
    ├── 3db54739886de51b9b46ab755e065c60d12df019.nq.gz
    ├── 3dbd165c7188fc1f77c754be1a05b1dc3e0a1522.nq.gz
    ├── 3e17af69cfd150ecdcd289d029ef797a76831606.nq.gz
    ├── 3ea4f33891f3a9ab1d349196d82f3692118aaa3c.nq.gz
    ├── 3ead7e3f91a87d1cc4ce6cf5fe8a882c4ebd4fa3.nq.gz
    ├── 3f70c931ac52436500908bcf13a4103cb6efcf4c.nq.gz
    ├── 3fa66ba491bbe824e6dc1d11081a2e5376b36305.nq.gz
    ├── 3fc61e5e9f5b90614e54bb187425322fa2759fc3.nq.gz
    ├── 40653bc1aff4539d9144ac62a6243889be3fd57c.nq.gz
    ├── 40a61934df2243712855c5b95514cd47a8142c08.nq.gz
    ├── 40bb020a5e610ffadc64757299712e410ae6f2e1.nq.gz
    ├── 4131fee0ba28ef7d74271857db112a3249eb09c6.nq.gz
    ├── 425ab13974b4d323dd5a24960c74338e0acc0268.nq.gz
    ├── 42e747bb0874e7b7b209231b8085dd3c35ae5fa8.nq.gz
    ├── 43b3be7465c6cb64cab84ce31bbb75712d775e03.nq.gz
    ├── 43dedc4a723a5931d66b5f830e61cc2b63f92d04.nq.gz
    ├── 442a0b9ca24a2af2254b8270b7d8933a7b51193e.nq.gz
    ├── 443dab17d143fffed3210bd435d9ffa36f6c94a8.nq.gz
    ├── 447068979283cb9f88034261f6201a512acc2878.nq.gz
    ├── 448f2b98f32f69e29b7a6ff4b73bfb4aa49469af.nq.gz
    ├── 4559d1831bb8f21894ddc815812264d49c573b6e.nq.gz
    ├── 47375521fc1c0d6b944dfa7912e676480bc5a89b.nq.gz
    ├── 48c094d82405a55a2753a03c6dd5ea4d1eb48222.nq.gz
    ├── 48e101aa7892d29fb5605f5a24dafbf08861ce40.nq.gz
    ├── 48e18b3e0f17b2783df4add79aee4067bf7a726e.nq.gz
    ├── 491ea63fd6182cb0f3bcafb5b2406d636ace7e8d.nq.gz
    ├── 49212fcc3b21ab26aa9a8d0acd1de27f86f11bb7.nq.gz
    ├── 493eda44fc289b918fe7d920a5ebc92c928d863c.nq.gz
    ├── 498697b033405abedb2392ef0fb1cc320216d22f.nq.gz
    ├── 4997a573bb5890295231341389953f51846b3454.nq.gz
    ├── 49a60610c8848b012275a18af3bafa032c59fe40.nq.gz
    ├── 49c168ad938d0eee771cc5fddffbab10722cfedb.nq.gz
    ├── 49cd5950837a87609c87b57431103bb6afa4bad3.nq.gz
    ├── 4a16d5b892efa2bb91549bf4bd398b91797e1033.nq.gz
    ├── 4aab53c1dd389386d79feee73e9d6af1d54ff33a.nq.gz
    ├── 4b11c3e75096d3cd9aa878b733832dc9088695b0.nq.gz
    ├── 4b6f3a67ea6a4768c3998c9efcddea826cc6f097.nq.gz
    ├── 4ba93b1b22dbf0990e579aa2861c03ce15eac2f5.nq.gz
    ├── 4bd091472294bf054fc6cf4a472776047cbc3a34.nq.gz
    ├── 4cd3a98d6194c8e016f9cadd7b5271096088f436.nq.gz
    ├── 4d10ceea06561683e3af40cf67a64d0bc6661015.nq.gz
    ├── 4d52ba560fe0df4f10dd031a411993c3d71075ec.nq.gz
    ├── 4da192b46e0b89c87da08e9f146cb69e6933be66.nq.gz
    ├── 4dc02e15ed1559be590fc33707c743b7e648e235.nq.gz
    ├── 4e09636bef03e3c298f702cfaa1343e4f69078c8.nq.gz
    ├── 4e84bdd5e7b90484e15c8bb136204e1ad251b42c.nq.gz
    ├── 4ebfb15c44fcf000afe302506889f41e0f370ac0.nq.gz
    ├── 4ed597fa2e60b29e56c2b7b5a0c02510c49efb5e.nq.gz
    ├── 4ed7650884ce49771da2c240b16e35edb515a756.nq.gz
    ├── 4ed79e5ab224ac79a586590841ffc1a7cd4b0156.nq.gz
    ├── 4fd237c66f3bdc1685255efffac2fb565ea9182f.nq.gz
    ├── 5034a2cf1bf26749cd8ffc229a49c0fc5f67c0ac.nq.gz
    ├── 5063823b381a89db03308d40b2ab0b47a711a80a.nq.gz
    ├── 51e44fa40a4783710d1e68d8fc716db25b910f18.nq.gz
    ├── 5319fa9dbffc9ece75ce014a3742efbb8e4a37e9.nq.gz
    ├── 541bb3bef3675a727ed8a52e82302e7127e25f70.nq.gz
    ├── 54d7554f3c8e70cd2200dd01f5132004c9c5b086.nq.gz
    ├── 54ea5c3b23d99ba4e3243ad1dbc010d06ef415d2.nq.gz
    ├── 5562d932c61458d0440f4b150c9e09c4d47e9669.nq.gz
    ├── 56dbc0b8055f3171610f4d79d913298a30f15286.nq.gz
    ├── 573121c52b560046c65ed15ad89923c7733eb30c.nq.gz
    ├── 578ac8b29e27ed52ce465faaf32e7acae15e34d6.nq.gz
    ├── 578d99d0e36dbb06996e984d6bf2df279a64982b.nq.gz
    ├── 57b135bc51702337ee803420d476d0b03e6db0c5.nq.gz
    ├── 57c64b563162e6cb373cf6efa5bda68b58b5ac9c.nq.gz
    ├── 58743d8d8c1abc1e553e1a8cacec9d9b24a7e2f7.nq.gz
    ├── 59519b25b27943fd6229a5e31badd2d85e546cfa.nq.gz
    ├── 59995d64a33998cc13a7904fe6b1538b1e70971d.nq.gz
    ├── 59f45f7ed9778836ee4065e163f4f428ab2bf6e4.nq.gz
    ├── 59f77cacc1aefede2e1a681148b03f8c8659216c.nq.gz
    ├── 5a2de31211df5f931ecb532ff7016ec3b38f87a1.nq.gz
    ├── 5b3fe661d13cdeeae4bcc33508ef632b03617e80.nq.gz
    ├── 5bc0b009a134c471178df61517efe78344c03282.nq.gz
    ├── 5be75662eb868be379a654ec1d288ddfd8248777.nq.gz
    ├── 5cc9c22a9cc7aae4444332a331bf0c66a2820e17.nq.gz
    ├── 5e08a3c5e1e56cb8217975284d1b6a66d7d709ed.nq.gz
    ├── 5e11d6917c420377c83a86d79ecddcba768c2b61.nq.gz
    ├── 5eef34c982fabdf8a032257ab34cc8509e7652cf.nq.gz
    ├── 5f2e0898e10e8eabe38867215d3721f7728c9715.nq.gz
    ├── 601c1483e944a77f7f1bc70bc91524cd7dc249a3.nq.gz
    ├── 603478bd6bb47e253047ed5ba103e1846dfacc9a.nq.gz
    ├── 6116fa5eb11869ebb4fa1dfa583ac68a8f353017.nq.gz
    ├── 61298d683f8dde7ea3e87558141f3d8e03791a2a.nq.gz
    ├── 6292fcaf1b145bf1ef7ab0a706ef45d8ac5d8e3c.nq.gz
    ├── 62ee99fd5db6027cdd4a5f70b76e6c8aa097fd0f.nq.gz
    ├── 630373139a1e880930cbe0fc05506065aed0625d.nq.gz
    ├── 6423745b2535c8fb0984a208cf4df8dd1561b6bc.nq.gz
    └── 6473839185285a481df9f4fa9a1a0ba60f06acdb.nq.gz

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

[bentoml/helm-charts](https://github.com/bentoml/helm-charts)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
