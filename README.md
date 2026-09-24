# Repolex Knowledge Graph of samuelcolvin/watchfiles

RDF knowledge graph data for [samuelcolvin/watchfiles](https://github.com/samuelcolvin/watchfiles), parsed by [repolex](https://repolex.ai).

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
lexq download samuelcolvin/watchfiles
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2b2327f2a007a32d736fffa4ab87d3f207053a49
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2b2327f2a007a32d736fffa4ab87d3f207053a49.nq.gz
│   └── repolex
│       └── 2b2327f2a007a32d736fffa4ab87d3f207053a49
│           └── chunk-001.nq.gz
├── blob
│   ├── 0709371448717e4e5b669f982ef0cd8d78cb9725.nq.gz
│   ├── 099657b5ca8656aed8ebdabc2ae965e31a35280a.nq.gz
│   ├── 0c23a3e3012e669511335e9c0ada46703f1927df.nq.gz
│   ├── 0cb54fdf242ef78972880b7d62dc5c34187d25a2.nq.gz
│   ├── 131d01178c5dfaf354a4dfd10a0a7f0f452ea21f.nq.gz
│   ├── 15742b92e7f1d976a2130609935a0b581d61ec9e.nq.gz
│   ├── 1c0b1419c8b31b2e997464b6c5450b38dca5c5dd.nq.gz
│   ├── 2568d46299756ef59b956328d738a12a8c8ad80b.nq.gz
│   ├── 2b9fb52631e79c72e19b1f7d1a37a0688b6088b3.nq.gz
│   ├── 2e748896556a7da45c816c4f37d15f48b746f5ef.nq.gz
│   ├── 2eb684710c7485bc5c47e6a75de7b1352eced598.nq.gz
│   ├── 39b4830d3f8a975a8811b6967bdc4e34af72537e.nq.gz
│   ├── 415b5ecb9e13204d1c345752ee9db118a14394f0.nq.gz
│   ├── 455963f41782c79a8b56535770d474fc3decb00c.nq.gz
│   ├── 4bcfe98e640c8284511312660fb8709b0afa888e.nq.gz
│   ├── 4d1c803f9bc81b967f7e50d04f9333b89a1ea1dc.nq.gz
│   ├── 518f2768ff8c0d14710e72b45c8e7a8728932a04.nq.gz
│   ├── 53533e8e4cf0a3bbeb6b44ba7c87a42c5e33f1dd.nq.gz
│   ├── 5af1363fb3f86f8f397d693c15f5822263c33822.nq.gz
│   ├── 61780798228d17af2d34fce4cfbdf35556832472.nq.gz
│   ├── 680b8979964c7b7aa7a14c406089931708ecb9c6.nq.gz
│   ├── 6a69f92020f5df77af6e8813ff1232493383b708.nq.gz
│   ├── 6c0c214e9e230a05b763e70ebc46019a4c7b988b.nq.gz
│   ├── 6d82db5c7970fbb8f18cde2be70fc705640ef01c.nq.gz
│   ├── 75306517965a54731b94dca8bace640e856af115.nq.gz
│   ├── 78981922613b2afb6025042ff6bd878ac1994e85.nq.gz
│   ├── 7caf56d07571339f3203e592be04ee4fb1553e4c.nq.gz
│   ├── 7cd6d6f0321bc62f12078af229fb4d0063b9a951.nq.gz
│   ├── 838f318f1519650bcfcbd192bca3515bbf1bad02.nq.gz
│   ├── 877fbd573e66d63349a03b5b829f0d52467137a3.nq.gz
│   ├── 91638198fd13adec48d68c265fa4f115bce60aca.nq.gz
│   ├── 964a7dc421a12f792dd87fb50c5b342e55aa72c9.nq.gz
│   ├── 97316e1c2c01ac747e3986294f6720e30895ffdf.nq.gz
│   ├── a23c98b37f61935ddb970103ed2f3557f8417f70.nq.gz
│   ├── b7512e45b005fbbc9f3636470b2fbfcbd3dd0e2e.nq.gz
│   ├── bdd9b15521a6e7860883f7d5fea2ed29e1c0422e.nq.gz
│   ├── cba6da08456179cdc9cd0e0dc66cce1f43ca42f5.nq.gz
│   ├── d22571a75a09dbeb68c2d5aa5557403cf05e435a.nq.gz
│   ├── d36c94b3d346804a15e68c709cb7175a01eded12.nq.gz
│   ├── d396c2a7cb4a9c69d07b596337b1fffb249c0191.nq.gz
│   ├── d5a912f568a204d1f5c9c75c0c3d8c15d85ff404.nq.gz
│   ├── d905d9da82c97264ab6f4920e20242e088850ce9.nq.gz
│   ├── d97dfe8743706d0f45001a92049cafb2e4f1703c.nq.gz
│   ├── e08cfff88f9897f616ba8e268052a13ccbf1cae8.nq.gz
│   ├── e1cd081ddf6a169e7b02c921fb2bc7fd0b4add1b.nq.gz
│   ├── e43eb1adf743ac9a5d7e59f7bd32b018820b8b54.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed847dc5a39ceef00489d143e1251c57ee525a0c.nq.gz
│   ├── ed9fed0bb09ebccc703a89e8ddd5a0b5dd46351d.nq.gz
│   ├── f1a5f7aa3ac46d6a79523b2cc3704b19953ccf04.nq.gz
│   ├── f1d589ed2b3065fad5ff774ad28f160a5bfcf8ba.nq.gz
│   ├── f1e1ddd57532543967def8d5a8799b8e54d6e233.nq.gz
│   ├── f2ad6c76f0115a6ba5b00456a849810e7ec0af20.nq.gz
│   ├── f450cfdf9b83e36dd37d30cdd79ac8bab46d18dd.nq.gz
│   ├── f55721f14ffbf4bdff2e62c701ddf86a3b044483.nq.gz
│   └── f7ac6ca136e52f26586b97b95270e8d2356dd279.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 2b2327f2a007a32d736fffa4ab87d3f207053a49.nq.gz
├── filetree
│   └── 2b2327f2a007a32d736fffa4ab87d3f207053a49.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 66 files
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

[samuelcolvin/watchfiles](https://github.com/samuelcolvin/watchfiles)

---
*Parsed on 2026-09-24 by [repolex](https://repolex.ai)*
