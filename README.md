# Repolex Knowledge Graph of jazzband/django-model-utils

RDF knowledge graph data for [jazzband/django-model-utils](https://github.com/jazzband/django-model-utils), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-model-utils
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9d2edee6d63264d4f3d813aa139e3ab388ee36f4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9d2edee6d63264d4f3d813aa139e3ab388ee36f4
│           └── chunk-001.nq.gz
├── blob
│   ├── 01e3613d9633fe3212747808982b5b5ee255afbc.nq.gz
│   ├── 01fffc4284e37f27d0b6a2858d0f419c9a168c99.nq.gz
│   ├── 03ec814f484fd75ca43414319aa799cb22213805.nq.gz
│   ├── 05f1474bcc02f18208ffeec96d76cea2ef81d842.nq.gz
│   ├── 06ac9d3ea4a4eede72340e5e3396858c8c2f8c51.nq.gz
│   ├── 0aa03cdb8a98a816cb5327535cbe0f6ba0065e70.nq.gz
│   ├── 0fbfecc10c5cd361d611cc90225cad2fe7747142.nq.gz
│   ├── 1317c2364da8ab69c115ab48bea625a89a3ef171.nq.gz
│   ├── 14b50cc0a231e3fb919a63045118755205948d6e.nq.gz
│   ├── 14b924130074f9f6af35831727a539a6184deeca.nq.gz
│   ├── 15cc3dfed35f5b0aaa55655939faffb714df94b5.nq.gz
│   ├── 190f046b1a26d8da5bc3c27ce5f50ba9ea39a8c9.nq.gz
│   ├── 19ed9027ff0599afc1ea57a5add5e444a4b77510.nq.gz
│   ├── 246b3992b9da32262a7513af9042764a61e3807e.nq.gz
│   ├── 25edcd78dc6416e957b8b23d890f1ee34f8eb642.nq.gz
│   ├── 337a24659d696fa17209bf87c5d904950ed2f4e5.nq.gz
│   ├── 365803eadd16da1d5cd2c9c482992b42077a97b4.nq.gz
│   ├── 3b5316be2a83f0cf39b912b0ae6eea74dbdd90c4.nq.gz
│   ├── 44bdcfc8c8092710206fd890b1c28792a7464f31.nq.gz
│   ├── 4593b4a5a2aaf1dffe00a5632418bcd182de33b8.nq.gz
│   ├── 4a9d27119796ee9bbb35817ebcb8fa92ab0a57b8.nq.gz
│   ├── 4c77aaad2ed1caba86a3a4b4f2927b3f80eec5f6.nq.gz
│   ├── 5299dc3d251273ac5ced5551f1b39587e1fd1011.nq.gz
│   ├── 5b9a4c37bc301e363a3f6eea4c99a40f37997a36.nq.gz
│   ├── 63db703c6d80257d285bc7b8960fd0a6afaa27be.nq.gz
│   ├── 640bf1baf7465ae3080c5256f61f0e73cc4093c3.nq.gz
│   ├── 66979417aaad699b133fd41614f0a6d022c9c3b7.nq.gz
│   ├── 67db007a4b632d985a6e8dd2c97e0de5cdc84128.nq.gz
│   ├── 694367e7eabed855d10c55dca9092748ff4b4d0f.nq.gz
│   ├── 6cf203a7a17b9e80dc4b3ab9aa754c0a754555e4.nq.gz
│   ├── 6dd62606e241a232e29ea9054da1314358310d74.nq.gz
│   ├── 6fce4e54a90a96a6e789f0c0cdffdde2fc891114.nq.gz
│   ├── 6fecd15dba65ebfc0e950924d6ae04365eae9277.nq.gz
│   ├── 71d0055c7f722d1ef8583aaf8570eb7eedefbac1.nq.gz
│   ├── 72bbcda8e4fde6c07ad230f9567cc742dfb61f55.nq.gz
│   ├── 747a5adb8f687695e50319962cc177568f4e95a8.nq.gz
│   ├── 775315081df8d41f06d132d50711e7fed815cb04.nq.gz
│   ├── 79a693adf4ee82c4c58c6705493d1aaa238f427d.nq.gz
│   ├── 7ee9658810fbadae81c1b3e8649c8934c65adc49.nq.gz
│   ├── 80ed5e593197e1a9caf93c6f5557bd6f12008ad7.nq.gz
│   ├── 859854850a22ec70d2aeca713c8eb5f3dd0f7815.nq.gz
│   ├── 89ca82ecf9903ea5ab31b290ab1e2ad19ddc6606.nq.gz
│   ├── 89f2cffdfc7b2bf7d0ead257d9ee55206d387ad1.nq.gz
│   ├── 8ea2c062c4f453ba1babd755439979dec5956a51.nq.gz
│   ├── 9063ceff6d3f5781a393bbbcc3a02f6250f931ea.nq.gz
│   ├── 935bef6a49ac61b15efe30d7284af823033ab6de.nq.gz
│   ├── 973b596894fed5f7ea6a6ec0b6f9677239732147.nq.gz
│   ├── 99ee5601f090c2aeeaa2362ca9a15ec7696a9ed5.nq.gz
│   ├── 9c9a4a4223cd3a03b166670d90d526f1071b56e4.nq.gz
│   ├── 9e410a0482bdd89f8795ab25e12e45899f9a8526.nq.gz
│   ├── a04f63eb84c55f7cf0a8608349cd2dc2eae2ee2d.nq.gz
│   ├── a4b69b2fe8ebc1592a7497da4e307b1bbbcfeb2b.nq.gz
│   ├── a898571ef5b200c8d085a168a30b534dad0e156e.nq.gz
│   ├── ad01f8a84add5229fe41a34b177ee8e475a01280.nq.gz
│   ├── b22e5b44d3361ee655a44765ebf0cc2f7c41173d.nq.gz
│   ├── b5933585bdb038f3311a37f5a7ee7162f4d31608.nq.gz
│   ├── bb3c02f592a9d67aabba6a6ce94f06d0fefd6ea9.nq.gz
│   ├── bc94f48a20a0a725397c60be60d4a58746c2a19f.nq.gz
│   ├── bf283d13962b887fa0693a3db86d9e03a458c6e6.nq.gz
│   ├── c2d6fe7e546d71f5cdee028ef34ee1ae7881a6fa.nq.gz
│   ├── c5bb2ce53f5c4de928f86e3ee6d33e8234e562a0.nq.gz
│   ├── c6c45a3ae31d5cb777013073314291b53698a055.nq.gz
│   ├── c745729e0b88b2a6cbaa17931ed9d165cf46f904.nq.gz
│   ├── c90369595731ac51bf54ca519ba733b0cb82487c.nq.gz
│   ├── ce709be3a6e189fbf1fef9a341c6cf4e38ad55d0.nq.gz
│   ├── ce7385404e23453db1f53ba7a23232459da909f9.nq.gz
│   ├── ced117cb5d15516fc14bec7d04cc098931e5ed58.nq.gz
│   ├── d0264e952618f50bbd8b7e30056c46d5aeaf5888.nq.gz
│   ├── d20f5f4818909acfa0dc63556af2a8cfb809452e.nq.gz
│   ├── d343b2976a388b2e2e27ec49e6d0c0445b9cf873.nq.gz
│   ├── d4eb136dd075b677a1abb669016a2995d3905c75.nq.gz
│   ├── d57960cf8f50b4a93c0f713b45ba0d2edc5d9e2d.nq.gz
│   ├── d9d71d9dc4d18abda014b0fe7b63d8ad2f538f6c.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e36301c4793d40edeb1e2e887ef1dfc8b6adc671.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9896c569ad9cf153c06eab873859d21995f172b.nq.gz
│   ├── f08012d8a7306e7a631f5a4a28841b50c5a1521c.nq.gz
│   ├── f0c0bd5c4100fece3d2b630488d220c095390873.nq.gz
│   ├── f384ddeac6a9fe6251616ef6febbc30775b607a6.nq.gz
│   ├── f51e5eb7291d58195dd90856ab01a7c9c1ac20be.nq.gz
│   ├── f9074513f18eb222095d4047241caf23d00fa466.nq.gz
│   ├── fb92345273020ae28b503c83f3e394d0b9f3e171.nq.gz
│   ├── fbab4aa6fead25d7383da5e53c61de3cf2ff6bc7.nq.gz
│   └── fe79e11f72e3a29b56c89e1b71b4c7e9afdface2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9d2edee6d63264d4f3d813aa139e3ab388ee36f4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 93 files
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

[jazzband/django-model-utils](https://github.com/jazzband/django-model-utils)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
