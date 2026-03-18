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
│   │   ├── 2a57335dc9cd6833daa820bc94d9b40c26a7917d.nq.gz
│   │   ├── 3ebf1ddaeb260c4b1ae502a01c7844fa8c1fa0e9.nq.gz
│   │   ├── 69483b4bd14f5845b5a1e55bca19e954e827f1d0.nq.gz
│   │   ├── 89cbdd9e7b39eb58896d316a7495597d3aba4371.nq.gz
│   │   ├── b5ce16571001d6e96e1693ac891fed5c2510c651.nq.gz
│   │   ├── bb548d0473d4e1c9b7bbfd6602c7bf12f7a84dd2.nq.gz
│   │   ├── f35b8ab0b5a2cef36673838d662e249dd9c94686.nq.gz
│   │   ├── f654a9112bbeac49ca2cd45bfbe11533c4666cf8.nq.gz
│   │   ├── f97607b89807936ac4ff96748d766cf4b9711f78.nq.gz
│   │   └── ffdc059bfe9ce6a4e144ba849dbedead332c6053.nq.gz
│   ├── dataflow
│   │   ├── 221dbe5ed46703ee255b1da0dec05086f5035f62.nq.gz
│   │   ├── 2a57335dc9cd6833daa820bc94d9b40c26a7917d.nq.gz
│   │   ├── 3ebf1ddaeb260c4b1ae502a01c7844fa8c1fa0e9.nq.gz
│   │   ├── 69483b4bd14f5845b5a1e55bca19e954e827f1d0.nq.gz
│   │   ├── 89cbdd9e7b39eb58896d316a7495597d3aba4371.nq.gz
│   │   ├── b5ce16571001d6e96e1693ac891fed5c2510c651.nq.gz
│   │   ├── bb548d0473d4e1c9b7bbfd6602c7bf12f7a84dd2.nq.gz
│   │   ├── f35b8ab0b5a2cef36673838d662e249dd9c94686.nq.gz
│   │   ├── f654a9112bbeac49ca2cd45bfbe11533c4666cf8.nq.gz
│   │   ├── f97607b89807936ac4ff96748d766cf4b9711f78.nq.gz
│   │   └── ffdc059bfe9ce6a4e144ba849dbedead332c6053.nq.gz
│   ├── lsp
│   │   ├── 221dbe5ed46703ee255b1da0dec05086f5035f62.nq.gz
│   │   ├── 2a57335dc9cd6833daa820bc94d9b40c26a7917d.nq.gz
│   │   ├── 3ebf1ddaeb260c4b1ae502a01c7844fa8c1fa0e9.nq.gz
│   │   ├── 69483b4bd14f5845b5a1e55bca19e954e827f1d0.nq.gz
│   │   ├── 89cbdd9e7b39eb58896d316a7495597d3aba4371.nq.gz
│   │   ├── b5ce16571001d6e96e1693ac891fed5c2510c651.nq.gz
│   │   ├── bb548d0473d4e1c9b7bbfd6602c7bf12f7a84dd2.nq.gz
│   │   ├── f35b8ab0b5a2cef36673838d662e249dd9c94686.nq.gz
│   │   ├── f654a9112bbeac49ca2cd45bfbe11533c4666cf8.nq.gz
│   │   ├── f97607b89807936ac4ff96748d766cf4b9711f78.nq.gz
│   │   └── ffdc059bfe9ce6a4e144ba849dbedead332c6053.nq.gz
│   └── repolex
│       ├── 221dbe5ed46703ee255b1da0dec05086f5035f62.nq.gz
│       ├── 2a57335dc9cd6833daa820bc94d9b40c26a7917d.nq.gz
│       ├── 3ebf1ddaeb260c4b1ae502a01c7844fa8c1fa0e9.nq.gz
│       ├── 69483b4bd14f5845b5a1e55bca19e954e827f1d0.nq.gz
│       ├── 89cbdd9e7b39eb58896d316a7495597d3aba4371.nq.gz
│       ├── b5ce16571001d6e96e1693ac891fed5c2510c651.nq.gz
│       ├── bb548d0473d4e1c9b7bbfd6602c7bf12f7a84dd2.nq.gz
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
    ├── 04664d44b61e3faf99f2f7d1b5946d5bc8282c61.nq.gz
    ├── 05a562f72196400a500f6b10ed0dbad29b543891.nq.gz
    ├── 069d43d8ecf84afb540da4fe1e1d802a5cd3359e.nq.gz
    ├── 06b25012e44e61fbb9c1d777b2b4bcf17f96ac8a.nq.gz
    ├── 078dcee8bc6405849fcbf10cb6f805e12d0ab472.nq.gz
    ├── 079c3b5757fef824065b31527e2893d5e10b444e.nq.gz
    ├── 08172d511464c360fc613ea58a94e6eaedbb3cc3.nq.gz
    ├── 08adf73d130851a565ee32430c0725edca4dfca6.nq.gz
    ├── 08e548c07db83cdc59555f1934353991baf127d9.nq.gz
    ├── 0a25bc68212a831098bf32cbc1d2d096bd6254e5.nq.gz
    ├── 0b7570f21c631b5594aa5420c090c8c88c1a879d.nq.gz
    ├── 0bae80e34a30208502959577bfb6eb8ed8ce406f.nq.gz
    ├── 103d7dcb6ad67342df019a5a69b5ba88dc3e3cbf.nq.gz
    ├── 112beaf6429b3d8f435f744f240e1bc0ca6c5486.nq.gz
    ├── 11951d4a555e700c5bf5e60a5dd3f83bd872290a.nq.gz
    ├── 11a024ec3961c150ba442a85d3cac6175bada10f.nq.gz
    ├── 11cdbfbc6852e842781da4d83649a0fb742cffa3.nq.gz
    ├── 120c4639875ba7e148715d21e3670826b15aacc7.nq.gz
    ├── 12a23ea615a7b46d6bdd5a53c6a8a739d5cab4f6.nq.gz
    ├── 14f02dc15b7dd70886b25b055fe9db99bc0941ff.nq.gz
    ├── 15a486ca6e2466011a3b72d3ad8e93ca409ac4b8.nq.gz
    ├── 161b449cd8dcac9b54ec59131bae412e43f71d4b.nq.gz
    ├── 169de39221c73123409330785477fdee95131445.nq.gz
    ├── 1701af2a3c89c238c4e2af7d48af2abac0bf4f87.nq.gz
    ├── 18443a91c85d6c100664da1e586ff11c3a3d3062.nq.gz
    ├── 188bb9e174397295062da708cc9f5207e2331768.nq.gz
    ├── 19063416577453dce1e29f389479f5f8d9893531.nq.gz
    ├── 1ac21ef1039fc194d4f615ddcc81f2d51ff0c72c.nq.gz
    ├── 1b19be3bcdc924bbe3ba17e1b16b06459fd1c8b8.nq.gz
    ├── 1bcfcb0d949d6842a482855ea127f4d31b1f16e9.nq.gz
    ├── 1bd87304f431593f3a8136e32d1abe25cbf1b23a.nq.gz
    ├── 1c1b88eb58872b74ba60ba626c2da60540ad5817.nq.gz
    ├── 1d2f71824aa936183182a9a3e83ae5b6d2f6029b.nq.gz
    ├── 1daa02d2fc84d2886b64ebd4789a8a6275b8f7d8.nq.gz
    ├── 1dcb2338c4c4627f67b6a981a6fd38a76833b20c.nq.gz
    ├── 1dd4e650f01b0de9d45801fbeb66a0c4d8386482.nq.gz
    ├── 1ec65fa2dfa65318e32c23cc14ab2300c75b6c2a.nq.gz
    ├── 1fe3cf3d5d10ef9e2d4145186c691ccce698195c.nq.gz
    ├── 202a91f8c199f9d06f1962408ec9c4534b19e773.nq.gz
    ├── 2076714cc804a169ceaf593850e3afaa8c4cec16.nq.gz
    ├── 20969472c7ddcdef351f5a70c32503b19019130b.nq.gz
    ├── 20d7b8b1ffc92f9f9ca0a156de660d63cb45968a.nq.gz
    ├── 213bde2ea63660c7e40731cece43383656526144.nq.gz
    ├── 21629087baf76463a48b973fd03371f746a032aa.nq.gz
    ├── 2199945813c83d439e097fc167718afbeaae9e8e.nq.gz
    ├── 21ffe56a315d858c99f47bb60ea84482445eb1c8.nq.gz
    ├── 22e1df1d9619c6528be93d126444299c8ba27fd9.nq.gz
    ├── 2608f5a36e1a5a32aa7b6988c30e7ccf43a08796.nq.gz
    ├── 261da37f78fbc5f5a02e1cab5123a0c93da15ed3.nq.gz
    ├── 26830403a9b356e2206e4c0c7e4e22ff00d14aa4.nq.gz
    ├── 26dddbd363aa8dae7cc6e9cbf163664b918d008d.nq.gz
    ├── 27333306577195a73511881fe75ca2b2fb2ed41d.nq.gz
    ├── 27e2420ed2e76d2766aea60566912d1428341222.nq.gz
    ├── 294cda0930df7db316c022db1cab65c48fdff638.nq.gz
    ├── 2a6e47234f56638934e012b8e227671c42af2461.nq.gz
    ├── 2c4468efb166259abfa687ffa7f6c0c2f63ed3d2.nq.gz
    ├── 2cb8bebba9a4411c8de1c4ae17ed98c098ee5a93.nq.gz
    ├── 2d02f9bcef1b7820fb5e72e485b2d1d0e158d8e8.nq.gz
    ├── 2d4a4454ef50bf34b538568f38ecd5d5f2641ea9.nq.gz
    ├── 2e3d22f312026ff2c863bbffcbc88b7f6fb942f5.nq.gz
    ├── 2e5e8124ff17c8eae9e317e09e58ff4246f941b6.nq.gz
    ├── 2fdf80fdd30885ec3cfd2358a4b11f24e25918ae.nq.gz
    ├── 300a63b8c93217b37527ca84e274100411107baf.nq.gz
    ├── 30602347512c3d61110e58a1bd8ed8a6c52ca3bd.nq.gz
    ├── 31a7e991c4daefe8b4cb43d42a5d2186da7bad2b.nq.gz
    ├── 328009f84c0677154932819b9c48d121767ca400.nq.gz
    ├── 32c0e338825308f6b9b4d0407aa5682a23e2dc9c.nq.gz
    ├── 3460b46b10c25a0f538c39dd14f77ac6328d8494.nq.gz
    ├── 35a643ea2139bce978da5c321905a6abf73fab0d.nq.gz
    ├── 374aa3c3540fe17768e0bfaef623ece51ee7c774.nq.gz
    ├── 377d5cc56ad1d54472e5333600306dcf5e5797fa.nq.gz
    ├── 3833cb6f09355376c29288d388e88241e12fd97d.nq.gz
    ├── 39467d9a51f2b20319855662982d8d0e601cf2e3.nq.gz
    ├── 3b5b09330a435238401036daf4f36d93801ac352.nq.gz
    ├── 3ba5aea303227adf70e76be2c74fbebd29c43d69.nq.gz
    ├── 3be384bf9e8f8a73178ac74ea62ea9829ea0ecf1.nq.gz
    ├── 3ddab109ad9ec6061eca508f8749996e5e5534a4.nq.gz
    ├── 3f2e5d329fe8acf2e6d5253e670e39a76e244578.nq.gz
    ├── 3fc73fea7633486b3dd0a2212efdf33ab618b75f.nq.gz
    ├── 41147562d86209afe62e81140760950840e453c8.nq.gz
    ├── 413c9714f77bdfc78f83c4b4ddb3ac0af5324b8b.nq.gz
    ├── 4446a6d64fa0b9ee3fc46e3b0ac6459a47cf11d5.nq.gz
    ├── 446029a4326c9ad2270476ff96d80824e32a433e.nq.gz
    ├── 44d40e6c416c28cba0eb46160a5d204458c71208.nq.gz
    ├── 44d4d9d5a7c38acb84d299e75e108e197b3040df.nq.gz
    ├── 473b670a7c6195561168a94337416f32a4db8e73.nq.gz
    ├── 47bf85e46349e6f61ab81f238a9171eddf93f24f.nq.gz
    ├── 49370eb167420ee5bf1802a92c713a31fddece60.nq.gz
    ├── 4953981d38780794a415aeaf9091e1174634326e.nq.gz
    ├── 496d3c0db78704e6d6b9af20bca666f475e44619.nq.gz
    ├── 4aa180687a7ae42527e9e533187b1762a8416659.nq.gz
    ├── 4b0421cf9ee47908beae4b4648babb75b09ee028.nq.gz
    ├── 4c39ac0455e6e0d7d0b8e2b07c01cdc8e68edacc.nq.gz
    ├── 4cdaa53d56d71d3ec11dc34a2811ca57cb6fa35b.nq.gz
    ├── 4d4b4aad6fe88e01587e8f749727f648936d90ee.nq.gz
    ├── 4d83d6a1868dcb5ce6ad3973f49d6ade440cf5e3.nq.gz
    ├── 4dd897a8afdbf27a50b8cd341bebe2cf987524bd.nq.gz
    ├── 4e91332bb51c30dbca434b9b8b32339bc6c3ba23.nq.gz
    ├── 4ed341dd28934c102aa7a40c74ee24b6555c1db1.nq.gz
    ├── 4f3ced6f3277f399b685c77f4b6d07018df66990.nq.gz
    ├── 4fea2fefdba320ed110cd0475a5e579b0e0be6cb.nq.gz
    ├── 50536488c95766ad3c4ea59ac5212411680d70a3.nq.gz
    ├── 506a82f8077751bd86fb19e0adf0562834d88b9e.nq.gz
    ├── 51b6df347cc9080195a38d10d0f78f6230f74c9d.nq.gz
    ├── 535f293490ce97e9ee271793c00ff56935e07e24.nq.gz
    ├── 53e01ed467839ffedb7a8bfe39cc7d211301ee06.nq.gz
    ├── 54124df1d3bbed65addd5df5f9c57c4ea07d4253.nq.gz
    ├── 5523422fe3d777997c43ba307a359169be97974a.nq.gz
    ├── 5552827238cc11ae2cb1c7040c46e0315fad6bca.nq.gz
    ├── 55e42ddebdc45db4a80e88cf35b10b9b852e1460.nq.gz
    ├── 565b1c366d75a1db2ee71302845b6247fdeb8c89.nq.gz
    ├── 580fdea4cdfa5a5bf74765e4ba0ef332fed11e68.nq.gz
    ├── 58324f10551c0f4ac61d888475b4348c27431440.nq.gz
    ├── 58db928450dc17d750357e18af3631ace77ec0ad.nq.gz
    ├── 58e0798da433e2995b45cec7f378b3eea4631c93.nq.gz
    ├── 59c48277ac6d33390cd803240728c77ec041a09f.nq.gz
    ├── 5a6bb75f2cfad00982957b9df46a84c8014d5e6c.nq.gz
    ├── 5a74c4f4d5be084e80498e1b6080cc19a15d042e.nq.gz
    ├── 5aac226df8343ce5f0b8c44342462b954fd53177.nq.gz
    ├── 5aacdb7cca624915c6d0770d5b92405d006e9fd1.nq.gz
    ├── 5b564209444e1da70236c8b6c68dbe4261e90379.nq.gz
    ├── 5b98bf3ac91d0adcc2b96009e2039f3ca0ad9359.nq.gz
    ├── 5bb07c89c68b7a735003bd626edf7e2dce016f1f.nq.gz
    ├── 5bdec56cd8323e77f3b31a5bd5f1b17ad819b580.nq.gz
    ├── 5be0c4060908e349051ee5c61194db883938b157.nq.gz
    ├── 5c3f813fae321adb776416c43aed60f8fe142b1e.nq.gz
    ├── 5cea8f8c757f95ff9e3cd863a5d43996f8ae4e18.nq.gz
    ├── 5d757dd1b444709555dec44d127a297bb02c2850.nq.gz
    ├── 5e020f310adc9aef33918db48ef051d82a83858c.nq.gz
    ├── 60e5e3023e9ef8dc9dbad7fb4058243a8910ce2a.nq.gz
    ├── 617bfb2c3f505ccbd97ae1a069c193076c13b4dd.nq.gz
    ├── 619530187c9e8b9df7945739464d3b7d21f12272.nq.gz
    ├── 624efddbc56da1da277d50187ee2e25978dcc0ac.nq.gz
    ├── 63f8521476758e26809961c907c0dad8cedee517.nq.gz
    ├── 64cc40fe1dad41ebacee3bfd828f9f18cc57b420.nq.gz
    ├── 6744e1c741ebf6b3abeed500fb1788db59e6bfa7.nq.gz
    ├── 67fc95b66a61f43229c974695024c3ff8ca649e0.nq.gz
    ├── 684c2d5d1c56c1a85c429c72e05397c51bdcae1e.nq.gz
    ├── 690583a8e03e5f98570fcd88dc4e2b35a8ad09f2.nq.gz
    ├── 695167c6de1986d439f27ded95d720c106f71a83.nq.gz
    ├── 6b7ce929eb1c76e2852b10a35fea331a7ca14d06.nq.gz
    ├── 6b85c5ecef251782251b12e74772d0825c56acc0.nq.gz
    ├── 6cf23459f5d93245db7c4ec4433e9969bcc249df.nq.gz
    ├── 6d6af1a83abf0c816be79b131271c1f311d28613.nq.gz
    ├── 6dfba08cd17f3e97743e60913545c92cf5e377ea.nq.gz
    ├── 6e1bb22a2bc896d032b01912a7e248e6e68ac20b.nq.gz
    ├── 6ffc751b5e507bf3d8b07447bfac4d63230fa1e2.nq.gz
    ├── 7046bc021ec25ab624d30aef69e963b0664aed40.nq.gz
    ├── 70982b46c6272c3301fd1b96e8427d92d6423d9a.nq.gz
    ├── 7158afc9fdb92ca4ef2bcedc6c36c6a31040cc70.nq.gz
    └── 721bcac79939349a05ecf8cd154a4cec4886a055.nq.gz

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
