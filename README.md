# Repolex Knowledge Graph of google-deepmind/reaf-sim

RDF knowledge graph data for [google-deepmind/reaf-sim](https://github.com/google-deepmind/reaf-sim), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/reaf-sim
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 80aa17f75c2603648bcf987ff8f3d08e2a19a698
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 80aa17f75c2603648bcf987ff8f3d08e2a19a698
│           └── chunk-001.nq.gz
├── blob
│   ├── 02ab98808b970993337bb6291fd46720dd2ca30e.nq.gz
│   ├── 034c49d08427383b1d54e063a94a8c63f29b7283.nq.gz
│   ├── 044eff186a2b443d38f3c4bf77157dd6494f85aa.nq.gz
│   ├── 09ac694c36bb65e911fab3593b6670179c874fb1.nq.gz
│   ├── 0bac9c1ae61f24996c4ba9db385a0fca9cf38a5b.nq.gz
│   ├── 0d410c1215af20d33bf62025cded315f03332298.nq.gz
│   ├── 0dcfa427c7d99079a982d87bbda5efdb3881fd7a.nq.gz
│   ├── 0effc0c568dd85889fbe6cc915b0e74a601c2e39.nq.gz
│   ├── 1027bfc6cfeea64b0df856445cfbcc9db3a74176.nq.gz
│   ├── 10d1ad82a7fe411c9515fe8f4e825342d7091895.nq.gz
│   ├── 15e32390d0eb50b5c2e27122f498585afbb75dd3.nq.gz
│   ├── 1625bf9a3f6e5cf5455b2549777f6aa9da019106.nq.gz
│   ├── 1c523730e59c6f72863deeceb6889980ccf72972.nq.gz
│   ├── 22b8dd9792084176ab99c25281190718052519a9.nq.gz
│   ├── 2490603689ddd8c0189e932bd746bf3684c6eec5.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26853a2daab4d4c2cfbe75f74d776bb75d9f28e1.nq.gz
│   ├── 288ce949a2a27f38cc9713a1cf887511c06ba5ca.nq.gz
│   ├── 2a78f7043b47357c50e178d9afebc86b040b2224.nq.gz
│   ├── 2e60fe77d5ad579245eeaf31f0c0a11bb3bb8251.nq.gz
│   ├── 2eff3d3e03f51988a447e64542bdba6e582703bf.nq.gz
│   ├── 316c3a2ba38bd76d9d172c3abe53cdb8236b0006.nq.gz
│   ├── 32c4e5c5937141e9ce8cf1e153f55d006b1cd6e1.nq.gz
│   ├── 37f669c2024e6c5f1caecdbb911d63441a3fdf4f.nq.gz
│   ├── 3db79d5f399231ee216e27623742c00d96190fce.nq.gz
│   ├── 3e2d3c0f57843c35b2f7a7257d312fb165ff75d1.nq.gz
│   ├── 3e9061ed4cc4fe9cc4d4cae2db2265872a5ed257.nq.gz
│   ├── 3f3e6c6d560f210ada1826997dbe095cb544373c.nq.gz
│   ├── 43c3679e2aca08e073266ce205344cc2ce254893.nq.gz
│   ├── 43fda89e9c4451e4777b69b34c5e38ed1807f643.nq.gz
│   ├── 45e5e12627faa35ce38e1cd3ba9bb6148835cb18.nq.gz
│   ├── 4763fc1e90abe7c5605788d3470c93d189584791.nq.gz
│   ├── 4a3efe00df4b898bdd91ca1b95aa86898d71c92a.nq.gz
│   ├── 4c8eacdd57647746120bbd146bd10095a0de2919.nq.gz
│   ├── 4ff4781daabcbaf517a6de53b625374aa3d9814d.nq.gz
│   ├── 55ba793698b6790b500563fbaf1004840dd54ea0.nq.gz
│   ├── 566c2928d252a26bb6f7b0ade34983db9abb94f1.nq.gz
│   ├── 583b8d4e3059f1787e40d2269588d7fbef321ce1.nq.gz
│   ├── 5b4002fa53fcc85c5b1650b3af7b32021ec16b26.nq.gz
│   ├── 5b42b232098864f948634f739eacc0e8d1ac4988.nq.gz
│   ├── 5c90222464ea9cfaa6adff30553b9b5c2b0a952c.nq.gz
│   ├── 5ee60430cb1a4f8fc1b1be9268fd9cae88ed0cc9.nq.gz
│   ├── 61444246c3131c25cae3d686c1cfe2d10ddca1d1.nq.gz
│   ├── 6217ab7b87ebe99cd2bf9168b33d051726dba92a.nq.gz
│   ├── 62ea65aacde09c2ff9b578b5390351c8fdf53987.nq.gz
│   ├── 6353d5f3d8dd0ebcfcb17e40a11585c7d842d778.nq.gz
│   ├── 64580f5c29631e6aba6147028f66af026ec66711.nq.gz
│   ├── 645fa87768e60bf067f069d3b14be0d7c48f02ea.nq.gz
│   ├── 687d07ea619cd379210f4a136b68bc120b5a616b.nq.gz
│   ├── 6950549c56569fcc7ce1e51234fe10308f3fc6fe.nq.gz
│   ├── 6b99a225c115c7a1dc8ea96b11d372fb27b46550.nq.gz
│   ├── 6c3b8f9c9e276d472427c11cba6f4ff7551e7fac.nq.gz
│   ├── 6c718aa79d9afd8729c8f29a0ec8a305d50c9a7e.nq.gz
│   ├── 6c893a9c418736131702f9d6b17661cd9bc03622.nq.gz
│   ├── 6d25f21c0f26848005b8cd74ac4bba5873c8cca6.nq.gz
│   ├── 6f16a197fea467e2f7eeac6f8b5e3841f5db9963.nq.gz
│   ├── 6f2cbbc797662b5f210bd87422c8fda63cee9446.nq.gz
│   ├── 710b06cb61f86556407b99271fa3310bce1e5a44.nq.gz
│   ├── 77779da66378e3977093661fbfb82de76425163d.nq.gz
│   ├── 77a72a188dfc0ffb2abdf59a9c0316968d929d01.nq.gz
│   ├── 79e6becf824bc2ae752c41cf249852fcd92c4b23.nq.gz
│   ├── 7cb3ec222009bfedd0348ca7c559ac0c4bddea1c.nq.gz
│   ├── 828c1c8bb2c1cdd6ee0beaf4e5d6c1c0d3928237.nq.gz
│   ├── 839162be467d69d81b073b9c79bbc78031c56706.nq.gz
│   ├── 8432c233e38c2623a9e06aa2ab6e6505eeb1ef9a.nq.gz
│   ├── 87cabac44a392ff22a7679d411e52907d5c1e917.nq.gz
│   ├── 88162df78fb127a2ec770fc46f8baa0b08ba05e6.nq.gz
│   ├── 8a2d2ed04774e2349a56b2e145d17b6f9b182147.nq.gz
│   ├── 8b9152901848f358927f20f4d01c09771bfdfda4.nq.gz
│   ├── 8c10e4a4ab4b8b9415c16744c3458408aa9cc0f0.nq.gz
│   ├── 8efc12131fa016e8720bd19c256a62d73adaa1de.nq.gz
│   ├── 915124ca6178674ef580eafed5d0ae93287f00c7.nq.gz
│   ├── 927a973a1662779a453c9fe2f6c7d7631819340c.nq.gz
│   ├── 9364597a1a5659b79bdbf4cebf64cddf2d1fa43f.nq.gz
│   ├── 93e0c3277e03b2ba1589e91ca38a0c794543abb8.nq.gz
│   ├── 94a89fdc4659de882d8ad5c5f751ac3b5886a91f.nq.gz
│   ├── 94f24ed2db38c7e780b5f177546436bdefb712a6.nq.gz
│   ├── 9b5403f316546c919ddf4be792ad75f0e38285a7.nq.gz
│   ├── 9c63a3c6981b08a2fdbca8098ba6d1b81e9e9f61.nq.gz
│   ├── 9f3199f590122934b1e0eeec4a23c1814a9b050e.nq.gz
│   ├── a07656d10eb9d6b785c0339061035c1f10597bda.nq.gz
│   ├── a169a09fef28bc5185c759e9988084ddbcc36dc2.nq.gz
│   ├── a2b5192b60f94a04b2cae329f4f7869be121d08c.nq.gz
│   ├── a47d8bba12f804ae40f821da834f9e43322ffac5.nq.gz
│   ├── a54f8dede7c7ceeceb22ef37fc8681f10559debd.nq.gz
│   ├── a55626cc3c28e0a761e0a45eadfdb2aae52ae998.nq.gz
│   ├── a6a949a37bb4ebe6d14e321ba6e672c85066db6e.nq.gz
│   ├── a8d443f318500fb0cc6510483407470b5635ab49.nq.gz
│   ├── a9344363d341a961168c8b7556878fa8717d683f.nq.gz
│   ├── aa54bc4fe14f8ee3a3e9dc500fd4e6b2340ad59b.nq.gz
│   ├── ab9d8d56b6cd0759ad8fc653466e28f09053ab42.nq.gz
│   ├── ad3ffa1ca6a065a642d65081921bac9b3b935c6d.nq.gz
│   ├── adc4575bfba2033cd47cf6d5cd645c3c81358bd4.nq.gz
│   ├── b03b4c20041e31d53ee78207ff5da8befbb2f247.nq.gz
│   ├── b266cf4268e3aecfe95663625a7a462e4ec1e148.nq.gz
│   ├── b936a3ffb8d7e8376c9dc1355cddf27f50c9e2fc.nq.gz
│   ├── b9937c775eba6213f9665b78c2ada0f1d718f2a7.nq.gz
│   ├── ba8703812c5bbe2c3ebaae3680d8b4526a26027e.nq.gz
│   ├── bbbfbf009877e6acadc309a480cf4b53474c0a35.nq.gz
│   ├── bca0afab097d06927620a5691712a2a4a2fa9d09.nq.gz
│   ├── c5519ef6dba6ed1c3998a3efea053cdace3170ca.nq.gz
│   ├── c7f2cc9010c985e45b2c6df69ce2479d0360261c.nq.gz
│   ├── c85410b1aee43276762c02e022fc5bc6a0d370b9.nq.gz
│   ├── cb374b4abb012a3951d16226c643060804fd5bd5.nq.gz
│   ├── cd41b44264d5e3ba1aa7923e61e2986507afb8f5.nq.gz
│   ├── ce88f3c8ffa08f89923313c672375851cd8cf80e.nq.gz
│   ├── cea1ffb358526dfef1e360aa59db0229a41b92be.nq.gz
│   ├── d18385ead5dd67038d98a91a31cb0e1a0f7a441b.nq.gz
│   ├── d2a8af3f0dfb9c375ea8a724a8a80240b5d5c3e3.nq.gz
│   ├── d5b95a74bb351d550a27c9777b05b89c63066668.nq.gz
│   ├── d865af115c6f6525826981c1f314768b911f98ae.nq.gz
│   ├── da91a8fe6cd333b876614be817226903f54cc398.nq.gz
│   ├── dac47d9669b4163dd9202c378ea8331db9218e4d.nq.gz
│   ├── dff3e6a65711b1cb9065a47b163d3703ed731299.nq.gz
│   ├── e124ac7194e37413093e1aac6eef960cfdb13e0b.nq.gz
│   ├── e226b2d860ac9e516f0da0f2c38cfd22c5e2f1fa.nq.gz
│   ├── e488c8d791adb623d1661c6d566a90737eff7056.nq.gz
│   ├── e59e55775e5bbef15fdb47eee00cdc59fa4adbfd.nq.gz
│   ├── e5e6e8949f7562389917527662c8236356adab41.nq.gz
│   ├── e8dfd4e82679a1d51f29deb7476a872df66f7052.nq.gz
│   ├── e9891929abbf9a3f30e4794f02bea72cc131544e.nq.gz
│   ├── ea3862456eb3560731cb58c41bf8ac7478aa9014.nq.gz
│   ├── ef42778d034ba21b8679b6d5107b038a991c6406.nq.gz
│   ├── efd0e301179cfb856eeff5490f9314be58a63242.nq.gz
│   ├── f4f88ac45299a8160ec9870b0cfee92d41623b30.nq.gz
│   ├── f89c179445c3b89493c30cbf31adb9099b5ab51f.nq.gz
│   ├── f93f2fa21091fe93b6bb51f84961a27698af04c1.nq.gz
│   ├── fa7077e210b22305e6dc3f19c693fa0f4507215f.nq.gz
│   ├── faa497ef4b9a4b574b06d2644c21123f7b14bd93.nq.gz
│   ├── fb4a1df662dff4a60c56079dd21d7828904b2994.nq.gz
│   ├── fb5dce873b6007ca9e65536edd582df8c9e530c6.nq.gz
│   ├── fb68a152649c03b1b3863e998507da8e7152b899.nq.gz
│   ├── fe5b18ed337a63f504c84d5a3f04d36d322ffe55.nq.gz
│   ├── ff6dab81f467db00a6d70cd631564bb20b506fce.nq.gz
│   ├── ff826ac95874bfc029fd8ef36c9d040c731e806c.nq.gz
│   └── ffe1cb86a977b4f6427cc1e04a88e73997826c6f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 80aa17f75c2603648bcf987ff8f3d08e2a19a698.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 143 files
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

[google-deepmind/reaf-sim](https://github.com/google-deepmind/reaf-sim)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
