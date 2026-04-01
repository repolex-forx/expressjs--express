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
└── aggregate
    ├── ast
    │   ├── 0437c513f2dbc8d1dfc5a3e35fe35182bd3a671e.nq.gz
    │   ├── 04bc62787be974874bc1467b23606c36bc9779ba.nq.gz
    │   ├── 08939683c7a2e5d7dc928d310ebab65878bffff3.nq.gz
    │   ├── 0ac1ba527e75e700698bcb4dad5905cea80e29f5.nq.gz
    │   ├── 0ce39a4cf6424f30f6c243a20f2a1b1e46d909d2.nq.gz
    │   ├── 0dc5836d5e6f41760d736d98d0cfa5b57bac84a7.nq.gz
    │   ├── 112dbb2ab40a6ecdd7ed0de4503dfc56655a24a3.nq.gz
    │   ├── 125533116008cd7e3a81b339a15f4a2059ae12ae.nq.gz
    │   ├── 147c2507c3bdcd22c7c0176e57c9d585d0aa2642.nq.gz
    │   ├── 14ceb8c046c6bbe07ede056c99be55e5a2e914e1.nq.gz
    │   ├── 15590d75b26f1e4b95b565f8306c763ee860d3e2.nq.gz
    │   ├── 21df421ebc7a5249bb31101da666bbf22adc3f18.nq.gz
    │   ├── 273a51a335694abd977e36a9b052bbd48190de78.nq.gz
    │   ├── 2a105df9f2bae5d2b0e5af64fc0367a159fe42f2.nq.gz
    │   ├── 2f6dfbc165337b0f998a281f7f7ac86674b8bf59.nq.gz
    │   ├── 311e83e591a149a7549bab543dfd126d3223f7fd.nq.gz
    │   ├── 3ab30210a26368812c2f08af7f737f3c9b740985.nq.gz
    │   ├── 3b49821e82bef2a94a3bda0fbb2fd4bc0d732842.nq.gz
    │   ├── 3d188fe13e1901222cd830dcdc9772a34b9bd745.nq.gz
    │   ├── 4405b849a9ea62dfa76f32031e187c844f8e217d.nq.gz
    │   ├── 45ef08cf99099bddaf995544c93272cd3b8c2355.nq.gz
    │   ├── 53589b4f37de415b10e368301d8279e513021d88.nq.gz
    │   ├── 5c04f85f93df5ca1dea84683509d4954a4b4204c.nq.gz
    │   ├── 621d074bd87dd7a7064c5607dbed05b97f80fcc0.nq.gz
    │   ├── 63ab25579bda70b4927a179b580a9c580b6c7ada.nq.gz
    │   ├── 6a6cce03b7f071bcd9027e5068b988770f4e1133.nq.gz
    │   ├── 6d39d0f8a809eed1b75e0d5bd4d2dad3d2190f25.nq.gz
    │   ├── 6da4a942caf956bd90df100283a716680c889eea.nq.gz
    │   ├── 73c5533e665743d305e266eee134c48d88d2dcfd.nq.gz
    │   ├── 776ee26bc3644c39f1db7de779e1744f8a24068f.nq.gz
    │   ├── 798d255ba63e9e35cbdeff95a008a982d10f07d3.nq.gz
    │   ├── 7cdbca0dc95f2c635187711d7bd9599010f2c575.nq.gz
    │   ├── 82891ea148c6774b98cfbe3d771d997a77537d16.nq.gz
    │   ├── 86328767fe6b253bdbf99343049cc57f1c3a1fbb.nq.gz
    │   ├── 916c53737d97b605385f9b5235a3a890f864c6bb.nq.gz
    │   ├── 92d37671c52d89b37d1546677ad4f48b9bdaab42.nq.gz
    │   ├── 957cf45fa14d5fe5cdaab87ea7e5bca8395725cd.nq.gz
    │   ├── 9bb47fba300a4c096e049e51b636b3c282eb11f7.nq.gz
    │   ├── abe0ffa311bf39ca2bbfc8791856753b7cabe843.nq.gz
    │   ├── b149430114b42299be84b5c1dfe25a8303605db5.nq.gz
    │   ├── b886eb52cf955c2f29ad31b514607d4e38c1dbaf.nq.gz
    │   ├── bcdeee2df510cea17ad4524cf53b9900a46d5042.nq.gz
    │   ├── bef6f208d16b96638cbfafff5ef516e278608e81.nq.gz
    │   ├── bf596dc0239aad85198ebfe70921fd79a1cdedc9.nq.gz
    │   ├── ca782dbc589bb69842f5b214d98d1b4cddd04ce9.nq.gz
    │   ├── cb59086305367d9fcd7d63b53cfca1a3e4ef77d7.nq.gz
    │   ├── cbc3163496621122fed1c86f806d6e09f333566e.nq.gz
    │   ├── ce2bcaef6889f06563c5b186e9f727f8b1b1b9d0.nq.gz
    │   ├── cf709f302120c0de62978036916778c29fed7d98.nq.gz
    │   ├── db2eb658ca8a257869621ab930ab3bf1dce830d9.nq.gz
    │   ├── dbac741a49a5a64336b70c06e85c2e2706e36336.nq.gz
    │   ├── dc31ea34b858f94b79690573db3f2fd632074a94.nq.gz
    │   ├── dc538f6e810bd462c98ee7e6aae24c64d4b1da93.nq.gz
    │   ├── e0afda444f776ddec94ebdae8e1ed7501e26fb22.nq.gz
    │   ├── e9c9f95ade0f20a048861ac886d4767a839d5286.nq.gz
    │   ├── ea3d60565242c47be97088ead2708d7b88390858.nq.gz
    │   ├── f15bba7309f2e0a17f7b7a5552b9618f074078c8.nq.gz
    │   ├── f1c46f51e5a99413addf4b6eaebf2714fe841669.nq.gz
    │   ├── f7be983a7718d4b6a74bd5d6ba7a6073ae3bfa6a.nq.gz
    │   ├── f7e73e2da07cb625859824794346c1b74a98c3b5.nq.gz
    │   ├── fd27f1f4e19710d683f78b0683d45c5d8c590eae.nq.gz
    │   └── ff23423d34d9d7f829d160aeb91b5c939ab4a4e1.nq.gz
    ├── dataflow
    │   ├── 0ce39a4cf6424f30f6c243a20f2a1b1e46d909d2.nq.gz
    │   ├── 125533116008cd7e3a81b339a15f4a2059ae12ae.nq.gz
    │   ├── 14ceb8c046c6bbe07ede056c99be55e5a2e914e1.nq.gz
    │   ├── 15590d75b26f1e4b95b565f8306c763ee860d3e2.nq.gz
    │   ├── 273a51a335694abd977e36a9b052bbd48190de78.nq.gz
    │   ├── 2f6dfbc165337b0f998a281f7f7ac86674b8bf59.nq.gz
    │   ├── 3b49821e82bef2a94a3bda0fbb2fd4bc0d732842.nq.gz
    │   ├── 3d188fe13e1901222cd830dcdc9772a34b9bd745.nq.gz
    │   ├── 4405b849a9ea62dfa76f32031e187c844f8e217d.nq.gz
    │   ├── 45ef08cf99099bddaf995544c93272cd3b8c2355.nq.gz
    │   ├── 6a6cce03b7f071bcd9027e5068b988770f4e1133.nq.gz
    │   ├── 6d39d0f8a809eed1b75e0d5bd4d2dad3d2190f25.nq.gz
    │   ├── 6da4a942caf956bd90df100283a716680c889eea.nq.gz
    │   ├── 7cdbca0dc95f2c635187711d7bd9599010f2c575.nq.gz
    │   ├── 82891ea148c6774b98cfbe3d771d997a77537d16.nq.gz
    │   ├── 86328767fe6b253bdbf99343049cc57f1c3a1fbb.nq.gz
    │   ├── 92d37671c52d89b37d1546677ad4f48b9bdaab42.nq.gz
    │   ├── b149430114b42299be84b5c1dfe25a8303605db5.nq.gz
    │   ├── cb59086305367d9fcd7d63b53cfca1a3e4ef77d7.nq.gz
    │   └── cbc3163496621122fed1c86f806d6e09f333566e.nq.gz
    ├── lsp
    │   ├── 0437c513f2dbc8d1dfc5a3e35fe35182bd3a671e.nq.gz
    │   ├── 04bc62787be974874bc1467b23606c36bc9779ba.nq.gz
    │   ├── 08939683c7a2e5d7dc928d310ebab65878bffff3.nq.gz
    │   ├── 0ac1ba527e75e700698bcb4dad5905cea80e29f5.nq.gz
    │   ├── 0ce39a4cf6424f30f6c243a20f2a1b1e46d909d2.nq.gz
    │   ├── 0dc5836d5e6f41760d736d98d0cfa5b57bac84a7.nq.gz
    │   ├── 112dbb2ab40a6ecdd7ed0de4503dfc56655a24a3.nq.gz
    │   ├── 125533116008cd7e3a81b339a15f4a2059ae12ae.nq.gz
    │   ├── 147c2507c3bdcd22c7c0176e57c9d585d0aa2642.nq.gz
    │   ├── 14ceb8c046c6bbe07ede056c99be55e5a2e914e1.nq.gz
    │   ├── 15590d75b26f1e4b95b565f8306c763ee860d3e2.nq.gz
    │   ├── 21df421ebc7a5249bb31101da666bbf22adc3f18.nq.gz
    │   ├── 273a51a335694abd977e36a9b052bbd48190de78.nq.gz
    │   ├── 2a105df9f2bae5d2b0e5af64fc0367a159fe42f2.nq.gz
    │   ├── 2f6dfbc165337b0f998a281f7f7ac86674b8bf59.nq.gz
    │   ├── 311e83e591a149a7549bab543dfd126d3223f7fd.nq.gz
    │   ├── 3ab30210a26368812c2f08af7f737f3c9b740985.nq.gz
    │   ├── 3b49821e82bef2a94a3bda0fbb2fd4bc0d732842.nq.gz
    │   ├── 3d188fe13e1901222cd830dcdc9772a34b9bd745.nq.gz
    │   ├── 4405b849a9ea62dfa76f32031e187c844f8e217d.nq.gz
    │   ├── 45ef08cf99099bddaf995544c93272cd3b8c2355.nq.gz
    │   ├── 53589b4f37de415b10e368301d8279e513021d88.nq.gz
    │   ├── 5c04f85f93df5ca1dea84683509d4954a4b4204c.nq.gz
    │   ├── 621d074bd87dd7a7064c5607dbed05b97f80fcc0.nq.gz
    │   ├── 63ab25579bda70b4927a179b580a9c580b6c7ada.nq.gz
    │   ├── 6a6cce03b7f071bcd9027e5068b988770f4e1133.nq.gz
    │   ├── 6d39d0f8a809eed1b75e0d5bd4d2dad3d2190f25.nq.gz
    │   ├── 6da4a942caf956bd90df100283a716680c889eea.nq.gz
    │   ├── 73c5533e665743d305e266eee134c48d88d2dcfd.nq.gz
    │   ├── 776ee26bc3644c39f1db7de779e1744f8a24068f.nq.gz
    │   ├── 798d255ba63e9e35cbdeff95a008a982d10f07d3.nq.gz
    │   ├── 7cdbca0dc95f2c635187711d7bd9599010f2c575.nq.gz
    │   ├── 82891ea148c6774b98cfbe3d771d997a77537d16.nq.gz
    │   ├── 86328767fe6b253bdbf99343049cc57f1c3a1fbb.nq.gz
    │   ├── 916c53737d97b605385f9b5235a3a890f864c6bb.nq.gz
    │   ├── 92d37671c52d89b37d1546677ad4f48b9bdaab42.nq.gz
    │   ├── 957cf45fa14d5fe5cdaab87ea7e5bca8395725cd.nq.gz
    │   ├── 9bb47fba300a4c096e049e51b636b3c282eb11f7.nq.gz
    │   ├── abe0ffa311bf39ca2bbfc8791856753b7cabe843.nq.gz
    │   ├── b149430114b42299be84b5c1dfe25a8303605db5.nq.gz
    │   ├── b886eb52cf955c2f29ad31b514607d4e38c1dbaf.nq.gz
    │   ├── bcdeee2df510cea17ad4524cf53b9900a46d5042.nq.gz
    │   ├── bef6f208d16b96638cbfafff5ef516e278608e81.nq.gz
    │   ├── bf596dc0239aad85198ebfe70921fd79a1cdedc9.nq.gz
    │   ├── ca782dbc589bb69842f5b214d98d1b4cddd04ce9.nq.gz
    │   ├── cb59086305367d9fcd7d63b53cfca1a3e4ef77d7.nq.gz
    │   ├── cbc3163496621122fed1c86f806d6e09f333566e.nq.gz
    │   ├── ce2bcaef6889f06563c5b186e9f727f8b1b1b9d0.nq.gz
    │   ├── cf709f302120c0de62978036916778c29fed7d98.nq.gz
    │   ├── db2eb658ca8a257869621ab930ab3bf1dce830d9.nq.gz
    │   ├── dbac741a49a5a64336b70c06e85c2e2706e36336.nq.gz
    │   ├── dc31ea34b858f94b79690573db3f2fd632074a94.nq.gz
    │   ├── dc538f6e810bd462c98ee7e6aae24c64d4b1da93.nq.gz
    │   ├── e0afda444f776ddec94ebdae8e1ed7501e26fb22.nq.gz
    │   ├── e9c9f95ade0f20a048861ac886d4767a839d5286.nq.gz
    │   ├── ea3d60565242c47be97088ead2708d7b88390858.nq.gz
    │   ├── f15bba7309f2e0a17f7b7a5552b9618f074078c8.nq.gz
    │   ├── f1c46f51e5a99413addf4b6eaebf2714fe841669.nq.gz
    │   ├── f7be983a7718d4b6a74bd5d6ba7a6073ae3bfa6a.nq.gz
    │   ├── f7e73e2da07cb625859824794346c1b74a98c3b5.nq.gz
    │   ├── fd27f1f4e19710d683f78b0683d45c5d8c590eae.nq.gz
    │   └── ff23423d34d9d7f829d160aeb91b5c939ab4a4e1.nq.gz
    └── repolex
        ├── 0437c513f2dbc8d1dfc5a3e35fe35182bd3a671e.nq.gz
        ├── 04bc62787be974874bc1467b23606c36bc9779ba.nq.gz
        ├── 08939683c7a2e5d7dc928d310ebab65878bffff3.nq.gz
        ├── 0ac1ba527e75e700698bcb4dad5905cea80e29f5.nq.gz
        ├── 0ce39a4cf6424f30f6c243a20f2a1b1e46d909d2.nq.gz
        ├── 0dc5836d5e6f41760d736d98d0cfa5b57bac84a7.nq.gz
        ├── 112dbb2ab40a6ecdd7ed0de4503dfc56655a24a3.nq.gz
        ├── 125533116008cd7e3a81b339a15f4a2059ae12ae.nq.gz
        ├── 147c2507c3bdcd22c7c0176e57c9d585d0aa2642.nq.gz
        ├── 14ceb8c046c6bbe07ede056c99be55e5a2e914e1.nq.gz
        ├── 15590d75b26f1e4b95b565f8306c763ee860d3e2.nq.gz
        ├── 21df421ebc7a5249bb31101da666bbf22adc3f18.nq.gz
        ├── 273a51a335694abd977e36a9b052bbd48190de78.nq.gz
        ├── 2a105df9f2bae5d2b0e5af64fc0367a159fe42f2.nq.gz
        ├── 2f6dfbc165337b0f998a281f7f7ac86674b8bf59.nq.gz
        ├── 311e83e591a149a7549bab543dfd126d3223f7fd.nq.gz
        ├── 3ab30210a26368812c2f08af7f737f3c9b740985.nq.gz
        ├── 3b49821e82bef2a94a3bda0fbb2fd4bc0d732842.nq.gz
        ├── 3d188fe13e1901222cd830dcdc9772a34b9bd745.nq.gz
        ├── 4405b849a9ea62dfa76f32031e187c844f8e217d.nq.gz
        ├── 45ef08cf99099bddaf995544c93272cd3b8c2355.nq.gz
        ├── 53589b4f37de415b10e368301d8279e513021d88.nq.gz
        ├── 5c04f85f93df5ca1dea84683509d4954a4b4204c.nq.gz
        ├── 621d074bd87dd7a7064c5607dbed05b97f80fcc0.nq.gz
        ├── 63ab25579bda70b4927a179b580a9c580b6c7ada.nq.gz
        ├── 6a6cce03b7f071bcd9027e5068b988770f4e1133.nq.gz
        ├── 6d39d0f8a809eed1b75e0d5bd4d2dad3d2190f25.nq.gz
        ├── 6da4a942caf956bd90df100283a716680c889eea.nq.gz
        ├── 73c5533e665743d305e266eee134c48d88d2dcfd.nq.gz
        ├── 776ee26bc3644c39f1db7de779e1744f8a24068f.nq.gz
        ├── 798d255ba63e9e35cbdeff95a008a982d10f07d3.nq.gz
        ├── 7cdbca0dc95f2c635187711d7bd9599010f2c575.nq.gz
        ├── 82891ea148c6774b98cfbe3d771d997a77537d16.nq.gz
        ├── 86328767fe6b253bdbf99343049cc57f1c3a1fbb.nq.gz
        ├── 916c53737d97b605385f9b5235a3a890f864c6bb.nq.gz
        ├── 92d37671c52d89b37d1546677ad4f48b9bdaab42.nq.gz
        ├── 957cf45fa14d5fe5cdaab87ea7e5bca8395725cd.nq.gz
        ├── 9bb47fba300a4c096e049e51b636b3c282eb11f7.nq.gz
        ├── abe0ffa311bf39ca2bbfc8791856753b7cabe843.nq.gz
        ├── b149430114b42299be84b5c1dfe25a8303605db5.nq.gz
        ├── b886eb52cf955c2f29ad31b514607d4e38c1dbaf.nq.gz
        ├── bcdeee2df510cea17ad4524cf53b9900a46d5042.nq.gz
        ├── bef6f208d16b96638cbfafff5ef516e278608e81.nq.gz
        ├── bf596dc0239aad85198ebfe70921fd79a1cdedc9.nq.gz
        ├── ca782dbc589bb69842f5b214d98d1b4cddd04ce9.nq.gz
        ├── cb59086305367d9fcd7d63b53cfca1a3e4ef77d7.nq.gz
        ├── cbc3163496621122fed1c86f806d6e09f333566e.nq.gz
        ├── ce2bcaef6889f06563c5b186e9f727f8b1b1b9d0.nq.gz
        ├── cf709f302120c0de62978036916778c29fed7d98.nq.gz
        ├── db2eb658ca8a257869621ab930ab3bf1dce830d9.nq.gz
        ├── dbac741a49a5a64336b70c06e85c2e2706e36336.nq.gz
        ├── dc31ea34b858f94b79690573db3f2fd632074a94.nq.gz
        ├── dc538f6e810bd462c98ee7e6aae24c64d4b1da93.nq.gz
        ├── e0afda444f776ddec94ebdae8e1ed7501e26fb22.nq.gz
        ├── e9c9f95ade0f20a048861ac886d4767a839d5286.nq.gz
        └── ea3d60565242c47be97088ead2708d7b88390858.nq.gz

6 directories, 200 files
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
*Parsed on 2026-04-01 by [repolex](https://repolex.ai)*
