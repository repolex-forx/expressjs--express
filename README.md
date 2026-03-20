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
│   │   ├── 0ac1ba527e75e700698bcb4dad5905cea80e29f5.nq.gz
│   │   ├── 0ce39a4cf6424f30f6c243a20f2a1b1e46d909d2.nq.gz
│   │   ├── 125533116008cd7e3a81b339a15f4a2059ae12ae.nq.gz
│   │   ├── 14ceb8c046c6bbe07ede056c99be55e5a2e914e1.nq.gz
│   │   ├── 15590d75b26f1e4b95b565f8306c763ee860d3e2.nq.gz
│   │   ├── 273a51a335694abd977e36a9b052bbd48190de78.nq.gz
│   │   ├── 2f6dfbc165337b0f998a281f7f7ac86674b8bf59.nq.gz
│   │   ├── 3ab30210a26368812c2f08af7f737f3c9b740985.nq.gz
│   │   ├── 3b49821e82bef2a94a3bda0fbb2fd4bc0d732842.nq.gz
│   │   ├── 3d188fe13e1901222cd830dcdc9772a34b9bd745.nq.gz
│   │   ├── 4405b849a9ea62dfa76f32031e187c844f8e217d.nq.gz
│   │   ├── 45ef08cf99099bddaf995544c93272cd3b8c2355.nq.gz
│   │   ├── 5c04f85f93df5ca1dea84683509d4954a4b4204c.nq.gz
│   │   ├── 6a6cce03b7f071bcd9027e5068b988770f4e1133.nq.gz
│   │   ├── 6d39d0f8a809eed1b75e0d5bd4d2dad3d2190f25.nq.gz
│   │   ├── 6da4a942caf956bd90df100283a716680c889eea.nq.gz
│   │   ├── 73c5533e665743d305e266eee134c48d88d2dcfd.nq.gz
│   │   ├── 776ee26bc3644c39f1db7de779e1744f8a24068f.nq.gz
│   │   ├── 798d255ba63e9e35cbdeff95a008a982d10f07d3.nq.gz
│   │   ├── 7cdbca0dc95f2c635187711d7bd9599010f2c575.nq.gz
│   │   ├── 82891ea148c6774b98cfbe3d771d997a77537d16.nq.gz
│   │   ├── 86328767fe6b253bdbf99343049cc57f1c3a1fbb.nq.gz
│   │   ├── 92d37671c52d89b37d1546677ad4f48b9bdaab42.nq.gz
│   │   ├── 957cf45fa14d5fe5cdaab87ea7e5bca8395725cd.nq.gz
│   │   ├── b149430114b42299be84b5c1dfe25a8303605db5.nq.gz
│   │   ├── bef6f208d16b96638cbfafff5ef516e278608e81.nq.gz
│   │   ├── bf596dc0239aad85198ebfe70921fd79a1cdedc9.nq.gz
│   │   ├── cb59086305367d9fcd7d63b53cfca1a3e4ef77d7.nq.gz
│   │   ├── cbc3163496621122fed1c86f806d6e09f333566e.nq.gz
│   │   ├── ce2bcaef6889f06563c5b186e9f727f8b1b1b9d0.nq.gz
│   │   ├── dc31ea34b858f94b79690573db3f2fd632074a94.nq.gz
│   │   ├── e0afda444f776ddec94ebdae8e1ed7501e26fb22.nq.gz
│   │   ├── f1c46f51e5a99413addf4b6eaebf2714fe841669.nq.gz
│   │   ├── f7be983a7718d4b6a74bd5d6ba7a6073ae3bfa6a.nq.gz
│   │   ├── f7e73e2da07cb625859824794346c1b74a98c3b5.nq.gz
│   │   └── ff23423d34d9d7f829d160aeb91b5c939ab4a4e1.nq.gz
│   ├── dataflow
│   │   ├── 0ce39a4cf6424f30f6c243a20f2a1b1e46d909d2.nq.gz
│   │   ├── 125533116008cd7e3a81b339a15f4a2059ae12ae.nq.gz
│   │   ├── 14ceb8c046c6bbe07ede056c99be55e5a2e914e1.nq.gz
│   │   ├── 15590d75b26f1e4b95b565f8306c763ee860d3e2.nq.gz
│   │   ├── 273a51a335694abd977e36a9b052bbd48190de78.nq.gz
│   │   ├── 2f6dfbc165337b0f998a281f7f7ac86674b8bf59.nq.gz
│   │   ├── 3b49821e82bef2a94a3bda0fbb2fd4bc0d732842.nq.gz
│   │   ├── 3d188fe13e1901222cd830dcdc9772a34b9bd745.nq.gz
│   │   ├── 4405b849a9ea62dfa76f32031e187c844f8e217d.nq.gz
│   │   ├── 45ef08cf99099bddaf995544c93272cd3b8c2355.nq.gz
│   │   ├── 6a6cce03b7f071bcd9027e5068b988770f4e1133.nq.gz
│   │   ├── 6d39d0f8a809eed1b75e0d5bd4d2dad3d2190f25.nq.gz
│   │   ├── 6da4a942caf956bd90df100283a716680c889eea.nq.gz
│   │   ├── 7cdbca0dc95f2c635187711d7bd9599010f2c575.nq.gz
│   │   ├── 82891ea148c6774b98cfbe3d771d997a77537d16.nq.gz
│   │   ├── 86328767fe6b253bdbf99343049cc57f1c3a1fbb.nq.gz
│   │   ├── 92d37671c52d89b37d1546677ad4f48b9bdaab42.nq.gz
│   │   ├── b149430114b42299be84b5c1dfe25a8303605db5.nq.gz
│   │   ├── cb59086305367d9fcd7d63b53cfca1a3e4ef77d7.nq.gz
│   │   └── cbc3163496621122fed1c86f806d6e09f333566e.nq.gz
│   ├── lsp
│   │   ├── 0ac1ba527e75e700698bcb4dad5905cea80e29f5.nq.gz
│   │   ├── 0ce39a4cf6424f30f6c243a20f2a1b1e46d909d2.nq.gz
│   │   ├── 125533116008cd7e3a81b339a15f4a2059ae12ae.nq.gz
│   │   ├── 14ceb8c046c6bbe07ede056c99be55e5a2e914e1.nq.gz
│   │   ├── 15590d75b26f1e4b95b565f8306c763ee860d3e2.nq.gz
│   │   ├── 273a51a335694abd977e36a9b052bbd48190de78.nq.gz
│   │   ├── 2f6dfbc165337b0f998a281f7f7ac86674b8bf59.nq.gz
│   │   ├── 3ab30210a26368812c2f08af7f737f3c9b740985.nq.gz
│   │   ├── 3b49821e82bef2a94a3bda0fbb2fd4bc0d732842.nq.gz
│   │   ├── 3d188fe13e1901222cd830dcdc9772a34b9bd745.nq.gz
│   │   ├── 4405b849a9ea62dfa76f32031e187c844f8e217d.nq.gz
│   │   ├── 45ef08cf99099bddaf995544c93272cd3b8c2355.nq.gz
│   │   ├── 5c04f85f93df5ca1dea84683509d4954a4b4204c.nq.gz
│   │   ├── 6a6cce03b7f071bcd9027e5068b988770f4e1133.nq.gz
│   │   ├── 6d39d0f8a809eed1b75e0d5bd4d2dad3d2190f25.nq.gz
│   │   ├── 6da4a942caf956bd90df100283a716680c889eea.nq.gz
│   │   ├── 73c5533e665743d305e266eee134c48d88d2dcfd.nq.gz
│   │   ├── 776ee26bc3644c39f1db7de779e1744f8a24068f.nq.gz
│   │   ├── 798d255ba63e9e35cbdeff95a008a982d10f07d3.nq.gz
│   │   ├── 7cdbca0dc95f2c635187711d7bd9599010f2c575.nq.gz
│   │   ├── 82891ea148c6774b98cfbe3d771d997a77537d16.nq.gz
│   │   ├── 86328767fe6b253bdbf99343049cc57f1c3a1fbb.nq.gz
│   │   ├── 92d37671c52d89b37d1546677ad4f48b9bdaab42.nq.gz
│   │   ├── 957cf45fa14d5fe5cdaab87ea7e5bca8395725cd.nq.gz
│   │   ├── b149430114b42299be84b5c1dfe25a8303605db5.nq.gz
│   │   ├── bef6f208d16b96638cbfafff5ef516e278608e81.nq.gz
│   │   ├── bf596dc0239aad85198ebfe70921fd79a1cdedc9.nq.gz
│   │   ├── cb59086305367d9fcd7d63b53cfca1a3e4ef77d7.nq.gz
│   │   ├── cbc3163496621122fed1c86f806d6e09f333566e.nq.gz
│   │   ├── ce2bcaef6889f06563c5b186e9f727f8b1b1b9d0.nq.gz
│   │   ├── dc31ea34b858f94b79690573db3f2fd632074a94.nq.gz
│   │   ├── e0afda444f776ddec94ebdae8e1ed7501e26fb22.nq.gz
│   │   ├── f1c46f51e5a99413addf4b6eaebf2714fe841669.nq.gz
│   │   ├── f7be983a7718d4b6a74bd5d6ba7a6073ae3bfa6a.nq.gz
│   │   ├── f7e73e2da07cb625859824794346c1b74a98c3b5.nq.gz
│   │   └── ff23423d34d9d7f829d160aeb91b5c939ab4a4e1.nq.gz
│   └── repolex
│       ├── 0ac1ba527e75e700698bcb4dad5905cea80e29f5.nq.gz
│       ├── 0ce39a4cf6424f30f6c243a20f2a1b1e46d909d2.nq.gz
│       ├── 125533116008cd7e3a81b339a15f4a2059ae12ae.nq.gz
│       ├── 14ceb8c046c6bbe07ede056c99be55e5a2e914e1.nq.gz
│       ├── 15590d75b26f1e4b95b565f8306c763ee860d3e2.nq.gz
│       ├── 273a51a335694abd977e36a9b052bbd48190de78.nq.gz
│       ├── 2f6dfbc165337b0f998a281f7f7ac86674b8bf59.nq.gz
│       ├── 3ab30210a26368812c2f08af7f737f3c9b740985.nq.gz
│       ├── 3b49821e82bef2a94a3bda0fbb2fd4bc0d732842.nq.gz
│       ├── 3d188fe13e1901222cd830dcdc9772a34b9bd745.nq.gz
│       ├── 4405b849a9ea62dfa76f32031e187c844f8e217d.nq.gz
│       ├── 45ef08cf99099bddaf995544c93272cd3b8c2355.nq.gz
│       ├── 5c04f85f93df5ca1dea84683509d4954a4b4204c.nq.gz
│       ├── 6a6cce03b7f071bcd9027e5068b988770f4e1133.nq.gz
│       ├── 6d39d0f8a809eed1b75e0d5bd4d2dad3d2190f25.nq.gz
│       ├── 6da4a942caf956bd90df100283a716680c889eea.nq.gz
│       ├── 73c5533e665743d305e266eee134c48d88d2dcfd.nq.gz
│       ├── 776ee26bc3644c39f1db7de779e1744f8a24068f.nq.gz
│       ├── 798d255ba63e9e35cbdeff95a008a982d10f07d3.nq.gz
│       ├── 7cdbca0dc95f2c635187711d7bd9599010f2c575.nq.gz
│       ├── 82891ea148c6774b98cfbe3d771d997a77537d16.nq.gz
│       ├── 86328767fe6b253bdbf99343049cc57f1c3a1fbb.nq.gz
│       ├── 92d37671c52d89b37d1546677ad4f48b9bdaab42.nq.gz
│       ├── 957cf45fa14d5fe5cdaab87ea7e5bca8395725cd.nq.gz
│       ├── b149430114b42299be84b5c1dfe25a8303605db5.nq.gz
│       ├── bef6f208d16b96638cbfafff5ef516e278608e81.nq.gz
│       ├── bf596dc0239aad85198ebfe70921fd79a1cdedc9.nq.gz
│       ├── cb59086305367d9fcd7d63b53cfca1a3e4ef77d7.nq.gz
│       ├── cbc3163496621122fed1c86f806d6e09f333566e.nq.gz
│       ├── ce2bcaef6889f06563c5b186e9f727f8b1b1b9d0.nq.gz
│       ├── dc31ea34b858f94b79690573db3f2fd632074a94.nq.gz
│       ├── e0afda444f776ddec94ebdae8e1ed7501e26fb22.nq.gz
│       ├── f1c46f51e5a99413addf4b6eaebf2714fe841669.nq.gz
│       ├── f7be983a7718d4b6a74bd5d6ba7a6073ae3bfa6a.nq.gz
│       ├── f7e73e2da07cb625859824794346c1b74a98c3b5.nq.gz
│       └── ff23423d34d9d7f829d160aeb91b5c939ab4a4e1.nq.gz
└── blob
    ├── 000f419c04e250e6361f5cac477d8d871ec32ae7.nq.gz
    ├── 00158b89960d3e1a7cf0027ca8136b97d2adbb06.nq.gz
    ├── 00175ad62d16c2a8c2d9720644406f674a34acb8.nq.gz
    ├── 0106e1f17aacfc2d94750710ec409527c9d58d0a.nq.gz
    ├── 010b98eeef699c0d0f4d0136d7d2d352b2b51d4c.nq.gz
    ├── 0117c4cefddf454abeb75ca8f8206b02da174646.nq.gz
    ├── 0158181ba584282a615222095fdb9f2b4bd1afea.nq.gz
    ├── 0174950d73df1450383edee67afcc8715a714209.nq.gz
    ├── 01b5626e2a7156699fd5bfe835fe4b2c9460faca.nq.gz
    ├── 01bb244c235cd9da69955e4d700dd9ceff4077ea.nq.gz
    ├── 02eb5166366d30b40122ac289fd6bbedd42a34f3.nq.gz
    ├── 02f249b7fbc7d0b52a66ac1bbcbd779ccd32bf1d.nq.gz
    ├── 030e7f64a18989ad8deefe2e7aee2c37d5aa42be.nq.gz
    ├── 031216f0768c0935b59f6b580786d6d6445ff577.nq.gz
    ├── 03132e36ff201c5e38e177948e6ced808faa7530.nq.gz
    ├── 03ad3244e79ea38573c7518f2d6d69126ff2997b.nq.gz
    ├── 03f7cbdabba30ef5a7ac6af629d2ada74f8cc80c.nq.gz
    ├── 043ffc6d0ea82d4ff521855856c49066d01b6dba.nq.gz
    ├── 0447575e49f47f03e5c5ba09ae5023c342107bff.nq.gz
    ├── 045adaa8630f6fecff185d932d5ddbc60b2ca2c4.nq.gz
    ├── 047bf7ecf24103f2e8af8e530601452cfea537b1.nq.gz
    ├── 04a1a7847b975e35914d3afcc520f8ae03dc983d.nq.gz
    ├── 057894161314b25f05c85b237d458f73855cee9b.nq.gz
    ├── 05b441772398e095929bcdf59e15d0263973d6dd.nq.gz
    ├── 05c2e43ab3ec9968e9791ae12763c54983f18f41.nq.gz
    ├── 061e243f4f7e69b9b0932ffc3952aa1d29324f47.nq.gz
    ├── 06a76fc6396a10bfd41d650394f8fe89934a662f.nq.gz
    ├── 06d467f87ad532ec6a194f58974b167237da5311.nq.gz
    ├── 07440302ea4be31fad29c95b53179abdd24d67e1.nq.gz
    ├── 075d3951757c580d5fbff43c0db732d3c352fbca.nq.gz
    ├── 0779c814bd69afe4eede8a7534ca14e9c994823c.nq.gz
    ├── 085099236673f972c3e1e8f36019f562eafc3eef.nq.gz
    ├── 0855acf479e1b7be7fc5674e42b956fc13c127d4.nq.gz
    ├── 08567e4dcb44e1b60355ffb8e9398cf802da327d.nq.gz
    ├── 08c68f79e2ee3d659ab4433b87065a23930d0469.nq.gz
    ├── 08cf8f91e922a0f2661852427b674b74693e3788.nq.gz
    ├── 08f0cb5429520609df8626b6f6c3a7c76c5a4d30.nq.gz
    ├── 094d28898a5340ef36a81e72311514011d753eca.nq.gz
    ├── 094e35c98c2461e04489080109e00f05118cd63f.nq.gz
    ├── 0950062e39bc6d374c739ef6e220bd4ad2570b5e.nq.gz
    ├── 09653e39abf5467c6fc9766092364e90093deac6.nq.gz
    ├── 098480639f6d30f95dc61f393e515ecb770efdfe.nq.gz
    ├── 09a0111cce1ad20986c8ecb8c6d3f847892836c0.nq.gz
    ├── 09cdb0c133c24019266282a5a36ac9243cb5a7bc.nq.gz
    ├── 0a39d62824f6e9206d1053d6a8019ef75fd9c4d9.nq.gz
    ├── 0a4392a46d54ff5e8c6d248a5089795c1f6938bc.nq.gz
    ├── 0a6e3356ebff5b98b1f3f5f69adcff9fe8c9ed5b.nq.gz
    ├── 0a901256855d2d1b72f4587455661f1577bf8a5e.nq.gz
    ├── 0a919f4929627c6f28ae9061434b01dd5f6d2682.nq.gz
    ├── 0b0060e2a4e6abd788389cc9d66d9a0cff019bd9.nq.gz
    ├── 0b25d599f5f870fbdf16d100b7c606b7813aa766.nq.gz
    ├── 0b5b899f23ac203b870a988625d15c5c3c1e86eb.nq.gz
    ├── 0b8c5ced5ddfdf5fee79a4681b506f596dee93e1.nq.gz
    ├── 0b9b0ba4edde892d558c574949fc3b65cdc5de8b.nq.gz
    ├── 0bee129ecd918cbd6bb74e55b73b58a664a9eac9.nq.gz
    ├── 0c1292dbd781eb5d8efe3df65eb19be0fc773519.nq.gz
    ├── 0c198cc39fa46a3435a27011d2d7df5b2758f67e.nq.gz
    ├── 0c84aa6183cae1e16d31228c2f9d5195cc6ae5b6.nq.gz
    ├── 0d0ed8b5e413944efbeda77b222dcd5bf0c6bced.nq.gz
    ├── 0d292d64573f05222add50797cdcc41fd0fd1f57.nq.gz
    ├── 0d87fd62447dea9e685691b9ff137fc0df4f466f.nq.gz
    ├── 0de25eb75f8e3e474159b795098c9ea6479832aa.nq.gz
    ├── 0df4780e2212613808fc0e59130448e1a43e6ee6.nq.gz
    ├── 0e068c22d6c02ac742386a2bd67966a07336e645.nq.gz
    ├── 0e2f86083ebac73b59695fb670796da1d9d156d6.nq.gz
    ├── 0e3373d548c5266ff63a31243e680cf411869b07.nq.gz
    ├── 0e3449d87e018d418dbc2664910083fddbc17b48.nq.gz
    ├── 0eb40f3f5cf9785ce6fe99f28814f0bcb7fbf699.nq.gz
    ├── 0f150bfeecf2b3901cae6b82df280fbd08417232.nq.gz
    ├── 0f1aa982ad2b9acafe088c59662323ba8eec4534.nq.gz
    ├── 0f3c76789296f12b9e911c543d98a1cc507cd8a2.nq.gz
    └── 0fabf7f437356c6eea480ce0dbaa806d8dd24f22.nq.gz

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
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*
