# Repolex Knowledge Graph of microsoft/debugpy

RDF knowledge graph data for [microsoft/debugpy](https://github.com/microsoft/debugpy), parsed by [repolex](https://repolex.ai).

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
rlex download microsoft/debugpy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 54af3783b144d02a0978534d61f411ec7b5305a4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 54af3783b144d02a0978534d61f411ec7b5305a4
│           └── chunk-001.nq.gz
└── blob
    ├── 00188429fda80b59f362516ec0ad6ae703b60766.nq.gz
    ├── 030e303ee89aaeb2a714ce6b86c417c8f2318f5d.nq.gz
    ├── 03aff39ad17089a92dbf22ef05674632ddbb73b2.nq.gz
    ├── 045325b232c286169b756a998ff26d60df8a6053.nq.gz
    ├── 0525536ad86c7135dc5cb241a6ad0efa0e5334d2.nq.gz
    ├── 052cac64df80cb19fb9fe3d7fbfc21c6c22eab6a.nq.gz
    ├── 0651754ba88d487019f8d4290d0ee7343b6eb597.nq.gz
    ├── 06c500e62acba4fbc1401ad9667f9c3fdb3572aa.nq.gz
    ├── 07d359d07cf1ed0c0074fdad71ffff5942f0adfa.nq.gz
    ├── 07f1ca703e5c5aa892e31c0b5ef9f302015bba11.nq.gz
    ├── 08c7cb264ebfdb6d72402ccfeb3b358e091f5d5d.nq.gz
    ├── 08fd02a7a7f013ad6a56e6c45ac840580c412e3c.nq.gz
    ├── 091149c1ffe3444b596ae99dafd71dd986a54cd6.nq.gz
    ├── 092102ad99e986e260a0400fc9310ac372efae6a.nq.gz
    ├── 0b70e1eaabcd09de76ec7bffb7694ef450202e14.nq.gz
    ├── 0bc7729bb359e40fa1844564db4fee5a7be6d836.nq.gz
    ├── 0c4dd3c4ae3ca1ac178690a5cdb02875fa1d9a43.nq.gz
    ├── 0c7bafbbd2cd4b317664a60afe301b548e231374.nq.gz
    ├── 0c8e600ca3632c9b3a2de2a69eb9c43f40949326.nq.gz
    ├── 0cb797e4095c083501b79979d097de3a292ced2f.nq.gz
    ├── 0e3100d3f0b0a6cd133653e467b4cce2a5825bb3.nq.gz
    ├── 0f19530d2dab7a3b82b5f0dc2b29fc08459b8eea.nq.gz
    ├── 0f35b8caff2c209c97ab55efd287b5daa1b671c8.nq.gz
    ├── 1049be0dd6357e8a59e8455b20d3822c2971260b.nq.gz
    ├── 10ed50d92df99f5cb9b2f9e2164f6cec1e018ab9.nq.gz
    ├── 1215d125c419bbc7064eb8af0b1eaf6e71da77eb.nq.gz
    ├── 1289d6450d7b000a1d3252ec0ec3c6a510f56cd1.nq.gz
    ├── 12c24d071b8e604d61c0420f939fb7263e4c69f7.nq.gz
    ├── 13372aef5e24af05341d49695ee84e5f9b594659.nq.gz
    ├── 137382274274d1d142a25e80e28a1bb1d60f9da3.nq.gz
    ├── 13a01b2ee1480c4ae258341111d3a15241f7bf1c.nq.gz
    ├── 13f999ffdf2d09f6c88dae759af8debf1199ef9d.nq.gz
    ├── 1447da7385c95867bf12c16a050c98afc28f9dee.nq.gz
    ├── 144ad24aa9b4655ee68685ae437c03e76000b4bb.nq.gz
    ├── 147872a33fd551740998ad329a9ffc01def54fbe.nq.gz
    ├── 147f0f8f0b21e05422d624a7472f413af96105e3.nq.gz
    ├── 14b9013c5a2f47a87bc2d0aad6cc6ad7962cc57f.nq.gz
    ├── 14ca964651e682de74f2ffeeb135d22f7e7c8c4a.nq.gz
    ├── 14dd4ddda14508d05de377c41ec1f1eb388fff68.nq.gz
    ├── 163d17358e5882bdf91ae55811aca881ac9595f7.nq.gz
    ├── 168cdad7fff4417015fe14f41ffcd227add786e0.nq.gz
    ├── 177b055d5e1a6c4596b1a0f80125aae98c47d975.nq.gz
    ├── 179424f80a5a2b72f549a499f478dbff48589a4d.nq.gz
    ├── 17c07afd0e943fa1b24a233e06c906eddd231024.nq.gz
    ├── 185d417d80dca8638c6b390b2333e1778193f862.nq.gz
    ├── 18c4f7409d7a6b66665ed9679d72b3b825de00d7.nq.gz
    ├── 18f537a63fee50d74ba7173c68d96557ae19063e.nq.gz
    ├── 1915fd43c0c1a964fac54cc42678101d4af4c089.nq.gz
    ├── 196f15eb5dfca88c3d5325e794555dc29da04831.nq.gz
    ├── 199a8cd747e7b5f4a79e4936eed8614c2fab1317.nq.gz
    ├── 1b4cfb3e164a323fccba007f02dd3c5a72a6fa6a.nq.gz
    ├── 1bbf9f8acd63b9ba7aae2a2a67394ea49eb67369.nq.gz
    ├── 1bd5b74b7590461b7fd6cad180084a57a9607810.nq.gz
    ├── 1d458268ebf88ffd7764dc26c5f9a4cbdc6f1637.nq.gz
    ├── 1dd827abf2cf4efc91a2052f6060630efccf6492.nq.gz
    ├── 1e58234e0b4260d3221d4ecf59923522540f1ccd.nq.gz
    ├── 1edcc1bc22323c43cd64297f70ddabfe68a61ce0.nq.gz
    ├── 20ed4e02a6abfadb02723e554d461fcfc6045796.nq.gz
    ├── 213a5b9d8dc0e134e64aa9e028606789f5ebf563.nq.gz
    ├── 2156245ad218240e914c08f107cca3c5acbe06d3.nq.gz
    ├── 2168c860805dc70f9c28ad23a970847e6664230e.nq.gz
    ├── 21a0acaf29a7054e97fca0478dfe0ce5f15ca199.nq.gz
    ├── 21bf8365b75abe8701b297326e463eff1345a230.nq.gz
    ├── 21db9604de6a7e9108b5c3b9a0d7c4ca589217be.nq.gz
    ├── 225465fbeb3fe615fa84925228ed484f54ac276a.nq.gz
    ├── 23333b61335c95c9bbac4e9ab1e6ef5e9e34aa7b.nq.gz
    ├── 23e7d4f547da4cfac744ab926bbe0fd090264b7b.nq.gz
    ├── 243f763178378ece999cabae56218bb85a1fa1c9.nq.gz
    ├── 254e38fe18781ecf3c0863121e29b80efc7393c5.nq.gz
    ├── 25c0e77fbe227d2be6bd04152a9f06852708d02e.nq.gz
    ├── 26e4d7f17090f9a9d2d8b1145fd7501c8da07a07.nq.gz
    ├── 2762b27b04973e4d19b57f463baa0f8588d29397.nq.gz
    ├── 285a798b584a5c483c99f34a88751694242d586e.nq.gz
    ├── 2913b60cc60e3adc1df7e0807cb920a9ee2d5a6b.nq.gz
    ├── 29ab37fa44e5d5ac92f841901e8b956acc054ede.nq.gz
    ├── 29cdc5bc1078e8f16d409215090f60083f31a063.nq.gz
    ├── 2b309900e03998756e7670a134b1db5a24279706.nq.gz
    ├── 2d5ac30f398b722e3dd75992f9d680d16edfe270.nq.gz
    ├── 2ed3bc7f5e81d2325b0bf0dc9aa328da8c96b33f.nq.gz
    ├── 2f468050db0ea8dd85612426d80d9c3ed6f06ffd.nq.gz
    ├── 2fb0fc2678181b69063f1d50c72d4d55a63bd8ed.nq.gz
    ├── 31278215534d8420a4980653349a70ce876f68a2.nq.gz
    ├── 330e5e42efb43559299aafe59480b90f3555f72c.nq.gz
    ├── 3360e1f88f1f30a42c0e1ccbb1c5e0acc9dbad1d.nq.gz
    ├── 3378a7ebfab72366a06c85949d21050b08819b97.nq.gz
    ├── 34b4b6bdb825fc270ed62d9eb0d4f00604110914.nq.gz
    ├── 3599769f953f616c3097542db58bdd21c758f060.nq.gz
    ├── 370e37c9e51c04791150650e84032c5afc30d557.nq.gz
    ├── 3a1f0d4063d9be763d02afeed0adf7876efdeb56.nq.gz
    ├── 3be04b79615c539d79f6b31e0e37aae1e59a9967.nq.gz
    ├── 3c929f3b85714cc5beab989b8003b03a905aea28.nq.gz
    ├── 3cf8d99445088948bfb9410e330072cf600038e1.nq.gz
    ├── 3d77101d5e26c0ac7f94449e616a396c68fa0580.nq.gz
    ├── 3d998e6055c09ccc851f569794eb9bf1566f63a8.nq.gz
    ├── 3e579ad212c6b7c0dc458fdabc9fdd1fb84aed5c.nq.gz
    ├── 3f04afcd32fccc3cd2d665226313f2dcac03bbcf.nq.gz
    ├── 3f35ab5a1bac61300e1392fe8a4423dd13cdf322.nq.gz
    ├── 3f3b157e3fa7965e0ee2e58404effd349051c688.nq.gz
    ├── 3f5454788865267ad266db2bdb7979f8b8bb41a2.nq.gz
    ├── 3f5f2e1a4a46ac476a9060ac6762cb5304ef4241.nq.gz
    ├── 404f9712566f3f7af1cdbabd4a8dd43d8580d28d.nq.gz
    ├── 4050a92d5d3647757c4b09e948457ba18e835407.nq.gz
    ├── 40865b7c7dd809a52b68c7290a81fefe6b3f851b.nq.gz
    ├── 40b6af8f2b38d535a6b7b6b4a837bd0caebc3bbd.nq.gz
    ├── 41213f41c70cc11998e511b8d8543bc1715d5adc.nq.gz
    ├── 4151bde7919454d8e12a4385fcc1463ec7aec519.nq.gz
    ├── 430cddd967cf5e6f9e977df41af9ce8f976048e3.nq.gz
    ├── 432267293c9667c37a89dd24d0df6e8d6c0753cf.nq.gz
    ├── 444fc0a42ba3219dd960ce2e3e340a08a896a4f1.nq.gz
    ├── 455114b65a4e769be20e1c313455634efd2d94ce.nq.gz
    ├── 45eb070d1e3e9f695544625e43b99cce99247845.nq.gz
    ├── 460dfa8a0bc06550af85d1d05b9f4c6a5f89a18b.nq.gz
    ├── 4817b1aa73197a1f31e744c2b8b3d6fc8f06b5cc.nq.gz
    ├── 48cdb5dc689e0797fc90c9b8646e7c05bf601908.nq.gz
    ├── 4958251d89ae79663ef6640d7485a36cc12e56cf.nq.gz
    ├── 496c091921ddd4df5a855a24edeb953747b43c06.nq.gz
    ├── 4a4c25fe62ff589f84b2ed3a44399340df7b8808.nq.gz
    ├── 4a90160e073434c62d6dcf36051282da76306de1.nq.gz
    ├── 4a9b6949021f9398b2b6b36c645558b57bd053bd.nq.gz
    ├── 4ac447d37bce6f5efc9678248d13252d0480a11d.nq.gz
    ├── 4b470f5f87041d717d65f3bbb957a1617cdeffdf.nq.gz
    ├── 4b80b546671bb819c3d6f30465a2779d9756db7a.nq.gz
    ├── 4b8e913584fa93ec6758742ca85883fb565cf256.nq.gz
    ├── 4c25d8329095f03b76a6c8d02e8b9f809c3b76c2.nq.gz
    ├── 4c284292771b46c8d563c378a6d3819655fa54c4.nq.gz
    ├── 4c3b0052bef6a48390634aaea70a9d6bc110a452.nq.gz
    ├── 4cc37a112185acd726baff8762f2fe74cf97c128.nq.gz
    ├── 4dd4af94b56e2eed51fcbd475fd622f60b21648b.nq.gz
    ├── 4dd91368c40fdc72f3077eabc48c534fd24774b6.nq.gz
    ├── 4e0a2d40866f6a75c30c06a9fe4c2c03ec4cae65.nq.gz
    ├── 4e14e698c0d90cd65c64ce2bbdb37a6c425aea43.nq.gz
    ├── 4ec3f1fb36023eed67dd567879ad0ac99302cf93.nq.gz
    ├── 4ee2868c44ce361036c16e7effb45f180efc96d8.nq.gz
    ├── 4f204732f87e25f866e083150466b314023b10e9.nq.gz
    ├── 4f4656ea7b774d49f3749dfd1210ee39b73b71a6.nq.gz
    ├── 500cbcefcd48e88e4e97d27411c0fa2c23985395.nq.gz
    ├── 50471f9943b30edfe5b7c56d761e2c1bb3241bab.nq.gz
    ├── 50619e0358633485fd63244bf3539b2252e307cb.nq.gz
    ├── 508961b7c47ababb843217d81cd97ecebbabd121.nq.gz
    ├── 510f916a372830e023667afc6ea33dc71bd4a1d4.nq.gz
    ├── 515f4836297fdf7567c066983c16e5eff598f7bd.nq.gz
    ├── 51c5e6079add1489bdd4010e33749c6062808e87.nq.gz
    ├── 51cc859cc4a2a421e010c65c0da090538cfdc470.nq.gz
    ├── 52acfcc021ca4694edd2655d8d70baba50b750d3.nq.gz
    ├── 52c5c404e59231fc6f0db45adf48506ed65248b7.nq.gz
    ├── 52faa7c2dfec34a2e61eb2bf59641069620e5d83.nq.gz
    ├── 53d8689ea43b174970a52ce2c303eab6b797dd66.nq.gz
    ├── 53eb28c7e1deca712c76669293b4666e2b39e466.nq.gz
    ├── 53fea8ffaa248449e3098c43b4405b030d85d09f.nq.gz
    ├── 54133f3e782b524c187b632c9b5d303c6fc0b5f1.nq.gz
    ├── 54f9884deeac0bb0aebd3ff38c83fe880eb80cf3.nq.gz
    ├── 556bbeb99d57a175ec8912d84b0ec4a9f83efc16.nq.gz
    ├── 55a213420e6941750884375315c9b4771686dd07.nq.gz
    ├── 5622813acd0aae0418856bc1cc1a6224403715a4.nq.gz
    ├── 5632d14cb837a0949913754d3912cc2ba22b42c4.nq.gz
    ├── 56e177ec36c0b52718c898b67fabacccee779992.nq.gz
    ├── 573e280cc32b78aa7518149274555961e0493a46.nq.gz
    ├── 57497ce0e968b709dbb10df3188d936620a2a358.nq.gz
    ├── 5864e3ca897db5819ae4e447ab2f7a211d5dd0fd.nq.gz
    ├── 59530336c3c17fa622bb34da87ebc023b37366b4.nq.gz
    ├── 59c6ee88d1d2b503bcdb97c56156fb71084af719.nq.gz
    ├── 5a72ec9df41f978596cd9a58b9b72eacf379b402.nq.gz
    ├── 5b0c5d254fd70573cb22ca3a89e79bd95e6cf05a.nq.gz
    ├── 5b2b34fe6d7c454c71581166e07af30dcafd3b8a.nq.gz
    ├── 5b4bb849af9583fec1ea0a0ccc0d571ef49aa8ba.nq.gz
    ├── 5bc54cc33fdffbaa76c6575daea974ad1073f3eb.nq.gz
    ├── 5bcb88bb325d7a80a350f4f7f08bf343c9d9ded5.nq.gz
    ├── 5c9580fce47d0f95107c491e8c18af9e85a52fb0.nq.gz
    ├── 5cb77f676c5ab0a522157d0cba527f8967c4f9ff.nq.gz
    ├── 5d8f49faff1e792fce9b1d68ecdf0e63b6e4416f.nq.gz
    ├── 5fcd3a83784b54a54ce133cbb83cae30a5ea66ca.nq.gz
    ├── 605e83cdbd0884c112a1be00d559cec8ba5ec165.nq.gz
    ├── 6221725a3b60db116e40ddb14fcfc4c90eecfb1b.nq.gz
    ├── 631691ef3d3a3fed88c748b54c09cb7750041d46.nq.gz
    ├── 64296a82937d9046330a746b769a08c1aea2baf5.nq.gz
    ├── 6502c069fc858aa8b3e2e48edf86be6fb1b079aa.nq.gz
    ├── 65192b021b1002b359ba9b4fb1acc706d5575334.nq.gz
    ├── 65590f72ba50a1725890fecbe400c28293095d8a.nq.gz
    ├── 65c83c45817d3d28741f3753bd8f91cda2fd4843.nq.gz
    ├── 65e699b98e55e7bd9d98473ce0de7ae83e94d232.nq.gz
    ├── 66b9ba63fc071fc781676e936daf4e513d30755c.nq.gz
    ├── 66d53012637e8d08aaf20fbdba950a6a7ec60e08.nq.gz
    ├── 67f6a259a387d70ef92e8b04f092fc1fe25fa87c.nq.gz
    ├── 694baca3b2716e13373848f107f02cf4bde2b77e.nq.gz
    ├── 69739a190927d84e0877cdbb44c078c0c191a834.nq.gz
    ├── 69a2b23f527b3d1f9e4b8b5c1b5a6667f28acc8c.nq.gz
    ├── 69b410d636a35e82915be75034c5ddaecf31e914.nq.gz
    ├── 6a700e931c82bb9d7c4cc8e06432d288e301e7f9.nq.gz
    ├── 6a89f0d4460a8aa8bdc63ff44e4b3d642a53d6ec.nq.gz
    ├── 6ae6ad87be7ef4c40192300bd5b53ca8862805b0.nq.gz
    ├── 6bda76c768dd6a6dc323511dd082f6e71c81a803.nq.gz
    ├── 6c46f0bbeb195e3c601bf1f4a7a948a67a483bfa.nq.gz
    ├── 6dbe78fbf4acf765b145de483374f2e0f9b7a8f9.nq.gz
    ├── 6ec6d7132c13e9aebdec0cb40b09a22c1486a631.nq.gz
    ├── 6efe9712dce33ebe7e0fc58848e82bba32aebd14.nq.gz
    ├── 6faf573cd1daeaf9214a5d93c17902136877069b.nq.gz
    ├── 6fd70e20b1f3873f14ca951cf8990ace9925d113.nq.gz
    └── 711223894375fe1186ac5bfffdc48fb1fa1e65cc.nq.gz

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

[microsoft/debugpy](https://github.com/microsoft/debugpy)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
