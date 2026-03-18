# Repolex Knowledge Graph of stretchr/testify

RDF knowledge graph data for [stretchr/testify](https://github.com/stretchr/testify), parsed by [repolex](https://repolex.ai).

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
lexq download stretchr/testify
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 221dbe5ed46703ee255b1da0dec05086f5035f62.nq.gz
│   │   ├── 3ebf1ddaeb260c4b1ae502a01c7844fa8c1fa0e9.nq.gz
│   │   ├── 69483b4bd14f5845b5a1e55bca19e954e827f1d0.nq.gz
│   │   ├── b5ce16571001d6e96e1693ac891fed5c2510c651.nq.gz
│   │   ├── f35b8ab0b5a2cef36673838d662e249dd9c94686.nq.gz
│   │   ├── f654a9112bbeac49ca2cd45bfbe11533c4666cf8.nq.gz
│   │   ├── f97607b89807936ac4ff96748d766cf4b9711f78.nq.gz
│   │   └── ffdc059bfe9ce6a4e144ba849dbedead332c6053.nq.gz
│   ├── dataflow
│   │   ├── 221dbe5ed46703ee255b1da0dec05086f5035f62.nq.gz
│   │   ├── 3ebf1ddaeb260c4b1ae502a01c7844fa8c1fa0e9.nq.gz
│   │   ├── 69483b4bd14f5845b5a1e55bca19e954e827f1d0.nq.gz
│   │   ├── b5ce16571001d6e96e1693ac891fed5c2510c651.nq.gz
│   │   ├── f35b8ab0b5a2cef36673838d662e249dd9c94686.nq.gz
│   │   ├── f654a9112bbeac49ca2cd45bfbe11533c4666cf8.nq.gz
│   │   ├── f97607b89807936ac4ff96748d766cf4b9711f78.nq.gz
│   │   └── ffdc059bfe9ce6a4e144ba849dbedead332c6053.nq.gz
│   ├── lsp
│   │   ├── 221dbe5ed46703ee255b1da0dec05086f5035f62.nq.gz
│   │   ├── 3ebf1ddaeb260c4b1ae502a01c7844fa8c1fa0e9.nq.gz
│   │   ├── 69483b4bd14f5845b5a1e55bca19e954e827f1d0.nq.gz
│   │   ├── b5ce16571001d6e96e1693ac891fed5c2510c651.nq.gz
│   │   ├── f35b8ab0b5a2cef36673838d662e249dd9c94686.nq.gz
│   │   ├── f654a9112bbeac49ca2cd45bfbe11533c4666cf8.nq.gz
│   │   ├── f97607b89807936ac4ff96748d766cf4b9711f78.nq.gz
│   │   └── ffdc059bfe9ce6a4e144ba849dbedead332c6053.nq.gz
│   └── repolex
│       ├── 221dbe5ed46703ee255b1da0dec05086f5035f62.nq.gz
│       ├── 3ebf1ddaeb260c4b1ae502a01c7844fa8c1fa0e9.nq.gz
│       ├── 69483b4bd14f5845b5a1e55bca19e954e827f1d0.nq.gz
│       ├── b5ce16571001d6e96e1693ac891fed5c2510c651.nq.gz
│       ├── f35b8ab0b5a2cef36673838d662e249dd9c94686.nq.gz
│       ├── f654a9112bbeac49ca2cd45bfbe11533c4666cf8.nq.gz
│       ├── f97607b89807936ac4ff96748d766cf4b9711f78.nq.gz
│       └── ffdc059bfe9ce6a4e144ba849dbedead332c6053.nq.gz
└── blob
    ├── 00268614f04567605359c96e714e834db9cebab6.nq.gz
    ├── 003e99fadb4f189565b409b9509ecf30b752d25a.nq.gz
    ├── 00df62a05992d6575377caea6ee99fc15c836bcb.nq.gz
    ├── 00e2d21fc858b4e0e64fbed05fea6348daf15179.nq.gz
    ├── 044da8b01f22644b8d10443c08a2d9ef073b315c.nq.gz
    ├── 069d43d8ecf84afb540da4fe1e1d802a5cd3359e.nq.gz
    ├── 06b25012e44e61fbb9c1d777b2b4bcf17f96ac8a.nq.gz
    ├── 078dcee8bc6405849fcbf10cb6f805e12d0ab472.nq.gz
    ├── 079c3b5757fef824065b31527e2893d5e10b444e.nq.gz
    ├── 08e548c07db83cdc59555f1934353991baf127d9.nq.gz
    ├── 0a25bc68212a831098bf32cbc1d2d096bd6254e5.nq.gz
    ├── 103d7dcb6ad67342df019a5a69b5ba88dc3e3cbf.nq.gz
    ├── 112beaf6429b3d8f435f744f240e1bc0ca6c5486.nq.gz
    ├── 11951d4a555e700c5bf5e60a5dd3f83bd872290a.nq.gz
    ├── 11a024ec3961c150ba442a85d3cac6175bada10f.nq.gz
    ├── 12a23ea615a7b46d6bdd5a53c6a8a739d5cab4f6.nq.gz
    ├── 14f02dc15b7dd70886b25b055fe9db99bc0941ff.nq.gz
    ├── 15a486ca6e2466011a3b72d3ad8e93ca409ac4b8.nq.gz
    ├── 161b449cd8dcac9b54ec59131bae412e43f71d4b.nq.gz
    ├── 169de39221c73123409330785477fdee95131445.nq.gz
    ├── 1701af2a3c89c238c4e2af7d48af2abac0bf4f87.nq.gz
    ├── 188bb9e174397295062da708cc9f5207e2331768.nq.gz
    ├── 1bcfcb0d949d6842a482855ea127f4d31b1f16e9.nq.gz
    ├── 1c1b88eb58872b74ba60ba626c2da60540ad5817.nq.gz
    ├── 1daa02d2fc84d2886b64ebd4789a8a6275b8f7d8.nq.gz
    ├── 1dcb2338c4c4627f67b6a981a6fd38a76833b20c.nq.gz
    ├── 1ec65fa2dfa65318e32c23cc14ab2300c75b6c2a.nq.gz
    ├── 1fe3cf3d5d10ef9e2d4145186c691ccce698195c.nq.gz
    ├── 202a91f8c199f9d06f1962408ec9c4534b19e773.nq.gz
    ├── 20969472c7ddcdef351f5a70c32503b19019130b.nq.gz
    ├── 20d7b8b1ffc92f9f9ca0a156de660d63cb45968a.nq.gz
    ├── 2199945813c83d439e097fc167718afbeaae9e8e.nq.gz
    ├── 22e1df1d9619c6528be93d126444299c8ba27fd9.nq.gz
    ├── 2608f5a36e1a5a32aa7b6988c30e7ccf43a08796.nq.gz
    ├── 261da37f78fbc5f5a02e1cab5123a0c93da15ed3.nq.gz
    ├── 26830403a9b356e2206e4c0c7e4e22ff00d14aa4.nq.gz
    ├── 26dddbd363aa8dae7cc6e9cbf163664b918d008d.nq.gz
    ├── 27e2420ed2e76d2766aea60566912d1428341222.nq.gz
    ├── 294cda0930df7db316c022db1cab65c48fdff638.nq.gz
    ├── 2c4468efb166259abfa687ffa7f6c0c2f63ed3d2.nq.gz
    ├── 2d4a4454ef50bf34b538568f38ecd5d5f2641ea9.nq.gz
    ├── 2e3d22f312026ff2c863bbffcbc88b7f6fb942f5.nq.gz
    ├── 2e5e8124ff17c8eae9e317e09e58ff4246f941b6.nq.gz
    ├── 300a63b8c93217b37527ca84e274100411107baf.nq.gz
    ├── 30602347512c3d61110e58a1bd8ed8a6c52ca3bd.nq.gz
    ├── 31a7e991c4daefe8b4cb43d42a5d2186da7bad2b.nq.gz
    ├── 328009f84c0677154932819b9c48d121767ca400.nq.gz
    ├── 32c0e338825308f6b9b4d0407aa5682a23e2dc9c.nq.gz
    ├── 3460b46b10c25a0f538c39dd14f77ac6328d8494.nq.gz
    ├── 35a643ea2139bce978da5c321905a6abf73fab0d.nq.gz
    ├── 377d5cc56ad1d54472e5333600306dcf5e5797fa.nq.gz
    ├── 3833cb6f09355376c29288d388e88241e12fd97d.nq.gz
    ├── 39467d9a51f2b20319855662982d8d0e601cf2e3.nq.gz
    ├── 3b5b09330a435238401036daf4f36d93801ac352.nq.gz
    ├── 3be384bf9e8f8a73178ac74ea62ea9829ea0ecf1.nq.gz
    ├── 3f2e5d329fe8acf2e6d5253e670e39a76e244578.nq.gz
    ├── 3fc73fea7633486b3dd0a2212efdf33ab618b75f.nq.gz
    ├── 41147562d86209afe62e81140760950840e453c8.nq.gz
    ├── 413c9714f77bdfc78f83c4b4ddb3ac0af5324b8b.nq.gz
    ├── 4446a6d64fa0b9ee3fc46e3b0ac6459a47cf11d5.nq.gz
    ├── 446029a4326c9ad2270476ff96d80824e32a433e.nq.gz
    ├── 44d4d9d5a7c38acb84d299e75e108e197b3040df.nq.gz
    ├── 473b670a7c6195561168a94337416f32a4db8e73.nq.gz
    ├── 47bf85e46349e6f61ab81f238a9171eddf93f24f.nq.gz
    ├── 49370eb167420ee5bf1802a92c713a31fddece60.nq.gz
    ├── 4953981d38780794a415aeaf9091e1174634326e.nq.gz
    ├── 496d3c0db78704e6d6b9af20bca666f475e44619.nq.gz
    ├── 4aa180687a7ae42527e9e533187b1762a8416659.nq.gz
    ├── 4b0421cf9ee47908beae4b4648babb75b09ee028.nq.gz
    ├── 4cdaa53d56d71d3ec11dc34a2811ca57cb6fa35b.nq.gz
    ├── 4d83d6a1868dcb5ce6ad3973f49d6ade440cf5e3.nq.gz
    ├── 4dd897a8afdbf27a50b8cd341bebe2cf987524bd.nq.gz
    ├── 4ed341dd28934c102aa7a40c74ee24b6555c1db1.nq.gz
    ├── 4f3ced6f3277f399b685c77f4b6d07018df66990.nq.gz
    ├── 4fea2fefdba320ed110cd0475a5e579b0e0be6cb.nq.gz
    ├── 50536488c95766ad3c4ea59ac5212411680d70a3.nq.gz
    ├── 51b6df347cc9080195a38d10d0f78f6230f74c9d.nq.gz
    ├── 535f293490ce97e9ee271793c00ff56935e07e24.nq.gz
    ├── 53e01ed467839ffedb7a8bfe39cc7d211301ee06.nq.gz
    ├── 54124df1d3bbed65addd5df5f9c57c4ea07d4253.nq.gz
    ├── 5552827238cc11ae2cb1c7040c46e0315fad6bca.nq.gz
    ├── 55e42ddebdc45db4a80e88cf35b10b9b852e1460.nq.gz
    ├── 565b1c366d75a1db2ee71302845b6247fdeb8c89.nq.gz
    ├── 580fdea4cdfa5a5bf74765e4ba0ef332fed11e68.nq.gz
    ├── 58324f10551c0f4ac61d888475b4348c27431440.nq.gz
    ├── 58e0798da433e2995b45cec7f378b3eea4631c93.nq.gz
    ├── 59c48277ac6d33390cd803240728c77ec041a09f.nq.gz
    ├── 5aac226df8343ce5f0b8c44342462b954fd53177.nq.gz
    ├── 5aacdb7cca624915c6d0770d5b92405d006e9fd1.nq.gz
    ├── 5b98bf3ac91d0adcc2b96009e2039f3ca0ad9359.nq.gz
    ├── 5bb07c89c68b7a735003bd626edf7e2dce016f1f.nq.gz
    ├── 5bdec56cd8323e77f3b31a5bd5f1b17ad819b580.nq.gz
    ├── 5be0c4060908e349051ee5c61194db883938b157.nq.gz
    ├── 5c3f813fae321adb776416c43aed60f8fe142b1e.nq.gz
    ├── 5cea8f8c757f95ff9e3cd863a5d43996f8ae4e18.nq.gz
    ├── 5d757dd1b444709555dec44d127a297bb02c2850.nq.gz
    ├── 5e020f310adc9aef33918db48ef051d82a83858c.nq.gz
    ├── 60e5e3023e9ef8dc9dbad7fb4058243a8910ce2a.nq.gz
    ├── 619530187c9e8b9df7945739464d3b7d21f12272.nq.gz
    ├── 624efddbc56da1da277d50187ee2e25978dcc0ac.nq.gz
    ├── 63f8521476758e26809961c907c0dad8cedee517.nq.gz
    ├── 64cc40fe1dad41ebacee3bfd828f9f18cc57b420.nq.gz
    ├── 67fc95b66a61f43229c974695024c3ff8ca649e0.nq.gz
    ├── 684c2d5d1c56c1a85c429c72e05397c51bdcae1e.nq.gz
    ├── 690583a8e03e5f98570fcd88dc4e2b35a8ad09f2.nq.gz
    ├── 695167c6de1986d439f27ded95d720c106f71a83.nq.gz
    ├── 6b85c5ecef251782251b12e74772d0825c56acc0.nq.gz
    ├── 6d6af1a83abf0c816be79b131271c1f311d28613.nq.gz
    ├── 6dfba08cd17f3e97743e60913545c92cf5e377ea.nq.gz
    ├── 6ffc751b5e507bf3d8b07447bfac4d63230fa1e2.nq.gz
    ├── 7046bc021ec25ab624d30aef69e963b0664aed40.nq.gz
    ├── 721bcac79939349a05ecf8cd154a4cec4886a055.nq.gz
    ├── 7324128ef19c51d1cc74cd2cae8c886b2a71e7df.nq.gz
    ├── 74b3191227eb21e80e0cd3183ec61ff9509ee8e5.nq.gz
    ├── 75944878358568654acef8e7d73cbe96cd146d05.nq.gz
    ├── 75ecdcaa2f3e9bb45c332222ffd8ff42f5beadda.nq.gz
    ├── 77aeb5c47eabd1b0cfbf64cf66a42766a9475f24.nq.gz
    ├── 7a35a648e0f9f9d3d490db1654e227b229d4f28b.nq.gz
    ├── 7aaef06b1ce32e3f0d2bfb328cc501fa9ec332eb.nq.gz
    ├── 7ac5d6d8edb0c08a8118206212eab5b9147da5ca.nq.gz
    ├── 7c519ff47ac3cb8f39fa775e031dd9c5f27db58b.nq.gz
    ├── 7da34b765f7840aabaa11e6f764e74c9f31d5d54.nq.gz
    ├── 7e9389a20a2afa25ecb936f7afde34871d643a07.nq.gz
    ├── 804fae035bcce327e855bac7caa2c04a02baf775.nq.gz
    ├── 84dbd6c790b952db01075f1b19b6449ed50a514c.nq.gz
    ├── 895591878bf7fba87e6061d3a394927c077ce146.nq.gz
    ├── 8a4a6589a2d42ca8efa4a2dc8477f602d8dff328.nq.gz
    ├── 8b4202d8906d869c49aa9de9fda1994dfb2e2b8d.nq.gz
    ├── 8b98a8af275f7724bc4b15dc03d758f6c059c25d.nq.gz
    ├── 8cb4615db7f30940f9ca909f1f8cb50ed8b5098e.nq.gz
    ├── 8d55a3aa8923db67d7a7994ec6cbbb854a22cfbb.nq.gz
    ├── 8fbcc153033225ea73c62386284288baadcefb74.nq.gz
    ├── 90e5dbe25a0ef02682b62accc98a273d1a18eabf.nq.gz
    ├── 914a10d83afca7aeae680dd08d7a5eb74fa6929c.nq.gz
    ├── 91772dfeb919224e3f35b7e9f13d4b866a8339f7.nq.gz
    ├── 91b5ee911cdbedbcd49fe68d545fc69a5580581b.nq.gz
    ├── 956a2211d4d50954ceaef5f3de6a67668d2b8226.nq.gz
    ├── 95d8e59da69bf8e207db7af447a2f792db6f5625.nq.gz
    ├── 963a2525872c7e634bc10ce89fca1e3376f0b396.nq.gz
    ├── 968434724559c180f09d0dadb0736282796c7a0d.nq.gz
    ├── 978eae264e643e808df29f1d079cc198cb313680.nq.gz
    ├── 991866ac49de070d1ced34ff156b8f2745190bc7.nq.gz
    ├── 99f9acfbba5f62791f35e3545540bd928a733b71.nq.gz
    ├── 9ad56851d9714967b6071772ff44182a1e86e431.nq.gz
    ├── 9bd4a80e4847c014478d6e36e15c3c9bdf93a194.nq.gz
    ├── 9cdfa9f9f617a1641f31f915802bcd5c66b872fe.nq.gz
    ├── 9ceebbc44e9c773d62018ec5af7291f0abb1f746.nq.gz
    ├── 9db889427a72000b50adf767245ca1bdaf2d3bc7.nq.gz
    ├── 9fe41dbdc0cb15506d682bea563da92e5cc08f60.nq.gz
    ├── a0ff95e27e524b488f1b5d9f51ecfef5d64b7981.nq.gz
    ├── a16374c8b44b30881940340a566d0fea1b90f56c.nq.gz
    ├── a38d88060b51b62d43b9310748dea6003b620f66.nq.gz
    ├── a3a062ce99547814c5d4e2911c60a52b6adb60a4.nq.gz
    ├── a4a95858ba6ec98ad24244f8d8d9fea6febb41f7.nq.gz
    ├── a55d1bba926cc71798f97fd760e8e06a5db47921.nq.gz
    ├── a8240d79dd538033baa77be61b6ef67f4fcb1ef2.nq.gz
    ├── aa1c2b95cddb861f99392ba9e84f99dcb1c04699.nq.gz
    ├── aacaac6f1e1e936ee0022c00e139756c9bdc2b3e.nq.gz
    ├── ab1b1e9fd576f90b154db920ac8996c76bbd7234.nq.gz
    ├── ac71d40581b941a74ef378a428524745853cc196.nq.gz
    ├── ac9b701725200bff6100a6539ca8a25630292413.nq.gz
    ├── ac9dc9d1d6156b64c31ac0b130e7a2b1ca86f06d.nq.gz
    ├── acd4e59ab476d6c82540104113a820aaaabea367.nq.gz
    ├── b120ae3b8f7e1830d7ef529448bb2cd14089fe22.nq.gz
    ├── b1d94aec53cc7fb8c91cde58f0e79c94c853aefb.nq.gz
    ├── b1e32f1d86b57e4d1026ca92b96ce044810ae996.nq.gz
    ├── b35c86392bf89ac9ba448abd0cb8fb99e3f2db5e.nq.gz
    └── b37cb0409879c28d8548a195f4257c4129ef6066.nq.gz

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

## Source repository

[stretchr/testify](https://github.com/stretchr/testify)

---
*Parsed on 2026-03-18 by [repolex](https://repolex.ai)*
