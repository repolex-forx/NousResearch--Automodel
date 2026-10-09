# Repolex Knowledge Graph of NousResearch/Automodel

RDF knowledge graph data for [NousResearch/Automodel](https://github.com/NousResearch/Automodel), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/Automodel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 922e6b0b34e3f22c6e959405d93a6aff530fc8ab
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 922e6b0b34e3f22c6e959405d93a6aff530fc8ab
│           └── chunk-001.nq.gz
└── blob
    ├── 00540a5adc7bf6012da08a03ebd1015b8f3f6f2c.nq.gz
    ├── 006797bb4eecb4e00e2535244f747391bb5c1626.nq.gz
    ├── 0406e7349bfdae93d54ae9ef289e6b990be0b06f.nq.gz
    ├── 040726958e7dd8de50ee054c81a8c52f4f001864.nq.gz
    ├── 04516d8737ccfa4b07eea4b6d773a5021abb0ea8.nq.gz
    ├── 047b7bd79c38e933e00e783d9efd0d684ad24026.nq.gz
    ├── 04b267d72e9321c7ed34f96acbcdc62ca377378b.nq.gz
    ├── 05d2a7bb1473b9f09f396e584e7151d4d37c3ef7.nq.gz
    ├── 0602d48f7dc104007670d183d529a5e8c5e7d248.nq.gz
    ├── 0611a7898b842827cb55d1eaa3aa67a262a2ee46.nq.gz
    ├── 0681f27ef5a68b1adfff84d9e7638fa20e48ead7.nq.gz
    ├── 070b8c0d7d97c4cc6966556b6cc56069b5819fb6.nq.gz
    ├── 0758bd87048e2b69c35260fa1af160d31fd38732.nq.gz
    ├── 07cbb0d3d3be86b9ed3b03dedb15c5ec92ea48b8.nq.gz
    ├── 083b54b8f331a31438c27267dd3730e72eb12e1d.nq.gz
    ├── 0856419d6efeaa3ec0be31024b15a2fecb9cbac9.nq.gz
    ├── 08720d7a91825c5bd974aee406e2d02660226d1e.nq.gz
    ├── 089e46f5b39d28ddee52ecf6f494a9fd9e86071f.nq.gz
    ├── 097fc316ab50bff93d2cd3314e342c0400db5dab.nq.gz
    ├── 0aa816d808521ac8960dfef1b9e421133e2dd8c4.nq.gz
    ├── 0c0fa50d1a40b8a45c1525ac312508cb95678947.nq.gz
    ├── 0c6f224208528245a2f2d649c8fd6499952eddd1.nq.gz
    ├── 0caf6b4de6d7e01e2498df4f4c18b44a43a3781c.nq.gz
    ├── 0ce4dd6c3007e55ca2fa254a93e9b4bd3ff02d23.nq.gz
    ├── 0d4233d318a0fdef82abc1958b363a1a4d9ff18c.nq.gz
    ├── 0d4525223ecaaf04a9a591ba3fd784f46b2195db.nq.gz
    ├── 0da6dadc5a98c31462af0f7353718ba6c5055915.nq.gz
    ├── 0dbd7839f9234e4f669fbc7fb77ca7c3e9b16c16.nq.gz
    ├── 0e11e9b507784e62b0e15847cb7153797b6f0a4d.nq.gz
    ├── 0e3f7f1ad783e7ef604dab99cefb7d39bb855b30.nq.gz
    ├── 0f3d5e5deb8fa4e6c76f0e45dd07426d652e0438.nq.gz
    ├── 0f7a8ffa1252f15847a79a51d3bf6409f286f14e.nq.gz
    ├── 0f7d58ad2648df54a204def87ab6ceaf3257ca3b.nq.gz
    ├── 0f819df83d2f8467b4fefcada52ebaaf361fdc44.nq.gz
    ├── 1082dd75ec20962f761be471f10dd3b4584cfb72.nq.gz
    ├── 108b65efec4748a8c22f92795538d6752a2332dd.nq.gz
    ├── 10c6454f05fbf63e53536a4ba452b6d11b0d64ed.nq.gz
    ├── 1103a524807931280ad7ce587d939f813a735991.nq.gz
    ├── 119f20c067809dff9fea23192d292cc056689040.nq.gz
    ├── 11eaf295629ad504c867cad14c7fde9642c3b51e.nq.gz
    ├── 11ffab49082fe3efa7b5c010a2e002c36baff119.nq.gz
    ├── 1264e877cec35b6836f181a1ea68b051a5fd6b35.nq.gz
    ├── 1495495a352230d2c4c366c86e2fe5a0d65efb4e.nq.gz
    ├── 15123f97ec17c6de460ea7364cf3233691195249.nq.gz
    ├── 1543776f1982752a524dbbccd3123c493631f126.nq.gz
    ├── 166d26188b68d65bb9e5f98ec9069dfb163fbf48.nq.gz
    ├── 16c81db8091bdb7aad2296305c45cc52244e1469.nq.gz
    ├── 16f6e3233bf83c8085d58974f3541a7ed518dbc3.nq.gz
    ├── 177bddc2aebe369e73eb28708d1f0ef9387bb989.nq.gz
    ├── 17b27c071887914f38683232790982affc8f0b77.nq.gz
    ├── 181f169d35c73f48d45432eab63027418054640e.nq.gz
    ├── 19547bb8f9e4755b9afe3760bbfe022c22ab5afb.nq.gz
    ├── 19e1ae044ed2a1355e14fa1359ce43ba468f0286.nq.gz
    ├── 1a87a2c412b9070916c69fe73aa84980cbbaea98.nq.gz
    ├── 1dff601f25058345d561347ab457d0e3e2d23703.nq.gz
    ├── 1e841b9d7357345c678b6e260123d2d6ef565c8e.nq.gz
    ├── 1ef992a2f7e59016c742daf249924be6d8b8ff29.nq.gz
    ├── 1efbaa837f5eee6f96fb46104ea6f9fc211eb952.nq.gz
    ├── 1f1270d6d0a343606caeef1b7d064b5e07898822.nq.gz
    ├── 1f4105e734e42454e36596bdc6e39b27b2c4ea8f.nq.gz
    ├── 1fb3483e278b555d5c6a98fb25daeb9652a7d0bf.nq.gz
    ├── 2045c270cb119a08abfa24b5b094bc6096ce0fda.nq.gz
    ├── 20fa9c13980523c3b5283d15fc3ac70dde156918.nq.gz
    ├── 23dad172bbf8941de67b7b0c40ec5073b10e9c9b.nq.gz
    ├── 2453fbb66f058e1a4ac2c6ccc6d17be1e2b04fc6.nq.gz
    ├── 260572e400ecce075278448a6adeba9772ce75ac.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 280ba79f26f1a16256cc70b52e081c4c03e26997.nq.gz
    ├── 2828caa673ea29f975463f57a3851826f24c8f12.nq.gz
    ├── 282e87c083fcbd3b4b543623b3299b0f2f456a64.nq.gz
    ├── 28a62896246b3bd4fad9e14cbc92f1e5dd02a19d.nq.gz
    ├── 2937a132b21da6569c82e78d0796c6198e0df28e.nq.gz
    ├── 2963bae2bf7d439c6b4e661b394ff044ff05863f.nq.gz
    ├── 29865a5ffb3415db05b959fd4a1a23ad66425088.nq.gz
    ├── 29cbe2140e3e918e5da28cfb592eb91c2abfa24e.nq.gz
    ├── 2bb9def4badb42324c6b6e5cf752bb9f2e7f1ba3.nq.gz
    ├── 2bed1fd318ff9f60ffc3b18cb7c2797dbbff90ea.nq.gz
    ├── 2c0af096cd00fed2912e7ca9bcda3ca53770df3e.nq.gz
    ├── 2d38d6fffee5fb7b2daa3e3a5125f44845b6edb0.nq.gz
    ├── 2d99b7b47d9d3be612f230e65071d6bcb70bcf2a.nq.gz
    ├── 2da6871463ab44cb10309775da54385bd013425b.nq.gz
    ├── 2e499cccecd1e91e18f17b68031d2950c3ccacf6.nq.gz
    ├── 2e99a9a968da4aab15d7abf5992ad58b69928fa6.nq.gz
    ├── 2faad334e99f89ce1089a376de7ef9bb0d757f80.nq.gz
    ├── 300ad6ce702ed4e3fa030765c8193d94483e84f8.nq.gz
    ├── 3066692f368a50e441c197704ced3d14f39aada3.nq.gz
    ├── 3135b03697cc3fb0a6a30d17c006c03bdc5773ad.nq.gz
    ├── 319872a81c5ee920d194a1d19b2d5fd9b9cea9fe.nq.gz
    ├── 319b427ccf4bb51f6a442573fef75595797d51a1.nq.gz
    ├── 32f067cd20be2deace99f34693aa93a5a286cca5.nq.gz
    ├── 33d0cf6cdf63ada7e557934af6f1c25eeabeb65c.nq.gz
    ├── 341a77c5bc66dee5d2ba0edf888f91e5bf225e3c.nq.gz
    ├── 35398ea675c77ad863ee524532b5a7c9dc609ed3.nq.gz
    ├── 3561f29e556f59f99098f49e7a3769c3cc83526d.nq.gz
    ├── 358fa6f1c19bf4ae9414cadace168324fedc843c.nq.gz
    ├── 368d190dd4cd901249086f49f478679a521ab2c5.nq.gz
    ├── 36d85548a2ab161500b5754cf3ac8c7ced2d2257.nq.gz
    ├── 370913d977feb78c9d122732d5200beaf15e0459.nq.gz
    ├── 3743263a171a834ef8a5c1cbc7cb1d0ec4cce196.nq.gz
    ├── 378b67fe18c757bcc3aa8e2db35ad5fc532bbf5e.nq.gz
    ├── 37f8361718dfa7cf8b665ecdc4a0c48bb7cf1a2a.nq.gz
    ├── 37fc22d17abda16e6c2c3367c93de53b5dfe5415.nq.gz
    ├── 391326fb4c62c48c650593a8797d95e02d048445.nq.gz
    ├── 3925b353accfc1268470a078653d0ac28a4d89b8.nq.gz
    ├── 396329a7c6983d37bd3c4cba32970f7524d09f0a.nq.gz
    ├── 3986c7912a1cc5ab16cbd7134d101e49801b50df.nq.gz
    ├── 39c79b5c515971d38abae12f30f0caa5a3dfe3e8.nq.gz
    ├── 3b4d8dc6ff26c410aa7b78d18ba2b5e806e3a700.nq.gz
    ├── 3c139b316fe4837259a277df1e15967255f8db2c.nq.gz
    ├── 3c183777d402a8d885b635f065cdb238d23fc7c3.nq.gz
    ├── 3e23fa585a45668a214ca32b8a500f6400f8dd0c.nq.gz
    ├── 3e7b3d2d0706cbd242fcb2fd3839d759932b3972.nq.gz
    ├── 3e7b65be3153a28449ddee89bc85708451382ff1.nq.gz
    ├── 3edf29c320431d31b9c31d8ce24030611f021d1b.nq.gz
    ├── 3f4130827b3ecd2624fa841658ee196a54cbe708.nq.gz
    ├── 3f67d87fa0857e404301bd719de39b7fee642be1.nq.gz
    ├── 3fe0d7c35d7581275c08b06793c4d0d8c68c2013.nq.gz
    ├── 417f21f6c0fad2267ae8cb04ac16921d57da5de9.nq.gz
    ├── 4286cf1865da34ec1d98b91fa2c97fc836a8ab23.nq.gz
    ├── 43cbd5846af71740d31cdda626f7668f7e484c0b.nq.gz
    ├── 43fcc5147d84412a6ff37b8edf4b41fe30720321.nq.gz
    ├── 44061d9af4739956915faeb913071c002d34b3d3.nq.gz
    ├── 44431281297820e141eaeb355755fbeea8c3f52a.nq.gz
    ├── 444505e00d37a7c048672b35027d3cf3604cf6ae.nq.gz
    ├── 4487835ef3444a042b8077ea1a7106b2d3109403.nq.gz
    ├── 45b1e4273c15e114700f04fc4711113468484463.nq.gz
    ├── 45e20a78a32c5e55876793fd552ef1bc5f5e8cf5.nq.gz
    ├── 460cac22600d83af09b6c7b9d726acab22711ad6.nq.gz
    ├── 466b643b6e46e3b3a47449003d864d0068d4be55.nq.gz
    ├── 4680784171ce1878c50f88a91a779a625f84351b.nq.gz
    ├── 479194bc521cc34eb06b253a4a74d228e11bf74e.nq.gz
    ├── 47947167995dbf8be52e6b6f85251fb5d0fa927f.nq.gz
    ├── 4a1118a5cc18866649dc53bf254718d436b2a203.nq.gz
    ├── 4a71be7ef9adc692603c626142f3874e1b6328d7.nq.gz
    ├── 4b12060bbcab2764f05d082c481efc2712b29bd0.nq.gz
    ├── 4b97102a59b21ef1ed3b5ae71606791ffbe4dcb5.nq.gz
    ├── 4c0cf99d2826121b4cb6a6d4a427883102a503ca.nq.gz
    ├── 4cbaec875b3808312dc732bdf7146700e967710d.nq.gz
    ├── 4d0a78b7d3c45334e7ad154d1761cb87d68e72e1.nq.gz
    ├── 4d9cf80d3b1af8ce23eae9d0e7795b5826bc32a9.nq.gz
    ├── 4e821203df23311747ad89c5ad2c9f4fd3307ced.nq.gz
    ├── 4eb906f3e5cc8a25bc2cbc05ccb0ea7d26229dbb.nq.gz
    ├── 4eec97285b5fafc271230ec15f22c1842b70a406.nq.gz
    ├── 4f5e416192cefb2b0978f2cbaf893eb2eea98c38.nq.gz
    ├── 4f90e346e5a0a1bb041ab69ea7b53300fa2e19a0.nq.gz
    ├── 4f93590fa0f740944d0b2f52d7fdfabbfd3d86ce.nq.gz
    ├── 4fd3d86583e3a61f6b9162040e1df6a7767f021f.nq.gz
    ├── 4fe08ab22ec03937d1943b3a57811479218f7bc8.nq.gz
    ├── 4ff838ac1bcb2df7e5a6a69c7d46af5a0cb3c1c3.nq.gz
    ├── 51394a5013ff5fe0a88964041ebe93d5c9f7811e.nq.gz
    ├── 517db0ca2f84e17527f713a42889d5a4d6b011e8.nq.gz
    ├── 51e686fb2216b7f2b399dafbf0c34d83cefe9805.nq.gz
    ├── 521814335e33eeb2f7f89a68b2deef27475646f5.nq.gz
    ├── 5249d1f1c01f25bdfcc5702c2bea0ee0df7a3c67.nq.gz
    ├── 52aa337aa91bc1f7d68e6293505430b6d8e10a31.nq.gz
    ├── 536f9051ba52bad88d699d108554af6fc297d72b.nq.gz
    ├── 53a689a81f985be15450c272f1c7802b787593e3.nq.gz
    ├── 5413dbcfddd944d0e15191aebcc8ab59615eb6f9.nq.gz
    ├── 54245c58c1f52849b8ab9a1293b336719a7aec6b.nq.gz
    ├── 5479b9d1b1738e6a57d9fb18be17e020b031d841.nq.gz
    ├── 579ea8c7aab0a2a24a7c8d29781441d08b822fd8.nq.gz
    ├── 57c68b5e1b4eba06415f037fdd8c4569c0aee1f7.nq.gz
    ├── 582037ecdb8d11f0cd6d30ca3260488630a51219.nq.gz
    ├── 5882c0e1e9bc11b03b21d72830c5c146bd1b69c9.nq.gz
    ├── 5910b6e7b50cfecad37cf694341d5cd26b301345.nq.gz
    ├── 59a06b74ca932ee66dac02d450c1504b19e18191.nq.gz
    ├── 5a400e86a2eefc10a1a8840a98624305b69224a1.nq.gz
    ├── 5a6d7db312029317a0cb8a6bc6cc3331b8f2ef7f.nq.gz
    ├── 5ac80c0639bb4333854053d64b949ca14bc0f110.nq.gz
    ├── 5b998d08d8ce2a0e9d3a121356984adb142eed3c.nq.gz
    ├── 5c114ff541aba23eb684274103ca623b08525e9b.nq.gz
    ├── 5c7ecbbb248a2bc06a96700ed50c3c3b254b1256.nq.gz
    ├── 5c8cccfd2f1967a96b0b0c10c4fab4d8e93afcd5.nq.gz
    ├── 5c95f85266de87bea3c8a0bd831e2f510d95a71c.nq.gz
    ├── 5cfbb856fb7f0e07e18ef2f71ee886e43d8f60ac.nq.gz
    ├── 5ddae6d2b92530753d30f33f426ac2848a84f32a.nq.gz
    ├── 5e29307361e589eb8d7021c75eeac829ef83c8b8.nq.gz
    ├── 5e443b5be34e46355c56468486894b75e8631c93.nq.gz
    ├── 5f198b202a91102994594a02671939a450a792f3.nq.gz
    ├── 6034a2c5e63c6a9fead3d445976aa988433ed13b.nq.gz
    ├── 60d8684abebe4b56402d6a2df4f7b801fb172846.nq.gz
    ├── 60fc546a87998f5674202e78fd9111d4341a0f04.nq.gz
    ├── 6221e996016a660f4d0587fc6d5b715b9ef56318.nq.gz
    ├── 624ac74c127b5d6752385bf9b55fd1b8af6c8be7.nq.gz
    ├── 62a492232f5ea8f90bdae292379a43e03e65e817.nq.gz
    ├── 63c730eb8061b86feb9bab33f58f75872ec7af70.nq.gz
    ├── 648db6ca25a3b27726879cb8cd31573adce1f3ce.nq.gz
    ├── 64e14c039b30c554f764afeac313235ac75eb53d.nq.gz
    ├── 64e24fdc81539c95d37366aa72d5859d7058aaad.nq.gz
    ├── 65c9015e20571943bf1664814734cdf681eb7e03.nq.gz
    ├── 65f9b458740276ab4aea33c0f72f24279f9477c0.nq.gz
    ├── 67fc279bb737efa9f4a984bf8a9c7dd3dc8dbf7a.nq.gz
    ├── 6a86f762021706770cd2e631047b26893af8c9a0.nq.gz
    ├── 6a8829043ed13136e857dccbe724c2855173b310.nq.gz
    ├── 6b187244ab3146aeb772240a4f496132210ceae0.nq.gz
    ├── 6bfd159f66e73dd1756ce5b7a8f9f8b0a3e3b038.nq.gz
    ├── 6c0e26889a699fba6a81315ba47215cac9380fca.nq.gz
    └── 6ce5808243f25000881d2c58d30e5fe3039d73e2.nq.gz

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

[NousResearch/Automodel](https://github.com/NousResearch/Automodel)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
