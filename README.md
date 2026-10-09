# Repolex Knowledge Graph of modelcontextprotocol/example-remote-client

RDF knowledge graph data for [modelcontextprotocol/example-remote-client](https://github.com/modelcontextprotocol/example-remote-client), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/example-remote-client
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f1736b32b5a7fbbe587956e4c7f6a3d2c2b0a32e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f1736b32b5a7fbbe587956e4c7f6a3d2c2b0a32e
│           └── chunk-001.nq.gz
├── blob
│   ├── 099658cf3d29c0c21bc9b61d0a8b02652ddb92a9.nq.gz
│   ├── 1ce9a7d03bf42e3192080bea9eec3b122e1ebfd7.nq.gz
│   ├── 1fe93261bc9a5ae1e1d2a989559c2ec63012ec48.nq.gz
│   ├── 2243cbdf7165a15ec90218dbcbd792aef6d95008.nq.gz
│   ├── 2bec1bef2f22e3c5f2f04f6463d1fff2a2637b46.nq.gz
│   ├── 3485bd0b9aac32a3866260245a536306a0dd6d92.nq.gz
│   ├── 34c98bf9d4e7251ebb80de2c068960c92e701284.nq.gz
│   ├── 37eba512f508e11571c3978a7697f2b543e8f94d.nq.gz
│   ├── 431f31989f1a32e1d8b58e25c04bace68a53c90a.nq.gz
│   ├── 4976b9b04a69038d21bfc6cf198fa8f2d46afa1b.nq.gz
│   ├── 4f035b92191b70f0aae5361f88cc7acb76780ab6.nq.gz
│   ├── 5238bdd2ec19c192b12aed6df57411ac3e519edb.nq.gz
│   ├── 5257aceafe53e156073dc44a743254e126aba8f6.nq.gz
│   ├── 56c356d983f2458b7a4bcd298e3010eed768f479.nq.gz
│   ├── 57982bffbae3a143834b8dd88f4db4b5a9bb3f7d.nq.gz
│   ├── 5a50c521b878d18e4c5f2b9697ba3d7beb350faa.nq.gz
│   ├── 5c2e5d1a1955baeb40b57059f474959433070be1.nq.gz
│   ├── 5c721436687abdf2da0a551f5d500d6a570c7a23.nq.gz
│   ├── 64dbd43ffd73a8e0bb99e9c4b87f94d73a6f349c.nq.gz
│   ├── 66a115e7bb16f139b826d9f9b3cbec8d6540f183.nq.gz
│   ├── 677035ee70f7a9df13fcbfb8fca3e837f90c4a05.nq.gz
│   ├── 6b3012e7c448d1a4aa404b5cdbf6ce64372f3442.nq.gz
│   ├── 6d210a11bdcfec848214d4a90d444086df319ec8.nq.gz
│   ├── 73126d2c7db40aef9f60cb1278c1450f633ddb40.nq.gz
│   ├── 77fef03058264fabb209d1b447fbb421762a339a.nq.gz
│   ├── 789fc339a1376657204d8bc35eedb12a971beb1d.nq.gz
│   ├── 843f285848c099446039209c0f9f26302cf5c705.nq.gz
│   ├── 89565ae93a84ecd2160a899d4ab5cf5a72006b43.nq.gz
│   ├── 89fbc5de21dee6a3a3983521e6ef1068835b31bc.nq.gz
│   ├── 8fe7e22a374c24b84f6fccb7f8ffd207098baf62.nq.gz
│   ├── 98d3214b736fa6ea64f3862a52dfc811a696a8a1.nq.gz
│   ├── a56560fe593492075d96b734170034cc26392710.nq.gz
│   ├── aede0f8537a9ac989c64c161821f6da06739e9c2.nq.gz
│   ├── b09e335e069544f4595226d2881f80366a098caa.nq.gz
│   ├── b1ab5503e6bdb46bf327f8dba7579ca30d0b84b9.nq.gz
│   ├── b3b1ee2feba790437ff27d803abc08e696400b42.nq.gz
│   ├── b98c9ac3e67ebc61c0d442f12e41e15d3fe7fc2e.nq.gz
│   ├── ba31244436929e4e4c67610551fbe0e4961e4abd.nq.gz
│   ├── bec1ceee5f5385d339bdbf0071f221adc82de83a.nq.gz
│   ├── c1260db8cc219136c2d1c15438d205b1d5bb5eb4.nq.gz
│   ├── c1faafc18db5fb1ffafcedf233cf68833f01ef07.nq.gz
│   ├── c4a6e9e9414828c96ce627d43cddf097686144a1.nq.gz
│   ├── c79302b78f1c0e9c1cdac046873937da873ba4ec.nq.gz
│   ├── c94bffd8bd700ee5f56495299e24c8554a5f6103.nq.gz
│   ├── cbe1cdf3cba04a00ec5a2cb756ca0320e52e3dc7.nq.gz
│   ├── cfdc43a918e6c42b515c5b5b6d7ae3fc3f8d7c22.nq.gz
│   ├── d2a4b3e0c9a56ce9958c2a978d3ea67d64086672.nq.gz
│   ├── d35fce6fccbf2d2a5f03d4863d1efafe67fcbd40.nq.gz
│   ├── df645aa5d57e2282d68072c72ca4aa5843bc4f7d.nq.gz
│   ├── e0c65074930c243518064cc83980fa553de663fa.nq.gz
│   ├── e99ebc2c0e00cc37de4cefee2bf2a332abb73d8d.nq.gz
│   ├── ee85b5c323f893f9b50a5b558a6d0c615e08f264.nq.gz
│   ├── eebc1038f124bc7e982026b428df4ce7318b21a4.nq.gz
│   ├── fb85a8871740a52f7209c2ea1ccef60bf0b9b32a.nq.gz
│   └── fc28b9215f7846e6365a715bfd143eb90570f0c6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f1736b32b5a7fbbe587956e4c7f6a3d2c2b0a32e.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 62 files
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

[modelcontextprotocol/example-remote-client](https://github.com/modelcontextprotocol/example-remote-client)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
