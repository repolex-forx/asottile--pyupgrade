# Repolex Knowledge Graph of asottile/pyupgrade

RDF knowledge graph data for [asottile/pyupgrade](https://github.com/asottile/pyupgrade), parsed by [repolex](https://repolex.ai).

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
rlex download asottile/pyupgrade
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9c750258a396dfd86f21f1510dddad2a21191675
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9c750258a396dfd86f21f1510dddad2a21191675
│           └── chunk-001.nq.gz
├── blob
│   ├── 0010cf3b39cacb2b0b2a1207cee667f36aad59a7.nq.gz
│   ├── 01fd88778c0fa49ff9da52161417210cc506b429.nq.gz
│   ├── 041ad736db72e97cf2fb8feb87bec6c3fee49500.nq.gz
│   ├── 07bc2288a98044531f6405d2afaf34057e1485e7.nq.gz
│   ├── 0971a515481f1eec9847c261e7f08611bdaec3d4.nq.gz
│   ├── 0b3b21fa5f1a46aeadc2ae879347776594c2fe7e.nq.gz
│   ├── 13c7aee9bac3ca0ec7d07f74e0c513bcfb870b79.nq.gz
│   ├── 142ab024034c34d1bc08e856bd14bc2b679e119a.nq.gz
│   ├── 1577dc8f19e9102466d3fb8db4b6fc2b2c381607.nq.gz
│   ├── 1b9b8b38a23e343cd1e1e13b707b0c612ae90dba.nq.gz
│   ├── 1d6bb0a94387f3c4865ee6e21ee90febb163b7e6.nq.gz
│   ├── 1e8b27e7374ea552bd3df0067c57687953a3dd14.nq.gz
│   ├── 215ab815c736e067fbec56e419d0e1e01467d171.nq.gz
│   ├── 241d5cbd06da8038eb404e068c6580a3068a01f6.nq.gz
│   ├── 244e117b293b4ba5820216f1f2fa7eca2d598315.nq.gz
│   ├── 263929bde82dc253d293169096016e85e9ab0a3f.nq.gz
│   ├── 2663c543ac1b06f7d6be2f22a39b2a62af550fdd.nq.gz
│   ├── 2698f6cff906cf7c83101145a12d51bd28f2be24.nq.gz
│   ├── 27d3ed3ba4d9e395bdd50034c96405a9487ac9c5.nq.gz
│   ├── 28c7ac75ab48e2a676cfe1aafb19f635dfda3e6b.nq.gz
│   ├── 2a71dfc8db4f08cd5799d0ff6a33680c49e24042.nq.gz
│   ├── 31421859f7a3dca76b8f9bd64efc84cd55bf6b15.nq.gz
│   ├── 31853450d6b260dd7093edf7a452963817abee6b.nq.gz
│   ├── 32de858cd903a24008522aeb99de3c720e49dbdf.nq.gz
│   ├── 335e1d4d463801dbbf07730fd733d2c8185470cc.nq.gz
│   ├── 37c9e6b1f6485c0720b92f63a951a9a378be38ee.nq.gz
│   ├── 38b7e69f030d43a6f2a4a08ba6bd66a84a47eebc.nq.gz
│   ├── 38b976bee0c886c04ca18606ee89451a8eea1b89.nq.gz
│   ├── 39f2a08a5282bf284f85982dd259107c896ddfaa.nq.gz
│   ├── 3c5fe39b6e8d00a9a900061a0ed83125de532590.nq.gz
│   ├── 3d93aefb2da505dba9c0114404cfaaeee5ad0d3f.nq.gz
│   ├── 3e07103ebb5b7ec0868cb15613d8f33c77f6f86c.nq.gz
│   ├── 4018ebbb8277b670de257d438ac2cc82d6ddcc4c.nq.gz
│   ├── 4543b9d6c77f5f005ed7d50087e14419fc316740.nq.gz
│   ├── 4e06dd36228df49977a8f68ca827daa67eaf05a7.nq.gz
│   ├── 4f3f56bf88ee9023ec84b153321d6e0817dae7c9.nq.gz
│   ├── 513ba2c245d06d259521fc4dbb5b1eb14f88788d.nq.gz
│   ├── 51e9179c33684e3a4fd70b830186f461d79643bf.nq.gz
│   ├── 522fbe20b89911bb8d68b4a684a51225dd571764.nq.gz
│   ├── 5411b95f3029254568a6033b9b04a448753fd525.nq.gz
│   ├── 546a3deecd82cde9b75a3d9f47698f60d5970f4b.nq.gz
│   ├── 5c38fa4e14f2e766cef8c3ef1d24e9867b1375c2.nq.gz
│   ├── 5caa2c77e1e4fe86a4dbc0a034ac9acacc0b1f94.nq.gz
│   ├── 5eeca59d66a98d56a4954eb8a7f216e520f30a48.nq.gz
│   ├── 6067e98a17ddf974945b5ca04cd435b34c7a5407.nq.gz
│   ├── 62ba198d07a0cb226debeb87199f2369fc13f8ee.nq.gz
│   ├── 6535a5a7375b3fe5a9f07aea4a516056c30b25a7.nq.gz
│   ├── 653c8f4096f185c2fc1e1a525a2b316a0cbd0fbd.nq.gz
│   ├── 6569b5ea0300442433a5382b9f9bde7677db1239.nq.gz
│   ├── 67c0a2c0c53364ec445de1d7d1044af50b813fe2.nq.gz
│   ├── 698640a1fa721d7860e3f26a1e6de83555743c6d.nq.gz
│   ├── 6eff553977f3e9232960c71dea6cae6ef0bba036.nq.gz
│   ├── 6fb1277bb7ef5b213637a160a7bc8cd828dc3b69.nq.gz
│   ├── 70992a618d887aeb3e27f225d6c0de725e280606.nq.gz
│   ├── 73fdafc487b9d5c430fdcf3cb9d8682700949af2.nq.gz
│   ├── 77dbd7e33502ef5992216ca6a05a48d264e73b37.nq.gz
│   ├── 7855e97072393491b94a35da6c82553b1c869fdd.nq.gz
│   ├── 789fca6fcc53f8c9ef7494e086a7a1965fed336c.nq.gz
│   ├── 7bddce841dc7a6650514c26575e4492d2045bc37.nq.gz
│   ├── 7dee8da29b2dd756e1c8d16fabc8fd3b9f8dc484.nq.gz
│   ├── 837e593d1c127b8e5213e5e17215ce0349c36518.nq.gz
│   ├── 83dcd09252a90a0661d553dd00a118541baad6bf.nq.gz
│   ├── 880a01bed7b7659e9a3f23c696706ea06a4f8ebe.nq.gz
│   ├── 882588aad657f7572a9e0e545ad80bc6eb144757.nq.gz
│   ├── 8a6fe8655ecdc46ba2734d6aff5fc7efeec1a69b.nq.gz
│   ├── 8c5115339295add727f178e665d9fc0b37f0a4e7.nq.gz
│   ├── 8d7f61784e7c340c9e4c5d8885d9903b1258ae09.nq.gz
│   ├── 8e19197d57e45c9334c1200a913e5ca838cea36e.nq.gz
│   ├── 90d0e390aded8e4fdb072cfc7cf96b06048af349.nq.gz
│   ├── 92b7c92599d393c67015ec51ec20d3646729aec5.nq.gz
│   ├── 93ca79b2cf12d5f6483b3c3513e62a9dd466e58d.nq.gz
│   ├── 9569d3c263dc6d4704a4bbe2cdc451dff45c1710.nq.gz
│   ├── 97f00f2efe9ec13c623496da85f0f8b36f2eeb69.nq.gz
│   ├── 99bb5f4a5ad97c944940ec1343997814be7b93ec.nq.gz
│   ├── 9afe95522ca7a15c479e61571bb753d34ce8c649.nq.gz
│   ├── 9b4039f25148b1e9a76da5ffee30248fb7669bcf.nq.gz
│   ├── 9b40f8ef3f6ce8427d9bddfdfd787dac870e411b.nq.gz
│   ├── 9c0f5cbb7ea156291e3ec466b3b5f93bbb582459.nq.gz
│   ├── 9c2c65f0cabe8da0ff2bbbd901234fed9e12b027.nq.gz
│   ├── 9e52e506f450382a71575f2c686d29b121fa50e0.nq.gz
│   ├── a08e043fcf03200c891a5683650c6e3bf81abdd0.nq.gz
│   ├── a4534c7d9b9646c3aff1b206ca23632c28fd8be8.nq.gz
│   ├── a484e956db33615490f7fc512323bddece1b410c.nq.gz
│   ├── a4bcb10be39a14a1364ef511c85d7ac13d76a2f1.nq.gz
│   ├── a60cdcc22fdbfd133db90e6a2971188f08a62364.nq.gz
│   ├── a69b3d34287d60f1fcddd895e8fb4529b5018694.nq.gz
│   ├── ac4d8339d9c100238bf3a9d03d5da3ab1d9dc5d6.nq.gz
│   ├── af4ae47529518f24acd66eee50999c3e0b55f167.nq.gz
│   ├── b1447c3015af9511f2dee402ca4b5ad62adf5dce.nq.gz
│   ├── b18f1e7e66e2ad6bcb0b6d886ab98cbd1d1c170f.nq.gz
│   ├── b2d4731131433fe953f3a85fbea224bd2c7a8a3f.nq.gz
│   ├── b32a3146815565ee39bf9b9f2fd1aadbbeee35f2.nq.gz
│   ├── b3ec51ddbb2cfc2e94455e71533464e31880f05b.nq.gz
│   ├── b40f8ff0c2b08ce07c1b2ba8e0ca5ebefd4c2e4d.nq.gz
│   ├── b5ecd60c86f02b74c72801c1e8eaf85ebf87d98f.nq.gz
│   ├── bdffba295f1a5e2096de044631f61c7968f3ca9f.nq.gz
│   ├── be6375ffa41ca48f38faf1d7312a6f4ef7602b49.nq.gz
│   ├── bf595db3e66ac0d11a7da0b672bf87081140fb77.nq.gz
│   ├── bfae7024bfd7268d519b37c89400cfe8a3c85254.nq.gz
│   ├── c6bf3ec17aef83984e736332ab73b5eab4575ecf.nq.gz
│   ├── c8a5a494a914899039136341cb95d4d1d4de12c3.nq.gz
│   ├── c976ddc4377554bb097e1b0201ba455bace0e32b.nq.gz
│   ├── ca1d90ea180858ae143c0e62d920e350d3acc62d.nq.gz
│   ├── cbdf6897270ee484a496aebb2f2b18c3c77410b3.nq.gz
│   ├── cec153f05d4f371ee4a8147eaa302f67910effe3.nq.gz
│   ├── cf21417fd1d3e9de0933745f06fea60cb2e7b31d.nq.gz
│   ├── cf4350e288bcb286188c09ebb3414224a82935fd.nq.gz
│   ├── d034012d69b736998cb0960ca69b1281b9b41437.nq.gz
│   ├── d52ae2d36a0bc40a60b9f287b979843768134677.nq.gz
│   ├── d63909ad9420c3285be29f5a914d4e8ff723b887.nq.gz
│   ├── d846d7d4705ed8a6d25670af3b90a606b7b0e8ec.nq.gz
│   ├── d8d259b7a0b329a218fe1190323cbe2b4ffe2936.nq.gz
│   ├── d93596501cdd607e2a28becdd6b6f2bc8a2b034f.nq.gz
│   ├── dcf36a5967c2dcd8580b8d428971f64cb7b46685.nq.gz
│   ├── e3835f6516bffb9ce7f3eeb3ca6e9a82654124c2.nq.gz
│   ├── e6680f848ce9ca42802c36d9034c56185cad0d06.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ee393f0504ff6d134ff272636a618032de644d.nq.gz
│   ├── ee1907ded6762a87db5a805c598f9f01655bd881.nq.gz
│   ├── eff5bf31823697fa97a998ee5366f9583ad6cccf.nq.gz
│   ├── f24164d3e82707bc36c9fb0727041cbc7639c506.nq.gz
│   ├── f2bc3c38c7ea3f56c6ed7b8a4d39880d8f511bec.nq.gz
│   ├── fa85d7a200d1b6794dfda78b2eac244df280517b.nq.gz
│   ├── fb2bbb9e3f2e51cc2933607dec126025d8661e3c.nq.gz
│   └── fc61080d600c9a4a61db057df6006b8b11d8ba30.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9c750258a396dfd86f21f1510dddad2a21191675.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 133 files
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

[asottile/pyupgrade](https://github.com/asottile/pyupgrade)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
