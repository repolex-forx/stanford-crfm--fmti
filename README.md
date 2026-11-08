# Repolex Knowledge Graph of stanford-crfm/fmti

RDF knowledge graph data for [stanford-crfm/fmti](https://github.com/stanford-crfm/fmti), parsed by [repolex](https://repolex.ai).

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
rlex download stanford-crfm/fmti
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f4500c5f4763966fddf71c468a148533a1236290
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f4500c5f4763966fddf71c468a148533a1236290
│           └── chunk-001.nq.gz
├── blob
│   ├── 01401783704dc633cefcfdbce2977b4d8bf545f9.nq.gz
│   ├── 057c590df86e30776d1f6b8c78e9cdb3dd63b91f.nq.gz
│   ├── 0645c4d099afb1df06569be7fe96763bbed35b5a.nq.gz
│   ├── 0673c479c30aec2d5c57baf0b04954eee2812f04.nq.gz
│   ├── 071f4d2274ac2a90a33c8e047a715d46da874b53.nq.gz
│   ├── 0dedf0c11dbf26c5c818e13a4c1ad365b1361fe6.nq.gz
│   ├── 0ffa7588e8890579cfc61bd85012621563b20025.nq.gz
│   ├── 1718f197d93e5def8b84f44ec3a2af4c533e4744.nq.gz
│   ├── 1727696e83ef0cb98a0ae8fb95064249d9f87ec9.nq.gz
│   ├── 1fe20dd75511e0955a92c30364bcb9afbedb4167.nq.gz
│   ├── 20c9029da033b5f08ac6c1ef70447ea6c84ca83b.nq.gz
│   ├── 27aad106fc7c46f5b54dc927f09fa465161c638e.nq.gz
│   ├── 2846a4d6073ad82e1be1e8ec6e25e454b0aa157b.nq.gz
│   ├── 3395148f313bfa6aa1d19be7419496126a6be416.nq.gz
│   ├── 36c2fe9edc4b88da1e53a90c635fe1da2f1bded4.nq.gz
│   ├── 3b8da28d32a762e56bb47217c3d8d5f09abc1c58.nq.gz
│   ├── 3d08154ced10c1e7d9a5a1485130ef387d8ad7c4.nq.gz
│   ├── 3da2bd8a0070e1d9d4bc6c3aeb5ac32110bceb3e.nq.gz
│   ├── 42b2435e984545217e52f866d2fb3380448f8271.nq.gz
│   ├── 4ee5db266dd8322583c3a4db02aa53e9507517c8.nq.gz
│   ├── 5809972d7dc2cf1f503b43a5f74168e2821f5639.nq.gz
│   ├── 5c080b6648a2ebd706534cf7db3b4e83419938de.nq.gz
│   ├── 5d4d45e41b7d2e206e492570e050262f16727d7d.nq.gz
│   ├── 6189b7b701f11d81c247cab6f22959c5d430b996.nq.gz
│   ├── 68bc17f9ff2104a9d7b6777058bb4c343ca72609.nq.gz
│   ├── 6bc63fd80a3bf0247c64b579757e0a8525ce59ae.nq.gz
│   ├── 724c40cd40ca53b3d83fbfe14ca6f40dc1c04f27.nq.gz
│   ├── 7a386ee5b6a1c6c0cc07eef586bebd0cdd5cb468.nq.gz
│   ├── 7a41352c385a89d2f4f1def824c3c64e14c518bd.nq.gz
│   ├── 816070594b00eca1670bfb39e008aca58de150c2.nq.gz
│   ├── 816eea76e7b197a73ef2be9164f346c9da669332.nq.gz
│   ├── 8cf2cc1d7b04b9abc30a066173de63d23b437e8a.nq.gz
│   ├── 8f08c2545cbee197edf978baf1cdaa0d36cab484.nq.gz
│   ├── 90e8451b3825bcf6a2662796a14439cea392f5f6.nq.gz
│   ├── 974259f1ce08fab33051a0ee4f14bcaae23731e9.nq.gz
│   ├── 9f7e96cffe905d2e3a1dd32be06a5cd904fbb7fa.nq.gz
│   ├── a6d3f35213e038c80a3b94ed8a761d517529085f.nq.gz
│   ├── a7ef675da26e5bd50c6ee9d8959c29fbb65dbdbc.nq.gz
│   ├── afba60fbce689298b2828f02259671bf50bf4de9.nq.gz
│   ├── b250a7f5521795f83fb205ae81be274fb9287e4a.nq.gz
│   ├── b5e6190ca32871e955523871dc9b8879ad0b81d9.nq.gz
│   ├── b86d93559966015649877fd7e0da9cb30c622e2a.nq.gz
│   ├── b8f1998adb50a96fc2e38f70767146cdca0e46b8.nq.gz
│   ├── bc057eb8ee006e3638597fae0818adeca8492851.nq.gz
│   ├── c5032d53d48e7dfa68350c3b5fe5d8e01eef03b7.nq.gz
│   ├── cce6b2f7fbbd8be8502249271d99274db8fc24fe.nq.gz
│   ├── cd74f4224e382152f1264c9af61b8897ff92adac.nq.gz
│   ├── d4a4d91716aff21e3b1e25f7344d486f93cab536.nq.gz
│   ├── d66a1af6d81699b190a68f5d74035487abb0296d.nq.gz
│   ├── da5187816048ee58e45486ad3b17c02c6af32f34.nq.gz
│   ├── dc51f76c48802b9645d106cdbaa1c325568622d7.nq.gz
│   ├── debd7e0730a0d8fce24a96e7f93bf32bf317c91e.nq.gz
│   ├── e04a6d75b509e6ed2093981ceaecd0bac14f4438.nq.gz
│   ├── e054e87adcbf28c92fb816521e6fd930a67fe27a.nq.gz
│   ├── e46c8a6fd954d5e3bcfac428b3e6b6687d7b105f.nq.gz
│   ├── e73ebf46e4a1dcd336a51a425a9e1ae425f5911d.nq.gz
│   ├── e8aaa0c74de328bf9c43a52308a8a4c6f493ff83.nq.gz
│   ├── ea46fe20cb3fce8fc7f19f8e4b4142115838036d.nq.gz
│   ├── ec489ebbe7516e3e6dcdbf3bb87ae354aaba36a5.nq.gz
│   ├── f0597a073503229ef41e2502dd1c1afaca01f67f.nq.gz
│   ├── f688175943d5dcd1e89befc10af75bbb4ea64b8d.nq.gz
│   ├── f6fb8c65afd33a857fa62edb55f19fe0f6cb92a4.nq.gz
│   ├── f784c488aa8132d796cafc490b4b5d1f05ace3e0.nq.gz
│   └── fd3103de423cbf78abffda43a9104f532d4f3177.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f4500c5f4763966fddf71c468a148533a1236290.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[stanford-crfm/fmti](https://github.com/stanford-crfm/fmti)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
