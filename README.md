# Repolex Knowledge Graph of UKPLab/arxiv2026-aitdna

RDF knowledge graph data for [UKPLab/arxiv2026-aitdna](https://github.com/UKPLab/arxiv2026-aitdna), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/arxiv2026-aitdna
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 28e3776681b563b5fb25ef137e33ba0e6147209a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 28e3776681b563b5fb25ef137e33ba0e6147209a
│           └── chunk-001.nq.gz
├── blob
│   ├── 09dee0898b5477bddd9a45487b634e54b5a4ebdb.nq.gz
│   ├── 0b2002f051a3fd8441325593b77d8a844c69ea8d.nq.gz
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 0d39a67c24f01c1af1e9cb675f380c3a1d1b2422.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 10cacbc02a037882b3f3f569a80741ce235140f6.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 14411fd93d699377c6e17280cabaf9a39d67dbdc.nq.gz
│   ├── 16a80c4aeb9ed858f069e9a6547d816050b90d3c.nq.gz
│   ├── 177de15c10f3087c19ca5287285048d497312302.nq.gz
│   ├── 18aef39063e2f5dbe1de20ecb70264795be8d708.nq.gz
│   ├── 1b6d96d729b3da8a11cc5e2fae4101acefb26ee3.nq.gz
│   ├── 21e3d4f221d63b7d692463f6665741d25f0b1ea4.nq.gz
│   ├── 224969cea28338e32da6c73d8083c10e0c6bb136.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 241e83dbe9d4c532abf70f90df6284acf72bfea2.nq.gz
│   ├── 2dc2a8fa00f487a8b3db7731a440640af682db3d.nq.gz
│   ├── 3167969bb442ab2fdf0358b473077f9e3ff521ad.nq.gz
│   ├── 334349a4e439734dc7a9e8c6f85cfdcff5de4a6d.nq.gz
│   ├── 348db4433a350e8f4450851144635845fff4ddb3.nq.gz
│   ├── 35775a6c49c3b5063fa34d016bf10b438f7dce13.nq.gz
│   ├── 36e98bd44e3690d86f1bf547b5736326f5181905.nq.gz
│   ├── 394a02233715b444a6826092302ac63eaf72e19f.nq.gz
│   ├── 3ade0bdf5dbb340698a09cc81c4bd8397d65b02f.nq.gz
│   ├── 3fbaca62a63bbc867a0703a21dd2114eff3783dc.nq.gz
│   ├── 432785fd88c31bc78e050aa72b0b11d3d8ec6273.nq.gz
│   ├── 45aee6baae2e6a811fe8400e988384b400d0bc6e.nq.gz
│   ├── 4adc89e4cad4745e341752ae6bc1994c5c9e4dbc.nq.gz
│   ├── 4b7a6de3682e114ebbc373c60a4d7f09c4ea6370.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 4d97098229513361cc86030b22528dc52084370b.nq.gz
│   ├── 4e97fbbb4ade70211223e80ea16a7804b553e422.nq.gz
│   ├── 50e0575f3407544ea24422f362dfb23d87aa849f.nq.gz
│   ├── 52ad969c4907274a4d0be8da39251c6c43975394.nq.gz
│   ├── 5412e5472fdea790affedeb484bc9f044e4c0189.nq.gz
│   ├── 555c6ae011157e173ff0951133b1c8eed00fa163.nq.gz
│   ├── 5b88208c56ee7d68b9f425095aa5e91de64f93cd.nq.gz
│   ├── 5bb7bf3ab7590503482f64fb51b8c326f77ccbb0.nq.gz
│   ├── 5dcef726f671e400c7a0873dc8e9d9f061889630.nq.gz
│   ├── 6115a57bc9f35230c1957b4d4d0b7b0a0908080d.nq.gz
│   ├── 638eb96936646634e8a011d68a74800551ee5f25.nq.gz
│   ├── 655e5ac830f6e34d0b318e8d131fd5f1a4fbfda8.nq.gz
│   ├── 65a6473ed505f9bc06fbf0c5001c00bc67429c00.nq.gz
│   ├── 69460f66a84e2a33084add6a39b575bde6fbbaf9.nq.gz
│   ├── 6b32081e66f2b7abebf6bbf2821ce183f6388333.nq.gz
│   ├── 7023cef005bc5dbec51aebb7830b47ba6df46fe8.nq.gz
│   ├── 7acd99725d9f6c316700718e857b75f41e71093a.nq.gz
│   ├── 828b6249806023328c2736be9394e5ea517b8313.nq.gz
│   ├── 84fdf52a8cdd22d4855d07aac455c880e4eaf4cb.nq.gz
│   ├── 8871abfdc9c3745a372d1b55952f4d24481e3ea0.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8b14d41f730e3642c5986d15e956bb8af5134367.nq.gz
│   ├── 8f86b82ca37869e77b9d953e77d467aaa757a412.nq.gz
│   ├── 967ce43ab399dbec1c9a097ddee80c231536a99c.nq.gz
│   ├── 971c9699876638150ecebdee5738c1b4c1eeb622.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── a01cc17739ecf18e97574e6fd2b08cdde65ff97d.nq.gz
│   ├── a02bc19eed188e6da432aec263632a462d4e67dc.nq.gz
│   ├── a0486103847163093681528f015c375f75ed5971.nq.gz
│   ├── a20bfcbcbde4ea4a5936efbbd6ef31dd55273d3d.nq.gz
│   ├── a231b879bb2b517c2d73f7a5288e23fd541ce8c8.nq.gz
│   ├── a3527b1eebd0297bddc35717b8e9f28e3d0cf3ec.nq.gz
│   ├── a417640db23f52bba680b759feca4610c0c68419.nq.gz
│   ├── a70d291241eea483a3e2ca58d7c779b17cc164b8.nq.gz
│   ├── adb92e074ba66c266c4963334a0d77b4520acc48.nq.gz
│   ├── b51549a583a56b707240d30cb0ead65694326b78.nq.gz
│   ├── b6451d980ddbcc0b017b87786c84a3d1097c753c.nq.gz
│   ├── b6cc89a23e0e81b8cf81a2b9de1fbede0e4fe9cb.nq.gz
│   ├── bee8fd6b7c7d7896bed7540ee5a7b41b785c1956.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c1117fa6343eecfa6295fc49884fcd2c17859933.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c7a351776c6d721e4c4b745d42d4091fc5346cc1.nq.gz
│   ├── c9d05c348a51f93fb729300f5f8adc632e13147f.nq.gz
│   ├── cbef0b60332265ff668fc46fe8ef943c1e476d1f.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── d6483e7352b96e6d85207cfaeaff41eac8d5e42e.nq.gz
│   ├── d75d54668563b996046be4f56a36a67bee7e9af3.nq.gz
│   ├── db3f94a2480bc279c357a861e5f13afd159d2dd3.nq.gz
│   ├── dd70baa82686b8dc0c6aa49f57b60edc114044c9.nq.gz
│   ├── de2ad6ec52051eab96f81aac62f1139f0402d17d.nq.gz
│   ├── e2d24c0d091995e77d3824f08cc6a95fe2637d1a.nq.gz
│   ├── e519cc118f74d0b98b7efe6736475792d1754ef4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8d5a726b324ab9aa67152076bb6d2cd3777f9ba.nq.gz
│   ├── eaca1439d8e97f2f9b3fa1befbd5ddf23132982c.nq.gz
│   ├── eb2b1bd38275d10358e136fcd1cd774d3fabee5e.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── f11186804d4fece0191b172e497b31dc9246d62d.nq.gz
│   ├── f50b79f2f8d0399dcbe24fcf668696f0d78a9d02.nq.gz
│   ├── f7dabd5f5158c6121f953ee17a7c8c24940876e7.nq.gz
│   └── fc439b14e291376d62c1a70d55df21e4385dea03.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 28e3776681b563b5fb25ef137e33ba0e6147209a.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 101 files
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

[UKPLab/arxiv2026-aitdna](https://github.com/UKPLab/arxiv2026-aitdna)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
