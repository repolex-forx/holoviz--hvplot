# Repolex Knowledge Graph of holoviz/hvplot

RDF knowledge graph data for [holoviz/hvplot](https://github.com/holoviz/hvplot), parsed by [repolex](https://repolex.ai).

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
rlex download holoviz/hvplot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3fc8075f9d809d0b4a7401dfa137d29ffc03fbf5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3fc8075f9d809d0b4a7401dfa137d29ffc03fbf5
│           └── chunk-001.nq.gz
└── blob
    ├── 001236b65f4cb59067377e9c011c47582c357ff0.nq.gz
    ├── 01929496510c79271c8332e8e93b2a7a486d6651.nq.gz
    ├── 03eda1d8b53562f7a505f1c2ac1736bbfd60f46e.nq.gz
    ├── 03ffdbef833083a56c984f73f40d110640cafe23.nq.gz
    ├── 05ada9e60d5a7860a2887bc76bd06e4c0699640d.nq.gz
    ├── 07038164af4481847811709a365074a35f88b000.nq.gz
    ├── 08844c8d4295c5489ce90ba66d4933c94de89ebd.nq.gz
    ├── 0d4d984001292a47a854ef9924004cefe8cdb5be.nq.gz
    ├── 0d512cbefc3d1e12c306177fe902d0edfb4a261c.nq.gz
    ├── 0f78ac7b4a0962913c30045fa0c489cceb79ff09.nq.gz
    ├── 0f7bc6411e33161a9c9c9c1310b434c57f65383a.nq.gz
    ├── 1198124aa59cfe72084b486f74a5dac00464a307.nq.gz
    ├── 119db9f6d96f67ca60ef15489f2de351e402ad71.nq.gz
    ├── 11f386dac3c9434b52b4b5098a05a008e0458a6a.nq.gz
    ├── 1224102c18823f4253810361db2ce7ad08c91d92.nq.gz
    ├── 1299a5d943a5057e2f9d5a74c23844780d402f72.nq.gz
    ├── 158364743bd7ce5b3ca07d1a5847729ebce1bf94.nq.gz
    ├── 17671488e92ce02922fc8307d2127f5dd6e2f7f5.nq.gz
    ├── 1ef6f7f547691b57f263342a31d887d79849c1c2.nq.gz
    ├── 1f1358529984aba9fb56837b819b1b875de52f12.nq.gz
    ├── 1f3cee43784262839d22b305ccd5f3f8b0aca825.nq.gz
    ├── 205e5fd4156306d5517edb9a87511e2a86a1d699.nq.gz
    ├── 2137c5f1ba757f41c740779251cbf6a340ad9a23.nq.gz
    ├── 22cce57afb26b233da70cd5063512541e9c259c4.nq.gz
    ├── 23325da367883f4be8579ee5a1f248c257d4dffd.nq.gz
    ├── 236db95429b152f898145e4fb31d9df8c1bd7ebb.nq.gz
    ├── 23b1be157a75959497435d35f0ead096f5735396.nq.gz
    ├── 23c7bc9935c29d276f636b0887c6680d0e80e3de.nq.gz
    ├── 249a2211909dcd1329c17b899cdecd20ccbd9cd5.nq.gz
    ├── 249d085352293b8c1d709378c5b803361ed7c1dc.nq.gz
    ├── 255d5f47a73e07a88957401ea3533669fb36870d.nq.gz
    ├── 271976918ecc40bbb7964dad1e00af371e15e8b5.nq.gz
    ├── 2766269138797e775f1e38f7faa836d7f19a0f38.nq.gz
    ├── 29c7131bdc6eb5160790095d1192e32485304604.nq.gz
    ├── 2b23f02676681afc087defb5bc6e8af456c54bb9.nq.gz
    ├── 2c76ffdd195686e74b2d81bf8e3f86880250650b.nq.gz
    ├── 2d9220fc522a74b0361f07f9f2b61ea2257a9154.nq.gz
    ├── 2e797ae35732ffc1ffa1db64e1e986528b368870.nq.gz
    ├── 2f38cba8ced298dd061a822beed5c7fb6ff5a03f.nq.gz
    ├── 307d1e7963c211ffc4c6a8b504364a9f5bdb8df0.nq.gz
    ├── 30a42f24e353968a05b6842621644948ee14971c.nq.gz
    ├── 30ea054c13b13f3c97eabcd6dfe36edcbde353b0.nq.gz
    ├── 31638b72d511e6cbe5f73befe4f0979b377de30e.nq.gz
    ├── 32283cea19308470f3318495ebb58f12f1063417.nq.gz
    ├── 393b40c1b452bd1bc4614cabffda08b7a5bd6340.nq.gz
    ├── 3a601d4a6a7cc1b28db1c42c4ced016b54a9798f.nq.gz
    ├── 3d34856d0fe2df82fedc696f902c60f4d3d0f618.nq.gz
    ├── 3de248fe40b0922b6585904f46cce230a9018a9c.nq.gz
    ├── 3f6605ec01f5b22e76b58de5f5bf79295e22d799.nq.gz
    ├── 3f88dccc19cd90b7808e600af837d4a78694d81a.nq.gz
    ├── 40bfd59aee3a9ab1e84ff910812b77a8c40ca426.nq.gz
    ├── 40f9268d16ab21f0ab1ed6aac362a96b3f8a4bb0.nq.gz
    ├── 4148d1c457e25323b8b7ed27d273db49cab48536.nq.gz
    ├── 434e71d0467de29a1c31d378c0e1b682369b41cc.nq.gz
    ├── 447e47a7134ccad4f3220e5c2b242b096be9e609.nq.gz
    ├── 44d5e0401073b79cb20d7bdaa2e35afce638ee4b.nq.gz
    ├── 4515ef177da3457e12493b7deab75ac2bf32010b.nq.gz
    ├── 4572f7546ff244f1a87ac96b02e95e3c600cf117.nq.gz
    ├── 47bbf868cd179f0f190cab85153c9120641ccab8.nq.gz
    ├── 483cfd85a9828e5e93fcd35fb126075a0f2ad6ca.nq.gz
    ├── 48969e2a6f00f8301ef905ddff1ac3c447472c03.nq.gz
    ├── 48f292785eeada1bfa04008df1fbe456163ba9f4.nq.gz
    ├── 4944cae20b05a95d1b768dba4b977dae4e6f9014.nq.gz
    ├── 4c03130868fcbd479af8ed077e388c58fe0d3813.nq.gz
    ├── 4d6971f909f2e83a29512fee2b89a74014db57b4.nq.gz
    ├── 4db6c04c29deee31edef8c54e3a778fea9eed8c1.nq.gz
    ├── 4df1b5187a205d75a90c53924d761c41e4bd8386.nq.gz
    ├── 4f67c9f401d6acdc6e92d27cb0dca6728c0e616b.nq.gz
    ├── 4f9ccb6ac95860f88ab2b2154185c22e0dcad22f.nq.gz
    ├── 505d16b032b31ecc231d255059c4e3086c496cc0.nq.gz
    ├── 5085f579e74e3411adecd576538b20c6a77fba36.nq.gz
    ├── 51ca8fa818be803b2de80251ef3c030bca903346.nq.gz
    ├── 527b847cee39cff3dbbbd641b9f8779657a15024.nq.gz
    ├── 53b34b1a0e88c213d8c51c4c4ff852c98abc5de6.nq.gz
    ├── 548196ec28fccd49c4a0b1c143bb987fb03b864b.nq.gz
    ├── 54c6aef41f74d991a951d746df234d6f4c266a98.nq.gz
    ├── 54e7a8fd60a338547dbac6febdad5257d962b287.nq.gz
    ├── 5541049ca9b7a65ed62cac878ea9bdacdab08201.nq.gz
    ├── 56558f1d4f7dbc790e3e2823f95d2fba4b572601.nq.gz
    ├── 5716f36b80db456869a94fe6336a938ef53379ec.nq.gz
    ├── 582920c25ed48ca68dc5026dd72f751705278e85.nq.gz
    ├── 5a8de61e5db266f5f6be0dd6461411702409ca6a.nq.gz
    ├── 5aaa28fefacb8477e2f3b052e81c478f193c5e95.nq.gz
    ├── 5b307b9bfe4703fdf846efe833fa1a81fd5fbe00.nq.gz
    ├── 5bb7d5622224d5fd50f309381742ac54db7c81ec.nq.gz
    ├── 5e12c7e1efffb55027700abcd72f5b190bbb6d4e.nq.gz
    ├── 5ec2af9feab35573a8f2bfe81352ca0517f5a245.nq.gz
    ├── 5fce7f4990ec7e0f427437d8b207155527cd3a73.nq.gz
    ├── 601a1d094805d6c2170e4d5bd8e49e75323faf1e.nq.gz
    ├── 61deaa442f3056f25643082c42f79d805f38c94a.nq.gz
    ├── 624d56945eafde9a1095437e4d535fc1bdf3663a.nq.gz
    ├── 627cdd441491b6491c4e89d48a02aacdfbbba26a.nq.gz
    ├── 634873ec3114c0db086f1910e8ffed6c637a5394.nq.gz
    ├── 646470cb01258099ba05aa07c0f279d2615e33d6.nq.gz
    ├── 648d12097be90afd1b158a4e29e41f9048aeb7b7.nq.gz
    ├── 64985c21fb709c3d85d58cf2efb378bba9aaf08e.nq.gz
    ├── 64cb887e6d8692fed27401535960863953a6226b.nq.gz
    ├── 6621e73a44f79c5546b7783322c5c30448d8fe9b.nq.gz
    ├── 669af21d3f94918a3e672ee0514a5b00f7373173.nq.gz
    ├── 66d01cebd5c9093ee5ffe5d656cc826738a178d4.nq.gz
    ├── 6a364a4eae84f06cc6e606d832a3f52e672920d1.nq.gz
    ├── 6ae6ded3413f82525895d2e462e99e4eb278e8b1.nq.gz
    ├── 6b2c055689decec0bfdf494fec69ab654e6391c6.nq.gz
    ├── 6b930c68145fe2a03f9200921e309fa9af9899de.nq.gz
    ├── 6bf9413e49af9ab0a6b2a830ac531d46e47980fc.nq.gz
    ├── 6cee71a54c99570bce47d2cfdc00e508da119d55.nq.gz
    ├── 6d14aa138af7d46cc951bde342fef4d0f0bedda4.nq.gz
    ├── 6eb1bf3a4cd211c059f2dcda2073d76296c19f3c.nq.gz
    ├── 70c643afc08640292c376264575b2cfa0f3e01c7.nq.gz
    ├── 728fc27167d529fa8896d62de1512e89248d557e.nq.gz
    ├── 736562d42103fa4449dd52a81c18715bfdd16f4d.nq.gz
    ├── 73711ba4b782fc6ef9e06f5a6a61f754feb99125.nq.gz
    ├── 73d8bbe57febcef29499393ef9462ef407151af2.nq.gz
    ├── 758a494e0dd207a70a1b7b989adda9e8dcaa9e09.nq.gz
    ├── 75afc529803a2e417e8e9d4fd78531760b019389.nq.gz
    ├── 767ea3302899ab11d06a89993d089ea14351d651.nq.gz
    ├── 76d945b603936bde1b4639617299e18c6485ab66.nq.gz
    ├── 779b8d96599ddcf2960eaf80b212c5022d4b7469.nq.gz
    ├── 78ce3feec7b4b6a8bd2e3ac8c88c05af6db1fbf0.nq.gz
    ├── 78eb05b06ca1b568e37b9dfe2c4ea6a4991f9d47.nq.gz
    ├── 793830b91185aebbee36261afda8eb5a79ab2cdd.nq.gz
    ├── 7ab2c36ce4b1620057fe9566bc7cb89675cc9f38.nq.gz
    ├── 7b8577b071a9d21bd65a3a38aa52d1c5d313d884.nq.gz
    ├── 7be5bb61929a13c9eccbd95da7a9ef1232a5a6bc.nq.gz
    ├── 7dbf4dd20c23a31e02550f7d871a4220879af449.nq.gz
    ├── 7f2f8d0a1adbeb95c2dad6ac25a2992963730ac7.nq.gz
    ├── 7f8fe061d77ab037a93884206232f6c56c4928c8.nq.gz
    ├── 7fe9758c12d5cf0d04e13e4817b2ed3ecd87a9b4.nq.gz
    ├── 803dfe43767f59701dc5f157729aba60f79f58bb.nq.gz
    ├── 81107f65367050f07964cf46298451e8132be978.nq.gz
    ├── 820e60f8b8b01c94f73a5cb3f741ea079b19cfda.nq.gz
    ├── 82179235b2d0947cee62b3e185492f08f7159df3.nq.gz
    ├── 846c49672e775298d4a5487dc8854b9e317533a6.nq.gz
    ├── 8696094044d61e877bd51f8649ef1dc9b59eea08.nq.gz
    ├── 874aab4659d4e264591b9eca570c26db649f0180.nq.gz
    ├── 87bbdb7a654541a4527b2de374cb281172d0c0c7.nq.gz
    ├── 8891f04192d175b4be5147f71bf8ab96e61f5f2d.nq.gz
    ├── 8929bc835900d1b68e0abb9f525392448ee9ea68.nq.gz
    ├── 8988686ac9ed49a7b6b0a432a964425946fb579b.nq.gz
    ├── 89c601da73186bd239747420904edee42567e536.nq.gz
    ├── 89ddfdb2c2ba7ea9a06be3bc9217a8386852b7ac.nq.gz
    ├── 8b77134a3d1dac6196419f847885a126d83bc540.nq.gz
    ├── 8c6ab8c3be1a914132bc30d0df6247a51649c7c0.nq.gz
    ├── 8cb6697876bd2657d4530ee123bd24d04dad46a1.nq.gz
    ├── 8cf23184293232a676139923a591b1a93cd235c3.nq.gz
    ├── 8ee7e83ad3b497b52242908b33a30a8b8c8790ef.nq.gz
    ├── 8f5dc1720639d07e0fc82f1819daa46e48f63cf9.nq.gz
    ├── 8f62c5058c2b26b516287fc54b2c359fcff3fa66.nq.gz
    ├── 8fb235d7045be0330d94bcb3abd2ac43badaa197.nq.gz
    ├── 9334311b47d219650fb67f9c1cdd0034c748fcbe.nq.gz
    ├── 94544341896d3cc267ff21a313fffbe8460585f6.nq.gz
    ├── 9572dc14734d2578a42cc017f5742d071eab4d76.nq.gz
    ├── 957a89ec03d3e8f529b47df76a0064c6aed265ad.nq.gz
    ├── 95dc9c560ce44a66d1d316e6de020fc644a0df39.nq.gz
    ├── 96ad955cfee70cea40c0f5b6501da48fc5293d09.nq.gz
    ├── 99a86f4d4ee4370e7b635db40e968fe5a58a525b.nq.gz
    ├── 9add7d77b96efbb166aac0006bf01cc024032e47.nq.gz
    ├── 9b8399cd48f7036b9cf5ba61f0a13d0813359db8.nq.gz
    ├── 9bd7c86bd19eb4d51fc1566cf54671a6e9c8c04c.nq.gz
    ├── 9c5119311f1f8eacac6007442164d95edbae0a17.nq.gz
    ├── 9c6a570276ce926c6ff84e86f10fa73160748c67.nq.gz
    ├── 9d217860f5562037a851fa8425700165659c5e92.nq.gz
    ├── 9de571079fcc42165b5b6e3bb2698ca9d272366e.nq.gz
    ├── 9e1016cb605045ace2bb387b7c5db7d3d230f2a7.nq.gz
    ├── 9fdbd18e02e664d9284b4569c11f5714dc265b1f.nq.gz
    ├── a0825a141994f896ad36c77626f8f55e1701553b.nq.gz
    ├── a0891c2ab5dfba7608731840fddce58635008d3f.nq.gz
    ├── a2344414e20a7458c098ea9f44e95ecc17434b01.nq.gz
    ├── a2e9633cec456de94111eb6fa2058e05ef802d86.nq.gz
    ├── a3100eabe6aacbc490a2c79bdb8e81c1db0e8768.nq.gz
    ├── a3686688da527b60b142cc23d6f48d6dacb5afce.nq.gz
    ├── a42a9e5b8a22bf72d76519e32a84824a818864b0.nq.gz
    ├── a7cfe215e17b85fc228b56d8fc689cf97fdfd237.nq.gz
    ├── a80e3bf05d4244d7ffb64f2e2e00c9d8a73989e5.nq.gz
    ├── a98a7ecea92dff72f805ee65b064280fcae18928.nq.gz
    ├── a9d5ca009c5124ecadb444ff5dace2ae87172c39.nq.gz
    ├── aa96eb33da1ec56728f627d9f8ca3dd3ad30d25a.nq.gz
    ├── ab22ea6b85cd666d139b5cc88e94106618e1fac3.nq.gz
    ├── abfb10ee3cb5f6de331aa65830a2dea6a9e8d425.nq.gz
    ├── ac29fd0463113735f90b51a190a359fd7a188969.nq.gz
    ├── ac43cc0ad61e4ae3d4a6592854e3af90d145577c.nq.gz
    ├── acf9e857cf358726e9c70555587e22483ae7750b.nq.gz
    ├── ad0695acdf4f65136c034068d3b3d019969dc779.nq.gz
    ├── ada322bd6f8483b10fc905a8627954440f6c8b5c.nq.gz
    ├── adaeb11331c38371f11bb4735aec4f7bfdda1df0.nq.gz
    ├── af18140eac33943bc09f7d0f77c2c4c2ecf49fed.nq.gz
    ├── af8ab47bf363bff08c533a11a76f22cb4ba4ec66.nq.gz
    ├── afac5ba97dce9a693333bc4568103cfd2a5f6de2.nq.gz
    ├── b12db2ba87cc3c3549f3047a989a63eb1e3ebc27.nq.gz
    ├── b15bba3adbce8edccecbc847d7ff4313ea054a60.nq.gz
    ├── b1caf7539d98e59e042a87bee442c01e5d6ae456.nq.gz
    ├── b2995441b749f4037bf6791ec51e9fe53fa08f01.nq.gz
    ├── b2a6b724b38b74d0fbad4a2b206c561e19a0b755.nq.gz
    ├── b420e05674dc449309441de725df790920ece731.nq.gz
    ├── b4e5636a4f109e579f4a3cdebb719af9c6bec906.nq.gz
    ├── b5aafef2541f49a0738e85e0cce21384e7df63db.nq.gz
    ├── b605d4b6c515c5f81e0d6e7b785f372786628b96.nq.gz
    └── b652aaade37fcc40e9b3d92cb75c704423942bb7.nq.gz

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

[holoviz/hvplot](https://github.com/holoviz/hvplot)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
