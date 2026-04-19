# Repolex Knowledge Graph of webpack-contrib/sass-loader

RDF knowledge graph data for [webpack-contrib/sass-loader](https://github.com/webpack-contrib/sass-loader), parsed by [repolex](https://repolex.ai).

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
lexq download webpack-contrib/sass-loader
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 694c8d92abf8e30f934810878281c7b227eb32a8
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 694c8d92abf8e30f934810878281c7b227eb32a8.nq.gz
│   └── repolex
│       └── 694c8d92abf8e30f934810878281c7b227eb32a8
│           └── chunk-001.nq.gz
└── blob
    ├── 0067df18bfd0f27810a6c62a003c318016617dab.nq.gz
    ├── 0082a21d78329ced1a9c214fd1915d642aeffaaf.nq.gz
    ├── 00d2826726c977ca8e4fa6471a60c3bbbe58caed.nq.gz
    ├── 012359f8ab1ab6c787cf42a6f8e193a7186fc8be.nq.gz
    ├── 015545580052e7fac456ec02fd0093dadae6704c.nq.gz
    ├── 0175ea5d4ddad8d58bb83813ca209638545227be.nq.gz
    ├── 0314d47b93f2970be4e07d34951f97cf100e95ec.nq.gz
    ├── 033ddb1657512f2f3f9a81bc7d5df32b60350e1f.nq.gz
    ├── 03597d36d3e486d35676c1b04f7ace272d702129.nq.gz
    ├── 03684d3a267ca6421734a755b006608061073c32.nq.gz
    ├── 05ae32fe3a4fc3f9d9b2c5192180416db750ca7b.nq.gz
    ├── 06a4f4e2a4ae679175f6d65a1744a05ebfd094a2.nq.gz
    ├── 08aed129929dfbcf4d1da94ea88d3c8bb36eb9d0.nq.gz
    ├── 093439b35f19feac65d741b11936d66c12a3367a.nq.gz
    ├── 098b359cab53a07b7da3a88ba5387932a333516a.nq.gz
    ├── 0b009832dbf6aab9e02fbe2bf9e3ee7568311f0d.nq.gz
    ├── 0f0934c4c20a9d1539cfc6ffe7c6dedc3ce38f52.nq.gz
    ├── 0ff1ed16a71801fa11e394191f660035e6150920.nq.gz
    ├── 0ffb6d83a2ced8a03def8073b36dd592b8fb9e05.nq.gz
    ├── 1057d056bf02d40cdab414505c14a93e5ff586be.nq.gz
    ├── 10b47500eccf519385960b6829fbbb4131f3d59d.nq.gz
    ├── 118d1715e241a2638231b5b97ebfdd43773a9d8c.nq.gz
    ├── 11948be3719bc67cc62e8248ddbcb5f2520f4e13.nq.gz
    ├── 11a45836c09333e62ef2c6b4faf7d8c9370a4dc9.nq.gz
    ├── 136270ff0e0abd398dd30ee0f223e7b9d3eb564d.nq.gz
    ├── 142062d90187a7b9c54d2b64fc8fc4df920b9c1e.nq.gz
    ├── 1467a9f7472a80066a7305331e42bbe233a41508.nq.gz
    ├── 14b644c6e2213c36c50228af948e6dc9cec13f65.nq.gz
    ├── 15b70814f134701308c618f5c8e5461adff758fa.nq.gz
    ├── 15c13ea96af9b1fccd0a25a450f6452a66fe6bdb.nq.gz
    ├── 15c710df7cd79f5de39bc32b6a1e41ffb0007153.nq.gz
    ├── 16e900542f51bcf49ead7a9d872e2ae0242c788e.nq.gz
    ├── 1800b4a6d2ba20985cfee547b34b6ffe7d9c100e.nq.gz
    ├── 18b2148d1664357ff860fb1ca99413dc38165cc4.nq.gz
    ├── 19949c42077d6c2e6edce72b0af55f38b2257d0f.nq.gz
    ├── 1a9bccf907dedead1a5971f2771a46bcbf87a980.nq.gz
    ├── 1aa2ee99285aea54aec3364801718800f12ae5ff.nq.gz
    ├── 1b0285de3e96a501aae7d2eaeef7fcb190d31c85.nq.gz
    ├── 1b36c58afad83d5eeec14c79dccb57ee9c3bff63.nq.gz
    ├── 1c8a9cb621f12cdb70815eeb3f45d329b34fd313.nq.gz
    ├── 1ce4f669dd7ef919f6928aaeb89612309e8f8a14.nq.gz
    ├── 1dacdef4d9d811ef069f05738ff5041ac0698dd7.nq.gz
    ├── 1db83145aeb1699f94fd1dced634a395505710c0.nq.gz
    ├── 1dc95977c1bbfa451b62320b662eac0e9a2e63a0.nq.gz
    ├── 1e5cda77586aee6b97bdf36429aa49d04d97a644.nq.gz
    ├── 1ebd9891de8e4b0ba817c07f9af46db9dfbdf26b.nq.gz
    ├── 1f0b47c5301f746e515c06dcf32870ed46d9ad6f.nq.gz
    ├── 1f7c60bed966c6431f0b0484ea14ad21422ad88d.nq.gz
    ├── 20299e3b09d4c31422fb87dd157ddb10d7994e9f.nq.gz
    ├── 217aba54403b26d371ac37cd0b37719750e7ca66.nq.gz
    ├── 2190cfacfe1e1de5412c7aa429c64fc6224cd801.nq.gz
    ├── 21aaefe0ac033b37c8714bd19692c37b24ba9b53.nq.gz
    ├── 21ae34d4ebb9640f3f78827e91f007f4d73d0727.nq.gz
    ├── 21ea86d01611223afda7924e43f78dfafb0650ab.nq.gz
    ├── 220c0e5c385a998d74d1a2dce121c712ce0a22a7.nq.gz
    ├── 226bc7e1f8c1e3c7997c1d399eb3f9abeec4459b.nq.gz
    ├── 22f8b4e1c62ee93a1b3901e310cb6b67dcb43826.nq.gz
    ├── 23d68a8ac86ae5f572dec11bdc8d26f541302370.nq.gz
    ├── 24762db2e6d75a174a5cce9d08a9c19d703fa224.nq.gz
    ├── 2491b435105cdd2403bf32b91f27dfcd771cc35d.nq.gz
    ├── 25209b1382aeefbc7abb1736ac3da9bd1b1524cc.nq.gz
    ├── 257b5c40d9e4549e30cd34c090431a2731a228ae.nq.gz
    ├── 258ea2e3ee7d9b4a5dc948429bc0c33cd1d36e58.nq.gz
    ├── 2740909ad3a295b03ad839eb5a6b5a2b50a0d6b9.nq.gz
    ├── 279069b42fd4904d664ad8a24ea28d0c8452bc18.nq.gz
    ├── 27dad19f18110a42bf4eed8f8a87b0ad379e003c.nq.gz
    ├── 2982a7641643980997ef682810659178f9f5e803.nq.gz
    ├── 2a9fd83a304b2ddccb900aac943dbd81e5e14d7d.nq.gz
    ├── 2adacedf3037cfdade431234069f069bce9afdee.nq.gz
    ├── 2ae69c8644f752cba97f57bb2f524d45950b04a0.nq.gz
    ├── 2b2c4b492051df4b23981d56270b6e12fb79f251.nq.gz
    ├── 2b3753c17bdbaffe3926cab081bbf931b898edc7.nq.gz
    ├── 2cf396ac60d79d122ff099ce06b8271d9f3eb6e7.nq.gz
    ├── 2d92bb99339fddf69b656aa167801cb9c6e75d77.nq.gz
    ├── 2f3677c02edf06a74e4cc8679738cebd1279dd9a.nq.gz
    ├── 2f3a379aa17890899e2270cfe218c26c1cf177b8.nq.gz
    ├── 3010843382c225130f37f367ecf3e3b76e3de587.nq.gz
    ├── 304e06995cc7266a8226c6d83c3469953127cd3e.nq.gz
    ├── 307528db6522622365e06f43b9b6fc4dfb7fad90.nq.gz
    ├── 30efe9caf5f5d9e97a16f36f2d05f36234a29b5b.nq.gz
    ├── 3200bf43c5fae1f4ae44243aaff24468875b74ea.nq.gz
    ├── 32a5f5cf1da4089c35696a1cc7af94f80854821d.nq.gz
    ├── 337cf747802d90e552f7188f6555ad9c106c2796.nq.gz
    ├── 33dc9072cad3be55512cb7b8795b3f4f72699ecd.nq.gz
    ├── 33fc14af743a4d4afeeed562459b017e0b1b8325.nq.gz
    ├── 34300903e2b82322280ec535d50d3b3d337712cd.nq.gz
    ├── 343d1ef8353f34e3e650ff17292629541c2dd7e1.nq.gz
    ├── 35c06b47f21eb106e2bd99ecbe9a66ab4a233168.nq.gz
    ├── 3608df72b1c6c57d4256c93e57306dae3dd2f4a2.nq.gz
    ├── 38f76fed55a869612c6806c482dbf259d7738173.nq.gz
    ├── 392473965549720cbb886187f56a73138d27e368.nq.gz
    ├── 39f4a79845cc240f84aa8408f4faf5c681513bdf.nq.gz
    ├── 3a7422172c3d87ee2fe8229ccd331611b3abdb6f.nq.gz
    ├── 3a7f6c3d981f84abe34709bfdfd9783b975d7050.nq.gz
    ├── 3b5ba5be90e0400a53a1315d4f27acb3904584cf.nq.gz
    ├── 3c4ee8447f53cce3c983629042cf17f8c0b7e195.nq.gz
    ├── 3c895cd88bc2ba1e9f91a0fc25ab4edc35f7d8a6.nq.gz
    ├── 3cc6baeaaea9f32910ee83b7f546b4190609a444.nq.gz
    ├── 3d5fa7325883ae8cb5373d031c5685efb8cbca59.nq.gz
    ├── 3ed568b1177766a4b61b75eb53524d01d072e8ff.nq.gz
    ├── 3f38808da296eeb3ce71b9dcabe81ed2fcc86ce0.nq.gz
    ├── 40088665d2810f9807a3ecb1e3e51623b1672298.nq.gz
    ├── 401661b4972fbb78da75a9529f6f3c6504ac2e0f.nq.gz
    ├── 42fd960af57c45d3e10007af4b9687c35f7dd090.nq.gz
    ├── 430c2156ace2ef276626b03158dd86657e49fac1.nq.gz
    ├── 431a9cc1760fd8b9a82fb807f585ff6b7ce4f084.nq.gz
    ├── 4376d14f69ceade2958e024bd948064987f45b05.nq.gz
    ├── 43af6eea930c1253de8a9a2d9ad0c8bbcb8d0163.nq.gz
    ├── 44a268e1dfdd9add26d371a645e672b21ac84546.nq.gz
    ├── 453eede2e019b6bb1166854fc4fa0564e5f158fa.nq.gz
    ├── 45820a11fc7588ea862027d6cec2bcd06f96c5e8.nq.gz
    ├── 47ab276cdab41d0b90ab30571f7645b39e22cbc9.nq.gz
    ├── 47e4a109f636d0f60d12dcf558280b48256b0498.nq.gz
    ├── 4823f286a58eb6bbfad08b09d1eabbf1edb52417.nq.gz
    ├── 49c76b1d535970b3fe5355d784169d48e12ac289.nq.gz
    ├── 4ad5620fe90e0e0951bb31697cc68deb9d44cb11.nq.gz
    ├── 4af889ac801cdf80c6ab76d6a99474f26b2c072a.nq.gz
    ├── 4c12f53283e5eed8cc6d858f6710f063023ae354.nq.gz
    ├── 4c27ba811440e9c4b0e1cb00172d798a8bc64f20.nq.gz
    ├── 4c64074df0506b01c26d50697d3d8461ac5a3b10.nq.gz
    ├── 4cf28ef95cb8cda5de3a2aeb8b77a5864dea6bb2.nq.gz
    ├── 4f76deec334b6a7b053a4fd421a1f219b466ff3a.nq.gz
    ├── 50043c9963097f6eb3b3da946720e825af909f5e.nq.gz
    ├── 500f80510722d685a51a22e9c600d9f689b0535c.nq.gz
    ├── 5049673a7c93de82c0567dd9d54baf344d6736be.nq.gz
    ├── 50a3bdc8dbaae130b91982ecf178c25fde20702f.nq.gz
    ├── 5141075bc6e04160563daf9f1cbd39d2f8f80026.nq.gz
    ├── 51c22230cd422b1099ed1329b548db5bf4a94a9f.nq.gz
    ├── 51ca4a6d9127aab308ced3f5381803ca68619256.nq.gz
    ├── 527660940bc45d09a0dad54c7d6d889ab95778a9.nq.gz
    ├── 52c0ec8185e8e3958107c37ffae667d8c9f61dae.nq.gz
    ├── 5421c31e4174d30248138055691b6cde661d44ca.nq.gz
    ├── 54a7e03ed3f525f4b15595c5e63abd8583da7f62.nq.gz
    ├── 565c7e891a01837f1a5f87eb36e20e757b9c3803.nq.gz
    ├── 571845c72cbc0be83de45be99fcbd16f2d3c17d0.nq.gz
    ├── 57332724195259fbc1f8d0d31f6a4e1e188eb86b.nq.gz
    ├── 579f125ca0f88dda59572201b8be247297c080b5.nq.gz
    ├── 57daa35d489b6a7fe72bd1a5023138219cf2c353.nq.gz
    ├── 59388567f746b1a003f95cdcd570a01eb18b6017.nq.gz
    ├── 595b32bb028362df089a76de1e9ae3f0d3e29abd.nq.gz
    ├── 59ec92a46a846232a1584ca4ee5ec177599c7f4b.nq.gz
    ├── 5ba5db151bdc27ab128fa2639388a4eb76ce1a73.nq.gz
    ├── 5d0650b88a44a4a0a5ca278a5758f246feb0cfb0.nq.gz
    ├── 5e100a07ded8d3b1f7644fc6765321972b36d5f6.nq.gz
    ├── 5f08cafc7976b7bd495b630b7d7bc1ba054325fb.nq.gz
    ├── 5f4dc6e3e3ad9fa66a3dea6ee928cba9d9f22021.nq.gz
    ├── 5f59a758c58ce2956ea0e61bc1c36096997138f1.nq.gz
    ├── 5f7952820781fd0eb6556e4bfd7a00ffcab1656c.nq.gz
    ├── 60050f4017a631d7836a5f62a0aafc6404ff79bb.nq.gz
    ├── 6011ec207ece0c014a85815e4431c99d265de0e4.nq.gz
    ├── 601c2fe9e39d8ce41b9fad4bc7b852d0ccd23c1f.nq.gz
    ├── 618abcb015894c48cd357a94419bf2ee6114b549.nq.gz
    ├── 63c1e1f67a74c52e80862bb8f677baffab094b5b.nq.gz
    ├── 64aab54a25851fc97a6883d06df86a18f94e1aaa.nq.gz
    ├── 66ff52958c747b8f5293ef0c24f5ee4172f2da2b.nq.gz
    ├── 677ee792232584aae7f328d7e0695e05e740732a.nq.gz
    ├── 67cfdc7e823403266fff1728076ba4ac03c7354c.nq.gz
    ├── 6800b2f98e86067a6d0f37cf73a06aff6a5ebff9.nq.gz
    ├── 68f1f608c365600fd6b15c3af9472f6d063305a0.nq.gz
    ├── 68f5d397596189a6c4910b922f50da4bf6e3ccff.nq.gz
    ├── 69231895a247f4186d1fd7758310700dfd251f8b.nq.gz
    ├── 69bce7ec9eecce59bf56e5152e4d787028623138.nq.gz
    ├── 69c5ce54f664d2dbed44ff23839fca06ad384475.nq.gz
    ├── 69e4d2365a51079295f7b05a0defbffdc4d50c71.nq.gz
    ├── 6a9a21fb257d38a5b4c8a45b54e67920a6c9c24e.nq.gz
    ├── 6ac53f20bd7185987f82460c56b6e0ccca5cde57.nq.gz
    ├── 6b5e961b59968b5912de497641306dc16f86ce48.nq.gz
    ├── 6ca84f4140fcd129f31e4916f17825f9cf7a5ab1.nq.gz
    ├── 6cdd35562060ae008320b128ba75b1679d3dfc97.nq.gz
    ├── 6d2e1cddb990823dd566dadece93eb5fe7e34abb.nq.gz
    ├── 6d98593ff78b1a1cef762ee3e6103aa20946c243.nq.gz
    ├── 6db6c89863ffac068cef92bef95b94441aa553ff.nq.gz
    ├── 6e364a000acf60e618421a19cfc166e955df1887.nq.gz
    ├── 70364abbb03d91a24d12f1366c4c640166293217.nq.gz
    ├── 70524e4c06cd8ae4e40d4f71c005d555b0d0e1aa.nq.gz
    ├── 7337418ebeed0e15b3732071feff2e06b80d67a6.nq.gz
    ├── 737e5b3c3357a96b69e30db1d27574b36c349919.nq.gz
    ├── 738d6ade29caa3faaf7c70fae8123b151526bc8f.nq.gz
    ├── 7422b1d78aa479602affa8673ac5e3b8d3fa6c71.nq.gz
    ├── 74e757108cf23709790e336203d3ecf25e4bb6ee.nq.gz
    ├── 7503b2cf00b4814b61d9e7981e5967f6b751d50e.nq.gz
    ├── 750cb7ba0917565649b1e9353e3388d6920aaea2.nq.gz
    ├── 752d87b1c6f6693c10c5a1a0f425fd61b4db04c3.nq.gz
    ├── 759132aacbe12da107f30b38baa763a042b443a8.nq.gz
    ├── 760641b3b6036c46c0cf7281a580b461b1098cf5.nq.gz
    ├── 768b20a34caaf9b21261830cf8d8c57a6f72d49a.nq.gz
    ├── 76c97ef2118c613002db914ae0c7c3a958f859c0.nq.gz
    ├── 7861befdf58cb2d060a0a3305e94c193b5e83c68.nq.gz
    ├── 78bdf88329477a4876db71cf642a88fe33c630a0.nq.gz
    ├── 78ecc47841f035676a3e73e571fca0aece4fd5de.nq.gz
    ├── 79f8ad787f902b0547f5743a51fac4715ffd2ca9.nq.gz
    ├── 7a621615e8230d0944c0bccb1ffe4befa5b5f2e0.nq.gz
    ├── 7b8f6af7c290133335f94bffcd25f0bf34f91ad9.nq.gz
    ├── 7d2e86df771081110cf0371eaec6bb941cc4e298.nq.gz
    ├── 7d5dde9968e16a4269ee70d17812534df38dd6a2.nq.gz
    ├── 7dacff3141fde7f45f4e712413fd9ddaf373d9f6.nq.gz
    └── 7de4a4db3afd5461db99a6c80a7a74fcdce6fb4d.nq.gz

8 directories, 200 files
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

[webpack-contrib/sass-loader](https://github.com/webpack-contrib/sass-loader)

---
*Parsed on 2026-04-19 by [repolex](https://repolex.ai)*
