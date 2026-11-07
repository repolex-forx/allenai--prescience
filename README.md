# Repolex Knowledge Graph of allenai/prescience

RDF knowledge graph data for [allenai/prescience](https://github.com/allenai/prescience), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/prescience
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 47384ed79c48cfef610f30af12ba883f2a0093cb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 47384ed79c48cfef610f30af12ba883f2a0093cb
│           └── chunk-001.nq.gz
├── blob
│   ├── 006712a688bf530772766ae91cc12be67255774d.nq.gz
│   ├── 00af3f06b68042c54c0747cd29b36af129e63466.nq.gz
│   ├── 0139062e39a143f12a6b462425089c73e7ab90c9.nq.gz
│   ├── 02c5368a846d89ba18a0fc11f2a83aae3f1f7094.nq.gz
│   ├── 06139b0c73aa134c1d162019e483818758de784e.nq.gz
│   ├── 068b00f5f9466fb7fd34d1f193067d9313039c54.nq.gz
│   ├── 0ca8ea11cb34b1a7b757707e8500a8603c38ed7e.nq.gz
│   ├── 12170e5e67dd22f7ed68d5482eadff58373452e9.nq.gz
│   ├── 130969a36db5d4927eac12c19778089c86513924.nq.gz
│   ├── 15559b710f9fe2ba018689f89616f8079bb102be.nq.gz
│   ├── 17c63c182b0aefdfeac12b7e2e51a13edd7a1bf9.nq.gz
│   ├── 1debebeeec02a31e8408bdd4cb7306135150096b.nq.gz
│   ├── 23f74461792f1aabf9456d995bff2d26545903de.nq.gz
│   ├── 268f11f336365eb07b86f8f93decca35f3bf718b.nq.gz
│   ├── 26930ec9833d8c206b2119c14c081944490aa9b8.nq.gz
│   ├── 27aa0ce70306d7b1a37c3027ee42c01f14d704a7.nq.gz
│   ├── 35903b5b10c485f3087d14516ad7e33133b83226.nq.gz
│   ├── 39f949e34ae02ad52966b6c69a183cb58bd38bf3.nq.gz
│   ├── 3cad3961a9c771d3346caaa12bf1c96738911cf2.nq.gz
│   ├── 3d64fdc2922d0d27723f5bda412295493e314a4c.nq.gz
│   ├── 3fbceeecb5284831590b0134e91840285c825e66.nq.gz
│   ├── 417fab56be668099a640a240c17fa801fca25920.nq.gz
│   ├── 46ef78a6b692c9dadefc330dae301dd5cfe7331c.nq.gz
│   ├── 476199e7010f7d8bc1f4da456826afe6ea61d56c.nq.gz
│   ├── 478ca6879251ad36ea01b1083987e7be35549ab3.nq.gz
│   ├── 47c9ae702d4468059b817375a8d5704bb6260d01.nq.gz
│   ├── 530a74b14a716442524111d70d011db5574b2675.nq.gz
│   ├── 55c97cbd28b1735293ab16715bcbd0a1e09dbe18.nq.gz
│   ├── 5772824d9df3629eb2cfe449828aa2fdbd1d8c6d.nq.gz
│   ├── 58d3a87b3983c1a00e0fcd22f2be11d81ff44ab5.nq.gz
│   ├── 59fa379b7942165d9ebb2f53e65439c7a3dad1bc.nq.gz
│   ├── 5a835285bc6f1ac760bd64ba9f46e2ccde13875f.nq.gz
│   ├── 5b66869cb456d57437dcabaea581c99feba01816.nq.gz
│   ├── 5b821ce2eee04ac2299345c4f0d52f1b8851503c.nq.gz
│   ├── 5bc6ba6507e296dbb64fca8477b0129ac9a5d938.nq.gz
│   ├── 5e3dc5299782b667d5c18a32df3bbcd77e251420.nq.gz
│   ├── 5ecee11f479373bc59fda7240584e820a0d62365.nq.gz
│   ├── 60f782a8299d0e207276a113089d677d3bbd8c27.nq.gz
│   ├── 6392da001a2899bfb597be577dacfdc119c2789d.nq.gz
│   ├── 65ebd9736f8e348e81043374b4a54e356af133aa.nq.gz
│   ├── 661703643cdc8649e1791e3c5c212acc7f888846.nq.gz
│   ├── 68071b92b427d14419df45e0e1dbd92676f220bc.nq.gz
│   ├── 6c9bd81ba5e3280bdde052438cc177fd224ab8e4.nq.gz
│   ├── 6cd0729b971f2702235024e285cac7898210edea.nq.gz
│   ├── 6d3aca076e55cb4417808fb4dee132c8f2c5a7c6.nq.gz
│   ├── 6f67136366d4d0bcd23b4f823cb62b51cc7aac9b.nq.gz
│   ├── 6f75d0abfa52fdfd19fc5a296da367f359b8e60b.nq.gz
│   ├── 6ff026f4fd6af2014ab9314c399fb9360cfde3c5.nq.gz
│   ├── 70172f7bbb4e1213be6ca9985f0770dd69a0f527.nq.gz
│   ├── 70cb3abb4a201fd145000bd5f725fa5d938f30b4.nq.gz
│   ├── 73eb52dc9646279d281fc444b37db8467511c09e.nq.gz
│   ├── 747c092910864f2dae8f09c879385ff1a6792f82.nq.gz
│   ├── 755010773929750aa2a6233373fbfebcecd6e64c.nq.gz
│   ├── 75eb31d863cf99f50d279f03f342d03f7bdf6b4d.nq.gz
│   ├── 7a2ab276b5b53f3093f6e288a13a1d952e0edfa5.nq.gz
│   ├── 7b2b4f24405abb6b67c8592d1ae06912ccdf8d3b.nq.gz
│   ├── 7b3ce7567219361e71ad0507970a0aed3ea9a58f.nq.gz
│   ├── 7be19e8bf393699c3b3955cb66e3a437965a0be6.nq.gz
│   ├── 7c5e6eb01ac07030f020fdf8773b0a13b98b59b3.nq.gz
│   ├── 7dd035924b6e9ab7997be58e8c08f704e4b218a6.nq.gz
│   ├── 7eccab401baa4b7b1c44b8b57b101a08a229d366.nq.gz
│   ├── 8069951e70506aa9631be668d67ee26056254401.nq.gz
│   ├── 833228629bfe060000f4ebdf500e32999ec8fba2.nq.gz
│   ├── 83ebdf040151bd6a59aa145913263493a28e62c5.nq.gz
│   ├── 86d2427ea989f5f91f4f57d239119c21e6070e8e.nq.gz
│   ├── 8715f92d48159f3c18bad339b496554e13369e88.nq.gz
│   ├── 8b2f6281177ab1000a635542756440096aa5f6f6.nq.gz
│   ├── 8c15f0a4e7976e438518141e92c52bd88de17d98.nq.gz
│   ├── 915724fa4058838b63a7d160b733963be0029934.nq.gz
│   ├── 91da5baf7c802dcc074d28dafe9031a77486a185.nq.gz
│   ├── 930e07bc9d7ad662ebcb609d85b5f4d91f007378.nq.gz
│   ├── 955c3f352a3472a5b654150bcd07757b6a2b1c18.nq.gz
│   ├── 95e9f17d6da20497209d1ea410a13e5ea690ff60.nq.gz
│   ├── 97aa9ac9e03d9f6cbabc64a602971f7b2d83e943.nq.gz
│   ├── 9880db7924c8da9be40372b1b016777a21465ddf.nq.gz
│   ├── 9b19998b0d70ee65ee3613008e24894546be619e.nq.gz
│   ├── 9ce9de8c185bfc85701468bbf28c1e318d42e16d.nq.gz
│   ├── 9ee113815b825f41cd5a0f1f182d2b49644835db.nq.gz
│   ├── a140b0227b81a87c18e880fdf823f13a90fac629.nq.gz
│   ├── a1e3901b1cc21829e01266c4a44878c1dfc4f149.nq.gz
│   ├── a24300ddb64876907c5a70d5fd6af72e0e161f95.nq.gz
│   ├── a2598f2d6c71d7cfb28ddff5560254606da976b6.nq.gz
│   ├── a30ea339a4c9d584577d934a14d85dde3d798768.nq.gz
│   ├── a6b6a98c47333790d1efa528ba5f5365f53c7650.nq.gz
│   ├── a985888f18370c115499c816e24c8d93ef456c13.nq.gz
│   ├── aa3527d6a26a397189928da7a29ed4d2beb58a67.nq.gz
│   ├── abbc2808b04232866a70e914bf91be073f81623c.nq.gz
│   ├── b209ce87f49a4d2ef426739da811d1aa2b3c0294.nq.gz
│   ├── b2e7b39cefd0982cd12cedd2330df62b4b2da6d7.nq.gz
│   ├── b368d4d740cf0ec48fa8b379909ad095940d3ad4.nq.gz
│   ├── b6d2a4b685da387a3c6241d489a807f7698b1aea.nq.gz
│   ├── b84596e7b18507167d60904bdbc664dced103d4f.nq.gz
│   ├── bd011e4303c13a5e970a42a7c0c2a1620ecaa052.nq.gz
│   ├── c1b96af7f4d42a16f5f0452cc6c2a55db880b504.nq.gz
│   ├── c3dafe2a0aa4ced270477649b40f49cc63998642.nq.gz
│   ├── c6b0fbbf4e2eb29058f660d8cf10d017c9d98f37.nq.gz
│   ├── c75d05681a2dbaa0b5d7fed7a6961726da70434f.nq.gz
│   ├── cd2f5a1745570e0e9e6d1a4d51beee8bebab733e.nq.gz
│   ├── cd77e730f01af4aacf53c0d5f3f06a9c90c3d8f9.nq.gz
│   ├── d171dd1550eabc0e02dd2fa412fac305395c2c28.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── dabc62ea2de4174f19bc3709143a371749cb8f04.nq.gz
│   ├── dbab72df47631b23414c2c443ae25a8ce3182450.nq.gz
│   ├── e0d195c4cfacd5ace813ca97c7823b5963c8f46f.nq.gz
│   ├── e12d7bef1908204ea69fc6633accd1cef05c2661.nq.gz
│   ├── e16acef4ec9b48554251df45668cbeaf351d97d1.nq.gz
│   ├── e24f8d2d828cbc1b37c0fc556b1312395dbb08ba.nq.gz
│   ├── e25aefc133c0c8b9738360485142254e1de6b7d3.nq.gz
│   ├── e298f1752ee4266e41edba3be5551d594df2a845.nq.gz
│   ├── e29a71fa4eb97744a507c90a81717f9316ce781b.nq.gz
│   ├── e34af3996edc79f784624a37458316e3594fb684.nq.gz
│   ├── e51fbb1d2ae7c0c13bf2c146f725bf87eeab2f17.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e766947b8e9d19abf00dc6d4de23896b2b433788.nq.gz
│   ├── e854910916c104dcfc66d3f42154f35ff15fc476.nq.gz
│   ├── e92fd82508764cecf2217e8039c566eb7a4acb2f.nq.gz
│   ├── eae8242c02934779e6da20a723ac6815a299a3d1.nq.gz
│   ├── ec38485e3f53af90b0c818471f06442d4c02ba91.nq.gz
│   ├── eda79456a24c0a52acd3d81f54774a025c9b271e.nq.gz
│   ├── ef0ec9bdb7cfec68f49f97bed16f30d7069d5ef6.nq.gz
│   ├── f0c38fafa0113b26cb51c7380bc97ed7dc7c4719.nq.gz
│   ├── f1c0bce4aa8d5bfd131cd2b9d85c27e2507799ae.nq.gz
│   ├── f1da6c90ea35da2933ffaf45bd0172dce6a48dc9.nq.gz
│   ├── f40c4c2655d5053256dbbcd1db9a180b5f31745e.nq.gz
│   ├── f677b5fe0c1181fbc790591b310ff7ea651efd81.nq.gz
│   ├── f90971fffe99f59c416008aa8d8e413bc6bf4bf5.nq.gz
│   ├── fb7c0e03018abd4a6deeb4fd529888a517ec0fe1.nq.gz
│   └── fbd28751f8323282f02ef18e4c89e806d8224e37.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 47384ed79c48cfef610f30af12ba883f2a0093cb.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 134 files
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

[allenai/prescience](https://github.com/allenai/prescience)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
