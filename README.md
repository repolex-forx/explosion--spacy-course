# Repolex Knowledge Graph of explosion/spacy-course

RDF knowledge graph data for [explosion/spacy-course](https://github.com/explosion/spacy-course), parsed by [repolex](https://repolex.ai).

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
rlex download explosion/spacy-course
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 77d8ee1630788b1fb0df1f80f999f7355941a37f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 77d8ee1630788b1fb0df1f80f999f7355941a37f
│           └── chunk-001.nq.gz
└── blob
    ├── 001d4207eceff5b2f2b04ca25a3a2336de1dc823.nq.gz
    ├── 003b2760568b21c051d4bb24453d87cc1a4026ce.nq.gz
    ├── 01fe8b05b65e795bad28853a273bf160e0e99a25.nq.gz
    ├── 03e9477ccea669a1ca17033e87a35272928b906a.nq.gz
    ├── 0417b01c69983c00ebbb800136313364eb69f121.nq.gz
    ├── 049024ba76e4c96bb18b177d632060d4cbef1066.nq.gz
    ├── 0515849203797c67c987bc04c0ec7f7c71299260.nq.gz
    ├── 055dd22d280df572c6e3e0ff0f7c9688fddb1a70.nq.gz
    ├── 058b483f534a3160dd57445f96864ca454b7a563.nq.gz
    ├── 05fc01f819eef298c297d8a085dbe2ff01dd6c22.nq.gz
    ├── 06430fe882c0f3bc12e2d006a6205cec73992046.nq.gz
    ├── 06e42f5aed5612e4527f239ab1f16ffdc05e6bd7.nq.gz
    ├── 07858368a365a7a488bf8c0dc9ed71f2f532f66d.nq.gz
    ├── 0896817bfb41a31f32991a7ed17c25c33ad6e529.nq.gz
    ├── 089e2970aab9a0fd7a5b81d52323da47b77ea67b.nq.gz
    ├── 08a6cd2286db1d6576bccfab6dcecb0c79695885.nq.gz
    ├── 093873e74a9354c45b70299d4b1f85f0013a64a8.nq.gz
    ├── 09db4d606c6314ecfebec4f81b6e80fefada978c.nq.gz
    ├── 0a5e5f501b6b958ec33375a0e46f1d246c94a7bd.nq.gz
    ├── 0a842d836f191e11317e1fa59ed07d00634a65c0.nq.gz
    ├── 0a8b24b640abbd39ce33653ac26f8d00a0b9dc99.nq.gz
    ├── 0afdfdf97d3cf48c11ee29e0d541677da45bf42a.nq.gz
    ├── 0b1d2b29470c8051c080fcf4d7552976b5741866.nq.gz
    ├── 0b615b87be6f38b72d413e5bb10d973b25eb70ee.nq.gz
    ├── 0bce523ed74d7e6207a5212536cd0fbcb7bde80d.nq.gz
    ├── 0c5de500c09e1bd2908c3b80d441bd00c00fe343.nq.gz
    ├── 0ca84fb949fa063400be5b4285bf3478880c44d1.nq.gz
    ├── 0cd4af032aee5c65dd06013b7ce2e17034315c83.nq.gz
    ├── 0d1b4cdf53c2044981422c0285f2494f0999bed3.nq.gz
    ├── 0fbe222c98df74b786f841c8d2660d09dc153bf4.nq.gz
    ├── 0fc1271f0c3a7a22b1c3d7bde70c5131a720d199.nq.gz
    ├── 1049be9e97b6ca84a53dff6f59aad82df2eceb8a.nq.gz
    ├── 106892414211ce3851002551355ce4fb6bfaaffe.nq.gz
    ├── 10face50ae09577fee88e2d52d82d06936eb8c83.nq.gz
    ├── 122f87f126ddb07f86297d85ac59780e891e926e.nq.gz
    ├── 12c70b72cce7cb45a63a764b85fa9fc3035ff2c7.nq.gz
    ├── 12efa41a96c7f827ac899be16d3af8940936d786.nq.gz
    ├── 149d170d5ca09a0770969752a63fa3165ac08880.nq.gz
    ├── 14b1d4266bf7ca28f419729a61aef1487fa92de9.nq.gz
    ├── 14b55e349e33fe30b099dfa90bfedda8dd72e942.nq.gz
    ├── 1571a0b85835ed2e4f49d3d06f331c8a311e704c.nq.gz
    ├── 16142ad05d886ef22a22af843e0170ea03fafee1.nq.gz
    ├── 164a43ed6a2cf4b3da3b2b1a7272de7dc8703d3e.nq.gz
    ├── 16ae5b78502f14be5cfad458c4852624461a11ca.nq.gz
    ├── 16fc2412b6d6c91c4d1fd1b02396ceb30a5173a0.nq.gz
    ├── 1722e093eaa62791fe351c5748f7fe27984321b8.nq.gz
    ├── 1774f47844ae5619ea9aec1426ec92fdb44eb39f.nq.gz
    ├── 17bf88a97b09f78ddf96ce46213137868e5a0e57.nq.gz
    ├── 18b878ccc1660aa428a8bc9f962f03c3c5d08853.nq.gz
    ├── 18bf2b7f0236448d9b2a23b99393608657cb5169.nq.gz
    ├── 18d3d6e82f441a9cf12d9590f41569ef5076d8d3.nq.gz
    ├── 18ea85aa1f9044703c2d73f43db37599ef80941c.nq.gz
    ├── 19e93f5b77f459cf261451906af9ba8518c2c810.nq.gz
    ├── 1a8509dcb44060d6f5273f27417ea74b7a1d5c85.nq.gz
    ├── 1b0351740f00288f721b02538a5cd70fc1eb2ca7.nq.gz
    ├── 1b4f24fd399c27142bc212391b02490a9c58778d.nq.gz
    ├── 1bd02687dee5a35b3c7c1c0fc13b8637f504049c.nq.gz
    ├── 1ca54bbde147e19c1a75f937c106d819822541f8.nq.gz
    ├── 1cdb7a0655ff586b1b94c67bfd8e2443d74fc01d.nq.gz
    ├── 1cdd3c8e6ecd3cfa8a50a5e1d0c7d84791824720.nq.gz
    ├── 1d15e374c4b127113929c5eeeeaf86176d572d87.nq.gz
    ├── 1d1bf5386148c795bfcb7b317cde2f59a3ea27ff.nq.gz
    ├── 1d275e1437d81582c334e3bb7ba448031d3fd580.nq.gz
    ├── 1d6f88dcce0149e31af4a73c1cc51b79d532d6b5.nq.gz
    ├── 1da1ac0b5b81f3976afdebb534ecaf177c0400a4.nq.gz
    ├── 1e1faea0911f4a309f0a9f933ae361b024291492.nq.gz
    ├── 1ecc95dc6d679b10920d6b8fa1d98b33af34f0db.nq.gz
    ├── 1f2334b3e213b22d5616173c8e7688a111d0f4f3.nq.gz
    ├── 205fa2bc0a7d268e15e069284dfa73c92bd1ce33.nq.gz
    ├── 20ae8795b2d44735bffc10c7f4e5a7a871e09a05.nq.gz
    ├── 20aec21a3d1ea83d5ced424ebc81e9238f3b5898.nq.gz
    ├── 20d386fc2112668ab14a38057c79b5b6439bcb31.nq.gz
    ├── 2224a8e3cfee5de722c8f5b2f66ceabeb788a38b.nq.gz
    ├── 2287b00d954e2783d42ac24936ee3e1320549ebb.nq.gz
    ├── 22f54650f76218478d169e81cd86e03b277161c7.nq.gz
    ├── 23984620fe623a39df4f5656bafec738ab409d21.nq.gz
    ├── 2447fca9a5fd43dc61fe029ab3d4b12cd8b9978c.nq.gz
    ├── 24da65231c1fdb0bbbaa4ba20aa350fe6c491d03.nq.gz
    ├── 25b17b4710c51dd90d4a237232f2ffac825bc4ba.nq.gz
    ├── 264cbdb9b1ad966c685a7781f987063c585d5776.nq.gz
    ├── 26cd6959af153cc2daa4873ad371ec87263474e8.nq.gz
    ├── 270efca34f3e7d1885851fc74d30e40a777e400f.nq.gz
    ├── 28343f47e7576637942ab0c1246eb00f7b85ddd9.nq.gz
    ├── 284ccd6f30db2bb8a4a2d2bfb7ba9ad4da325235.nq.gz
    ├── 2878a9eaac0e94a76bb3b6ebc2f9c50c81f95d3d.nq.gz
    ├── 2879cddcafa1162a256b4ccbcebefe11e27a1416.nq.gz
    ├── 28da743abaa02b19f3ac09e6f2aa6b6334a852ae.nq.gz
    ├── 28dba0b69ba8dadddae524266d68c933f7e1cb69.nq.gz
    ├── 29068a4e23c4cd10b66532441c893cf2582d6c49.nq.gz
    ├── 2a145ab11f78cc5615c8d4ed402ea232a50a31a2.nq.gz
    ├── 2aea48bedda7d2dd1772501fc2c35824f6237584.nq.gz
    ├── 2b2e932760f30834fbc2be31a0a6915186b7e347.nq.gz
    ├── 2b7e7f9b0f7f6be3ea1c982a6611517906c3d121.nq.gz
    ├── 2d76067f416c1549a27a8c601e00ef3f3abcb574.nq.gz
    ├── 2e43178d281874e239245d502646103d18a6ffd3.nq.gz
    ├── 2e5e385754066e473b97d98250868bbc81c3752f.nq.gz
    ├── 2e7c9c77224b1efd68e9319d68d98f4238426240.nq.gz
    ├── 2e9df15a9a7667673a41dd43243647ed87da196d.nq.gz
    ├── 2ecd36dc9848e2121dad50e0f2bd1559cb191c4a.nq.gz
    ├── 2f403392ea9f21f7d826f9b6545d6d8fe22486c2.nq.gz
    ├── 2f4c19ffc607b7a383a3c6f9f71701ace5ecbd36.nq.gz
    ├── 2fbc7110f4f946f4479873a78626c0ac31c39eb6.nq.gz
    ├── 2fe52696624698a7fdf57140f328063c22d890a5.nq.gz
    ├── 300890f74cab58ca1b176a3741e6c79142cdc605.nq.gz
    ├── 30fb14dc5a68e162f6fb026aed2f2928b02cc418.nq.gz
    ├── 30fecf7301e8386919f03bc084075f26f0f1b28b.nq.gz
    ├── 31297614398652ab3c8812ecf7a567c2c362828b.nq.gz
    ├── 31998d91cfd8ebc5a1c6b26b0191581c8a92c5c0.nq.gz
    ├── 322db6476ca826907fa7b02342649e4034562514.nq.gz
    ├── 32999dafea0f41ee943250708c2ab20b715b9f9b.nq.gz
    ├── 330e448a439ab8844a70e174661451d2b96a533d.nq.gz
    ├── 337a04a981b888ecc144fda915dad0e0ca9c46ed.nq.gz
    ├── 33d8cfa4341d2fb16a6e62bf67bc7e9ffbad0d96.nq.gz
    ├── 3466c2a074be08f6e5dccee9916775415d857ee7.nq.gz
    ├── 35f9130c547d7eff92dd851760d76fa89b81edc3.nq.gz
    ├── 36f755a8ee63bc04740bce15cdf1f445ad6a2c7c.nq.gz
    ├── 372da5645b1ea814ab8129da4a635931193f4c9b.nq.gz
    ├── 37323ae717115ab23099563d22fee5282991828f.nq.gz
    ├── 3752ca1fd572e535315ace8be2576a49588e98d4.nq.gz
    ├── 3764cb4f54759840252a3b22b6dae967823513b4.nq.gz
    ├── 37df3caaef807219ce2c45ebe8315ba895926ddb.nq.gz
    ├── 38995ecf58067f7ae70ff281709236de19149c49.nq.gz
    ├── 38a8a5d7406f706a5d55ed0c4ca1077fe2dc018d.nq.gz
    ├── 392e541c95003e2f2abb919e7b011ff2a4bc2b3e.nq.gz
    ├── 392efc82961adf2b2dc6a6d93a5feb842d8b09b3.nq.gz
    ├── 39de0676c128fdf0696b4e1608fc0b8920f7a939.nq.gz
    ├── 3a52320a7375a1f2d61bd2de6ee3b0ded8b696f7.nq.gz
    ├── 3ac04e66ab6b4535a5e9af3f17be3a49490a5078.nq.gz
    ├── 3ac3c53fa029fa13b27b56e94ffd701e32b23a7e.nq.gz
    ├── 3ad1f0c13eb227ea3bd1d8f374e538055073ca04.nq.gz
    ├── 3f19e98cbeb3e68807482b995cb57f4fe6012540.nq.gz
    ├── 3fb6cd5a967e45dd5bcbc62ea55ec40d991a7171.nq.gz
    ├── 3fd8995d9eb9db735a84221adee54574864f8475.nq.gz
    ├── 423790bc149687f73ee5c732a7428e43f3f28feb.nq.gz
    ├── 4240d2e5c1682244f94737376666eab24b77a9f1.nq.gz
    ├── 425f13d814b5b58f5bbefb7f118aa82d100a7095.nq.gz
    ├── 434d4f532491df6f1f2e69ef3cd285c2521056a8.nq.gz
    ├── 445452238a526ecf8f34794c46a8fe7c27609edf.nq.gz
    ├── 4487b0b25415b690bdd59b9f5f660471c61dbfd0.nq.gz
    ├── 44b90017aa751458d8491bd5152aa9072add9c42.nq.gz
    ├── 4556391b9807934eeb94e994dd67845650f2ff9d.nq.gz
    ├── 4572151d53e8d12178a2ca81622645d5aa8372ae.nq.gz
    ├── 4591c674813edf0b5656754aed0081e63ac09205.nq.gz
    ├── 470ad443f1450640814523f7ac2f201501fa42dc.nq.gz
    ├── 48d747f6284d0022f94a894260aa070c9a83a1c8.nq.gz
    ├── 49922e29752f152c073daeaf6d11cf4d469fd975.nq.gz
    ├── 4a2d23b55a23e5ab6f45525243067064eceb54f4.nq.gz
    ├── 4a6c94c2bf8740b6d89260eebf1323bc5d3c3180.nq.gz
    ├── 4b49bfe294c65863344e4450f6ef714d129d7ed7.nq.gz
    ├── 4b7b961d745bbcd2aea6236965a285c7d02ac049.nq.gz
    ├── 4b8d88bc97988751718ed87250c9197c07f94dd9.nq.gz
    ├── 4bca84fc7423fb1ac0e9827eefb5094f89bba0fc.nq.gz
    ├── 4bde7f91baa6e5819d9c6d9797eec90606d8c3b4.nq.gz
    ├── 4c62a96f5060f9da9a3c375370c7f35ebb690b3a.nq.gz
    ├── 4ca2c7506adf9228720bc819c1b169828ad348ce.nq.gz
    ├── 4ce72fb0813ee0cd38a07b4493ed2bf9b910a547.nq.gz
    ├── 4d402c10b7ca70be0a153a4ab0bec3214c55e5e9.nq.gz
    ├── 4d73f2aab34be725b6e91ed6f5a250c5b2ba2e85.nq.gz
    ├── 4e897d6eb55836ee3781778748d4e568a3a73009.nq.gz
    ├── 4ea31b8db03457a55c7900bf50cc89367306d7eb.nq.gz
    ├── 4eb2f6dd2fd8ed60fc69b094fe48346b13b728eb.nq.gz
    ├── 4fcaa88f606dccf2f0dfd441e11c4d85b6828d3a.nq.gz
    ├── 505dbc6c10a4d932cf2ca2dbf4ccfdbdd854ba93.nq.gz
    ├── 522b113148b15e8486a5328542f380015f3967dc.nq.gz
    ├── 529feb9df9bbf37a75a9ce6406748debc758b09a.nq.gz
    ├── 531e540169edf3681f166bbee9c7e08ac1e776ae.nq.gz
    ├── 532df0cc71fed912adc1d5dfd16dfc13a7e589ec.nq.gz
    ├── 53d055fc32589853ce1bf0234c0b1339db5493fb.nq.gz
    ├── 53e1697cdb5aa905c897c9b7df6de7b9279deae4.nq.gz
    ├── 54b6476eefcbda9c14181ebe6841c57ae72c5fee.nq.gz
    ├── 55a457bf899e38a559d3c4455c8d221825764a7e.nq.gz
    ├── 55d9c1f5cc11408bb3e4142e9d436197abb9a9b9.nq.gz
    ├── 569488138911262f4b1392cb7a8e883d673af59a.nq.gz
    ├── 56c7e8a0ff595fbbc6a45065dedb818366a82af2.nq.gz
    ├── 5727334679e0fba7293a5e78e5b0b6ce24497243.nq.gz
    ├── 5729590f6da7b58994bb28a2296f035b3d9aa14d.nq.gz
    ├── 581f59e25e55cec1f11c3ffe3a417dc83c9cdadb.nq.gz
    ├── 591bdbe42be566fbf2fd1c10043a0c732eaf5b5c.nq.gz
    ├── 59941cf0ac8521e04b9a24f5993f441b4727661b.nq.gz
    ├── 5a3ba5fb28cdb435835bef0ac3b93ee6503fa9cb.nq.gz
    ├── 5a7e89ea99485fdfe11232f18d5f2e849a57de5d.nq.gz
    ├── 5ac9a4be9c3d8bf4ec9986ef1ccc708f58f648c8.nq.gz
    ├── 5acc788f411fcdd72794b090eb4227fda86dd3b9.nq.gz
    ├── 5c9a88b12858ed304784d4b39e834c954880195c.nq.gz
    ├── 5d9aa3b6387c411002934a8a1bb9b701f4d69ba6.nq.gz
    ├── 5f9afc1bbb704c0c0bfa98859f9a8d40374b9049.nq.gz
    ├── 5fce795fdc035310cde692a2b9bb81281351f25c.nq.gz
    ├── 60d7218b31cf98b37203047fd7f345d3b6055f31.nq.gz
    ├── 61007021ce468cd105c7a6f87bdb12c9dc3adc26.nq.gz
    ├── 616fd607670c1a55163fe00306dc0d930744f38f.nq.gz
    ├── 61ba284f73b80777e2a86f4862578d9babde59f5.nq.gz
    ├── 61e2be87d610c1f6dde4754cea09eb1807555787.nq.gz
    ├── 62006a9006134559cbde2e01ab25eabe2b71c9e7.nq.gz
    ├── 62366de4f890a7d34b1eddc66476dd0c81cab820.nq.gz
    ├── 632926d5139773e24ea96fc906761359e1829640.nq.gz
    ├── 633cbd52ec783005008c2a399fadb8f8a4a9472d.nq.gz
    ├── 64f9cbbdc7fbf8cee82ae653f0ce107dd26d2d41.nq.gz
    └── 6518a9ab3f4635188a15be561eafc295fffde66c.nq.gz

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

[explosion/spacy-course](https://github.com/explosion/spacy-course)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
