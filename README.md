# Repolex Knowledge Graph of expressjs/express

RDF knowledge graph data for [expressjs/express](https://github.com/expressjs/express), parsed by [repolex](https://repolex.ai).

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
lexq download expressjs/express
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0ce39a4cf6424f30f6c243a20f2a1b1e46d909d2.nq.gz
│   │   ├── 125533116008cd7e3a81b339a15f4a2059ae12ae.nq.gz
│   │   ├── 14ceb8c046c6bbe07ede056c99be55e5a2e914e1.nq.gz
│   │   ├── 273a51a335694abd977e36a9b052bbd48190de78.nq.gz
│   │   ├── 2f6dfbc165337b0f998a281f7f7ac86674b8bf59.nq.gz
│   │   ├── 3b49821e82bef2a94a3bda0fbb2fd4bc0d732842.nq.gz
│   │   ├── 45ef08cf99099bddaf995544c93272cd3b8c2355.nq.gz
│   │   ├── 6a6cce03b7f071bcd9027e5068b988770f4e1133.nq.gz
│   │   ├── 6da4a942caf956bd90df100283a716680c889eea.nq.gz
│   │   ├── 7cdbca0dc95f2c635187711d7bd9599010f2c575.nq.gz
│   │   ├── 82891ea148c6774b98cfbe3d771d997a77537d16.nq.gz
│   │   └── cbc3163496621122fed1c86f806d6e09f333566e.nq.gz
│   ├── dataflow
│   │   ├── 0ce39a4cf6424f30f6c243a20f2a1b1e46d909d2.nq.gz
│   │   ├── 125533116008cd7e3a81b339a15f4a2059ae12ae.nq.gz
│   │   ├── 14ceb8c046c6bbe07ede056c99be55e5a2e914e1.nq.gz
│   │   ├── 273a51a335694abd977e36a9b052bbd48190de78.nq.gz
│   │   ├── 2f6dfbc165337b0f998a281f7f7ac86674b8bf59.nq.gz
│   │   ├── 3b49821e82bef2a94a3bda0fbb2fd4bc0d732842.nq.gz
│   │   ├── 45ef08cf99099bddaf995544c93272cd3b8c2355.nq.gz
│   │   ├── 6a6cce03b7f071bcd9027e5068b988770f4e1133.nq.gz
│   │   ├── 6da4a942caf956bd90df100283a716680c889eea.nq.gz
│   │   ├── 7cdbca0dc95f2c635187711d7bd9599010f2c575.nq.gz
│   │   ├── 82891ea148c6774b98cfbe3d771d997a77537d16.nq.gz
│   │   └── cbc3163496621122fed1c86f806d6e09f333566e.nq.gz
│   ├── lsp
│   │   ├── 0ce39a4cf6424f30f6c243a20f2a1b1e46d909d2.nq.gz
│   │   ├── 125533116008cd7e3a81b339a15f4a2059ae12ae.nq.gz
│   │   ├── 14ceb8c046c6bbe07ede056c99be55e5a2e914e1.nq.gz
│   │   ├── 273a51a335694abd977e36a9b052bbd48190de78.nq.gz
│   │   ├── 2f6dfbc165337b0f998a281f7f7ac86674b8bf59.nq.gz
│   │   ├── 3b49821e82bef2a94a3bda0fbb2fd4bc0d732842.nq.gz
│   │   ├── 45ef08cf99099bddaf995544c93272cd3b8c2355.nq.gz
│   │   ├── 6a6cce03b7f071bcd9027e5068b988770f4e1133.nq.gz
│   │   ├── 6da4a942caf956bd90df100283a716680c889eea.nq.gz
│   │   ├── 7cdbca0dc95f2c635187711d7bd9599010f2c575.nq.gz
│   │   ├── 82891ea148c6774b98cfbe3d771d997a77537d16.nq.gz
│   │   └── cbc3163496621122fed1c86f806d6e09f333566e.nq.gz
│   └── repolex
│       ├── 0ce39a4cf6424f30f6c243a20f2a1b1e46d909d2.nq.gz
│       ├── 125533116008cd7e3a81b339a15f4a2059ae12ae.nq.gz
│       ├── 14ceb8c046c6bbe07ede056c99be55e5a2e914e1.nq.gz
│       ├── 273a51a335694abd977e36a9b052bbd48190de78.nq.gz
│       ├── 2f6dfbc165337b0f998a281f7f7ac86674b8bf59.nq.gz
│       ├── 3b49821e82bef2a94a3bda0fbb2fd4bc0d732842.nq.gz
│       ├── 45ef08cf99099bddaf995544c93272cd3b8c2355.nq.gz
│       ├── 6a6cce03b7f071bcd9027e5068b988770f4e1133.nq.gz
│       ├── 6da4a942caf956bd90df100283a716680c889eea.nq.gz
│       ├── 7cdbca0dc95f2c635187711d7bd9599010f2c575.nq.gz
│       ├── 82891ea148c6774b98cfbe3d771d997a77537d16.nq.gz
│       └── cbc3163496621122fed1c86f806d6e09f333566e.nq.gz
└── blob
    ├── 0106e1f17aacfc2d94750710ec409527c9d58d0a.nq.gz
    ├── 010b98eeef699c0d0f4d0136d7d2d352b2b51d4c.nq.gz
    ├── 01b5626e2a7156699fd5bfe835fe4b2c9460faca.nq.gz
    ├── 030e7f64a18989ad8deefe2e7aee2c37d5aa42be.nq.gz
    ├── 043ffc6d0ea82d4ff521855856c49066d01b6dba.nq.gz
    ├── 05c2e43ab3ec9968e9791ae12763c54983f18f41.nq.gz
    ├── 06d467f87ad532ec6a194f58974b167237da5311.nq.gz
    ├── 0a39d62824f6e9206d1053d6a8019ef75fd9c4d9.nq.gz
    ├── 0a4392a46d54ff5e8c6d248a5089795c1f6938bc.nq.gz
    ├── 0b5b899f23ac203b870a988625d15c5c3c1e86eb.nq.gz
    ├── 0bee129ecd918cbd6bb74e55b73b58a664a9eac9.nq.gz
    ├── 0e068c22d6c02ac742386a2bd67966a07336e645.nq.gz
    ├── 0fabf7f437356c6eea480ce0dbaa806d8dd24f22.nq.gz
    ├── 0fcb366e38573e3f5e58ef0b14d94710b36c6480.nq.gz
    ├── 10a5c376c55a84aede4b8ce059756eaa93799669.nq.gz
    ├── 10bef3cbaade93cae32274313e5f58f152c88b38.nq.gz
    ├── 10c9ea3931d98cf3f4ce74b6ab567e258d733359.nq.gz
    ├── 10dee36b8bd59a09320732326089d00b2fe22127.nq.gz
    ├── 135eb9339b723ea597dcc04a3411606d117139dd.nq.gz
    ├── 14bef4c8f1bf68f8f2c39af43636e99c93a02093.nq.gz
    ├── 15002c107ef71d2cb09598d20624d5d75d6ecd6b.nq.gz
    ├── 15e0db2bb24ca21d940eca266c5b070964d66848.nq.gz
    ├── 1627f64f982c40ee8e4188e279e7f53d7a6bec28.nq.gz
    ├── 167c033cf4a35d63299a69d3e203bce5e29669e5.nq.gz
    ├── 18d0a44e2e149cbecd47847040f83f2a63712ae0.nq.gz
    ├── 19098e5b63d95a42ffa2c3b1aade17d4f3a5b9b2.nq.gz
    ├── 196002ce1a1b3b7c1d4fe2f76696bab760122636.nq.gz
    ├── 19a89d63ccd50c3b5f57adb908694c1d3cafa37f.nq.gz
    ├── 1a6a3d3bbe195ea40a12af24a0696d725e233511.nq.gz
    ├── 1aced491543e818860022f2391f6487aa398f3ef.nq.gz
    ├── 1afe16153928846134c0dee651a1c613033bc0bc.nq.gz
    ├── 1b8f5a2e90d8415761b4df54f24d090a6198ee7b.nq.gz
    ├── 1c5288da73f5c4aefca889a77aca926b6ed8fd40.nq.gz
    ├── 1c54f349d628f3e5135340f8903ae75cc2381054.nq.gz
    ├── 1ce95538de3d7180755f0f0e1bb85e5744938b98.nq.gz
    ├── 1ceb1a2ca2d479ea67f5daefbc18fe07a80033a9.nq.gz
    ├── 1ceebe57be5af06c1ed6abaa13717f1ae343f8ea.nq.gz
    ├── 1d67ff45a3ecac8f09b8e25a85b9a165c43e7bb4.nq.gz
    ├── 1e167eb5e38230fcccaeab4d97a2e2202e0ee4a8.nq.gz
    ├── 1e8a1f67224f8b8d80a835435d9438eae820160b.nq.gz
    ├── 1ef7d9ed74622d40c2d13c31357d90a322881553.nq.gz
    ├── 1f019dfa4623247fa08df9c387a0588fa16a81b4.nq.gz
    ├── 1f02cf39acf12ee2d2a21f30d0628442df735663.nq.gz
    ├── 1f6ea3adb3a0ea56f997586850e71229061a5545.nq.gz
    ├── 1fcfb66b73e0ab3deb49baaabb6732bf47f71941.nq.gz
    ├── 205265a6618b5abc801ff8e30276577e98aba23f.nq.gz
    ├── 22614defbab43315c0f83e78e12ef56eb824ec84.nq.gz
    ├── 227758cdd65e5b0813a5ed60603dfc99a46f5607.nq.gz
    ├── 22a2e78408b70cd4328a449bb91fadffabcd31ee.nq.gz
    ├── 22fb09194f91915faaf375b71665381264f9572f.nq.gz
    ├── 2436b0f44ec6b765a49ef6734ac8ccdfe427f528.nq.gz
    ├── 247710deedda5fb9c8789eabe47710365a682bdb.nq.gz
    ├── 24d384b2fa2d9b6134b73b716f84687f2934b54d.nq.gz
    ├── 25b23a5691b8dd5b7df5380f79d66cc995dd0e58.nq.gz
    ├── 2646d014052cea169143737cbd3ead35d534ff58.nq.gz
    ├── 26b6c738fbe44298d80fd374cd1b53b8db9d4524.nq.gz
    ├── 26bf5f53703d6b5b28d86fe82ae07d2d18a4a90e.nq.gz
    ├── 275635ec853ca2a29640dd0de4403f546f5b1cd9.nq.gz
    ├── 2801cb94eb1244569ef8d5af4f81bcbe14eb0b54.nq.gz
    ├── 28b3468678f2cd6a09b9d6dade7dbbb6f5332c22.nq.gz
    ├── 29943ff073096ad95cee22da27eb14fcb27ed6f2.nq.gz
    ├── 2ad08d59d4ed2eb02fa4da977941a4fba4cc31bf.nq.gz
    ├── 2af8467ba13275abf8d3af696abd819092f3c46d.nq.gz
    ├── 2bc3ac05688c9a1fb770b5bec7235d0827591be3.nq.gz
    ├── 2beb16553d7c66c593eae81ac45213d640903bff.nq.gz
    ├── 2c5afcb3a93d4d65380fef29978322713989ab4c.nq.gz
    ├── 2d0f3010ae3d170626d3ff649fdb9cecc8e9688d.nq.gz
    ├── 2dc51dae9ad54ea5b279aef89095933294c18c38.nq.gz
    ├── 2e15f7ab113e85b8c935d3e027d900bf0bf11f09.nq.gz
    ├── 2ee0b141c762d8259ffc19ab70fac76426eda98e.nq.gz
    ├── 2f1eb0fc0094bd36b5fa7ee74219625d28446138.nq.gz
    ├── 2fa1826362e99f6b15b860a8f50f19e4dc4b7313.nq.gz
    ├── 305bead06886c3ad632fe62fb6001343fd7f2a72.nq.gz
    ├── 31a7a78b23babfc337dc54d5f1d3e9b1d4fe5dd5.nq.gz
    ├── 333618af97937fef1c7d2526186fdcb2d995e621.nq.gz
    ├── 3380d9c4bb0c08600f77ee04f69cfc73dac53712.nq.gz
    ├── 33f3a440337060a8e51d85de76d4595890c5d4e3.nq.gz
    ├── 34cf8505541ed9ac724deaada770afcd41585f8b.nq.gz
    ├── 34f25da378d666a0299c611f34c7a283d4da5d27.nq.gz
    ├── 371c0205ed90e22993f5033c7e272042ff49b998.nq.gz
    ├── 377a002c1685c44768a2e2a830a70bb548dd4dea.nq.gz
    ├── 38cfc09d53ef0c297efde6d2bfbd8c23899a145f.nq.gz
    ├── 38e996da45b0539c443dd7838f44c4ddc8616872.nq.gz
    ├── 39db613762a48f884d58abe8cf08579cf64e73d3.nq.gz
    ├── 3a5e42002b90e92c9e416be106d90586907f2db5.nq.gz
    ├── 3b12905572a136ae4649be250dc24b315c621e5e.nq.gz
    ├── 3c1f7849be60b406e6aecbebccf1af5ea03bf40e.nq.gz
    ├── 3ce2f795019be68033b4c662b461c0a444c4721a.nq.gz
    ├── 3d8451d3075947bad9eb9830492468a978fdd4c9.nq.gz
    ├── 3d96558486a8388cdd66e9632447ac87f18ada34.nq.gz
    ├── 3db58b87038e28f64788284b781afae34e1580e2.nq.gz
    ├── 3eafc8fb2349fa65549ded07bd196ab6b64ca27b.nq.gz
    ├── 3ecc22fcd498e56f78f2a4e4fa6ca6244f25350e.nq.gz
    ├── 3f0b45b46d3eee968cde97c5f6a08c3236016dd4.nq.gz
    ├── 3fd2f0fffef37b0a82df7a46df7c14cab769a58a.nq.gz
    ├── 40503cea08fc97a1a16a9f29bcc05ea8b2966129.nq.gz
    ├── 412d0923c469c661c8074a133039fb4721520ead.nq.gz
    ├── 4165cf1ed061b6255a749c62aa006226f6a12371.nq.gz
    ├── 41b107cf5f0bb9ea5751efc1b6c13ca16f19cc13.nq.gz
    ├── 436f40b54c6659da6da134740654c5cf9e9f99f7.nq.gz
    ├── 4372d7759d1f96e5b72672b5ab48772ff0878ee0.nq.gz
    ├── 4386f136291707bfe5654f4da36d0fbbe3f29ebc.nq.gz
    ├── 456fb7fe4a356e74f3a22777b55bfae4f6e5f8f7.nq.gz
    ├── 46422ec57b98e821b8964788d4f1a22d245b5266.nq.gz
    ├── 46b4bbc8b1fd2c8b254a4fe75296f236189ebcd3.nq.gz
    ├── 4713c9d20e62d8d687b87bb115fe51dca735612c.nq.gz
    ├── 47be84780517281e0013609418dc1031a67ef50a.nq.gz
    ├── 482a3c4a826d73225d7bb57aa07972dd9563ff32.nq.gz
    ├── 485d92a1a8093a488941f9da5f18ea839a1f83ef.nq.gz
    ├── 49313054449e757d2dd2798e7814c5c77af7c22a.nq.gz
    ├── 49bc97df0231872d5eafe6b71d495e97db413e22.nq.gz
    ├── 49c2052bdc996fc720e5f5e750802ed64d704bfd.nq.gz
    ├── 4a15f3388ea7afaf27fa6193895ebeb7306e9bc1.nq.gz
    ├── 4a80bfb7d523545aacea4a0eec80af63a9e1c0b4.nq.gz
    ├── 4a94d12fd8405c32b4c20abe777c1a9a7e6a30cb.nq.gz
    ├── 4c70c63bb536d2bf1f07e749dfb596b263792492.nq.gz
    ├── 4cac4e8f230acae58abe6092f17d6f3e574fb968.nq.gz
    ├── 4d1580187517ce755be1156d42cee06638b8a50d.nq.gz
    ├── 4df0d2d88f33a051b69a7350afb634db980c7445.nq.gz
    ├── 4df112578e2fd9e7fb909c63d7076a7ad6d0e242.nq.gz
    ├── 4e776071cdc5b68e3b0d4485b6ba90c81124db4f.nq.gz
    ├── 4f1450589ed01dcc0c98c016358632648126ffd1.nq.gz
    ├── 4f6272cfdedf0736fcd5b72d9a010b34ec476470.nq.gz
    ├── 503302d6beb32a90626233a114d0cae76537bd33.nq.gz
    ├── 50b972d3bd551c401bd6ab39eee5ae0fda9fd0d3.nq.gz
    ├── 51b344257cf3c32a34d8fc30875708bd8f7d657b.nq.gz
    ├── 51c84f909958f726a12fc852dcac13c7780e295c.nq.gz
    ├── 51e5ab446766878991251613044e3129a2a072f9.nq.gz
    ├── 5271ceb252d606ef9c83844844b9547ccce3c1c0.nq.gz
    ├── 5273ee8bcf7b1bf10b98594f145152a61df8ec07.nq.gz
    ├── 536d2832aa4282d35fb4bcdafb9de166f6de76d9.nq.gz
    ├── 5505536dac4fa0b52c91ec5c308e06886e8f3320.nq.gz
    ├── 5589b0e53a8233b33fefee1a240c606cbe093a2a.nq.gz
    ├── 567c8c4cb2fec7bc733f03fe8d7327c2fc7564c7.nq.gz
    ├── 56ad9f144c6dbd904c3168bd12367ad3774c89d0.nq.gz
    ├── 571ff819cc3efeb2c42a711929d271b9c758ff92.nq.gz
    ├── 58a6847b034d19ca3e8f2df63464efd0d1a16d10.nq.gz
    ├── 5a06718d3bbd0034c571a87ebc659df65d689bb8.nq.gz
    ├── 5b1c42bbc4dda780e39bc9713419a6d871cadf3d.nq.gz
    ├── 5b613f9512f92c51949c829264f0b0f42bc250f8.nq.gz
    ├── 5bebca381e9a19c3e2f5e80c09200e0e06b631cd.nq.gz
    ├── 5c5064f51a5689618e371fc130781caef74a5736.nq.gz
    ├── 5d6d3d1cee29f2149f218377b4ee4d39da983ebe.nq.gz
    ├── 5d992226fade81c05c34b585b42e1337f4258f99.nq.gz
    ├── 5da5b43c7394d4993a447d0cb33067aa981f68aa.nq.gz
    ├── 5dd4c8cb63536973ac40523a1eb0a9d9808ea14a.nq.gz
    ├── 5e17a8a59ab7bac73140da63aa96913dc6f093bb.nq.gz
    ├── 5e9da3f4cb6e6e0236c8cbc34825fb9c297c97f0.nq.gz
    ├── 5f02c4c21d43a825e3ce65ef97e343899ff77475.nq.gz
    ├── 5fc3c956979430dbb3e69670ff4f10f017678bab.nq.gz
    ├── 5fd302f41ee71dde0ba9577b19723e5e5fb372bb.nq.gz
    └── 607cfd35f0aef1c5e894d630cfe5858b901d6390.nq.gz

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

## Source repository

[expressjs/express](https://github.com/expressjs/express)

---
*Parsed on 2026-03-18 by [repolex](https://repolex.ai)*
