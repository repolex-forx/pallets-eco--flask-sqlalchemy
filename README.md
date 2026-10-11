# Repolex Knowledge Graph of pallets-eco/flask-sqlalchemy

RDF knowledge graph data for [pallets-eco/flask-sqlalchemy](https://github.com/pallets-eco/flask-sqlalchemy), parsed by [repolex](https://repolex.ai).

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
rlex download pallets-eco/flask-sqlalchemy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 80ac6ef26bd12a6b5472a494d541a7d2442a38a4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 80ac6ef26bd12a6b5472a494d541a7d2442a38a4
│           └── chunk-001.nq.gz
├── blob
│   ├── 0d09b9e2443ae6b296978e09d8a57e17962e3f2a.nq.gz
│   ├── 0d436e2b06ba3b47e769673d61b301180ce74051.nq.gz
│   ├── 0d596280f188f20a9084c0ad8a27de970759debd.nq.gz
│   ├── 0e88d5e312bf5fad8f19927700ac6e50d4482ada.nq.gz
│   ├── 149f537699905cd86438b43501cc7681606a18b5.nq.gz
│   ├── 14e24a9e365c04778fd559261cb96de2ca04c96f.nq.gz
│   ├── 170e5bb7b314a5af6d9607e87121ca86179845d1.nq.gz
│   ├── 18e842dbd495f2a1912d46991736e468686387b4.nq.gz
│   ├── 1b5467e56fabd633f63a9207250d76356421ed13.nq.gz
│   ├── 1fa7312e14a8146411b4f35e46ccc1589172179d.nq.gz
│   ├── 1fefddd7cec9e69d5bc26a17495fdc7cc0a1fa32.nq.gz
│   ├── 28078db0dfd0c0bcf1dcc8897886aa73315027e2.nq.gz
│   ├── 287b216d04e7aa8d108a7994d8ff51558b2cf4bf.nq.gz
│   ├── 29e79329b75827a47eee4f1f3bc795a135c16208.nq.gz
│   ├── 2a445f9c62843f5205e3e4a920fd49c1808a399e.nq.gz
│   ├── 2bbbe96ed5d8bb8c273ba962d71d55f9d3817c7c.nq.gz
│   ├── 2f1f4d0c3c57c4916577e3acc4b9d3f1d1e6f23c.nq.gz
│   ├── 2ff985a67af35fdfd1076354b771c425867cdab4.nq.gz
│   ├── 35f927d2852d0e6ba54480e55d1c76ad46d72c58.nq.gz
│   ├── 3d49d6e04447e2111b7647fd59db6aaf3a3094ad.nq.gz
│   ├── 42b81b16b9fdb571385de1e963978c4de9e3e607.nq.gz
│   ├── 42da287d3e5903ed2eb8eb9684400c2415e3d5d4.nq.gz
│   ├── 4be0dd35e698ff8b32b43683bb9aa1e4f2e4e673.nq.gz
│   ├── 4f20c1e5f209f78c10e4fc3d745716d8a6d43a0a.nq.gz
│   ├── 5a513e697bc4f4460a90e5cefc69e092d3bdfb56.nq.gz
│   ├── 5be1cb0d09788f0e9bd3a7227b2d1c532a8da1f3.nq.gz
│   ├── 5eb7e0eed505a58a722687b77e880368e34c7caf.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 62c1b887d73cc6325731f0c9c97927df23a42d1d.nq.gz
│   ├── 631fffa82c449827f9c5c102fa190801478484bc.nq.gz
│   ├── 6468a7341895d96559df2a59b535c7015b0481fc.nq.gz
│   ├── 6b79eaa1d6e754caa0986f1f206799c325b95b4c.nq.gz
│   ├── 7028b65381146f82fadb9b102c432f8b05341af6.nq.gz
│   ├── 722dc5d35eaecd08f840d9115fad5be0ed57e356.nq.gz
│   ├── 793f1030a2ed0b76354530ad7fe9dce538db0de4.nq.gz
│   ├── 7ac59691c7f5c8582011d7bf885eaea5a1c567c9.nq.gz
│   ├── 8289fdf5136923b3da8f4b673f3b4cab8b78bf26.nq.gz
│   ├── 85e87cc72a95e5a4995cbec6d87ead8e637f53d1.nq.gz
│   ├── 86eff90532805f66287383c914acf7a54bfb43cc.nq.gz
│   ├── 88be7e2e612bf785e314bf88899f12c687e76315.nq.gz
│   ├── 890350ec401c4968a4b91b44ffa8bfeb154f8eb9.nq.gz
│   ├── 8b54e5bc8590c7cafa61f333dea4ad4123b716ac.nq.gz
│   ├── 8c8c5abba5f0473db74d7a7c246d8d2b651d089c.nq.gz
│   ├── 8ebcb7bc8b0d8a40031c5fb644e31ddcc49703bd.nq.gz
│   ├── 8f000f7d799703a6f894d6b791f17125af8e0016.nq.gz
│   ├── 916727333143663caa8defcfd9f77b6de321b388.nq.gz
│   ├── 954237b9b9f2b248bb1397a15c055c0af1cad03e.nq.gz
│   ├── 955deaf27bc821a6367e818f36c016892fed3d33.nq.gz
│   ├── 988e89f12808290331e5fb851b4dee73ebeb0a09.nq.gz
│   ├── 9a6834ad19626fef3511f5684049040f28338165.nq.gz
│   ├── 9d227a0cc43c3268d15722b763bd94ad298645a1.nq.gz
│   ├── 9dc979688f6b974ed556e3fbcfa7d324bac00977.nq.gz
│   ├── a0238c280332f3e1973a6c360040957ecf7cdcd5.nq.gz
│   ├── a4cf4ff3218721818dbad54062faf82b796fbe15.nq.gz
│   ├── aad17f0a25dc3fa7666d360d9339964c19f25aa7.nq.gz
│   ├── ae19f5d3cdbc70e03fada625116156c1d33ad82d.nq.gz
│   ├── afc434815a1703ce2e6971986bbb07f3aa2721c1.nq.gz
│   ├── b872bc7b51301ff0172857f0cf995e98ab8a3cc6.nq.gz
│   ├── b9e7fc7fde7b0d8eb74efdc90c2d635def132bd8.nq.gz
│   ├── bb1a7559e1785e2d3a7aa574e4daa7445c0ec922.nq.gz
│   ├── bbbace9ad1e142396c647fd3597c39b3cc85d121.nq.gz
│   ├── c1d056c1d18e4b09a737c49ae2586d695d25264f.nq.gz
│   ├── c2fa0591c0243c91face8b5e42c11a8441d0a58a.nq.gz
│   ├── c4c24ec8d8d460ce42b60a1af77949c8d3b1cb31.nq.gz
│   ├── c5cc73a2d4058befcaa7fe0dbd13e8da5cab4020.nq.gz
│   ├── ccae54b4c89572df4906d1b0f63985a9753d3f9a.nq.gz
│   ├── cfa94c75c34a9c365499db687eb1815f1864aa17.nq.gz
│   ├── d4ab92f4d89f26fa3415117048dcaf0d0f47cea3.nq.gz
│   ├── d4b2c1e945dcd123e76e2cc44ba49b4d6b25102b.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d4dbadac7989d949a301a4312d679d0fbede78e0.nq.gz
│   ├── d5e7f5e880d28700db27f82bab2d964dd6cb415d.nq.gz
│   ├── d61b5d67a9550267dcf8c8e4f3b7c988b38d9146.nq.gz
│   ├── d7d7e4bef6ebbcf2a1480198b49ddac7a8bd0850.nq.gz
│   ├── da684b1d28b82205db3c7a5bc52a638798eec065.nq.gz
│   ├── db757c3a8e4322d5566b17721ef2e1096cb74994.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8273be951c52357ab8248e29e6b04d86327697c.nq.gz
│   ├── e8c453cc824b8f972ed5a7aa62624b7ecf3308f2.nq.gz
│   ├── eb124d251a733352fc4e867844072e876d1a8508.nq.gz
│   ├── eb25149743047e0b1f73cac85cdfd5c8043123ca.nq.gz
│   ├── f75aeffda39ee8fc96db1cbf07f71315a9f77bd1.nq.gz
│   ├── f95976439a56beee4635dfeb93282748b0963ae4.nq.gz
│   └── fd83d1a967d336e938ab8c2715adda982dc3a2ab.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 80ac6ef26bd12a6b5472a494d541a7d2442a38a4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 92 files
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

[pallets-eco/flask-sqlalchemy](https://github.com/pallets-eco/flask-sqlalchemy)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
