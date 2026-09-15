# Repolex Knowledge Graph of dtolnay/unicode-ident

RDF knowledge graph data for [dtolnay/unicode-ident](https://github.com/dtolnay/unicode-ident), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download dtolnay/unicode-ident
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 10d5e534c9e06fffcdc6896d4779ffb25641659b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 12f0a68b138f1914e9abff76bb1d438b4a953f49
│   │   │   └── chunk-001.nq.gz
│   │   ├── 22456b4ace5f3eb45737b42966accc3ca59aa568
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5b54a632702b5744a1c40ea01c127c0ac0498172
│   │   │   └── chunk-001.nq.gz
│   │   ├── 86d0232be0c9c6d9c9c524e4f5eb6e3454a0dce4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8ffbcd4fd7cc2966fc6aeacd3d47e9da56421a7d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 93ab72c02e41056e63a3414d80878d18f2f7a962
│   │   │   └── chunk-001.nq.gz
│   │   ├── 94f16bda863a04aabdcaa28c2e5979b5822800c1
│   │   │   └── chunk-001.nq.gz
│   │   ├── dc018bf1ca82d295f72a84e7ed432e5d2bcbe2fe
│   │   │   └── chunk-001.nq.gz
│   │   └── e34a369149a64064013c29f6c36e8f2bbc450656
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8ffbcd4fd7cc2966fc6aeacd3d47e9da56421a7d.nq.gz
│   └── repolex
│       └── 8ffbcd4fd7cc2966fc6aeacd3d47e9da56421a7d
│           └── chunk-001.nq.gz
├── blob
│   ├── 040c4e1818ea4efffe7b6437cea4db372058102e.nq.gz
│   ├── 05e7b1aa2ff308b57fb409c70c521b4575cba311.nq.gz
│   ├── 0881831a7830fb958f83723c9069d25eaa821004.nq.gz
│   ├── 09689bf3f36d3a6ae880cba9cb9ce201b4f3f81d.nq.gz
│   ├── 0a2746f952a431d1bc8999998fbef8b345aaa475.nq.gz
│   ├── 0cca9ecce648a8d10fb4436521bc92c9e52164b5.nq.gz
│   ├── 0d101a4a953b171a7a8b1a307e017277a77beff3.nq.gz
│   ├── 0ebd2add95d418eb1a9fe3551e15caeb69fd5c66.nq.gz
│   ├── 11f2842a303a7935740f7a1d09139b0b9c28c3b6.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 1c3f064185201c53a5891c04f57c8f4b75dffb0c.nq.gz
│   ├── 1f5adc1f24e1df411ddab159a5ffdb7c2f34000b.nq.gz
│   ├── 1fee85df93e6e42f41e324bf37e0a04989e7e8a4.nq.gz
│   ├── 24481653faaa1af00182205766eff3bcac2da6b1.nq.gz
│   ├── 2d73ed9a63c5389dd0e4bf6f1f9b3b4a3251a9dc.nq.gz
│   ├── 2db53f3359521a82de3b67e04801940ecd1a277b.nq.gz
│   ├── 2dcce792a43fa7b00c75021815e8a7ee93008763.nq.gz
│   ├── 2df5244f86981d53dfb21b6401529272e72f086d.nq.gz
│   ├── 2e4668ef62528cef691a8a662756227a83a02c5b.nq.gz
│   ├── 308f2b044779e39393e505ba8372b6f8317a5316.nq.gz
│   ├── 30aeee973b85656ce3ad7427ca441724949b7633.nq.gz
│   ├── 30fed198153387bfdbe3675a444ca4efee9fda88.nq.gz
│   ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
│   ├── 33aba13a286b45067b328b9bf79a17f5901b8f57.nq.gz
│   ├── 3d786d682069d2befd054dabd8724f9bebc94efc.nq.gz
│   ├── 3e31c5cc5789c862ff89ef3c7a508d04f13ef328.nq.gz
│   ├── 3f558fffe84f806f305a03a7a2ccbb3c0a3db953.nq.gz
│   ├── 3f89a865d14fd0ef72ff7b3e70d1e7b1ffb35287.nq.gz
│   ├── 41f4ac1ee95b911fc0e01a77d1c8d01e553aab72.nq.gz
│   ├── 468d4458cf722b8cf768dcdaf04a914c770a4a68.nq.gz
│   ├── 49ca9f492f379db17c737d9453ec79157050c0c1.nq.gz
│   ├── 4b2614b3a2f67cf2dfbb86ff147f247b80b26bad.nq.gz
│   ├── 4b6f16f1981095f3b5961d6425265c7b108747f5.nq.gz
│   ├── 4c41ed460a6f675896a3a005e423124149bfc852.nq.gz
│   ├── 4e0b1ba1644000b919bab1356dcaee673f2ae89e.nq.gz
│   ├── 4f63372822f88261afee4d8dc433e653af0b9c5a.nq.gz
│   ├── 4fffb2f89cbd8f2169ce9914bd16bd43785bb368.nq.gz
│   ├── 50363caaeb40e175c74b8fcea6bcdbcc0f72df99.nq.gz
│   ├── 5195efb13d21065b1cc82584194097bc8964844e.nq.gz
│   ├── 59634efe78b82bf1e75e9ee4e6a8542fa016d64b.nq.gz
│   ├── 5d71a4d06538707ff698fdca7f00f3cd33375e6f.nq.gz
│   ├── 610adf31b5254b1163ee4dd2259d96aa6fc80b15.nq.gz
│   ├── 67b0560f1305c06e5078f7be833e1d70f4cb884c.nq.gz
│   ├── 6c834efa8a418f2b6fdd4b87998e041b6cf4418e.nq.gz
│   ├── 727063eefa00e613d7042517d9f8d568de23b97f.nq.gz
│   ├── 72bfd8bd7b9507e36629ae7c587499a2a9c8cd47.nq.gz
│   ├── 735b3eedd2af8168f555d3db0439dd096edf13bb.nq.gz
│   ├── 73abaab12987b7901a09da519a348c6c6e570196.nq.gz
│   ├── 7498812f0d3f4800b474368633a4ee230e3a8abc.nq.gz
│   ├── 750707701cdae985156601cc906195021ba6a6e5.nq.gz
│   ├── 764a7e756e90a8ecea7febc921a733e7f0195dc9.nq.gz
│   ├── 771dc459c6868e86a080eb6c08c4502a0df1dbf7.nq.gz
│   ├── 7af031aab073a25a3b655d567728fa5649c768a9.nq.gz
│   ├── 7ed13fa9999c7e8fa434334435d383b824a5da38.nq.gz
│   ├── 7fc36dca32dff2a91dd1c0b06a1670df2e0ddd79.nq.gz
│   ├── 821e7cb0fcabfee2e3ebabb0222f508b00e2a28b.nq.gz
│   ├── 83100df936dd3bf0d08626a1c821b4e93608f044.nq.gz
│   ├── 85d0d580d230c1815f58a831be11234f9559d8f7.nq.gz
│   ├── 89df1e8b03f0f22365a41b06858d96e7a18b36c0.nq.gz
│   ├── 8a17330aaf63f9305bef9c7b1f6f7806feb47808.nq.gz
│   ├── 90d3605cda6d83a05bcf1ec3288a9c796206fd38.nq.gz
│   ├── 92d1285f1fbb56b819fe01d8650709246b8e8536.nq.gz
│   ├── 9396996b746b3475eeb8d993c9407b04712cd188.nq.gz
│   ├── 9abe4913b3ee65fc98176e239d75e1c6e18d2b0a.nq.gz
│   ├── 9d66c3298034bb6edec85e0385237beeb1b4fcbc.nq.gz
│   ├── 9db6fe9589160b28621332eaafb587577794a55e.nq.gz
│   ├── 9f00add52f6a39592895ba91c9046b97d5b3dc1e.nq.gz
│   ├── a1414447724e755b3495ae138083e86d7efbc44b.nq.gz
│   ├── a32d0cde7375ab2762412811ac0c34dd738fc9d3.nq.gz
│   ├── a557eeb19a36d58de5d23fb5a8147b969b614e4f.nq.gz
│   ├── a5975b67e57e82eddf216bdb249e32fc1c58c440.nq.gz
│   ├── aaa2e2b144c88ba9411ec41ba06010db1ff4d308.nq.gz
│   ├── ad53d534c0804eefcc4a66b561e0a7e8cf664ff0.nq.gz
│   ├── ad7245ca5f29e82bd13ab587834e460c26f00e2c.nq.gz
│   ├── af5526bf7345b3f02ec03e089d2a02dbc8a5cedb.nq.gz
│   ├── b2dce8029d3398c500273b2dc0631448cae7a993.nq.gz
│   ├── b316b2639f1c104efcd27369cc159db96dacf6b8.nq.gz
│   ├── b355f3096d07a5631e46192344a1bc17aaa625ae.nq.gz
│   ├── b3b8d8d8247893a0aa70c86363424b054a6a17bf.nq.gz
│   ├── b4c0e8012b2668f5f394bd00558d7a3f52ace006.nq.gz
│   ├── b58b3612b3cbde2a37cb9adc4dee83899f555867.nq.gz
│   ├── b6511a3c4145770b7bbc24fb131713f5bda201d5.nq.gz
│   ├── b8a44b4bbb4bdf61f42f3a0dce24671dc9a292a7.nq.gz
│   ├── bd37c48460fdbfd82951274e9006561cf9f216d1.nq.gz
│   ├── c8adab3eec7d301331416ff973f75ff4495dc526.nq.gz
│   ├── ca269545e8a68c346e9e02ac558ab251a813ab7b.nq.gz
│   ├── cbeffb983afc9a5c8ae505f32225227ca8065873.nq.gz
│   ├── cc15f2d5dc8d10036bcc13cc6785f161bef921d3.nq.gz
│   ├── d016b808dc64945146c2deda448dd890a9608cc4.nq.gz
│   ├── d0b7aa760a513f9e3e71b85d5dea65027df5b689.nq.gz
│   ├── d8b3c84b96e7cbb5c35c2af4c7d824c38be6b7e6.nq.gz
│   ├── dc39a74a049113e484e5535544db964a65508efd.nq.gz
│   ├── dc92f2ebafa3dfed12fbdfe4df0c4b9f3fda837d.nq.gz
│   ├── dfb943bfee6fe1a57e3b054cc85ebd3dedf1dafb.nq.gz
│   ├── e2bcd736e38c92c072a895455026574ce13f4ee6.nq.gz
│   ├── e33609d251c814ccd3a30337c965a875645c2117.nq.gz
│   ├── e559676efc7694aacf0a2f4347085f334bbc9a7f.nq.gz
│   ├── e5d6adb08152d0b19056b89615654ba4db07cc67.nq.gz
│   ├── e9e21997b1aca0707f8749ea13c09aec66c899d2.nq.gz
│   ├── eb21d43bcd4bb5c2bd57a0320a82e7990a58c7c1.nq.gz
│   ├── ec4dd86115ddb1d77a813f6d10f8f7cf3804f778.nq.gz
│   ├── f1008b4e3b2703d4b360b9cca966c321a7d574fb.nq.gz
│   ├── f1316bcd3a5ea11d9b865631ffe6a05d6fa2b3a4.nq.gz
│   ├── f3d05403ca300b0cf5c12efb563810565c85f1b2.nq.gz
│   ├── f596ce9b1a5fe2a9a38073d5f710bd9f730a9276.nq.gz
│   ├── f775754c8b866d6f382d9e6e7c56e231d6fa23e4.nq.gz
│   ├── fc4cfb7ce03cdfc82c704972dfdf522e6987d7d8.nq.gz
│   ├── fc7b48e44b73348087e8a5334c3e80a5b4e18782.nq.gz
│   └── ff3d84268556fd2b8a572eff4b3006e7f08000ec.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 8ffbcd4fd7cc2966fc6aeacd3d47e9da56421a7d.nq.gz
├── filetree
│   ├── 10d5e534c9e06fffcdc6896d4779ffb25641659b.nq.gz
│   ├── 12f0a68b138f1914e9abff76bb1d438b4a953f49.nq.gz
│   ├── 22456b4ace5f3eb45737b42966accc3ca59aa568.nq.gz
│   ├── 5b54a632702b5744a1c40ea01c127c0ac0498172.nq.gz
│   ├── 86d0232be0c9c6d9c9c524e4f5eb6e3454a0dce4.nq.gz
│   ├── 8ffbcd4fd7cc2966fc6aeacd3d47e9da56421a7d.nq.gz
│   ├── 93ab72c02e41056e63a3414d80878d18f2f7a962.nq.gz
│   ├── 94f16bda863a04aabdcaa28c2e5979b5822800c1.nq.gz
│   ├── dc018bf1ca82d295f72a84e7ed432e5d2bcbe2fe.nq.gz
│   └── e34a369149a64064013c29f6c36e8f2bbc450656.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

24 directories, 137 files
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

## Source repository

[dtolnay/unicode-ident](https://github.com/dtolnay/unicode-ident)

---
*Parsed on 2026-09-15 by [repolex](https://repolex.ai)*
