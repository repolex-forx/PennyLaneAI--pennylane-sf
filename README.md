# Repolex Knowledge Graph of PennyLaneAI/pennylane-sf

RDF knowledge graph data for [PennyLaneAI/pennylane-sf](https://github.com/PennyLaneAI/pennylane-sf), parsed by [repolex](https://repolex.ai).

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
rlex download PennyLaneAI/pennylane-sf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f1a3204669ef72b637ff8fea683420b5474baa14
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f1a3204669ef72b637ff8fea683420b5474baa14
│           └── chunk-001.nq.gz
├── blob
│   ├── 049b2a8391337241ba0ab8dd3b5b3f5dab273cab.nq.gz
│   ├── 0b0823b3d3123a7e21abdb5c0f6f03f696e636dc.nq.gz
│   ├── 0ec8523c488d25cf67ca82cb7b5d9de45e996844.nq.gz
│   ├── 0fa856f8243d336604700ed302b5debe15d9c5ce.nq.gz
│   ├── 10bd335a4522daf891e05f12f05910ad58a69d91.nq.gz
│   ├── 14d21dfe98dd2ce745ec9789253c665b4c920125.nq.gz
│   ├── 16d0e28e4fe34c1196d274de6dc7d53cf235794c.nq.gz
│   ├── 199dfbfed0b92f0f6ef1b63c1f449db159ea36dd.nq.gz
│   ├── 1fd203417d5f8afeb41664e8cc436ddf776d3400.nq.gz
│   ├── 21da9259c0da43d97f7fe8835a3cc415d6630a01.nq.gz
│   ├── 24304e96488c275234fedf5ac020d168bf35007f.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 280b22058db88081ef5d553f907eec1153e60e54.nq.gz
│   ├── 29007449f8cb2d48f3ef3710be74033753056d1b.nq.gz
│   ├── 2ad508a2b3acb619d064608d6fee05eb9ff1ce18.nq.gz
│   ├── 3753dbfee6a6d1ede2685cc68dbac1d502f69180.nq.gz
│   ├── 49b055340d6db1e8c8f11b383868d2a73ae8bf65.nq.gz
│   ├── 4a64711f19f82388409756c59081e71cb91dfd0d.nq.gz
│   ├── 544bfad5e5c359ac301087f27408d0a6217f1be8.nq.gz
│   ├── 59a9e0b043e0bf3d229f5317b08741e8fb9b2989.nq.gz
│   ├── 5a9e4b4d9cbf6d9e785f0caee90b85f03a51bb8e.nq.gz
│   ├── 6127d6343bf1aed8a10e635a77b382ec05cda0d1.nq.gz
│   ├── 652ebc8871b6009a97fbcfd53d572668768938eb.nq.gz
│   ├── 6a27138c564ec3e746e66641ba17f99e2b55d22e.nq.gz
│   ├── 6d45995cd5ed7c38b0f59ccc0692d9a8f4bce71c.nq.gz
│   ├── 6f9e005b8c172b734d433f5eb753ec45a8206de5.nq.gz
│   ├── 6fe54ded8910e5617ebfbdc83a4a505ceb035b55.nq.gz
│   ├── 734dc40efffbdeae9dd2e9f1856ec4d32812535f.nq.gz
│   ├── 75ac5de4cc009077b49fbb717435aff32ae517b9.nq.gz
│   ├── 77c92f9a9d76ad8844a7506c9f8af46c8bef41b7.nq.gz
│   ├── 8ad12440f1c83b98b5c1c402e937da41f084d63c.nq.gz
│   ├── 9f7ff29470f730c9c4ec99f43a2c8f739c202a06.nq.gz
│   ├── a1e5a674d07ea867d49dd68eec1f3cf4766db6de.nq.gz
│   ├── a36bf5244e2c53f5481335250be82e6acb96a53b.nq.gz
│   ├── a43d5d8bf6393dbff99e6260de60a67bc2a564c6.nq.gz
│   ├── acec3018b28e98a178feab8026368e0204f6b46a.nq.gz
│   ├── ad95f0cb19b5e8e9033b0394f8a25ebac49e106e.nq.gz
│   ├── b19821f945f072fcee188b4281f9432403d515ee.nq.gz
│   ├── b3100aba2243c9aebce14d757119d84a75e903c7.nq.gz
│   ├── b3da76fd0006293bd0b2f77e828d43926b138a72.nq.gz
│   ├── b64f7c88f9b92d4daa4e3a40adcfe6433feda3cd.nq.gz
│   ├── b69348d97da3e161718a410312935f4746b6cb54.nq.gz
│   ├── c1abf5ce880a2cf740a44abc033326098d8524f3.nq.gz
│   ├── c2dd713819f372be60f277c6e0461891dd70f9e7.nq.gz
│   ├── c51b21f94ad40933b6a7ae315ac80dd9853b347d.nq.gz
│   ├── cde9ae6de65475e9d1503276b8bba13c516b9f91.nq.gz
│   ├── cf510d1b3ccda19d64692a87b998b1b0b134747a.nq.gz
│   ├── cfb4973b5bfca0e0380fc09a6edd570d7340562a.nq.gz
│   ├── d800f3c074dcf94d306e0467a0e337f979e7eca8.nq.gz
│   ├── d9a259015802350bb2e9b9ea963b8b95cc1d61f8.nq.gz
│   ├── daefc757aa7efb73dca9b38994b98d4a677c5b92.nq.gz
│   ├── dbfdf634be67e30360c8712852f91218ed553e9b.nq.gz
│   ├── df70f6714f57a3e857dead7b64224a1528e72aeb.nq.gz
│   ├── e62de881b87e322b8f79bd42f934f6b473be2727.nq.gz
│   ├── e66bd9fae46bbd9f01c18b7378e84bd23e591874.nq.gz
│   ├── eb649727d02beae72f7749b977577a2906efbf48.nq.gz
│   ├── f67bec815653a41d9d6bb7cda75b00f728640fe0.nq.gz
│   ├── f9e031a633d195e204ee51aae50632f93c68a8f1.nq.gz
│   └── fc4614024be2571643598d57affad98b9733ea38.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f1a3204669ef72b637ff8fea683420b5474baa14.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 67 files
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

[PennyLaneAI/pennylane-sf](https://github.com/PennyLaneAI/pennylane-sf)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
