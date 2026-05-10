# Repolex Knowledge Graph of seanmonstar/reqwest

RDF knowledge graph data for [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest), parsed by [repolex](https://repolex.ai).

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
lexq download seanmonstar/reqwest
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 01f03a4c01fb13e2262a513ed21e2b84b5186f46
│   │   │   └── chunk-001.nq.gz
│   │   ├── 62a80af8fbb743a2c7bfcb64d8896f80a3b9f6fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9a9daa7921dc875b90dd1798d2edbd86e476a30a
│   │   │   └── chunk-001.nq.gz
│   │   └── a9a88c4ee00a61b801f4f8e8cb643cdfb9a05b2b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 01f03a4c01fb13e2262a513ed21e2b84b5186f46.nq.gz
│   │   ├── 9a9daa7921dc875b90dd1798d2edbd86e476a30a.nq.gz
│   │   └── a9a88c4ee00a61b801f4f8e8cb643cdfb9a05b2b.nq.gz
│   └── repolex
│       └── 01f03a4c01fb13e2262a513ed21e2b84b5186f46
│           └── chunk-001.nq.gz
├── blob
│   ├── 02873f7d76f06299b7de5c011df5d78583f07c48.nq.gz
│   ├── 089784f17720d267f176b9393728e3931162d8a4.nq.gz
│   ├── 1028ebfade7bfa0689fbb1b54f70df6ad246d31d.nq.gz
│   ├── 1128d633e57d6f7f614c331be1cf86f06ea7f548.nq.gz
│   ├── 11db7f65b7358732932c5c800d026033b68692d1.nq.gz
│   ├── 126d458d6571e221f6b1959637ec162f5c02ce1f.nq.gz
│   ├── 1301225c15378222dfa935b7d1e2419fd07e620e.nq.gz
│   ├── 147c363075bbd71ec89146372fe8b04d4cf7f53f.nq.gz
│   ├── 1595ee88953140ae25b465cdb4299d0bdf293ccb.nq.gz
│   ├── 15d264e58373a88e2ebe93e26e209cbe0d45acc9.nq.gz
│   ├── 186717358a1bf6788688b6ead91f5e8c7dcd4878.nq.gz
│   ├── 190f2c7c65e67d4e3b2235e30928c7c89e257104.nq.gz
│   ├── 193370f22f91b15b0c185b75c3ac8c01ba6dc34c.nq.gz
│   ├── 19fb7fe203fbd86266ad6592a4476a28cb4398ea.nq.gz
│   ├── 1ac46f62ed79244e71da6af9f237263b7b59f620.nq.gz
│   ├── 1be18aeb81531be9c4818865c75fb6ef967fc841.nq.gz
│   ├── 1d14efd50b2fe7f02f4be93b2e7db53a72204e42.nq.gz
│   ├── 1d845380fbb23921fe024d19a282df48c71167b9.nq.gz
│   ├── 1dc88a8b878f39e0501c209d12aa273c234bf88b.nq.gz
│   ├── 2242852ea7e6f2bc2ed59af36b886454d1885f1e.nq.gz
│   ├── 242166d409d5d4f220d2faafdb421c492b7f2a30.nq.gz
│   ├── 255d9d8aa4fb2318cb923e6ff4e3db994b781b4d.nq.gz
│   ├── 2681f66001a6ca26746300fc07dc35999b8a7955.nq.gz
│   ├── 26b2e71b6fdc3872ae7a5619c97f32d9ec93b670.nq.gz
│   ├── 27493dd30660dd1f7c29c02ce117c745051658ac.nq.gz
│   ├── 279fe5f1aaa51ef8752410c133dc1b7fb73d43ff.nq.gz
│   ├── 2a84b1f75bc147452e06f02fd3ec434e34614a75.nq.gz
│   ├── 2b43a2d40fdc13dfbfdecbca181d48463e6ce4ab.nq.gz
│   ├── 2bafa9237bf197b2d2f29682422b9d9b2f7c0ed6.nq.gz
│   ├── 301eb536f0c1b45b6322e69fc9629dcc7728d544.nq.gz
│   ├── 33151d4a134c006c9fcb656dc7984c32041610fb.nq.gz
│   ├── 33805f15fd7a6d2832a3bbe253bf011b35487aa1.nq.gz
│   ├── 339f6e8c333541f2b6add61c26b56eabc5175afb.nq.gz
│   ├── 343b1c239729d5a03be99c43e0afdaca7752622d.nq.gz
│   ├── 348c8e163c3148b66af9707bd3e74fb6d1a2c010.nq.gz
│   ├── 35f60b63ce86134313f8e15c206d8a098780f7d4.nq.gz
│   ├── 3683502865dd662ecc68d15c7bf3f4e9c1de554d.nq.gz
│   ├── 3737d48b0cc975d872f94a8ca125e33549e6a429.nq.gz
│   ├── 37580cf987dff2670ffffd38838254f891d6ed4d.nq.gz
│   ├── 38265b17da63dd6527fc787b8de74cafeb2a6838.nq.gz
│   ├── 3920c5fcb5805de3b23bb9d8da0786907d0f1a2a.nq.gz
│   ├── 3a52fde1740c21fab751deba5c43812d7f4a4ba5.nq.gz
│   ├── 3e2bb8ed893d5f859fbbcebc6d9f59c020607aad.nq.gz
│   ├── 3f93f05e5abf2a69270be42e00ec836bea5a1dbb.nq.gz
│   ├── 417c8076df090a950902a6561ddd128de076178e.nq.gz
│   ├── 49fe37052b0fe96c0cfb8ae7220e7a574f2316b4.nq.gz
│   ├── 4e8b1b8e51558738f3e47f2b1e5310fe28170b49.nq.gz
│   ├── 4f22ea27c8e9333ce5ac6d58d7265f970989610e.nq.gz
│   ├── 5191181cb8c0a232cab7c10a02fbd871226dfe34.nq.gz
│   ├── 5196756fbfd93b7dab03c78c7166992781dc5fc5.nq.gz
│   ├── 52fad04ee6cec84531fca6d114039a4ec98f375f.nq.gz
│   ├── 53a2379e54943927c5b09e5b9df858acfcdbd72b.nq.gz
│   ├── 5906471a1b447245b17dc967db40c2086b4c85ff.nq.gz
│   ├── 59a3106e52e2bad7c01f94cade0cafec1c0c73d2.nq.gz
│   ├── 5a6ed6cbbcafa70db745197e8c49f049051b0d42.nq.gz
│   ├── 5ce4d454a15f9733b7bc2fd0a5963f108b06d0a1.nq.gz
│   ├── 5daac96bd6362e34de2160d63aede4855e101ec3.nq.gz
│   ├── 5dcad896ba5a3d210f8b95d777a7dcc7156067aa.nq.gz
│   ├── 5de3ddbb3a96452208fcf88f6b4dfb466c54a160.nq.gz
│   ├── 5e6dbddb4c588cc5f544ed4e1afc4684389fb631.nq.gz
│   ├── 6023b6bdd63a5e3e907afb7fd842333f304b952d.nq.gz
│   ├── 60ee93ae4463ca5e3df126ffff8f8a0e1ec77751.nq.gz
│   ├── 6bcb1ae8995fcc4a1ed9269c192c112ca33ebf53.nq.gz
│   ├── 710ce54732a3fe351f22d7c851d8b94cd59c04b2.nq.gz
│   ├── 717a22f326c55a3e336c2724b99ae18e453cefef.nq.gz
│   ├── 757035e2419512e11770773dd25aa01ce6ee1f5d.nq.gz
│   ├── 76ced8f595925f9fc423dce8db9b1cc0b7314f28.nq.gz
│   ├── 7a61c2e27cf4300a6c0acfbdecdbaf102110df6d.nq.gz
│   ├── 7a67c0457ac82d6f915ecf81692b122938ee6572.nq.gz
│   ├── 7aa75fd9ba6a3323bab722550470ab7235eae0c3.nq.gz
│   ├── 7ac08a768fd31c42fed77b6ee3eb787abb6eb6f5.nq.gz
│   ├── 7d3bd0dae79da20a0a83e8176652751d964e78f3.nq.gz
│   ├── 7fd670d7ff4418aa2c888bb5bc2285c73cb9a103.nq.gz
│   ├── 801bba19080436caeab3a78a02f36f8f0b69e7e6.nq.gz
│   ├── 809a75a4df4976767a95042760db7649800d289c.nq.gz
│   ├── 82d237b2f16f9a7b9cb539fc97acbf78f6b9daf0.nq.gz
│   ├── 87c702d81eb2cc3373779337654e6858bb30cfb9.nq.gz
│   ├── 88866c9cc5984688735007e9f139d3482fcc59f8.nq.gz
│   ├── 8d40c503f59004a6e2125d1433bbae42ff3191ba.nq.gz
│   ├── 8d730f39b2b1c8eb2a140e88cdc0a2059e1914ef.nq.gz
│   ├── 8dbdde0210850899940fb4b880956400824cb297.nq.gz
│   ├── 916e3d15cd9beeacf6a381dd6057c8028f75865d.nq.gz
│   ├── 9332301ec64b7efbf9e76c95c3762be431ba962d.nq.gz
│   ├── 93a2459ae57b744382cf559311c0a33539b8df58.nq.gz
│   ├── 95676386b7b10b5d4f56c1eca08349bf11d5ecd5.nq.gz
│   ├── 9977ce225f288555122767e99b309b1b02e0196a.nq.gz
│   ├── 99a7efc54cdaeebde8a611f64c06b4af0a661f12.nq.gz
│   ├── 9a00393911327ce1528a7c6df36dd79e67953c24.nq.gz
│   ├── 9b5b4c951d2be921b6ca813223649e833996e899.nq.gz
│   ├── 9c92cba5332aac2193ed8664f20c41d87ba631bd.nq.gz
│   ├── 9ceab790982a2980517583ee5f1a247d332add89.nq.gz
│   ├── a33e4d24d9e032847ee5d4b85dd821aeba028185.nq.gz
│   ├── a3992e8182a95667e26c092e3d20bbfbb9df6ccc.nq.gz
│   ├── a3b05658e3b263f3c0c6f31e502ba29b48da3e6a.nq.gz
│   ├── a57891807f5536d2958dc136a655400d2063ab37.nq.gz
│   ├── a6b3376daef6e0ce45479f26768d6bb60126d15c.nq.gz
│   ├── a6c7ba7028daa289964b959d21b3ff87f78ade4d.nq.gz
│   ├── a9e817aba53c738a945d4fc5c9437f4d3b4e9283.nq.gz
│   ├── aa6d8d8c17df88b258b5b5c0faf288e0b5a8f946.nq.gz
│   ├── b487344ed22d15a4f5044d105b811f6ab40abcda.nq.gz
│   ├── b5ee8320745bf69c3b2b405d7d7c82715b05ec73.nq.gz
│   ├── b7b8dcf316520bcfd3340b03052613c8bf3da475.nq.gz
│   ├── b8eec42a1b56947366c6c79515631516e073bcd9.nq.gz
│   ├── ba116ed92417cd14f063a544731d0b81c40b2e2a.nq.gz
│   ├── bcde795b9b56f9aba943c55ebf6a7e52a3c88ecd.nq.gz
│   ├── bde32b0bf340d926136924f4075f43361cab08cd.nq.gz
│   ├── be0895a750beff237b205daa2b29a0f32aba87e2.nq.gz
│   ├── be463094f65064d3c3217e0223aa3697200c8b34.nq.gz
│   ├── beff338b04dce30b08f903232b3c03e8bb4735d3.nq.gz
│   ├── bfa9aca39d4237a0d5f9f077fe11abbfafc85503.nq.gz
│   ├── c19141db86d4db8145943c5d5326dce5cc9f913c.nq.gz
│   ├── c3f24c1d72691f4580b9f696579afed059b90a47.nq.gz
│   ├── c594b9868d1eea33d79ebe6369136dfc321e9768.nq.gz
│   ├── c7d3c95accc4b4fe591556a9f0a463344d1460a5.nq.gz
│   ├── ca52dd5e05183da07c679195f08e620e8fb84d9b.nq.gz
│   ├── cb5fb74ac689064b3e4e292a4e184435adb9b342.nq.gz
│   ├── d0de89de53d7614d5f5cb038083da995354aaeec.nq.gz
│   ├── d542070a9b066e868de920b5d5b97bcf9c5c532f.nq.gz
│   ├── d774e9ee58a7b3901761045276a53db4466cf168.nq.gz
│   ├── da830328ee30b7907de8d7ebf08bf89ddb687db6.nq.gz
│   ├── da93d49b10d4d91f395f2bc0891bca03e2510e5e.nq.gz
│   ├── db9e84f0cb3452ac710429c3a60fbe264833cfd3.nq.gz
│   ├── de580e9d102732c1694f8a6d31d911b2bfdab7d6.nq.gz
│   ├── dfe5610b0aa7600dfec3e7db30018259894fe3f6.nq.gz
│   ├── e1389c0667073aa53c5369695c4043b873c715b3.nq.gz
│   ├── e14d3100818b1a8c52cef683b217b43fe8a68a74.nq.gz
│   ├── e2eb715908f483a589f629d406cb27a072282d83.nq.gz
│   ├── e38c6744be6d58893c7b5da69ac38e1e1c703bbe.nq.gz
│   ├── e573f2a52aefc858adf2c7379e841e4816407f90.nq.gz
│   ├── e6584ce7a9d055ceaf045244bcfad6c333895e52.nq.gz
│   ├── e867d45d5bda48d3c82936edab82f336d95f3b1f.nq.gz
│   ├── e8890c836ae84026ccf39eb90d61572a71c5bf64.nq.gz
│   ├── e8b1023c79b00a80f7f7029452624003329e3969.nq.gz
│   ├── e9928e351e84b54f67a574b4e0cc8ca539325772.nq.gz
│   ├── e9b653db462aacb1ac2a5316a872ea7df81de0d2.nq.gz
│   ├── ea25bf8cbf8527bf0e065c31ad746336a4121f55.nq.gz
│   ├── ea4d1ced5f7cccdbb393e2f07d96ab2ad288c6fe.nq.gz
│   ├── ed6203c1d581ab52684b147a9beed97c8ff49439.nq.gz
│   ├── ed8a263b2c8ef83359237665ae182d3cb3008e76.nq.gz
│   ├── efcaad4d12c05c7226e2f9782eec7a17c3909b44.nq.gz
│   ├── f213b55bc9b1ee95d4b83e7e38d477752be87f53.nq.gz
│   ├── f2d456e1328b17beafcc532333bbc6cf16e3d147.nq.gz
│   ├── f720e3613aef596a6d572db834b95d5cf9b9a00e.nq.gz
│   ├── f79c2a4df45ac2a6a0ba95d2a039a536d9e7e8e0.nq.gz
│   ├── f81b6f1c392f31c210a21313f2effb2db1b5cff4.nq.gz
│   ├── f975b29511490bd2441b5fc859047804cead0ed6.nq.gz
│   ├── fb164f5a6fe52f105553e0ae4b88e77cbebffa92.nq.gz
│   ├── fb2848757165db3600cf94447123dd8a0189a5c0.nq.gz
│   ├── fbd2d71386775cc9f5c81694b0d39f061da043ea.nq.gz
│   ├── fc9c0edb636967a78d81664403d6769e9d3456b5.nq.gz
│   ├── fce977f69ac6de1debb4e6218a4c5dc0828a079a.nq.gz
│   ├── fcece36bf5a713e1712758b41f928340d3276075.nq.gz
│   └── fe3f5b3b01f95a043c676bd8466c95d9d37f6468.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 01f03a4c01fb13e2262a513ed21e2b84b5186f46.nq.gz
│   ├── 9a9daa7921dc875b90dd1798d2edbd86e476a30a.nq.gz
│   └── a9a88c4ee00a61b801f4f8e8cb643cdfb9a05b2b.nq.gz
├── filetree
│   ├── 01f03a4c01fb13e2262a513ed21e2b84b5186f46.nq.gz
│   ├── 62a80af8fbb743a2c7bfcb64d8896f80a3b9f6fa.nq.gz
│   ├── 9a9daa7921dc875b90dd1798d2edbd86e476a30a.nq.gz
│   └── a9a88c4ee00a61b801f4f8e8cb643cdfb9a05b2b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

18 directories, 173 files
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

[seanmonstar/reqwest](https://github.com/seanmonstar/reqwest)

---
*Parsed on 2026-05-10 by [repolex](https://repolex.ai)*
