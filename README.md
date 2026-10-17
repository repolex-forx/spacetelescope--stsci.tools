# Repolex Knowledge Graph of spacetelescope/stsci.tools

RDF knowledge graph data for [spacetelescope/stsci.tools](https://github.com/spacetelescope/stsci.tools), parsed by [repolex](https://repolex.ai).

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
rlex download spacetelescope/stsci.tools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fc95b645196345f4a8a29ac11b5269f475f69a63
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fc95b645196345f4a8a29ac11b5269f475f69a63
│           └── chunk-001.nq.gz
├── blob
│   ├── 008bb1b0d8bdf96c5b166de78e9f790ca97911b9.nq.gz
│   ├── 07739395eff098651d64758fefde6f918a7d86e1.nq.gz
│   ├── 082e75ed4f9a8e60d190ca653dc61bc9b1232d1b.nq.gz
│   ├── 08e93a808fceef18046cb77ae11f24790f4aa69a.nq.gz
│   ├── 0a35ce8c4d877f6afae9bdc6b11296d9ffdb1bb6.nq.gz
│   ├── 0c4e3b2ce380d73e74220abbf962542c93eda73e.nq.gz
│   ├── 0d1c68cfe2a1ea299f1f9fe12b90050b581406d2.nq.gz
│   ├── 1272ae5f801cd428c60ee5104c90ac32d67881ce.nq.gz
│   ├── 14e67b3ad23f1a27788d57bc05924986ebeee447.nq.gz
│   ├── 159ec36091871b61d3bcb0449348909ecb7a7f47.nq.gz
│   ├── 17fbecb1115f8894bd510f100fcdb5255ae3c682.nq.gz
│   ├── 1895ba534cddcef86d2f24624ab594f6cf828fa9.nq.gz
│   ├── 1a76efad3d0d592dab710c01e166fe3ab97abed4.nq.gz
│   ├── 1ef30f33c243700ff5440bd2f24ebf2c79b5b447.nq.gz
│   ├── 1f3c9f6377f96384e9b1d2310b492835a2890d91.nq.gz
│   ├── 24872894cc02fb15759d270e4b3fecebe8e039a7.nq.gz
│   ├── 29a9324a78a86412835889ca6460475a331e32af.nq.gz
│   ├── 2d1bc4113711e44c907962b09472c63403cd185f.nq.gz
│   ├── 2eeb3b944979d62d1ce7a586ac5fd00cb595319e.nq.gz
│   ├── 30a3b38e3e1a6089ae9fad6cbe80f382296c5c64.nq.gz
│   ├── 31fed302bc8a8f855e09f78b4142f8832cccc716.nq.gz
│   ├── 320cbb43ecb2a7351f7abd3e34da7d6e5a3218c4.nq.gz
│   ├── 325828bf56148cc15dfd9bace36c0aa1a2c1de75.nq.gz
│   ├── 35beae81cde26b13c442cc70c1ba51b285abd0e4.nq.gz
│   ├── 38baf40412006ad5b449da3ac579ed82b55a6408.nq.gz
│   ├── 39c9f58e0fba6f860c17eac42d236f00e872aa1a.nq.gz
│   ├── 3b89155ad4caedff269b44e4527ccd3315b64963.nq.gz
│   ├── 3be265dd7958ff14108e9d214d4d7ec1283a705b.nq.gz
│   ├── 3c85599cad86bc7920493091f2fc9217ef0b518e.nq.gz
│   ├── 3fd526e59044e318b65abe6644ea8565fe5f8fb9.nq.gz
│   ├── 4183757f7ae774768d6d22d2d62fb16569e27c6d.nq.gz
│   ├── 41b71bebbc6cb3c7b07c27d7e15d7ed75bdf0a08.nq.gz
│   ├── 47dd39e1c68046587adb654477c49e4fa56c5955.nq.gz
│   ├── 4bce00566e80ad9665933bf812629998c5429b29.nq.gz
│   ├── 5034a5c170cc6a26f328e99fb0cb58f05f40dd54.nq.gz
│   ├── 53df59f86ebf66f83583da36cc4ea8b04a9bd7c7.nq.gz
│   ├── 582f792fd9e7b4ee6933426cc82d4270ae5c2653.nq.gz
│   ├── 595a28f50c07260d9b7751b316726e1936bbdf83.nq.gz
│   ├── 5a4d64fb2aa28607af4c1f06aa784b7847b7d6ea.nq.gz
│   ├── 68eb8f790414517aa9dbe14f46c0bbc185223feb.nq.gz
│   ├── 6fc00c68c232b91a88cc5a02228db7bd1c0d5c61.nq.gz
│   ├── 718ced174b61e46e4661164f724c1b5eec036634.nq.gz
│   ├── 73dba4b7a59f3f3d8c3412d9f3d0d260aac5ed8c.nq.gz
│   ├── 76721b26f2c1836c31b97ef750ee9f42281ada43.nq.gz
│   ├── 769790f436015c26797736243ba795bdde990c44.nq.gz
│   ├── 7eb8bef682dce857bc28b6821f6a1ffb3414b5cc.nq.gz
│   ├── 81196812603b2886e71672bc45cb82a01303550d.nq.gz
│   ├── 871c56c3164cf7305e34fe43233afe519fcf634a.nq.gz
│   ├── 881f8682826323a1668b989c39f8f6487e95294d.nq.gz
│   ├── 8912ca0eab38963acee9b59fed6671df7e858499.nq.gz
│   ├── 89c7da55ed72d67399a733f250a5720966f8a17b.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8be410228932dbd4b071631b3ff675547ab1d0af.nq.gz
│   ├── 8df30effa82def4b0c3a0d6ec990618c6b947bfc.nq.gz
│   ├── 8df7717cedbb81b965d6b960f26f14b873c2d942.nq.gz
│   ├── 90a042d49c0366e1c28fff99d6650001eb6ebe13.nq.gz
│   ├── 90e3b588252dd88345cb817241d93274ac4d4ad0.nq.gz
│   ├── 911212adc0359aa33efb0650961b17e3d0254109.nq.gz
│   ├── 943e8785b134f2587a72b3c8e2ec17e5ea1b3440.nq.gz
│   ├── 94a58825c67557e24c3d88e23a282c87caa8d17f.nq.gz
│   ├── 9535205f3215da38ee5c0ed4c98c2faa3a8c3708.nq.gz
│   ├── 9719fddd42a120114e8dab7ef0b1c69b03ddba1c.nq.gz
│   ├── 97c988c1804d3c7671efb9ce4b34a04651e008b7.nq.gz
│   ├── 983dbf9f4d83fd078bc2d4fa35292784d2629b46.nq.gz
│   ├── 9a1a6fa7c5ff0209575ca0a4edc33c5febeab17c.nq.gz
│   ├── 9c11fd2a53cc433981d88355a01eac3516574019.nq.gz
│   ├── a0ce5f4c13027c3484aa46053fb4ebad948e9d10.nq.gz
│   ├── a81eb0d436b0bf673aa4dbd179cf613ff3385750.nq.gz
│   ├── a951036c25a3919ecfffc8684cff70ed5e4c59af.nq.gz
│   ├── a9e044391aaa53c873c30cec6173f87245bd8f0b.nq.gz
│   ├── abd8fc4c348805045f2f097b6a8e563987fe1a14.nq.gz
│   ├── ac6e4fdc3187adcf094002ede08407975fd41acf.nq.gz
│   ├── b1ab0de28440188df111c60b5d9b79e4143d217c.nq.gz
│   ├── b572f6912771d6f58f783e9bf9869f84acd9c3a2.nq.gz
│   ├── bcfc91ba6a72c339524e3d89a8f38b4cf35b78eb.nq.gz
│   ├── be9a3b9560af03af7ad56c578623e3f65116d5c9.nq.gz
│   ├── c0da848f8187c11a32ec376199d034a5f2e0783f.nq.gz
│   ├── c153449eb0dd4d802697fd084c7cae8670630c2f.nq.gz
│   ├── c419a6a95fc6f7f2b2f981ddea5143acd90095f8.nq.gz
│   ├── c7f84329e13c7d9dc56d66303a1a8bde292084c8.nq.gz
│   ├── c9f0d19b591a97e452d8c05a72f9484da947cb42.nq.gz
│   ├── ce56019caa35433ec28d7b89e940a5bc3a172658.nq.gz
│   ├── d0b0c90153cea2f9d9a9e05f95338cc2b290562d.nq.gz
│   ├── d0bf46e9ca4012e2aed6c708237276ced91dae9c.nq.gz
│   ├── d8d0483081a32e910acbfbc26dd013099d07810b.nq.gz
│   ├── d8ef88d0210d3f676d15c300a60fdb561baa3de3.nq.gz
│   ├── db44b5e2610e335a38bf1c1573df2cd0278a7ae5.nq.gz
│   ├── de8844adac49272ed8ef100de78678a6b61f0c60.nq.gz
│   ├── e019491ae82876423309e057fca6962aaeb0a072.nq.gz
│   ├── e574fd07a58dc3f3d13ac5e84387bd06dd1b462a.nq.gz
│   ├── e5cc25d4c2e09ea1d9a3b8ca95469de3e05609fe.nq.gz
│   ├── e86b95612d1866fe4feed54e9218fada76279db5.nq.gz
│   ├── e8ef1169507759f8b0d21573e4b02dec191dd2a8.nq.gz
│   ├── e9b7a4d3ec4f71f434bf2566d6a48a840ef8b362.nq.gz
│   ├── ea5c5ad3d13775f34b72215eaf195c020ed52cbc.nq.gz
│   ├── ebc571e85f9bf36a70e0afa2ef360a42f2071d12.nq.gz
│   ├── ebfc6acccab0d10ba8aed9bbd07cb38b0305c113.nq.gz
│   ├── f655bf1fd714500b8fac58515fdd12d217b0cce8.nq.gz
│   ├── f691bb32b5b1691d6eb8ffc5bdd070df0ef61ba5.nq.gz
│   ├── f7051cc1a7e3d3401706b3e7c82d6d1ccb91175e.nq.gz
│   ├── f711ee728392cb3d88e2c3cfc4efc288ca737207.nq.gz
│   ├── f9ddc88dd96041ebbb6b6efc87b8bf385c612dd2.nq.gz
│   └── fb5684d91dc61f2bc47c1bf1739b69d1f86c4765.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fc95b645196345f4a8a29ac11b5269f475f69a63.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 111 files
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

[spacetelescope/stsci.tools](https://github.com/spacetelescope/stsci.tools)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
