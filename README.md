# Repolex Knowledge Graph of pypa/cibuildwheel

RDF knowledge graph data for [pypa/cibuildwheel](https://github.com/pypa/cibuildwheel), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/cibuildwheel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b3395e271a35f73dad77f21802abe9b986dfe299
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b3395e271a35f73dad77f21802abe9b986dfe299
│           └── chunk-001.nq.gz
└── blob
    ├── 0240d2f8a4813e5832a37aafbd6a1b4a739c5846.nq.gz
    ├── 02c7ac9358fec214ff97b845fd56b8fe34de50fb.nq.gz
    ├── 051b57ab76c88b6c61f893c7d02c438d7174f957.nq.gz
    ├── 05689756c8e68258bfcb04821f9f053077f67481.nq.gz
    ├── 060d24f853ae0dd45477f7606e148035d5964576.nq.gz
    ├── 07bb5ddde4de62a51be63b6ae7c9024f1f3c9cbc.nq.gz
    ├── 08c1abeef5938fdf74f9eeeb175a5f71c6d0c8b3.nq.gz
    ├── 08c4490566f629fa3cee71c1bcb2277b5674324c.nq.gz
    ├── 08ff5497d6533bacd697caf3ae768a58df862291.nq.gz
    ├── 0c50dcce2bef8061b53307428b6257b98513e7b9.nq.gz
    ├── 0e1036196c8e958681fdf007e0f61697f5b99ba6.nq.gz
    ├── 0fa33967e00fcf2d15de497f612f9db12190849b.nq.gz
    ├── 1035a0bfdd293cd0a4de315984d99dceb9309cfd.nq.gz
    ├── 113b2b131b0a51d3c149876a433f305432d347c3.nq.gz
    ├── 11784a1b115865bbe191fd55f2a9c0a44ea1bdc3.nq.gz
    ├── 129a78fab27f9217c40c0a196e024512bd4362dc.nq.gz
    ├── 13bcbe06957cfae97a7cb335c4865f4625a75c6f.nq.gz
    ├── 14cd6e5df377581f462e9f8a87707818dd69ad5a.nq.gz
    ├── 185d2a74d2aca318500458b948a864ac82d54cc6.nq.gz
    ├── 19c40418636870a52a15ce4eaa30372867fe5223.nq.gz
    ├── 1a1842b4bad3c003f3ce39412af3ab3da510d300.nq.gz
    ├── 1a279f13a2608823f01b64571861243d31378edb.nq.gz
    ├── 1a38fc32dadf0760731400b17d985580e1287b2b.nq.gz
    ├── 1b586d29e72e00ad89d0df159aa3fa58b358e022.nq.gz
    ├── 1d5d271c24057a53f17b1f50059fe33eddb7cd7c.nq.gz
    ├── 1e3c4988886652d005af5e776be62137a59ff7f2.nq.gz
    ├── 1fecb48ea0b775316e2b4e294ec4a1115ce97e53.nq.gz
    ├── 21089c8e33023af1898e30e76b42410dbd9f89af.nq.gz
    ├── 21550afb03b8672895dfe069ac88bc92ce88a1ae.nq.gz
    ├── 21d48e10d6b0d7cf70dd8a8d1ff3b9062bb7e607.nq.gz
    ├── 2202398fa88b0a4af0c8729704a4757fbefc6a9e.nq.gz
    ├── 2226ffebdfe06027766ee8da6980fa86e607c13b.nq.gz
    ├── 2240a62972cdbed8b1c31c5601cfda974bd6479b.nq.gz
    ├── 225ec83284e0fa12592be17163c718822bca32c3.nq.gz
    ├── 2809b17b1cd71e75e6fed65025406d7784feb7c6.nq.gz
    ├── 2945b71ca076c5b47735ecdcaefad3497b239734.nq.gz
    ├── 2ab3b44ddb7266d71e83569ba2a3f80aa18be4fe.nq.gz
    ├── 2af873cfab90d1ec546d10ece3788816739bae24.nq.gz
    ├── 2c5b27208d52a710d0511ac1d112f6e097b42951.nq.gz
    ├── 2cafd6f3ade233525c576fd8bd21dd7888066894.nq.gz
    ├── 2cfae0a1d7f435b26a1e16f91c5fa771a11a1e5d.nq.gz
    ├── 2d97ed17cecf32838e3217b5101d8eae1b41992b.nq.gz
    ├── 2e2db6413cad994c87fe055739a71b1d87733a4f.nq.gz
    ├── 2eade095c85da1256468840b16e3b5179ae84a96.nq.gz
    ├── 2f36f38f57d43b20388320be64dd43dbf7275cf2.nq.gz
    ├── 2f48039e8b137c70bb954a33a309a6cc806ec524.nq.gz
    ├── 2f870bffb513370671c2d2da7dd2b890941fce6d.nq.gz
    ├── 300e44f0598398c4008137f3253869c168e86787.nq.gz
    ├── 30cc0c06f1bae56eb4571820e4adfe7d816bb8f9.nq.gz
    ├── 30d7ffe671ca5537a4659c7d1c87e7dbc5933a5e.nq.gz
    ├── 30f07defcd8287ff29e9d937ef8bc8ad6845a685.nq.gz
    ├── 337ebe2d635c274043dda175bb08b0d37902683e.nq.gz
    ├── 349efb705f7a471950de2d69423f8c0098b829a2.nq.gz
    ├── 355dfd3d6bf76d5e7a1490c3a50d8c4c79caf7fa.nq.gz
    ├── 35615a37d451ff1bbdc2230cbabde228e3ec443b.nq.gz
    ├── 364cae3af7aed57e4c7cabb2f9a102f1c5c634fd.nq.gz
    ├── 366baffa1e48eaa12476101f0c52d78ec95dbe73.nq.gz
    ├── 36e83c6ecc33ca6932abef2807381983744b5d6b.nq.gz
    ├── 3762c279c15a2455edefafb171d6904bbb48539c.nq.gz
    ├── 394f0da7de6f668dd6d45c4c916a99ac75662794.nq.gz
    ├── 3b92b41bc0815e2e8010e3da23a03084dd4186c6.nq.gz
    ├── 3c1004d26995677fce08fad234e230c12e971b8e.nq.gz
    ├── 3c6aa6d6bedcf8250755d203a42e8c6a29444315.nq.gz
    ├── 3cde251d6fea92b64520e86beec067a374b1e675.nq.gz
    ├── 3d648c640994b5d94a360b51a70e38eb3e9d11f7.nq.gz
    ├── 4024697a90d9ca85aeecc329677cdc89b2da8791.nq.gz
    ├── 4070ff8e650c7c750af0d8017209b7db6644c0f6.nq.gz
    ├── 422da5b58e95bffc54715ddc95a8dd98a876d2ce.nq.gz
    ├── 47f528cbc498a4f357c5b922142a924ccbb181a6.nq.gz
    ├── 499fff6d4dcd5fe05c25687146c977ec463f85cc.nq.gz
    ├── 4ade1ff9756a8d6b1cb0f7341afb9a4bd6be3f16.nq.gz
    ├── 4d25b2ded03529ac3b699e725ae0a94287845643.nq.gz
    ├── 4d5867d169118a854bd58489ecfc2af8315ca55e.nq.gz
    ├── 4ee4b3e1762513a52a299e65bee9516d111e6414.nq.gz
    ├── 5122212221460106d4f8ee23c236037be2fbbd07.nq.gz
    ├── 51eab9ee4946db1be5ee7d14f0dd804a58a4c18b.nq.gz
    ├── 529ce6fd7eb0a4a90913d3a44d9a94b029abffce.nq.gz
    ├── 53363ffcd4541cd06718f3a1373a4823a7388b35.nq.gz
    ├── 53b0887daef4acf3b29a27cf9cd255b8125e02da.nq.gz
    ├── 55ffa3eabc7bb4d4d03e1cbb0d16ed6d5a31e440.nq.gz
    ├── 595eb7fcbf625c3c0613e4dace751215519fedcc.nq.gz
    ├── 5a327a6620e4be466004992a71bf24a46ac6405c.nq.gz
    ├── 5bf8a460683afa1c1e15cacc6d46ea7922f1c78c.nq.gz
    ├── 5c044cdcb1257967a2475ce73b306a28f72f050d.nq.gz
    ├── 5db292a9fff4e0ba7013b62f575531ba688224db.nq.gz
    ├── 5dfe4a3d9c320659d89447af54d3c754e52eed68.nq.gz
    ├── 5e931976c15bf981b95a560545b3b08ce0cefeec.nq.gz
    ├── 5f34f5e9540be57912820f95b2990939badad057.nq.gz
    ├── 5f5f9a493326ce314d68802c802367070bfe8df2.nq.gz
    ├── 5ff62c1f4b954fdaeb756c045cef33c31e1581e1.nq.gz
    ├── 6023be5ce87407ef5b322ea783781ab8195d8eb9.nq.gz
    ├── 606ba546ec607f16b635d74aaa62ef0034f1b8b7.nq.gz
    ├── 627dbc162bd139c38658a2040da2125ee3062092.nq.gz
    ├── 62fd01e70118afa1859b3a0f75f6fd1697eac174.nq.gz
    ├── 6381f17e3a9757bdb9c5dd99151b24ea562ffb57.nq.gz
    ├── 6413c9320308043e6f252b3ce0d53c54e272c6a9.nq.gz
    ├── 657428ff56fd9b295b5cf8d8406be074db16843a.nq.gz
    ├── 6576fb9084e761dcccd584c54f1519ec1775afcd.nq.gz
    ├── 6771ccf7895ff39d65c3edb75de3ad11125edbdf.nq.gz
    ├── 680ed6b9fe7c925b94a25a1e46d9c912ccb6f7e4.nq.gz
    ├── 69039d56965af33306e9a8c8140935733a86a97e.nq.gz
    ├── 694d6e2434480e745eb2b5e52170e71ab717e0a9.nq.gz
    ├── 6981c2566f7518f98b06abb3a08ad2245f18c28a.nq.gz
    ├── 6a3576383a1073331734032f8daca02d739a5168.nq.gz
    ├── 6cbecb130b951352d28cbab41f068a81e6c6c0d0.nq.gz
    ├── 6d99dafe88f0d6bfc078742e1511530f20acf734.nq.gz
    ├── 6ec04b1c59cbea582cfeb31a8e776e82ad2b00bf.nq.gz
    ├── 6f02a9837bfa5b7f749efbc8841d829488a30b73.nq.gz
    ├── 70a8bcdd41c91a8db8da55c0e56de3be4641d6c7.nq.gz
    ├── 7242a7ebd9add4fce18f5f6d2dab5c3fade795a3.nq.gz
    ├── 72c0433b98d21a9097778c389961cc9cad16442d.nq.gz
    ├── 770508a63d7f43b8e8f23ef287e6e77ceb87d05f.nq.gz
    ├── 7741a7c22988894e89c763d8ef16f4a5c815f910.nq.gz
    ├── 775b81bcdd03cdea0939173445e1e439191f63bb.nq.gz
    ├── 78d4ab9e3dcc91efc39e0b002e760c328b2c7569.nq.gz
    ├── 7a8826acc8afde1104758d66facc9ea57dc7e3db.nq.gz
    ├── 7c49b615bd22a0344903789d7f714934474b2940.nq.gz
    ├── 7d19ac50acd32eaab78cf4980f3844134ddd5ba7.nq.gz
    ├── 7e6b8b2d99015e8bea8ea317bd060a3d8ea1470e.nq.gz
    ├── 7fb2083ed4e344938db193dded625fe1bc1f3df6.nq.gz
    ├── 809f6332c833b4e1f2b0dacfa29fb22fb1a94922.nq.gz
    ├── 8324526ce026ff50cb82d677f7b9daa857228187.nq.gz
    ├── 83cec17f1af6bbfdaebabbc7b1cedbac5454368d.nq.gz
    ├── 85039da2537c97bc6ee17d46dbd52e4eda0a543e.nq.gz
    ├── 88fa8dd984f632782497eb4231ecf18903becf2a.nq.gz
    ├── 8ad5b84a56771984488dcd01037c84c70d8eedb6.nq.gz
    ├── 8b0fd3806a68ec5ff439069381d3a6708deaecff.nq.gz
    ├── 8cd905a1b0b7e3ee46df7419098dedfb107ceeb0.nq.gz
    ├── 90287f5b2529b623c2b1d19e4d56be4bf2224a3f.nq.gz
    ├── 903e579ba8cf49fea762bc408cd5dfc3e296d2b3.nq.gz
    ├── 929009b5f9cf4bebbeb3c61d390ef7122a596ecc.nq.gz
    ├── 92df1a8cea3c2db44a6a07f37baccd46d6c4ea7c.nq.gz
    ├── 95115b0c4db92cbb5a7126345c5f7956c479fb0f.nq.gz
    ├── 9657127ddb7231e7a487abd80a57e27bdde8ec09.nq.gz
    ├── 99816175a40e3853e204f4e6f8deacfdc96a498b.nq.gz
    ├── 9a0d5d9f1035af978f73390f2f74a3c6b4b24fa0.nq.gz
    ├── 9b8714fc08abc5e0a214ad5ecf2676cdda8a53d6.nq.gz
    ├── 9d3681eb839c95b7df5e6647cea75d6ffb3d2c04.nq.gz
    ├── 9e5fadd9f11aecb376589c3cae2334b0acc6891f.nq.gz
    ├── 9eeb79ecb15f3ad7176db0600bf05c0850b5c321.nq.gz
    ├── a102851053bf52a6b5595d3d4aee1d0cf5951bc8.nq.gz
    ├── a50599dca0899ee915107118dca18a4ab3293311.nq.gz
    ├── a66e46a82501c431dbef8460611475e3758d4fbd.nq.gz
    ├── a73ff5cfcbb341ee8d51861562784d9527c9c8ad.nq.gz
    ├── a7809b908668969ec6e7010234080ef95661f487.nq.gz
    ├── a7d5ca074d8285b76af1879a150f3c5de96466c0.nq.gz
    ├── aad425c6855f35a77c552a72dca77cd8da540348.nq.gz
    ├── abef03073a6820dd05a29ab6e5e11a68266b97c6.nq.gz
    ├── ae4d23e88d550c5683606fdbce7fe799cbe53b80.nq.gz
    ├── afd0191cf5643cf6a8a11c63ff186974ea2a301f.nq.gz
    ├── b204c509192d859f26a56a23618d67fcb9f83a47.nq.gz
    ├── b379b0c62487b740baddbacea1cf8a3e069116ea.nq.gz
    ├── b48793fd89e2fcc03237270fbe4e46109899a23b.nq.gz
    ├── b49047a9a4aa200778c57bb740ddb6e726308426.nq.gz
    ├── b74a801a03f6bdce6108d76dfe12ab3e690f3159.nq.gz
    ├── b76ad42ce8bdf518a217585fbf76abf199820d86.nq.gz
    ├── b783d79e4d1481d9528e4bc27575ee3d19e1b01f.nq.gz
    ├── b8cf9c9dc0baad2a093be4735212b0e138414ae9.nq.gz
    ├── b8e8b3f330884363cba2b70c9633ce3c3918b394.nq.gz
    ├── b9dde25652106699b1bcbb736628447c6faf29a1.nq.gz
    ├── bbc7c21b53d53e862417ac0b67d1785972deb9d7.nq.gz
    ├── bd3d0ef5aa06b683b6896a1cff5d436c40ce5fe8.nq.gz
    ├── bea4893210f5ade182703391a64361d7f2e6314e.nq.gz
    ├── c01678b8e276ea8debfad1092ae4b41cc479869e.nq.gz
    ├── c168345e930f3a0c0ec344bf191ecd053023559b.nq.gz
    ├── c1fd64ebffc266a89aeb9dd77d0f293d68f72887.nq.gz
    ├── c280940ebc002a032d0dc2f7538fa756eb828373.nq.gz
    ├── c2fa6eee9a134b1b57e02809a8b48ae5b8a8113c.nq.gz
    ├── c5818faf70782e84a74f5cd535d51d2ad2af2051.nq.gz
    ├── c863bc44ba5214aee08e31268dc74323a246104d.nq.gz
    ├── c8a04bc64f052f2eac81551102a9aebb342f6ef5.nq.gz
    ├── ca120ad451d255742aed8a6b4325017789b91d97.nq.gz
    ├── cb0026ba016d549ada99e19967710494388351c7.nq.gz
    ├── cc3e15a2bd08175ebbde3fbdbd303988580474df.nq.gz
    ├── cd812200fa24c09cda4c9c568b589ad7a81c2ae1.nq.gz
    ├── cdbdf6012d3b045b756739ead575afdd2662db0d.nq.gz
    ├── ce83e865e02e25bbc24be82eb929785afb2a3f81.nq.gz
    ├── d0ebec927c8735fde1a75dce13811cca863e6117.nq.gz
    ├── d15c040b4f17739b3662d6ca0d526d4045738afb.nq.gz
    ├── d3af380b59b8522774edfe59ed358ff57e5caf57.nq.gz
    ├── d7f37f0df8dabee8235af1572297d7222851ab88.nq.gz
    ├── d7f8f6899d81731f24bc177af8cabf5575b0238e.nq.gz
    ├── d812a29739c44c9565234ab7aaaf2f0add542949.nq.gz
    ├── d826150d4cc22505ab6a57d3e02d731d3a047ac1.nq.gz
    ├── d88087eaa14bf02f9f11e3fa64550a6bac45f282.nq.gz
    ├── d8a2c2aebc5c8dae6aa00abe6f1c3a53b8a353b9.nq.gz
    ├── d8e15b51c2579edfbd837bf5796366abb0b482aa.nq.gz
    ├── da36d1805728a51c4fe75c4c4b23c0ee341f2dd9.nq.gz
    ├── dc96f743e7e16dcd268fbcb324593697a043e74c.nq.gz
    ├── dce31e30b445859f6cfdcd076fbd10c742229306.nq.gz
    ├── dd6200abfd42c5eb2e4a9d393ede0a0efa0e56ec.nq.gz
    ├── e070fa445e15b2b86b114f80be2ff33889126d94.nq.gz
    ├── e0f4daba7f69077ad32a0626e93fadfae98ee225.nq.gz
    ├── e2a33b812dd80e41666b6fee6d67336cb9553d9d.nq.gz
    ├── e2dfd05c5bda254f2086e87bb6c88c7a25f3a3d7.nq.gz
    ├── e33f4d4b68c8735967843c4839c161af8aaf1b3b.nq.gz
    ├── e42a12d6e76eb1f00c46a8a4f517ab4bdd743667.nq.gz
    └── e4992f00e3362bbeb2a86dec3a43d1e8cd7e5801.nq.gz

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

[pypa/cibuildwheel](https://github.com/pypa/cibuildwheel)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
