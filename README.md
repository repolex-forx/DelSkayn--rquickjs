# Repolex Knowledge Graph of DelSkayn/rquickjs

RDF knowledge graph data for [DelSkayn/rquickjs](https://github.com/DelSkayn/rquickjs), parsed by [repolex](https://repolex.ai).

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
rlex download DelSkayn/rquickjs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 635f9322ccc875e3f9851e7f75ec538cf3274fd5
│   │   │   └── chunk-001.nq.gz
│   │   └── f3039c8d931417049ce6133b3ff4550ca38438a5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 635f9322ccc875e3f9851e7f75ec538cf3274fd5.nq.gz
│   └── repolex
│       └── 635f9322ccc875e3f9851e7f75ec538cf3274fd5
│           └── chunk-001.nq.gz
└── blob
    ├── 043ea9aee9fe17a2e60ad47e378ad72fd07110c5.nq.gz
    ├── 05c5e81f75a161a7be3a5550a0f67d92a0ad636f.nq.gz
    ├── 07a56000f54eeffd3027d024c513d1246c44b112.nq.gz
    ├── 0848c8487a10b394cdbd3025f6a20212f265e7d1.nq.gz
    ├── 086c3a4d41bddbb61849f48373a75e3c131f0b21.nq.gz
    ├── 098810ac43ee687d7d7d10ab83719968d8fe4e7b.nq.gz
    ├── 09fb0e7f12fce04d8127233816d72782062f7996.nq.gz
    ├── 0ab8a6b9e879109c807baae35112913d11aa5b46.nq.gz
    ├── 0ac91d500267efe63ca569b352459ac764f1353b.nq.gz
    ├── 0d1cc8026f2d9f45d709bd2ffd26202a87c1854a.nq.gz
    ├── 0e9bfa5f08ace1b2645d8008b2e20b5ea83d31c2.nq.gz
    ├── 10c66690a9e007ab4e736a3c1eba30faac4cbd1c.nq.gz
    ├── 1304d2e8b080ca08b30489f248d5b8af4b2fa49c.nq.gz
    ├── 13713048ba54c290a30938edfb48e2904acf1e71.nq.gz
    ├── 13b371c4bdec11a909afee9408c6b6fb1ebc4539.nq.gz
    ├── 14091242ca4de58a8117bf92e70f0173f1347fed.nq.gz
    ├── 143bb9d485c1e59beec32ec4b15fa07aec45094b.nq.gz
    ├── 15b314a0b76803ca465f76badaf22431baf89f4a.nq.gz
    ├── 16198d84f13f2f4fddeddda4c9ed5e2d5d2306a3.nq.gz
    ├── 161bc76b8afee5c9ee57aa9ef24e2c50ab26d96f.nq.gz
    ├── 18b15977604b38882b9b05f401fbdf06d7d1e171.nq.gz
    ├── 1a3434dced5648399634c8c16660c01641268960.nq.gz
    ├── 1b7322731eb5fa217ad8a8e89791597802eb6e35.nq.gz
    ├── 1c39dd2daf37beb7d05b6d3afc389f386130469b.nq.gz
    ├── 1d91637151ac5111104a856df8e129bdbb19119c.nq.gz
    ├── 2096a5e644a093e7ceff727f6691ef720ecb2a2f.nq.gz
    ├── 21b9b8bc256a422ac485df77635781f2731a4f76.nq.gz
    ├── 23446507e60f77d9f41c4cec88cfdcd37bf32c84.nq.gz
    ├── 23809017df2c8367046902d3479ee4465109fd91.nq.gz
    ├── 23e2731972c06041c2b8f5bc29277e0ab1c63515.nq.gz
    ├── 23f6447557493976b0d7a115a35660b51f3e4a7e.nq.gz
    ├── 24cd7cedfc00722c470a512dd9ccce1c2bad72a3.nq.gz
    ├── 24e84634d76d31fdbfe294f48a4371efce5afb23.nq.gz
    ├── 250ffb89b8d988de8574df9d13f3277aab7291f1.nq.gz
    ├── 2532cf305f59b1537063ee4e546edb699de93204.nq.gz
    ├── 261f5720123666c8f02338513c57dd888990a585.nq.gz
    ├── 26d3733c8e85a30d0f4aca40f4fe134f9806c36e.nq.gz
    ├── 271f2ea3f8b318c547373725920c10b622e465c0.nq.gz
    ├── 2841d79a1f251d80fcde89381bad6fdba4651edf.nq.gz
    ├── 291c25295cc7630bd7abf6654812be64062d14b6.nq.gz
    ├── 2ae5c6ef3981b205f6a7ed3d743d604ebda9405c.nq.gz
    ├── 2b0cb42d59990c90662633c531443241690f5da1.nq.gz
    ├── 2cac7eebafa51692a9ca4bf763294f32b24ed10d.nq.gz
    ├── 2dbb44d3a05b0b12d8e7fc13925361210c1d9b6f.nq.gz
    ├── 2deb8ae2c188f3a17544613724651f8247318671.nq.gz
    ├── 2f2c202db7d8bf0a004c73c7b97dff06db71fb43.nq.gz
    ├── 2fcec7cc36e3c42e18928a82f642d1e10bd21fda.nq.gz
    ├── 301b459bf14dbc2bdef069a0fab437f1cc093241.nq.gz
    ├── 30423def78377ff317f2b021ee6ac44f57945f5f.nq.gz
    ├── 30f366da93e13dd6828d4862a0eda6d25d1044b5.nq.gz
    ├── 32ffb58ba47a2e4a8084eaa6ba749a8179d083e7.nq.gz
    ├── 357c5e61ef79056b805bd9e75825493e08101940.nq.gz
    ├── 35d188d01fb4434ae0c8ee7276b73d25bd3759d6.nq.gz
    ├── 35f9cbccebb7178e68615c2de2eb1e71b652710e.nq.gz
    ├── 367646bf9c64869f132beac41b4c2611180f8e34.nq.gz
    ├── 3aa726b708598dbbf587e7ca2dcd0eff4987bef7.nq.gz
    ├── 3bdb81df9bfa4e2ea20f600843e59425dac415c9.nq.gz
    ├── 3c2422abb5c56b42595c805c2e1c3525a802e1c0.nq.gz
    ├── 3c904eeb96dfe32737a56bdade7349d4366e6d4a.nq.gz
    ├── 3e0a4abdc0042bf63b8cc15b354a2d9735756688.nq.gz
    ├── 3e5563db9c47f85fe43ca860cdfc8769e4ec27a7.nq.gz
    ├── 409f1fb11751cb02815f4ea60b893f781f4c620f.nq.gz
    ├── 40a6d99067a48b09ecf647e97f3076e5b5f768d7.nq.gz
    ├── 43d4840c79959bac434e1bfffceb36d158bc665a.nq.gz
    ├── 449387780de1405fb928b0bc7160dd7aa1a16544.nq.gz
    ├── 44d02523f4689ba8adb89e878a140bbf0fdee541.nq.gz
    ├── 453e606e6bf6312362b9cba36847d41e0725e756.nq.gz
    ├── 45aa1b4bfe962f73432f8b5beeeb7ec0ba6d0841.nq.gz
    ├── 48f0ad6b959f23f87fc4609cafbadf8c83b66933.nq.gz
    ├── 4a70a02ddbab74e8db481ee855d244a78e5865a8.nq.gz
    ├── 4e04f0531152305a1b513a931b7dc74b4c80adac.nq.gz
    ├── 4fd936a9a2ea45d8c55f4c9a8df930270fa9fb9a.nq.gz
    ├── 5022bf7c5f498bc54c7a096f7eca1788421a3ec7.nq.gz
    ├── 5096268028db5941604ef7d9ccf516dde8a1180e.nq.gz
    ├── 5175e76609f5be809eb0b49f2bb1c65e56075248.nq.gz
    ├── 520f16a4dbf9fb47afc5eefed0951a4aedaf3660.nq.gz
    ├── 522db7ad74956ef8a14c2450cd0297b091503746.nq.gz
    ├── 52949cea1b2a970d1a9632f90a46c5865c7fd437.nq.gz
    ├── 59262148140ba09fe00ced4798acb65de802fb08.nq.gz
    ├── 5f32f7889f6b4a5da5d0cd619a879c9048ebce16.nq.gz
    ├── 5f4c9fd6f8a6ebeb7f14e25f2e10fa71cc700e3d.nq.gz
    ├── 5f67e2f6b839b1da6ba5bf093a362f15edef20bd.nq.gz
    ├── 606c3395facdbd1d36c2f7ad5dd7c8c61cc9cb38.nq.gz
    ├── 60dad0cd3ede5bc98d78f2e59ac842b9efaacb9b.nq.gz
    ├── 60f7294160ebbefc934cabfbb183c1e1f25cda6c.nq.gz
    ├── 6341013ea705bdc768dec84454824f591c537666.nq.gz
    ├── 63eb2b3e80354b4b1d35ac046aab57e56a236820.nq.gz
    ├── 666be38ceaa30a1410ef9f7b179a30644e4eaf87.nq.gz
    ├── 68dba38a0a279acc97dac290882ae3983219d4ca.nq.gz
    ├── 69cb76019a474330e99666f147ecb85e44de1ce6.nq.gz
    ├── 6ac09c2e793c3605b88084979a37f6374bb50165.nq.gz
    ├── 6d739d8c59ddb9ba38338fd77fa5ae0f4cccac80.nq.gz
    ├── 6e15a17258d593d73bdb2fa4a5c62588ccfa61a5.nq.gz
    ├── 6ef20c8c42453961cb9ff25949d2a226e07d4c20.nq.gz
    ├── 703e5c43f527afc0fd601a3f97e799c3ed9d36d5.nq.gz
    ├── 7045870d9d785acb763916377366e72a1e24a65b.nq.gz
    ├── 74de93c918048f79cdbd56ab40ed177d10f11182.nq.gz
    ├── 7931621d250bc430c92a69a068452e21ac362a38.nq.gz
    ├── 7ba028f31cb0d5e5384ae9b638f100d9df1c5181.nq.gz
    ├── 7c6ee57d03a8c65630d1fbe8eb35b80b46a4f263.nq.gz
    ├── 7ca25ccedca56d1290e97df4e6d38b62e0d6efc9.nq.gz
    ├── 7d4940c1cfdc7f62afddfdd38f4bf919ce38d977.nq.gz
    ├── 8356b82e47c149c77040203bf3b65677057b2a95.nq.gz
    ├── 836f3c54b261a00ab0d6977ff2e5b54dfd2589b5.nq.gz
    ├── 83f2dc4b3b16db06590d03c94d9d12f71c52feea.nq.gz
    ├── 889f561b5f0d7f5709994809ac0ac64a0d03eb19.nq.gz
    ├── 88eceb0fef762adeef73b77270b07752ae673f79.nq.gz
    ├── 8907c663c0b5e540989612fd68dcebef95215d3d.nq.gz
    ├── 8908c58738bd823fb3d68e99e99e5a76208a0afd.nq.gz
    ├── 891a5e7b4e1edb7dd1ba5e204d8298fc26dab3a4.nq.gz
    ├── 89f7ad5cf5c3f23d3ef6203419c8c4b798d1a2b2.nq.gz
    ├── 8ab076fd337566fe5717f5bd21fefd6fe2520ea0.nq.gz
    ├── 8f001838c5e3c1510fbe91c15d711b4f0f93c59a.nq.gz
    ├── 8f9c12524f40c51e1af190237db284cfe5fe0a19.nq.gz
    ├── 905bbc0d238f47c69575c6aac371e8032c6de73e.nq.gz
    ├── 91f8c50e8a756ea9f2f0b549e4a7b7608b67f23a.nq.gz
    ├── 92d01b4815408cce3771b3192276d2f41bdb0293.nq.gz
    ├── 92fa43869ef269e0c800a8f2fbc3bd5337622e38.nq.gz
    ├── 93dbc50887369c7ed69d017e3011306e55458d14.nq.gz
    ├── 9580177c92cd65fa5317e40accf466dd903cf9b6.nq.gz
    ├── 95de312788ca80635ecbdc34324be906d31a61fd.nq.gz
    ├── 9b30c78b6cb420927d716b11de5cbd5859fa5bb2.nq.gz
    ├── 9c8512aaadeb7925e13a0c0b9e39de472abbe968.nq.gz
    ├── 9cac184b822753e25c3955819e205ba96f40f854.nq.gz
    ├── 9defa5b00f2710a0bddb64cec88d16295e46e08c.nq.gz
    ├── 9e8f6ca6429b9324e7431c7cad454dec8066a8d0.nq.gz
    ├── 9f97bcebe6f9948de968f9b5070e42a16aaf9d07.nq.gz
    ├── a07ee6b3613ab510df933608c591bed92ecb1ccd.nq.gz
    ├── a200ebdf5a3291b065bc0f1a26fd8c9154750f4e.nq.gz
    ├── a3dca60927be73adb31ddd0d0dfad39cca47aa75.nq.gz
    ├── a4784da0f79cf8ee7ddf4ddc4bd560ecbcf4003e.nq.gz
    ├── a8a6d2c1f7d7bc43fb6364bb60db150ea1401f6e.nq.gz
    ├── a997413ffb0c185a28455ded79db79eb5e05f060.nq.gz
    ├── a9f296e0ee3bebafc07bef412f59845a01dec84d.nq.gz
    ├── abaf97f08adac4f8b04110e23517c248c3bfc7ba.nq.gz
    ├── abe476c851516b2650925ed99ba59732dabaedaa.nq.gz
    ├── ac74d6b3999d2d40ad0d3a809992659bc37d3769.nq.gz
    ├── acb32551e237cf8e70d387b7e3099ee1d89d0688.nq.gz
    ├── acc8e53eeda40300329a14b9cc3b0854d9dfd47f.nq.gz
    ├── adf8aaf524064977d4d415ec89b90ac9abdc1825.nq.gz
    ├── ae6ba079aaa25c8c1a26f641045685f281bda885.nq.gz
    ├── aedee10e645da8391e0fd9ba2613b3136bca2f1f.nq.gz
    ├── afda460a02f27b95bacba46f0a586d3a900d4484.nq.gz
    ├── b0a8b5c1e16e5354bac19b4bbeadf012d17c39e0.nq.gz
    ├── b1bd12ec8a9e5260110e15b4a735436394dabeb2.nq.gz
    ├── b2a1082566a7fe8d4c359a37ab34b0422d8945a5.nq.gz
    ├── b32652f8045e953abb449cf7d9303fb21782b61e.nq.gz
    ├── b4566e43988fdcf44cd1c6ee8d2b6ff28c994c22.nq.gz
    ├── b4b72e76df522e8250c88e951c7d11fa53d24777.nq.gz
    ├── b50652df286327ecfe995a7bd1e2a8984da1f945.nq.gz
    ├── b8f51a45cc4a275f4fef53c5f6fdd22691520891.nq.gz
    ├── bc441f6da8dccfd5a903a68e69f38b5dfcb26f6c.nq.gz
    ├── bcc5b2c2edf12660698b4f837bc3ac0f1240aa64.nq.gz
    ├── be1e30521c1ceb3ca2af491fbf495aef5ec7e89a.nq.gz
    ├── c097bd73486df40e136000a5417510054afd598c.nq.gz
    ├── c13fd1857ce5834144c74bba5115d722a347e835.nq.gz
    ├── c14236d707890ecae07aec7b6aa335f383c47c75.nq.gz
    ├── c2bd872d9035ba0b09a5660fd6df2873a0f7d082.nq.gz
    ├── c34cb34ce5c6a5d395837b98157527a6377751e5.nq.gz
    ├── c36fa940eae3bfd8db5e7661c739d704655b0f9b.nq.gz
    ├── c45f125b1161b6c5ea07408499cd219a65e9194f.nq.gz
    ├── c632d8e3f2f92ec9878566e21278d3cc04547eb6.nq.gz
    ├── c69d18522ed2f8c037341f06e14be7421f700293.nq.gz
    ├── c6ccac5222deb7182d2c822f145413189d84beb0.nq.gz
    ├── c6e35b840159edb08c572b91f91d1979d5616e19.nq.gz
    ├── c70f2ab5b0c0bbf736bcb69fe2883f3396c7b5fe.nq.gz
    ├── c8dbe1a4d4a5be8d6ceddd969228a23721210642.nq.gz
    ├── ca534f0be1836cebce8171436a2dd9ee5827d851.nq.gz
    ├── cb68fe492d041731d8aa3c7df898a60295aab44e.nq.gz
    ├── ce47c4678805aa1c1280617d37477d81f24b8127.nq.gz
    ├── d03193f9b44a6f5609df0fa0486920b16a42df5b.nq.gz
    ├── d14f83b64589fea9d5a41cdcc30714edaeab8bf9.nq.gz
    ├── d208ea32e2f08b94ca0b305bf1d5bb51520aafa9.nq.gz
    ├── d21bf215d93dd23df0b3b54e2e4633b6cdb9e16e.nq.gz
    ├── d2446d26e2c1ce95aeac2ddfbdde4b048ea96012.nq.gz
    ├── d42d601c80b3599359251dac31dab462de7f4de4.nq.gz
    ├── d55b33a96f184d43eef90058db3be2ec9fdf2bfc.nq.gz
    ├── d59a69f6ed8925af553bc262750892b3093b88a9.nq.gz
    ├── d8adf02d5854ad951bdb06652b64a4e9a3c43075.nq.gz
    ├── d96c5d75f9ce8470636b81873d398058ca9edf9f.nq.gz
    ├── daf177733982c5898517d1deda3688435b84f4fc.nq.gz
    ├── dcc7b17aa239de6351f466e4c1ae1dceac8bc85a.nq.gz
    ├── dd09a061328b8652de4b166f19a22694665e24b4.nq.gz
    ├── dd240cf07e295ba3baa9abac262a0c6ead63d4bc.nq.gz
    ├── e06bc9e228096ccb72c97b73f0d01629ff4cb4c5.nq.gz
    ├── e12ec7dcf7fa6134e056aea191150bd8bea34920.nq.gz
    ├── e17c366095a95c616f111c26daf0781a3ec822eb.nq.gz
    ├── e195d95b37165aa470d1580d434254db7a493c5c.nq.gz
    ├── e1f70ab4dca9dd347a05ae132e0cd1be70b03db7.nq.gz
    ├── e4e7b7665a9339261f73148f7f92ee171a6ba75b.nq.gz
    ├── e63e73d7369be17009fb0ac3cd1178d0147fbaa4.nq.gz
    ├── e7fa83cde1757d557ed6b52b03a0f2ff37c6b5b4.nq.gz
    ├── eb5a316cbd195d26e3f768c7dd8e1b47299e17f8.nq.gz
    ├── ed315d20a366b2bad056614db7dcd934728536c1.nq.gz
    ├── eeab485dcec5a8fc7bbf252cb1bded0f9b886d61.nq.gz
    └── f2c564a58172eec78fc97adb006f7be16ecc85bb.nq.gz

9 directories, 200 files
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

[DelSkayn/rquickjs](https://github.com/DelSkayn/rquickjs)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
