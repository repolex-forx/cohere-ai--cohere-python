# Repolex Knowledge Graph of cohere-ai/cohere-python

RDF knowledge graph data for [cohere-ai/cohere-python](https://github.com/cohere-ai/cohere-python), parsed by [repolex](https://repolex.ai).

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
rlex download cohere-ai/cohere-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0eacfe77e1710322b355928574cfec18f6791c42
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0eacfe77e1710322b355928574cfec18f6791c42
│           └── chunk-001.nq.gz
└── blob
    ├── 01477638da3ea11415a8400abe037c943eaa0e66.nq.gz
    ├── 019c128e6b7eca707a2ff2a3be1456c9a2440bdc.nq.gz
    ├── 01dd86199d0b6c5f25ea726e0b846cc3324351d1.nq.gz
    ├── 02101e122cf6cb9991f8af64fc9bacff98529f99.nq.gz
    ├── 026ef2a7f5421f2cc7a0f762ad3282a5ea3142c3.nq.gz
    ├── 02adfc85f7f65b9fa9785d08ace57041d3df2088.nq.gz
    ├── 0330f178e8c84e37384c82a21be7692c8d9d9369.nq.gz
    ├── 046d4c8ecbb08f102768448a3768ab2a419577ff.nq.gz
    ├── 04899930a38cba6b6600a952816073c9c138db22.nq.gz
    ├── 053f470a767319a7dd9e870084ef9d30c967357e.nq.gz
    ├── 057e798925e1962e1a943ab3afeacb848ed363d7.nq.gz
    ├── 05c88f899fd0d8f8f1174a1c9c43ea937a57e4da.nq.gz
    ├── 0614ebce14f07c180b5ce5e703c3495570c6db3c.nq.gz
    ├── 07641982c1ce4c726891fc3c018447ac5a37aca9.nq.gz
    ├── 07756d28391f662a69f31fe097e4e98208d557b5.nq.gz
    ├── 07d7e45b85a17844bc95f36afaf0e614ae225950.nq.gz
    ├── 089cee925b5f0c7a3bb9eee716cc5d3cb0ef6bc7.nq.gz
    ├── 09d09897d089e48ec78df126b360b35638a5312c.nq.gz
    ├── 0a75c4d90780c8c9055365c98ef38b177836e593.nq.gz
    ├── 0c6ed78604906b3aec6a11b78d2fcc8253b0bd38.nq.gz
    ├── 0d6ac42f5760ec6ad70c68119ea27dbc02350584.nq.gz
    ├── 0fa2972a8c318207f09f10cc319a1d36dc61a643.nq.gz
    ├── 0fb8f727fc27391dfe93193a7249958c2c605239.nq.gz
    ├── 10317165f68a772b09b2c8b5da2e9e3b62a6cf07.nq.gz
    ├── 1091c0e34a79e2e3187091388e3363d58cbe8ecf.nq.gz
    ├── 1142ba881ceb42fe5826820b77c327f01835e1fc.nq.gz
    ├── 12a1682768ae535e9e85a72175333a891c913854.nq.gz
    ├── 1330b2c18623d9fb8d404efa5acf57a3f4f82281.nq.gz
    ├── 14065836ee4b862dd8952b9e24209fdcdd2bed0c.nq.gz
    ├── 145877d0abae1bda432031972edda125306ffdac.nq.gz
    ├── 14d88d8f8ed4faf50339e8d4d834e0716f2cf231.nq.gz
    ├── 1541d94f419dbf3a3aeb9ca8800f634cd5d8146a.nq.gz
    ├── 1637805dd7cba8615d951f95bd4a123e100a8e31.nq.gz
    ├── 16b4bcdd0843eb5ffae8202da0aac29f2539b277.nq.gz
    ├── 16f47b031f9f842a9e8468f01a9217d05d23b046.nq.gz
    ├── 17bfbe0da1c8238c1d19a3d16bdd83f43884be94.nq.gz
    ├── 17fe8147084c6885fbac447f46749408165acf9b.nq.gz
    ├── 183fbfa34a496983b8b28401d21f7fc2f65f8138.nq.gz
    ├── 1928498db7d89f6c0233ea0019f080b76a5ff125.nq.gz
    ├── 19b1cf87cc0792ce9f26bb74677bcaeb65fcd0fb.nq.gz
    ├── 19b784c9451fbd04198db3dcb0872427afbddf67.nq.gz
    ├── 1af57f8fd0d2f9872ae06f67a13416ea3fb848e0.nq.gz
    ├── 1c801a4bc08bb1e0c42e59f978ad275f4656a150.nq.gz
    ├── 1cdc53ec163d5276e63a0b8afb835bfbd8e5cae1.nq.gz
    ├── 1d14139d5dd60fd01273cac1b4679ca37207ec49.nq.gz
    ├── 1d753e26f739f5adcd22dc47dede4c113f761417.nq.gz
    ├── 1e3fa06b2694c030a93c1236ff4dede5e62e2db2.nq.gz
    ├── 1eaf04f9747aa40338417746e40e69ecc92d601b.nq.gz
    ├── 1f6b35ec0bdf42c17630a419256a39f164ae05cc.nq.gz
    ├── 1f8ced078c1dd617628bdca0e5abbbc5b1566b62.nq.gz
    ├── 1f94c050a576fd2cd690f0cd951ad435477bcaf2.nq.gz
    ├── 201b623aa3dc43592b8025d0e8351fe5cb17d312.nq.gz
    ├── 2044e347e1725c97a99d0fa8e182f5f615db4e7a.nq.gz
    ├── 20935518ecee67cdbcf6956cdc11bc336f6064d7.nq.gz
    ├── 209635c0494ec76be7c355697f54a93412544fa7.nq.gz
    ├── 21b295724aa769a49c3f7a1025dfe53e93e3f907.nq.gz
    ├── 23436375538722ccd2713ab0ebacee538556bed7.nq.gz
    ├── 253c450768dc10fa4d782ff8f680a9fcd9d3ce2e.nq.gz
    ├── 27ebb800d94ba6f9f273bad53ff852bdec9b2796.nq.gz
    ├── 2841123550b3752bbe7c5c9e9c8bd9ede9f0bdff.nq.gz
    ├── 28f680019c249b243144355e2a2553ff73737330.nq.gz
    ├── 2a7e0463a87f40a41183b353eefa7dfae37ef7b1.nq.gz
    ├── 2c272d6f0d12e94e3db1e7e297a3e26c716850db.nq.gz
    ├── 2ce3b4dba2b22ef8bcf7383f65be6beafde16457.nq.gz
    ├── 2d1a1719cf68d10bce66b8201245c8ad266d0c50.nq.gz
    ├── 2d6a00eb2e533ed7282214f1e4197404d799018c.nq.gz
    ├── 2d9d4c21a2c940f5f790bfbc70ed30a8e9fc87a9.nq.gz
    ├── 2e84b80cd7d1b6554030cceabddb4032f3faef86.nq.gz
    ├── 2eac895b2b2e4599ff25f53c662bd149eed394df.nq.gz
    ├── 2f6f9038a297553f1d41ccbe16398a6c753506d2.nq.gz
    ├── 30c12cb05abcb03b1b7392ef28ce05abf9c9fd67.nq.gz
    ├── 3183001d40462d0f35f8c2aea4e309bc565ea79a.nq.gz
    ├── 3229acb53026432ad4ddaec7158a1b78076a1119.nq.gz
    ├── 347a0e426b7ec9603fb2249b5c420bcca74b3026.nq.gz
    ├── 34c344317a12757c1096d299cab16c8418a3410f.nq.gz
    ├── 367de5a5b3f50b9fbf48eb56486b8f68ef930e22.nq.gz
    ├── 3750837f2e5ed40f400d2c5346fcaa8b3a236986.nq.gz
    ├── 37f9db4ed2eb665f63c44879e37beb765a366587.nq.gz
    ├── 3d032044fcd190972481d19acec37082ecd8a690.nq.gz
    ├── 3e5a78650965db9429ac0ff53b5bff7f532b8c97.nq.gz
    ├── 3e846cfb231f2a96a4004df7942131b205854a7d.nq.gz
    ├── 3eca74ee2f079d5e1bded1d97a2383359dd103c4.nq.gz
    ├── 3ed0ba471bcb73f9827eeffc2e738f324eb77a13.nq.gz
    ├── 3f953cbdbdd09b839ac594f4fe67afd8f65daa1b.nq.gz
    ├── 40b814c218725200014efa27d79903988d164a71.nq.gz
    ├── 40d91f6dfe8b9a01f29a5a61e6ce91dd171fda3b.nq.gz
    ├── 4129633e63b999dc53902c423a7ccc2acae44adb.nq.gz
    ├── 4165a760350fea42095086af1b9b79a7d2b09104.nq.gz
    ├── 430dbbe4daf5abc24498bf8ec0f845a38d1db41a.nq.gz
    ├── 437ed84dd49305a87972b4a512f7225740fb3cd0.nq.gz
    ├── 441756fdb2c80ac8c2d280ca020dcff8092621c0.nq.gz
    ├── 44406153d698b80f86013897687f25171aa6ca68.nq.gz
    ├── 44b0d27c08952bcf507d01558ee469408c8d9abe.nq.gz
    ├── 4527c6a8adeca807f21c459c7098b0368d9aa36a.nq.gz
    ├── 4650b8556a34e7f4bb1febb904bd193c4ceaf616.nq.gz
    ├── 46dd458a87349ff40c1fe4834e5f2d9f63906853.nq.gz
    ├── 46f2706faa9aacd7f0d53571353639b17dc42509.nq.gz
    ├── 4928ff3364b2a686e6270a6ce4f57dcf793ca57b.nq.gz
    ├── 49ff9fd556fc94610f8206689d0c0e58fae1b16d.nq.gz
    ├── 4a1ba649d644c837bb1f9e0d1ea4968feb2407ba.nq.gz
    ├── 4b7a167e1fd7d4eb50f5ef63b008b0ef737bccf0.nq.gz
    ├── 4c23bb3352bcf103ad801aa563aa6cf224079d7d.nq.gz
    ├── 4c28eb29881ad2aa52bbe06b88018931b9af2afd.nq.gz
    ├── 4ce388e73a2839c4db0ed991a50c690bc6ee1714.nq.gz
    ├── 4d40dc9597147e26aed14dcea8c699e64d83d319.nq.gz
    ├── 4deff7f05b337808fbb72b103b72878ac2c55657.nq.gz
    ├── 5030925b6b89ed3a097472992444bda628236bab.nq.gz
    ├── 50ebab8925b4d8657338d3eb315af38d327be127.nq.gz
    ├── 517ccbdc77308816a160217b1704320835f7d5c6.nq.gz
    ├── 52512d33376cd14ff7809e007bd2685bfa2d141b.nq.gz
    ├── 5440913fd4bc8760e3cdb3a61855d87f5f41b859.nq.gz
    ├── 558d96a7739f08fddb35d09bb58ab0cb151fb68a.nq.gz
    ├── 55a00c205969126fa58a7dd4285fc3f693dfcfc8.nq.gz
    ├── 56c9684b8c2dd477e4986e82a37b18f0c857fba9.nq.gz
    ├── 57431f0c74c0e3722ff5eaace95f501e14eee90d.nq.gz
    ├── 57ac2ecdd44492e75a72205d1165f19ce1bdb56f.nq.gz
    ├── 58696082ecd88316b0d0267311dd76c91f73b4d6.nq.gz
    ├── 5a3633bbd33f2bf2a863e65d9ae68e977031a865.nq.gz
    ├── 5a46b8a3e955250f8dc989a5492f94d9c02e8358.nq.gz
    ├── 5cd9d4724610f1de890164dacce9796638bf09cb.nq.gz
    ├── 5cde0202dcf357bdc706ddaddb2b07a9fe49fffa.nq.gz
    ├── 5d503c214011cedf84671b65a100504ad3939143.nq.gz
    ├── 5f99eccb5467523e700ab1679fa98d3d9082e1d1.nq.gz
    ├── 5fed6db44e0c72be8277c2f6b22d336ac3b2970e.nq.gz
    ├── 607e204698222e8e81168dba33ea81b6a1cde6d8.nq.gz
    ├── 60d68102bac20070456fb5180a47b2bceaaa424f.nq.gz
    ├── 61ceb5b58318b09872b74564ca203b3b24fbeb8c.nq.gz
    ├── 61fd58d7127e54bcf1339100dddbc6a937281031.nq.gz
    ├── 626c4802d768686dbfdd80c87d8392a001bf9dc8.nq.gz
    ├── 6319356307b3dc59dd7fa5852bf981a8b2dc642f.nq.gz
    ├── 63cb36c9feda99b84421d6f2db9533ff4fd008ff.nq.gz
    ├── 64f580e891d1bbaec0640b5fe6df7b295a42cfbb.nq.gz
    ├── 652f233db045860e109ccd14b6fcebee6ea69a1e.nq.gz
    ├── 65769469799c4d76b14873d8a2ca1f890006ae60.nq.gz
    ├── 6577fb807e042ea1bfc2c29bcb0d607e7e0a2d0a.nq.gz
    ├── 658a9ac5e60d56f5fd6cffded2caf857e72ba3b2.nq.gz
    ├── 694d74c673ae7da2f5af7350fe3146fbd80b60e8.nq.gz
    ├── 69a37c3351e9d13210a286036038cf21ccac1763.nq.gz
    ├── 69f4e8ce4dc1f27f51bdabd76c34cd718cff2fd0.nq.gz
    ├── 6a5618b59ac9749caff7271b7989d17f94e01c65.nq.gz
    ├── 6a9cf5a4fef189c619a70b7a6d182027b02c5bb7.nq.gz
    ├── 6b392fa7753a600035f09d5c0efdc4e7fdbf769b.nq.gz
    ├── 6f3b6d6b52ca5d5ee0f6f9ca0768c206904f3754.nq.gz
    ├── 6f850a60cba321de59f940ea48995e15c7978048.nq.gz
    ├── 6f915268b00b513bf365543ef89ad30ec49115ce.nq.gz
    ├── 705d6f1ba4d2747b048f13a221669f1a619d3198.nq.gz
    ├── 70816b99fc7a36d9f20fecf9436eb38b67957d5b.nq.gz
    ├── 72a40f06c594edfb005e6d9c7a7c6c6e7bd07647.nq.gz
    ├── 72bc8d1b5a7cada0b321c19f740eba55afc10d7b.nq.gz
    ├── 730e5a3382ebb716c5bbd9159041430efea45a8c.nq.gz
    ├── 731479b11f7198a38b316908f1b42295c0ab7b14.nq.gz
    ├── 73e720ce7f7baa301b11f55764b1749669562e41.nq.gz
    ├── 74928d6a47412470035107d1633d0a2ca410833b.nq.gz
    ├── 750bd75b9d71ead494d4d2f1441d9090feb680be.nq.gz
    ├── 75f557df64af15e8bf0d091d0a5253f84a7afe9e.nq.gz
    ├── 764e73e8670fbdbf5fbd4f26982407fff8b32ab8.nq.gz
    ├── 773ec7a5c81b6e5c8093144d889c3ac40c6e5cd7.nq.gz
    ├── 77f9f91155dd9c7a3cf6e0aa4f0af5fd47ca4e2c.nq.gz
    ├── 78c91565a0f6ae4cdab0c2e229c062754e19d784.nq.gz
    ├── 79703264b627f44906a9b88f34edb4a8d1ee203c.nq.gz
    ├── 798bc1318714dc340173290c883e575677ec73c8.nq.gz
    ├── 7a97f27391f637d48c9cd3c4d09114d0e21ea975.nq.gz
    ├── 7b9b8fd2577cb1cb017fa1f13e23505efd2ba2c4.nq.gz
    ├── 7c298540b251fb289bb058180dcdbfa90d340f08.nq.gz
    ├── 7d024cc6d39bdc20fcd768de0ae6bd57a84af11e.nq.gz
    ├── 7df774b8fcf8b95f347fc601a6840149d8944f6e.nq.gz
    ├── 7e48bb6f1f1067df47dadc5b89888d9aa99ff291.nq.gz
    ├── 7e79818a6adb1bbf5b5c42e9517217d598e73af8.nq.gz
    ├── 7ed9b71fb0878d40e257b2264dd4d75f17496bf2.nq.gz
    ├── 7f0de68522c86c6238a5233750530012db213a80.nq.gz
    ├── 7f1761209a441984a979ea6cd2c76e40d9877017.nq.gz
    ├── 7fbec2afbd4bb0ea0b3aafd3bfea93ea951fce2a.nq.gz
    ├── 7fecafcdbd51eee7de9ecbb8771d3693e651d93c.nq.gz
    ├── 807e9939d931ed674aba4364ac3d611dee486298.nq.gz
    ├── 8100102317ba4a6fc84519ef2ba68318fddeec93.nq.gz
    ├── 81605a8a65ed7f9cdae1a5aad58a8f57817b6886.nq.gz
    ├── 8195fb3718f831109a19dc5c11fd8d9feabc4196.nq.gz
    ├── 81a94dbb3ffd68bb03a1edac0fdceb29b1057a4b.nq.gz
    ├── 820d0695a9d2ab9fcf8a699bd27e7e8262d92768.nq.gz
    ├── 833beebafbe68a8e2b86eff1ebdf389978515934.nq.gz
    ├── 836c2a6235a1bba128b84435c3be0f98a835ed36.nq.gz
    ├── 83a6f2d56f755b33dd3cf11152a70904e179a927.nq.gz
    ├── 83ff5d98346eb72376f5fff38f54abd084473e40.nq.gz
    ├── 84d0da0ae2320dca16f35289e61ced5458babdd5.nq.gz
    ├── 8513edd8cc772d1a7ff9f7205904f9a418b0d476.nq.gz
    ├── 8517e61fa0c3622a0ccecd25162928c656361a06.nq.gz
    ├── 852d1258e6961e737fdd45ad5a55049b3680f6fb.nq.gz
    ├── 85ddbb1c831a0dcb265a3a9296a4754e1745a586.nq.gz
    ├── 86b2043ffae761e57e82fc5ca219e4356ef7fd35.nq.gz
    ├── 875c2803f9315098a3b37911c3f54b14d51feeed.nq.gz
    ├── 878024e326664df1b10d0defaa3967229677235c.nq.gz
    ├── 88c9afd93593fe09aed01d7afaf5181be35a1f2a.nq.gz
    ├── 8a6fe47497d6991a88444b3615409d87480ffdfe.nq.gz
    ├── 8aca37eddffc55d92563adeb9fac0dbbce2fd630.nq.gz
    ├── 8e2e7c08f526ae2cfc4b75e2145de70b906e69e2.nq.gz
    ├── 8ecb49bb659ef87d01e5eaaf729d6338b31e1742.nq.gz
    ├── 8f0e0b5e6cdde5732892e684cb4016d8d07494d6.nq.gz
    └── 8f26e2fd4defaa11f84c8234bea6e563ee3e0b1d.nq.gz

7 directories, 200 files
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

[cohere-ai/cohere-python](https://github.com/cohere-ai/cohere-python)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
