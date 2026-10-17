# Repolex Knowledge Graph of dask/dask-ml

RDF knowledge graph data for [dask/dask-ml](https://github.com/dask/dask-ml), parsed by [repolex](https://repolex.ai).

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
rlex download dask/dask-ml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fcc8111ac686e086985902f2050b3b17464966dc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fcc8111ac686e086985902f2050b3b17464966dc
│           └── chunk-001.nq.gz
├── blob
│   ├── 0108694939f4f2b45dab636c777cd137afb9a982.nq.gz
│   ├── 03e52ec8467b455f07baa0cefbabe9ec4a4f0435.nq.gz
│   ├── 0cabbc3f0534abb2c9b7908a3f89be8cf2030fbd.nq.gz
│   ├── 0cfafa7aa5e3f7507e256abd1cef02b26ed88137.nq.gz
│   ├── 0dbc1d97208aae6e72e1296f503f3f00735658d5.nq.gz
│   ├── 0e811e6fffc4d41544b69b0e6b858b8d08e8ed42.nq.gz
│   ├── 121b8f5dc6716ebe9ce0282df05607c2c317d6eb.nq.gz
│   ├── 127a22fa4f0fff106ee3783ab1a5f0ba9f2a37be.nq.gz
│   ├── 13aececbb305a819fa746be47ff238dfed5045f2.nq.gz
│   ├── 1483ca8a16823f33cc161dfbe5b04abd619bd960.nq.gz
│   ├── 1727c7538f36d8479cdaaed7cdd4c8c5cc634d21.nq.gz
│   ├── 1a4e7fcb62041da274e2642183292f131665910f.nq.gz
│   ├── 1ae5fcb411025ff74f4d8df15d6be94de402ae87.nq.gz
│   ├── 1b974ffbdd4fede028ed935b6610b2993b4ee05f.nq.gz
│   ├── 1cfbcd1f649a59cc94703a5e67cbeb67890baa1a.nq.gz
│   ├── 1f25ef7b5e4faa137ce93f3ca21811f51b730b12.nq.gz
│   ├── 1f55d50e7c7301892b533becc4c79061d4055563.nq.gz
│   ├── 216f19c16b08547724a68899d04d90ece791bcbf.nq.gz
│   ├── 21c3e9e217af515ee96736bfbfdd3663554aa9d8.nq.gz
│   ├── 21fa63d0463ff5d36378a06e8ec8fac015a86a70.nq.gz
│   ├── 225904bb7df2d4ee73051a8e04c4c7bf1e720426.nq.gz
│   ├── 24636eea1c5641945e4fb9ae562edb1d65519586.nq.gz
│   ├── 26f0bd5c4b1a4f08d069a793b3cac79d414e8485.nq.gz
│   ├── 2a593d9256e1c03dae00cd00df783a93fbfc3dc9.nq.gz
│   ├── 2dc631eaff00ae3ac2f9509f0e09c93016c9f061.nq.gz
│   ├── 2e2c2f68b9b7aa1b7d337a1b285c1aebb50c54af.nq.gz
│   ├── 2fe9d6406c7a6250e471ef18c99d293982cbd26e.nq.gz
│   ├── 32b85f721596182642a69d19893d3abd0462e2d4.nq.gz
│   ├── 331226d36e36b4d351a92e95d07610a218492f6b.nq.gz
│   ├── 359f9634621568aad70876c5997fca0e933270d6.nq.gz
│   ├── 37ffdee813f72af40730a0d416410e4984ea246a.nq.gz
│   ├── 3c8abce19a8e32f5a90f711a6f4e3ce3740551f3.nq.gz
│   ├── 405cc45a0c47ceed1c21a53332a03148d1e5fc47.nq.gz
│   ├── 41b43a98672940cc5be93dabccdc30ba6b8441f6.nq.gz
│   ├── 41c40457b9c58719d2ffd3afb6db13a8642bdcb3.nq.gz
│   ├── 45365286d52d55ee8f24ad8667befd98e778f0df.nq.gz
│   ├── 4775018c358e7d0426990ec3afbacd7ecec23976.nq.gz
│   ├── 47e2ceb89f7021de1278aa527a90418dc85891dd.nq.gz
│   ├── 493178be8c0d79f713419c6107c586de31ec70b4.nq.gz
│   ├── 4a126195ea5a4746e12289407ddef923418e5329.nq.gz
│   ├── 4a79986e0d620a85f572ac108da6036b28e89c58.nq.gz
│   ├── 4afa148e5194bd033d3b1cce6e5a36789b09688d.nq.gz
│   ├── 4d892587f48f3399b8dafe83da86d67779292b35.nq.gz
│   ├── 4deb55612fcdbf8b9768d85caed58dd7a22e086b.nq.gz
│   ├── 5171695e9fb2f74c3c633ebc24b775f398d2a720.nq.gz
│   ├── 52915140d968e5f8fc03e18bdb97a8cdbdf61ac9.nq.gz
│   ├── 5c461838b37d7f95edd4dd965d6a6695a4463f63.nq.gz
│   ├── 6688fa068128a911e57439bba00b230495379487.nq.gz
│   ├── 66a5b9051c2e12e92a28deb656e6473fa93b1274.nq.gz
│   ├── 68ff05a4071850db251264ee4d63f8df70c8b440.nq.gz
│   ├── 6a8f63a4b516d6519bfd5ea446b187fc62f5ba28.nq.gz
│   ├── 6abaa77c1fc142ee055e28f217edb870a0e148bc.nq.gz
│   ├── 6b39a254c6700da2cb8994a9428a6588bbbcff8f.nq.gz
│   ├── 6c8263293f5fe903d9410625a9d04db2e43591dc.nq.gz
│   ├── 6cd247e8091be78f88376e5bb4b8c9acb20084ca.nq.gz
│   ├── 6d13ac6aca2de306805a8f493c96d92a3c0ae9d9.nq.gz
│   ├── 6e453411627daa2b88d427d071bc811ed1259195.nq.gz
│   ├── 6f2be0f607b594c0505dbd9e9e1081c0158a6cf7.nq.gz
│   ├── 6fc941988f95bb51f91175295aa77ae92cec517b.nq.gz
│   ├── 70e46d3583189154cd3c939f286ef0d704ea8c06.nq.gz
│   ├── 71deaa3ea948fe6311c6e7b9f5f09720a1c511e0.nq.gz
│   ├── 749d33b4e6759cf4905077caabc651ff479ff62b.nq.gz
│   ├── 75be548239b5957c9641912660494b91e70a604c.nq.gz
│   ├── 76811e6804ec441bb875f9a41c4a4a2f9e9d3ba5.nq.gz
│   ├── 79b04f813e91e9cb0b199e4df2246075e5c8b7e7.nq.gz
│   ├── 79ff2cf8077947a292fd0a1702ab2cda994f70d9.nq.gz
│   ├── 7ac14983d4f8461fa433dcb5c6545a3b9a0954a1.nq.gz
│   ├── 7b394def4ad16d525905d4c476cb0de6cd63d1bd.nq.gz
│   ├── 7fb64a4f80eb038fc412798d77d25f642665a5a5.nq.gz
│   ├── 81012e898d0766e4a64ed2b684d33ec671cf2fca.nq.gz
│   ├── 8392f9d72a9d294bdfee0e9d5896c479824080bf.nq.gz
│   ├── 84b3c064808707fd36bfa8dfd4c4c334d4229e68.nq.gz
│   ├── 857e2c28ce1da306b4ea9288fc5e4ad29848dc5b.nq.gz
│   ├── 86683778996f6e20499b84c09692ed135368bb20.nq.gz
│   ├── 866dcc435c420827c563062bc0c69e37c736fd61.nq.gz
│   ├── 8c533c5a700f51bdbfbd640990f26ef6c6edd91a.nq.gz
│   ├── 911b3635d99a5fa8cb73131f6b04fe2498642f50.nq.gz
│   ├── 927f3c0ff06bba76a7b3ecfd50519a8ff1b4d0ba.nq.gz
│   ├── 93c6c2098842ff10662fb680ea0ee7d3ad30d626.nq.gz
│   ├── 9591ade874773d9986e5db1ca5754ed060489f1e.nq.gz
│   ├── 9710d03a6d42288198244920dcec7c87568bc635.nq.gz
│   ├── 984a4e8b510dd982541dfaf48362789c807170c6.nq.gz
│   ├── 9af0a607920267b40085f0700ca3ba30ded14c89.nq.gz
│   ├── 9bc8e37be38ff7ae6c556608f5d9bb963e736dd9.nq.gz
│   ├── 9bf675f69f250e7d48474ffcd178497eadfe653b.nq.gz
│   ├── 9c171972fa9ada3f254d6ddac8aeecbe1aa2044f.nq.gz
│   ├── 9e58890424c67ccda789ea32f24760a2359ea7ee.nq.gz
│   ├── a04efcb80be07ed3cdd399cef1f05688c524a0f4.nq.gz
│   ├── a3aeeac20c543ef828ceb6e90e6b9e9e982ed08e.nq.gz
│   ├── a561ee0d5ec2f18b7ecc93fed945c5c23496519a.nq.gz
│   ├── a7c125db9c000988b3b97088aac18a3ae9aabaa6.nq.gz
│   ├── aa10d6063e4389c1ac2d412fb6da92fe4e7a56c5.nq.gz
│   ├── aa1287ac322c860388507468094782b355d5b0fb.nq.gz
│   ├── acf8b76c42ba9469cb0bd8559974de14a9eb0310.nq.gz
│   ├── aea5b72e1a314d024572f7d2ca5aa3e82463d967.nq.gz
│   ├── b5df46fa18fe6fde7b90e9d93ea084b63039e753.nq.gz
│   ├── b6862871dd00cec9569122b902ddc2d9f0b5ae32.nq.gz
│   ├── b7b3ce895fb411b5b6ec60ce307f05b63589f7e1.nq.gz
│   ├── b84aec43d57d881290027d58aba854db6160d1c4.nq.gz
│   ├── bbc907797e18314144ec54cbbd32f4d53ff07d7f.nq.gz
│   ├── bbdb22a4b93abce0370d76c351600ceafe23ec5a.nq.gz
│   ├── bce639c624991a0298e81eb97b82d918de84f816.nq.gz
│   ├── c0199924936107f831f6ce8675c421b92aadbf77.nq.gz
│   ├── c0396d39cc9319967a69cff87a83820425b26937.nq.gz
│   ├── c0c180fbd794992cfec13f45a2060785fbeccfdd.nq.gz
│   ├── c20abfbd0c32124c36400e643fd8fb0a2afdddde.nq.gz
│   ├── c2601a30c566cda253d38cde62df1a76c6c22dc7.nq.gz
│   ├── c3cbe645999a128a638404b34a29ce4d64e8a1e5.nq.gz
│   ├── c45673640e24d282cc813f6c5a747fa9579fe9a6.nq.gz
│   ├── c4f631c57f7ebf6f09728ad6d316979ac029ecd9.nq.gz
│   ├── c54bda3334c82eb935a3c563b3634440db795082.nq.gz
│   ├── c62f6256f3e58a0456befd9f7af7869b9f347134.nq.gz
│   ├── c78dcf036eabe63d6e5c8ae95a757e00d9d8d106.nq.gz
│   ├── c91746185476ab1cf60aa7f44964c40e0d344c29.nq.gz
│   ├── caec93970f7d3ddd90662b3d32ce953d6290cc42.nq.gz
│   ├── ccb7e7bca7cec7664f5c195ea5d727a28c3250e9.nq.gz
│   ├── cda7c20b5841fcf96d6f653437af1d6bb4845dc7.nq.gz
│   ├── d15580c7debc87b47276794c7642deb18c1acc23.nq.gz
│   ├── d223675bac5250ba2860d0d78356633bb5e12647.nq.gz
│   ├── d2266d5ccaac25aab06eaafa9b960ffd0c4cea72.nq.gz
│   ├── d24009a5f85f5132d961f11c8a3d82b5ff945ccd.nq.gz
│   ├── d33d6ac3f38c7960f21c0f7797fc9000afd21627.nq.gz
│   ├── d39fcc6b36105c5df048a00758e1c26f4ad90866.nq.gz
│   ├── d41354815de3a04dd6954c724cc8a0a04758c234.nq.gz
│   ├── d5f113f81ff7f0f58a67e8330ac5930e9be61131.nq.gz
│   ├── d9e805967f7c887eab35c6448793cf02cc169dfc.nq.gz
│   ├── da8a0df970e7a838b42eeda38f4625a821c79721.nq.gz
│   ├── db6a1a8e8221917758378e1c3ee679938c96f3fa.nq.gz
│   ├── dc9f1e64e22e230a16f1d604a31cfcccc7c675f4.nq.gz
│   ├── de64b9d295e2c0ed3c2fdd208d56605c25e66483.nq.gz
│   ├── df81c6769eb145fbf48b76e6d739178b97213a90.nq.gz
│   ├── e1b782e530d43c63c4ab672735057cf94decd456.nq.gz
│   ├── e26097748c8630286a09f113724dc0d49a631aef.nq.gz
│   ├── e4a79462f8e47da1a811d4ec0b64beefb5e0d962.nq.gz
│   ├── e5344a54a7046a9135c9bffa9ba2bda2772b7e7b.nq.gz
│   ├── e60477e91164ffab0017a6175a9fc635e3659864.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6b60b1d61f6bd0289a23cc9ce71e803b599227e.nq.gz
│   ├── e7666c179d07d2cfaa836b920619c9e53ebd0700.nq.gz
│   ├── e833a30d34edf5e563658caa25631be04314727a.nq.gz
│   ├── e88ad2230ac7e379327e1e565618c35143292cf7.nq.gz
│   ├── e92b9bed6cd0aebb4c521a0989bba72b76bc2127.nq.gz
│   ├── ebc53247252f1dfa55ee3c8cd617b9a77595ce8c.nq.gz
│   ├── ed1ac30caa9fd879e57107c3b0cec689bbd7dbfc.nq.gz
│   ├── ef5d5a15c6e5500aed0ea4618a37c2b6a6d97cd5.nq.gz
│   ├── eff10a8e57064bff2acc684d273019b2bc9423ec.nq.gz
│   ├── f3e257b3a3fc3fa1bc1da91b748fa1d76239cb3a.nq.gz
│   ├── f4b11eda770e4606376a354d09a24093a2e35a19.nq.gz
│   ├── fa6cb2327a60c855f58e5dbd7cef7cde4a7f08a0.nq.gz
│   ├── faa6f515624b6f6932dbeb35e86d67f42ef7b190.nq.gz
│   ├── fb1bdcf3c3cf5f53f589ae17884f25301af9b4d9.nq.gz
│   ├── fd6a35f7662b07dc9058a8ccc0a42e161ddbc6a8.nq.gz
│   ├── fe426bcb53674a7b475cf3f09529167933db3c13.nq.gz
│   └── fef1656c62540b244ef741505f92ff4059263436.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fcc8111ac686e086985902f2050b3b17464966dc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 162 files
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

[dask/dask-ml](https://github.com/dask/dask-ml)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
