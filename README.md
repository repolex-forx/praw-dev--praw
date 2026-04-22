# Repolex Knowledge Graph of praw-dev/praw

RDF knowledge graph data for [praw-dev/praw](https://github.com/praw-dev/praw), parsed by [repolex](https://repolex.ai).

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
lexq download praw-dev/praw
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ac922d9d68b80fbc0660b269c733d63ca5325ea2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ac922d9d68b80fbc0660b269c733d63ca5325ea2.nq.gz
│   └── repolex
│       └── ac922d9d68b80fbc0660b269c733d63ca5325ea2
│           └── chunk-001.nq.gz
└── blob
    ├── 008d86ef1d9527b4dc6bc5f473c4337e0a0f5599.nq.gz
    ├── 009ffa3710d162cd34641ec52245a63ff85896f5.nq.gz
    ├── 011bcf35d9863f20046646eed4ed7e7c4eeb7af4.nq.gz
    ├── 014d217e61d539977c44473e5967c3da6f26e2b9.nq.gz
    ├── 01940ec4c1919fbe442ee782f530cf42c985d816.nq.gz
    ├── 02a84de8c8d4247c85c96c02d861312933d4ee30.nq.gz
    ├── 03d87afbee49932c109df9b75ced740ce2348480.nq.gz
    ├── 03f87d03af02326fa29139ba7d7b061e1b646fa4.nq.gz
    ├── 059746be530af4807dbc12cf8f697e5198479f9e.nq.gz
    ├── 05dc07289f2b34cfb0d1303cc79d4e1c1f869904.nq.gz
    ├── 05ef6bee404f4febbccd299a33e0dd7e61abb5bb.nq.gz
    ├── 06d185621da621575a66effbb2950c54a5e33bb5.nq.gz
    ├── 0730d478e64de92365c7ea44ce41209a0f1e7c77.nq.gz
    ├── 086e2a953f80798b57d04fc61773fb6cbdf8fd19.nq.gz
    ├── 08c89da3c0bb64b06fa6fbd00fadcf1335bac5be.nq.gz
    ├── 09006c0b9061f16485292446efcaeb7c58f1e409.nq.gz
    ├── 090ca1f555d1c5f0e0d098119609806d17677c6b.nq.gz
    ├── 09641723578eef97aec29b3f80390f03d8794f0c.nq.gz
    ├── 09ca527837bcfe7d369ea32f02c213cedffea13b.nq.gz
    ├── 0ab3fb20d95ad12c4da1cb539fa1ddf2c1f81528.nq.gz
    ├── 0aba0f52e97fc5f8aafdba2d10b6e5dedaff00de.nq.gz
    ├── 0ae2f86bf127229ea936cce43dbf702a140763f6.nq.gz
    ├── 0affa06401b1cc17e4a755dcb9ce1ecc3a649e04.nq.gz
    ├── 0b8e4dc52fb3fb2abb425b3b5f852a459e1e6419.nq.gz
    ├── 0be84041a4ae0eba705f072c8e83b841d40e277c.nq.gz
    ├── 0c6b1756df5d21e92123b156e7fc88109169b9d0.nq.gz
    ├── 0c77c8ae79e0e742b27b5b39c5aea89a4cd9c52e.nq.gz
    ├── 0d3838014c04a1a9cc1bb4d2e362618ba6188a16.nq.gz
    ├── 0d43d2e2c1620038c3789f148abc2d3d22267186.nq.gz
    ├── 0d6664b32102092640b88fc478f2f338ede91f7c.nq.gz
    ├── 0dc1cbb7cb4f61ab17f467d4352c6008cd92047c.nq.gz
    ├── 0dc277479c237c5dbb39124be490eaa37356bb34.nq.gz
    ├── 0defe898b7747007ce90bcddf116c012c2fd35b8.nq.gz
    ├── 0e1105667e5db07c3879d87c7cb356cfdcc8fe41.nq.gz
    ├── 0fd3b00f7f8a5259b6559ee1809351cd4c6851b8.nq.gz
    ├── 0fe27500f2a2e416adf6df4a7737185574cf03e6.nq.gz
    ├── 0fe476642aed89b43f8b199438d85a6bb10ca128.nq.gz
    ├── 102ad8f6ee47638c702efb2fb6fefc995989be8f.nq.gz
    ├── 10ae5a6c5c331134af5017ec3c036499d04ee6b7.nq.gz
    ├── 1112e1f8d1e6344d98e41a6b03e324412d63d982.nq.gz
    ├── 11da918dde3d59520d547b3c416a5d545cce843d.nq.gz
    ├── 11f162c09e9acf49b4b87c8e69640c9beeef23f9.nq.gz
    ├── 120a46e37dc1a337cf39bc4c92538aabf2e4116b.nq.gz
    ├── 12424c3ff8a0ece9781046a3a3473fff5e108b94.nq.gz
    ├── 12764bbc719b41cf4d4e383dc3c021b9cb61c75c.nq.gz
    ├── 12de90979214bb7da1be3eff9fde1fbacc534419.nq.gz
    ├── 13245df89a88750fc567a2389b63506fe930900e.nq.gz
    ├── 14afea4d93259f52df51c79a2818a18b99ab7cc7.nq.gz
    ├── 15df772f0fddecdd935c605de558c034b94b21ea.nq.gz
    ├── 15e396682d68de1c916c637191b1fd42d5dbf46b.nq.gz
    ├── 15eaf05675456340937bd56d7d595142f44c77eb.nq.gz
    ├── 16b6dff071a8d54c6bfd4e2d571cc90b7f021233.nq.gz
    ├── 179581c015a3fc1cb2a23e100520bf4a460e66c3.nq.gz
    ├── 1797addaa7c52bd4af8333e7472adfd7c2b5b091.nq.gz
    ├── 17de634121d5e7e93df10dd26eaa19f3f314fe2a.nq.gz
    ├── 186ddc085d1fc79a8ca9f2ab12edb63b7bb38f6c.nq.gz
    ├── 18b5d3dab159fafbf4a8027a5bfc89d0f9a9dab9.nq.gz
    ├── 19952965bbf7b8da7076cf84f50141e1f97141a6.nq.gz
    ├── 1b35efe285ff4a26c08004a870112788afec4adf.nq.gz
    ├── 1bd548ef8fc4167d5c62168d9e8eae65b50b2c87.nq.gz
    ├── 1bdf75fb9d1388a1a4753ceab153cc91b522ef91.nq.gz
    ├── 1cfe7652af2d0f40e36a614c2a2d56465e39693d.nq.gz
    ├── 1dd567d46ed7a229900005e1a2a8cdffbae5f658.nq.gz
    ├── 1e2e3ffb712dbf58acaf315fbf566a28a23b0a45.nq.gz
    ├── 1e326fc506e99044ca4bef24a3c7816abad01bb6.nq.gz
    ├── 1e49af5dc9211c38c0999be47eed8a5513035f40.nq.gz
    ├── 1e75d6fac40de06bceb2b3224b25e5e9667aaa8e.nq.gz
    ├── 1f1b3d1b3063c796ea95c75a0b101c9378f7213f.nq.gz
    ├── 1f6e22f09d8b139ee2392ff78322c94ed1bfcd83.nq.gz
    ├── 1f788c1de937f5ff5937808f2f97e4193a62de03.nq.gz
    ├── 1fc1e3faba782101c0b8a00473ac7406e2815c53.nq.gz
    ├── 1fc6422e135a849b44a84a78ceb52162c01fb4f7.nq.gz
    ├── 1fe44975d4f82cbac8f9effc9cae7d7cb914d0bb.nq.gz
    ├── 1ff9fae54c5c0a47206e7fafc417b4a08227dec1.nq.gz
    ├── 206a57a1f5c95e678a0f0956855658ac6a82ebd9.nq.gz
    ├── 215c906da4b46d5f3d0002d76abacd40490c6e5a.nq.gz
    ├── 22016ee4a1afa6c1ddd4ecbfc2dece911e1afe7e.nq.gz
    ├── 2235da9c1ff0289211d7d35463c55fa0904bd943.nq.gz
    ├── 226ca4991856da053529cc71eb1de267b79def8d.nq.gz
    ├── 2281777aa1147adba38244be993758c848c0bda2.nq.gz
    ├── 22fe67431da38e052c22f069cc366e344b01e0bf.nq.gz
    ├── 238539d3bbddc72b7a8a2e9646e8d06b5c1de3e9.nq.gz
    ├── 23c388ac360677d1cb7be28e40d17410d49486e2.nq.gz
    ├── 23e78b0719de6f4dd2ef83cc5982029b5d792bb3.nq.gz
    ├── 240820a908423b228c034cb990e1ed6c5ebe2b83.nq.gz
    ├── 2658c5ab6dd9482f701eb1df2f18651274620f77.nq.gz
    ├── 2699cb8d198220ae2103dada736f749614cfac6f.nq.gz
    ├── 26ac4af7263f60c9b8e62032a1edb044f8bd239a.nq.gz
    ├── 27ee6777cc689638332526b812ba9985393681ff.nq.gz
    ├── 285f28f14c4a37075bf93215e74d41240d2d275f.nq.gz
    ├── 28948b03be9e84f2a2e6685a2502d7457e816aa4.nq.gz
    ├── 28e5276cf001b65c790127ce5caeecb7b9fc063b.nq.gz
    ├── 2909ef85fbfe0e3152b677aafe389907db85d04f.nq.gz
    ├── 29bdc85602965c6edd8f38fc6f59800bec35bb9e.nq.gz
    ├── 2a13bb3c5a0c3a2e6b8328e4972f5959a294c452.nq.gz
    ├── 2a1b4dc24da187a4c7ccde37bb70ec06f281b87d.nq.gz
    ├── 2b141b53fd109513c6ed5b1b261b8590a6f66c5a.nq.gz
    ├── 2b585eb9eb81e43d883da546aacc066f72d738ce.nq.gz
    ├── 2d7f5e25214618502744cc6476a9054b08a2078a.nq.gz
    ├── 2d81c2d884ed96919a96ce63f405d37af2a85825.nq.gz
    ├── 2dff13c6d111d439b47a2f1ed9b14aded229ce62.nq.gz
    ├── 2e103fc87e61a8f49e90d16aeb86383fb37690a5.nq.gz
    ├── 2ec2584e0e75a0349e80391813916f287f127508.nq.gz
    ├── 2ef094c97a5c9aa84622f26bb40ea3d508379da1.nq.gz
    ├── 2f57a1d4867ce100ba18d60a9cfeabb9d240a35c.nq.gz
    ├── 2f71e05737992e0894b47e8d81965a665480c376.nq.gz
    ├── 306bda02d4376592f01c4582795fec93add3d610.nq.gz
    ├── 3073762165352a6861b5debe933b891655e71431.nq.gz
    ├── 30a115777a439a3a22d742ea69676d2830c26b7b.nq.gz
    ├── 320451d30e557b11af2f6c8aabbf1f38a6744adb.nq.gz
    ├── 3489bcc9395a88bbe2d8afe052ab77454e946fad.nq.gz
    ├── 353970cf977660c16908f33862b91fa958a27893.nq.gz
    ├── 36586a02c7724ce5f1634e16a446a74d719908f7.nq.gz
    ├── 3677a0552ad6a9eddc78f185d96b42097232b934.nq.gz
    ├── 371773d3949f03f99b6446f53245c4a35fa39968.nq.gz
    ├── 374759af42e1bd418ea45101f46d7b2a11add2f7.nq.gz
    ├── 37d19db3c23a2ad6cd2c2144c2edba58717caa2f.nq.gz
    ├── 3860ae7cbe3132fb3b340f5312f449dbc548bf74.nq.gz
    ├── 38987676e1086de62bcff282de48b5d8ff27440d.nq.gz
    ├── 396e9dcd9861b05016bca3bac52cbfbfcae41bb9.nq.gz
    ├── 399fe8a2dfeaceb927b3bdaeb44e6436efa8bc54.nq.gz
    ├── 39db1ec8767271e6805466a1ae1d578486d4c161.nq.gz
    ├── 3b761d14a71b679608d5fff76a27d5d2d00e08c2.nq.gz
    ├── 3b7d2d4f01621d5e15572919776e92b7bdaf477a.nq.gz
    ├── 3bebb8032a19e7b67febe13cf8fc196f6d49e304.nq.gz
    ├── 3bfc4ca3c7392e2bad7ac0bd9b3811e0120c7850.nq.gz
    ├── 3cd608b0f73c737224ca5af000a07e589350bd46.nq.gz
    ├── 3cdf07e0a0ff270d80b01e280aa1fc748ba0ccea.nq.gz
    ├── 3d4dafd045e77dbe26ab36cf72204c2ce9c3d548.nq.gz
    ├── 3d5ac09c25375f19becf9b1149e175c18a2720e4.nq.gz
    ├── 3e5d0d5a925e9dc20848d59c996f2e09cba63943.nq.gz
    ├── 3e6aea48ec4a292f936e6b3e93229cbe6f3e3abd.nq.gz
    ├── 3ed7b71d71b2af518fa77fe23e8148b24e6af520.nq.gz
    ├── 3fd96321dc029f319f2f60c250ed237a601b167b.nq.gz
    ├── 4004c1422c9ea9e99a9e1a36620d4324e92ac955.nq.gz
    ├── 40afd0efd3fd4ab1553250a298556910eb486c17.nq.gz
    ├── 40bb414dd210f314a24b0d82570c32c5747674e8.nq.gz
    ├── 41561b781fe6122cbd3afb469d7b8af2e7f0a714.nq.gz
    ├── 41d779b40930981fad999f2ccebc0fc6c7b4aa0a.nq.gz
    ├── 41dc3355ffeb521974a1b692a511fe403b7d29d9.nq.gz
    ├── 424950c2f57bfde45b5f8890e252c0c212916874.nq.gz
    ├── 42b4e6e1e7af48497bf6e015e7b128de3b67cae0.nq.gz
    ├── 42f00503a03e206e5a425724afb485c3a5dff006.nq.gz
    ├── 434956f4a40593f20eb8e2c0e2d7bf61ad6fbe0d.nq.gz
    ├── 4384ed1018b03e817276bacdde1522aea78c3397.nq.gz
    ├── 43fe14329d8e6fb675f7e4ffb886eeaba15226a4.nq.gz
    ├── 44c9b100c7a1293ceacde804d659ce889d5a9b8f.nq.gz
    ├── 450ff08d2e8ce937d399e8f1eb08696daa25e0f1.nq.gz
    ├── 45c2deffd4930296d3c750b988495ce2917e2f48.nq.gz
    ├── 461f2c37584b1939d8909f4ce3ef8e6cc9bc7aa3.nq.gz
    ├── 46c124aad4823b41a4c0b425415ce41e97f10c29.nq.gz
    ├── 471a535cece300eec19b930515ffd636b53bb278.nq.gz
    ├── 48caf65a629580dbd096e7fe13e1e78e60b36351.nq.gz
    ├── 4933d9038afd17d86494b0f99f620e6a51d0798b.nq.gz
    ├── 4970324d45e15efb096ef2c2f7baa48c74df5773.nq.gz
    ├── 499162fc3f16bfbe8df3b99114ab33cf12efc5aa.nq.gz
    ├── 49d29abc65784bf3b07260ca80011d9736dc37ee.nq.gz
    ├── 4a3ec7c7432d6caf0e9809619c3f3e99304b1fbf.nq.gz
    ├── 4aaec3d88df139a0ed4e52e3768f5a08ce8956ef.nq.gz
    ├── 4ab168fc5eb9c2a750e14bfdae437f3544411efb.nq.gz
    ├── 4ad2ed82b3f1f40fa2047977d1a0dbe1ff93d0e3.nq.gz
    ├── 4b20540974e165cd4cf7587956b3be85748e6a31.nq.gz
    ├── 4b62f73a9eabe0f5384dbd707f8b55b0c4c32e27.nq.gz
    ├── 4b99b8084f794cb3a283bc946a83a692b3bdfdf0.nq.gz
    ├── 4c1cc47314e97682ed5cf3d462a5419540051812.nq.gz
    ├── 4ca238d0562f93b4278bdb4a53342b0df2f86da6.nq.gz
    ├── 4cee94d5a777028f37c0fe2ff9dae84667c939ed.nq.gz
    ├── 4cfdd949bba78edba428067d7503c545da7bfd71.nq.gz
    ├── 4d06a7608e9df156a745498973ff8d94d723f998.nq.gz
    ├── 4d0d4d574035d35b61d71be997b866c0cbd4877d.nq.gz
    ├── 4e529f357bdad23686bb719328ae28a186a46ec8.nq.gz
    ├── 4ef1613204253f1c30ec1b6cb2ffa1a6a799a39b.nq.gz
    ├── 4f31fbe598a0a75db2678cf06b40408188b8bd71.nq.gz
    ├── 4f789aa6a92596499fbdc1689fcede9ec8bf0e2f.nq.gz
    ├── 4f84b5ff22bd70e07f2cb1a01d666ca4902f2c7f.nq.gz
    ├── 4fd51c28bd17b7b85e2f4c639128cb9aa7f02444.nq.gz
    ├── 50100a7c106a5556d1bd7d816680c8c00d048e1d.nq.gz
    ├── 5028970398580fd860a63a4b52368389c7d5482f.nq.gz
    ├── 509a07c9821b5ab4453bf5b5825104fe7166832f.nq.gz
    ├── 50ee2345d702246a61be0784f2961da1043f8d9e.nq.gz
    ├── 515819336f9f7df30e5c5e74010b251237e97576.nq.gz
    ├── 517210afb51fec25fa430f2c7a5f7827913f73af.nq.gz
    ├── 51d9098bcedee877280944be77e98d7906ec131c.nq.gz
    ├── 52dc7a1921dc509e94483b89660e623174771f5b.nq.gz
    ├── 5334f8f72020ddc5d854c2c6d0e6000685073faf.nq.gz
    ├── 536cbf0e5abbbb1079f3c99aeb186beade1f82fe.nq.gz
    ├── 53f3d0d0069e3635c5e32826268843ce0dff511d.nq.gz
    ├── 540c6512302a13ae02d5becb985c6f9826fee571.nq.gz
    ├── 54177e6201fd6791f62ca0872eea5f3b7aaee9d6.nq.gz
    ├── 5448b8c570d517c3137fcdd58c3511d8570ac0f4.nq.gz
    ├── 548c9df378e8e6e5cf7c80fbcec7e702aecdfbd5.nq.gz
    ├── 54e990bff5e738e2cc8b0f5ba30d29aa5f2d6318.nq.gz
    ├── 555e4b41032a5d601a34afbc45afe1e761fee4e7.nq.gz
    ├── 55faa6df7bb277b36d2743c23efabece765fda96.nq.gz
    ├── 563f3e95783401b54ade1894a8a23c6cd77e0488.nq.gz
    ├── 56d3cea499648be8febee667170f3cb4ea8ee7b7.nq.gz
    └── 570fba2fce0876a1df13f65dff32bd4146e65dbb.nq.gz

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

[praw-dev/praw](https://github.com/praw-dev/praw)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
