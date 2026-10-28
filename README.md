# Repolex Knowledge Graph of huggingface/transformers-ci

RDF knowledge graph data for [huggingface/transformers-ci](https://github.com/huggingface/transformers-ci), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/transformers-ci
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 431b37bd4122d418db1d779ee76e5c5cdc63fbc2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 431b37bd4122d418db1d779ee76e5c5cdc63fbc2
│           └── chunk-001.nq.gz
└── blob
    ├── 00a85e4504cc0d8596d7b0171d6865ffabcd6486.nq.gz
    ├── 00e688e47c6e3affb7b464bc7218be5028d096b1.nq.gz
    ├── 010385b04a32a63d2e05d9a6a04701c5904b86eb.nq.gz
    ├── 02bf195fc05ee630e7ec4ddd7f838ba51774d9e0.nq.gz
    ├── 02d58f322355045ce770c257cd963cc11628ea58.nq.gz
    ├── 04636a70eabeb0df8d5e611f0069c0465a9cb5a0.nq.gz
    ├── 050d442dd323bbdad017d34d74db40bac74e9e4e.nq.gz
    ├── 062f2663b7964117ac15b5e1f5935cfacf91515d.nq.gz
    ├── 067b859fe8cd11ccf94e9aee5c2b8152b30bf30c.nq.gz
    ├── 073c5c313c0ce237b9d6cb62309c1c6eaf759233.nq.gz
    ├── 082f47191aef81f76c9aa97a775312d0426ad5d6.nq.gz
    ├── 094a9aa16e0633f471e6ca85af377f8b8939a08e.nq.gz
    ├── 0a273f808a58ca0e2a106d003e2c52d31ba79e49.nq.gz
    ├── 0a28970fc2dcc84c054165681db4a9c6c9ff8acb.nq.gz
    ├── 0b1206bff8ad821b3a3922454b6823ab35c0449b.nq.gz
    ├── 0c74e353e54b05ee55edb7636bf9e35c2ea5c401.nq.gz
    ├── 0da3d5cfdac34609b1f679f66614638e4af1be31.nq.gz
    ├── 0dd6c6df9d6f3939146964fc99691b8359fd3eb5.nq.gz
    ├── 0df76004a7548e0413c40e84bab5f280c82ca58c.nq.gz
    ├── 0e11117e67f8cf5271d4a7b96662b16e9fd431ea.nq.gz
    ├── 0e91050d11e8332d497e8f4b5952af621c576c55.nq.gz
    ├── 0fc32807edf13811a7e1727c212e0ef701fae58c.nq.gz
    ├── 10e2c4a9238e32fb4d48eb31395d8ca91277178c.nq.gz
    ├── 10f9949f8dbaafcec6a4170e12775d1db9d6944d.nq.gz
    ├── 132cff8d0511d4ab45da2879d7f57e3cea4b8a1d.nq.gz
    ├── 141e3bfd541921c8ecc9e52986293443b732a477.nq.gz
    ├── 150afcc5be869961ee83b6cf0bb73a87b61847fb.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 164ab52bd348ef47f8c888d62e94c428582f70ca.nq.gz
    ├── 17f9057b90b61f16fc9a724e5235dd8806efff19.nq.gz
    ├── 197db04f31ad7189e7f5e9b76be85121ee36992d.nq.gz
    ├── 19dd1d86baa2a4f12b2a67c0b5c91ef1f378188a.nq.gz
    ├── 1bbb704a1f5af53f1b1330890b100e15a6f6adcb.nq.gz
    ├── 1e0835b06b052f061a182b24598a07e9091e8839.nq.gz
    ├── 1e3aed5535587b16b95a094b29d1a5af71031130.nq.gz
    ├── 1fc7c48d012550296e7c2153ed4d790b18f75b03.nq.gz
    ├── 22cdd253c839266fda5b460772974ced8ade723d.nq.gz
    ├── 23439d54e1daa0db05f528d4640a45322c7aaf8f.nq.gz
    ├── 248583c3d7e2c846d1fd21e45b46f6a5fdc545f4.nq.gz
    ├── 26d520738caf405baeadf4db45bf65ee201d34c4.nq.gz
    ├── 28562c39ba0ba8dcf4bdfef67d409b60a4ab4176.nq.gz
    ├── 291d0af921485ba102b4a681f66b1f89b6f7c330.nq.gz
    ├── 2b6d58cc16cc7a632e7e77870b5e09af6d66373d.nq.gz
    ├── 2b8ae0690d9b3b528ae3611a45136095614529de.nq.gz
    ├── 2c2af05ead8a40ec5e7b33a93cf1d25dc8d35c40.nq.gz
    ├── 2c964fabf609f9ae4375fdae51ac1434a86a3112.nq.gz
    ├── 2d9c15b780848ae3021e82b000cfeb40b3b035dd.nq.gz
    ├── 2e3e5c73919c4c7f97df3fa84d30a03134f435ca.nq.gz
    ├── 2ebcbe1ebc0dff4358ce2fdccadb27ddfe8d9bf0.nq.gz
    ├── 2f1f85243ed7e10fdfc69b153e34a479d71f717d.nq.gz
    ├── 3073360b5650ca18a45e4f3ffc65a1bc379488e6.nq.gz
    ├── 33338aa5d357029163b99d3a7e18fac16f0dfc24.nq.gz
    ├── 33498e6fa9e7c68e42c7e07f10848c83d3157d36.nq.gz
    ├── 33ba95cf3181b4c6915bf40d72beaa5480461a77.nq.gz
    ├── 3433f2bf4ca9977d3201251eb0c0616cc0effb31.nq.gz
    ├── 34fd6547b08f60ba474b0ea295509785ddf037b4.nq.gz
    ├── 36caeb565838afab4150f3055c7fff897bb4916f.nq.gz
    ├── 3747244dbaaf0794788006d0d7ddb4c87fa2ed2f.nq.gz
    ├── 377a43bc9e622ece7a7175d3f266796952d551ae.nq.gz
    ├── 379496dd3d4638d0428034ee5b349af2b7469cba.nq.gz
    ├── 38499a39454ae4769393a7f9fd9e22b044cf7ae9.nq.gz
    ├── 3871f082bb25db1beca5df5ff15220688d72bce2.nq.gz
    ├── 39e80ee8b3d3915289f96b09a9c3d0eaceec2cfb.nq.gz
    ├── 3b301e5403745bcb8efa115204168297e8b87f95.nq.gz
    ├── 3c0336547cf0da754de08bd29df81d9e22e42418.nq.gz
    ├── 3d70a7fd7f001eb4b909b055a6067fafeeb3e852.nq.gz
    ├── 3e271e75ac55bdfa20eef7b559dae337a79fbf42.nq.gz
    ├── 3f8deb064314d0a2c9fecad673cb39e57c8beb64.nq.gz
    ├── 3faf4592da5f9a2ff9f64b42b5ed449f40c082c0.nq.gz
    ├── 409152f06f38dc2acc32ce62dc2c8d136133f4c0.nq.gz
    ├── 44473de714370a60e8f04882ed7ee29fdb79570b.nq.gz
    ├── 44481b1e3a0999d4f0cd8742d3552e6af5b1f352.nq.gz
    ├── 445392ef72482a906cb1a20cf3fe4a9f70c4691b.nq.gz
    ├── 4499feab0724348a3b77d8946ee87bdf18da5af7.nq.gz
    ├── 466a829a992c48bafa264104087213c1c174b44d.nq.gz
    ├── 48affc0361a95bf41b73ca6c87acf3f3fd24de28.nq.gz
    ├── 4927e3e80dc363a02d562cbfdf3821c4ebcc0336.nq.gz
    ├── 49f816fdac8ad072a22fefc8772771fbafb086ec.nq.gz
    ├── 4a2f19206ca078b0da6bc1d2e856623fa22b437e.nq.gz
    ├── 4b1c9c34e83130bf74a4349ed351360d33e8672c.nq.gz
    ├── 4b9db4f1474da24b4fd6737e2dc7827911becaa9.nq.gz
    ├── 4cb0032e485b3bd9c9dbc6d5d336579c51fd1db3.nq.gz
    ├── 4cd0446ed7342a05d76deb79822af1ddaeaf1cce.nq.gz
    ├── 4da2e22baf9ba835cae793b09cd1a3130a1a4264.nq.gz
    ├── 5280469e560ea1321d6c01fe13df235452d55690.nq.gz
    ├── 52a0ef6c825f21a75e29bc4c46b381687d13735c.nq.gz
    ├── 53fccf9a817cb43c0c51af760873f21fd4a9d70b.nq.gz
    ├── 54e660e3046833f700770497a008cc88651c942a.nq.gz
    ├── 589cb6c8a9668af8095b1eca24c797b2763e9ae2.nq.gz
    ├── 5907b9ce84cd5f85b0838e0c2f1027bd7f5ccf55.nq.gz
    ├── 59ba5528f231d7583d952bf516d637a8fd7eda42.nq.gz
    ├── 5a98d764528e0f204d67bd2a856c73a64a410001.nq.gz
    ├── 5ab76ed864f900e67c6fbb8cc640a665619d1607.nq.gz
    ├── 5b6472d187dd631336be601326ae35c14f98837f.nq.gz
    ├── 5c3d152b9b6f1f743bfe48dd97a23cedb7c1e762.nq.gz
    ├── 5cec479693d16d0fdb20f56f1eeb4d062ad84267.nq.gz
    ├── 5d160b2f2c0f1385ea943494b6150dc09e58db44.nq.gz
    ├── 5fd6bd487bc75209aea866da83a861c7c03e7b73.nq.gz
    ├── 60f979df24fcaabf4b71ddf8f0a328a21bfb1769.nq.gz
    ├── 61764b8f1a7b060bea6923ed256cd9a3e8fcd403.nq.gz
    ├── 62237a0c225ada24df23151481d6e155f1519fce.nq.gz
    ├── 6262837879db8fcb350af6775a0a8222021b693f.nq.gz
    ├── 6274861ae242393d81b15d182a12483556a6d26d.nq.gz
    ├── 639a0e47d50a163d457ac11648aefaec36619d09.nq.gz
    ├── 6466ad80d318ef33b0994a69605cf9e34cbb669f.nq.gz
    ├── 659a88700b65941e41f7c9906d1fc204a6063aad.nq.gz
    ├── 679ed6785441541e62d3bbac7d809fc12378f972.nq.gz
    ├── 68a14a990ef4ac01d31a7b1a67dcf40a69e8da4a.nq.gz
    ├── 6a64b7fe6153fe44d32927f41e8291e6f958a5de.nq.gz
    ├── 6b40c8e42bfcb403e7f404fbf20e792348c3487e.nq.gz
    ├── 6be352aa352653c8efbeeb7b03c459ed7def540b.nq.gz
    ├── 6cbe6966765fbce443c4f58abbbbad54bf686869.nq.gz
    ├── 6ce011a90bb259f9ff0acd9b543d34bc741a5b24.nq.gz
    ├── 6ceded4d297e53e572a805d8973eb6993db78279.nq.gz
    ├── 6eeccb2a2b5fe82218a737cdb37186dd1d7e87ad.nq.gz
    ├── 72135a230f864f709ceff1454590f9a414006547.nq.gz
    ├── 73c44e23239105dc5240e819a9ffb26040409bcd.nq.gz
    ├── 751f38c874b7cbfc9db50cee663d1c1eb236b942.nq.gz
    ├── 75cf994d0c933f095a7527278e38e9e856caf37d.nq.gz
    ├── 760a27761b2caf985b0efcfd7693dab98653f970.nq.gz
    ├── 76b4a7fe12a7e7055d17fd8fea0699c02a0fb674.nq.gz
    ├── 771225ef2bd878f6a3cb5e5dc48bee7d3b6c5846.nq.gz
    ├── 78f9033f85f073ed0662e86dbbffed7e64052323.nq.gz
    ├── 7a2296392d334999eb175e12b884b25367db012e.nq.gz
    ├── 7b11f561fae2fbc10d9d76edae8c368e9e4fec0d.nq.gz
    ├── 7d1e0845b561bae02040e91a9a8785563ab43f81.nq.gz
    ├── 7ff99dd28c5acf021782a6a85f449d0c2d272be6.nq.gz
    ├── 80cbc3a255b83b760c80d9a242d62f7290e7ccb3.nq.gz
    ├── 819f52ffec32f9edaed49981e34620a7d0aa986b.nq.gz
    ├── 81e47cedf9b9af7ea6276d356e7fe58c2299b8d6.nq.gz
    ├── 848b1047f34fc8c0c697bbfe667a869aa684259c.nq.gz
    ├── 856764de1d09116134d8d9523f2480a2ffa16aa4.nq.gz
    ├── 86015685273c9585661fdd6775ca0d06cf8d4072.nq.gz
    ├── 8a307a38444ce101650deb0b7739bbfbfe4f0b67.nq.gz
    ├── 8a996d63110b43794e4cb3821b70749a6f7cf536.nq.gz
    ├── 8ab6ff430b4571752a2c143f5007b7a4af2817c0.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8b480b49125d18146c72ba272a30f6ede625e3fe.nq.gz
    ├── 8bd3bd6cc90c50c34230fe0203fc3029677872c9.nq.gz
    ├── 8bdf8e065c6c99162aad8e1f945052ca6168d0d0.nq.gz
    ├── 8beb31b355ba528f09f1f07ed3fd78d3777c4330.nq.gz
    ├── 8c1b4ff21056125b27e0da2e0a8ddde8ff9bbad0.nq.gz
    ├── 8cd9770701a66bab28b7eda2bf2a9b6d1a3ec274.nq.gz
    ├── 8d8806fbd3cb13a4ded4bc883954441c18550fa7.nq.gz
    ├── 8e3f986eda76e11b88c1e9f1f13b0e57bb37e61c.nq.gz
    ├── 8e691cb21ce5dc9e6f960e390a807062d806e746.nq.gz
    ├── 8f6247b8c1e58cc6af53fc91e3b2bf5eb4c21bd4.nq.gz
    ├── 8faad3040d362fffe87d93c6064ddb3bb2b3bc78.nq.gz
    ├── 8fb03e581b6eddd4f8cd3f4ca2b7d0419cae2d9a.nq.gz
    ├── 901bfb40cc194b71d0e4d7adc0eb7d06875b42f5.nq.gz
    ├── 91bd8020c2e5d5c0c8ab872ff7e4bf28a3b23476.nq.gz
    ├── 91fb6ec8635a43835243fed972b4e539f9b8b2be.nq.gz
    ├── 926307abb6da148d7e2e0ec793bf3bd04fd8dc5a.nq.gz
    ├── 945949ac0d7a3bfce287600503762096135d8cc9.nq.gz
    ├── 94949e5bbe536d5c2e8204b6521b7ae03d3e452a.nq.gz
    ├── 94c6253a03c0b8f06cc5858318bbd220c54c9335.nq.gz
    ├── 952dad882509a1c0ab1833aa8fb2b4d65e679cf4.nq.gz
    ├── 956dcc04274a5d50f3373f2aa3a2d0b3d1626430.nq.gz
    ├── 9671857ef4e04f70d0279474c5dbe1566aa940d7.nq.gz
    ├── 9a36b93b6fb7179018e816e2fe9e3747646af366.nq.gz
    ├── 9b29fbfe2de03a72b1df923db0509fb98348bfbc.nq.gz
    ├── 9d0b98067ee79b19792e674c7849d691b6c7322f.nq.gz
    ├── 9e4e9975be27d41319b645f352b4847c5aa24fc2.nq.gz
    ├── 9ecd8c1c07678c03a723a7273d2c34390a1a6d7c.nq.gz
    ├── a030e6822a8ad744d7104cb666cda6414e663e66.nq.gz
    ├── a05046ce0657f2de1ed95ce03bb639eb664fa458.nq.gz
    ├── a060abed61de7bea46373414e561217528be0302.nq.gz
    ├── a130bee2f0f8423a4e471300370737e0d06784ba.nq.gz
    ├── a15fe3114a438dd4c8c37281b857a8623ffdd38f.nq.gz
    ├── a375f53e4975aff556403dac8382241ab2ba2ef2.nq.gz
    ├── a40930b7c2a4c0f4e961b3339f2e25de56ba43c4.nq.gz
    ├── a562db7ac20c3ba37da9ac84d3a9a9f5956a958e.nq.gz
    ├── a65555deaca8861bef98b841e0a393034415f65e.nq.gz
    ├── a7753c3409db7a512e35bddbed522df5710e3b54.nq.gz
    ├── a80e4e19a3b178ba582134a1cfc636434c203b17.nq.gz
    ├── a97e40f94c0a851b8422245ae459e67432fbf4b5.nq.gz
    ├── aa9982df301d4a9d2b5704aa50f9c341cba60124.nq.gz
    ├── ac16615536e11c0e04b1c9b5129c1874256d693a.nq.gz
    ├── ae6af77a55dbe6b6b893c9ba61f8a9f9eb8c89ef.nq.gz
    ├── b084df755b8676df88bbd114c385cae687a5df47.nq.gz
    ├── b1c5b6eb045c9ca272f7df27ec6210473be2c828.nq.gz
    ├── b21c43f3bbb44afe2d553132712d9a6f9c17f053.nq.gz
    ├── b35a23e92d7002917e97db680d6d361d24aaf30b.nq.gz
    ├── b4f34fcf3b3bf46c8e9fbee1f41bc7102b3a66ae.nq.gz
    ├── b50cdf6b37d84e6d00c27d857b134785249cdf8d.nq.gz
    ├── b76fc89f0ad619b5132609becd4134c1759f0799.nq.gz
    ├── b7ab3c502934577b5e5bfb66bd6a0ce1e0f6b0ec.nq.gz
    ├── b9c54c369272843f1d69345a2ef34ea04987902c.nq.gz
    ├── bb6a92251026074f37766994a80743baae8d3964.nq.gz
    ├── bbd7c43d69413b8f82a1896153550acb6762dcdc.nq.gz
    ├── bc6214cadc4e4b73c44cc5179423e7c2f5bfcbb8.nq.gz
    ├── bd4106faf5e8caf1910b5cdf6c8513eee52bc7f9.nq.gz
    ├── be597b455a429fa9cc4eec048e59fbf51dc57d5a.nq.gz
    ├── c27ca9f9f65f45ac0f8b1a1803ba24f5b31dddfc.nq.gz
    ├── c50c06d9c92e2e9451cc58a80480c6d74cec8a5a.nq.gz
    ├── c5147236e0aa7fe47557fb3ce6ae6a745ceaca62.nq.gz
    ├── c56919ba8d2a0517144df045fbbfa4f6098b3f62.nq.gz
    └── c7b6c3586d7388b7db3dd6ea26e786af00d3503a.nq.gz

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

[huggingface/transformers-ci](https://github.com/huggingface/transformers-ci)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
