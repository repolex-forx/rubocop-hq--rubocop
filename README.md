# Repolex Knowledge Graph of rubocop-hq/rubocop

RDF knowledge graph data for [rubocop-hq/rubocop](https://github.com/rubocop-hq/rubocop), parsed by [repolex](https://repolex.ai).

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
lexq download rubocop-hq/rubocop
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── af8026643d436c4570bf7063a7475e2cad95fd49
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── af8026643d436c4570bf7063a7475e2cad95fd49.nq.gz
│   └── repolex
│       └── af8026643d436c4570bf7063a7475e2cad95fd49
│           └── chunk-001.nq.gz
└── blob
    ├── 0005c4e16da2823f46a927fc6cbb75afd662250d.nq.gz
    ├── 0022a76ae9fc6e96dccc67d4bbc56ac379c97e38.nq.gz
    ├── 00387e897d293920ec3e4c4a2909f4f5185b89ae.nq.gz
    ├── 004593fa8724152ee2563eb7fbf6a839196e4d9a.nq.gz
    ├── 0082df9886eba66718e21d5f5905031f37820210.nq.gz
    ├── 00d6245e64f295955a8834343223fb2ca2402c88.nq.gz
    ├── 00f8db3627bb54785903e7f6a8af5eff6cb6d490.nq.gz
    ├── 010e1873fabdfa2708acc2d44507c575d1c69356.nq.gz
    ├── 011acb0a81457f46cfbeff19b4a5e8892754133b.nq.gz
    ├── 0127f3896c1ec9d3ab6d27997650ac1ea3cfad25.nq.gz
    ├── 012fe8f8d40b05ba6c87a805f2d8b75a7d0908ca.nq.gz
    ├── 017414b633a3506367c441adff541a458d11b2be.nq.gz
    ├── 01791df26ddfb146c89fb7e3c2dc9ef5d29554a8.nq.gz
    ├── 018603a58e6919aa389d93ea949ebcf1f49f1d47.nq.gz
    ├── 01c4a6c0f2bd051f07902bf8f6642d5821762b70.nq.gz
    ├── 01ce526e7b5c8a122cf8ee008b0093cb734fe597.nq.gz
    ├── 01e34a3e41c0ff7d12e6f0aba6aade66f22636b5.nq.gz
    ├── 020463e9abd7ab66f9a7b0d56bd8f4aeb7e6aa9d.nq.gz
    ├── 020d752501f42d21de96cd59d07a7ef70112538c.nq.gz
    ├── 02348fa2cfabf8194bd0977a154e6c788bdc0255.nq.gz
    ├── 029932ac50608ec918092a833797ce17788eaf78.nq.gz
    ├── 02c2110eb3cd68d0b9f6b85e146ff7935540edce.nq.gz
    ├── 02c702b3ac47de13b1efac6b7ac36105a6db520a.nq.gz
    ├── 02cd60b06d7d7ae38192bc782b477cf4260f752c.nq.gz
    ├── 02d0c78306beefa0786e5a6d39a17e0f757f463c.nq.gz
    ├── 02e5ecd4ad5ead851916af40edbfc521dc8532ed.nq.gz
    ├── 02f9c11a8d0f03225b29a4b6b0ebfb3c1f8a6178.nq.gz
    ├── 02fcd376284f9a698409bad6726296dc06173b73.nq.gz
    ├── 033ae7f244dcde7de4150a9b2513564a6bc3aa3e.nq.gz
    ├── 03477e614be21bae05e90d678eede5b54409e9a4.nq.gz
    ├── 034b7edbef6ff0a26ad1c13bbfc5000c99837650.nq.gz
    ├── 039518eb2ffc983a462b905dc23a26d2cedb56e0.nq.gz
    ├── 03ae98ccb4961d3f0893c16e486a3b79fd471f81.nq.gz
    ├── 03e98403dec40d7094ca518f6e1487b3ac4b6633.nq.gz
    ├── 03ec44f3eede81cee9a4c8c812f62759e5994b6f.nq.gz
    ├── 03fa8fed4888a6f5fe80b23238e5895721661970.nq.gz
    ├── 0417ff79ff5911b23b29bfd85007f9289c79a355.nq.gz
    ├── 0437358ba175306c18eaaec84901d990dfa6030c.nq.gz
    ├── 04559183f60577f7a8747e51959a00e04ba180b0.nq.gz
    ├── 046cfd171ee71533eea530b7c06019d1ef99d793.nq.gz
    ├── 0502363ca421bb3938222dc26e6734a44c164cba.nq.gz
    ├── 0505ac6b8555646552363c640b2ceb205f0b4a41.nq.gz
    ├── 050b3542292a7788bf4491a27c670e025f0bcfcd.nq.gz
    ├── 05408b8b4aa8352c74b462d9f0dfdaa814376d7e.nq.gz
    ├── 0564e0b149332ecce2c5825bd383307c7c9f2997.nq.gz
    ├── 056d7efd293ab8a0ddec3ff803382826a2668b2b.nq.gz
    ├── 056f01ad57aba91ea2107407cb970be0311d04d6.nq.gz
    ├── 05878c3b7676283ded9c91382a213555766ebc82.nq.gz
    ├── 058d793dafd6fa75bce638850ae18e885448b09b.nq.gz
    ├── 058e6c4f6d29e17d8006edffc504606dc2ba7f00.nq.gz
    ├── 0593bd653119ca3ddd18583cefb56948080d62fc.nq.gz
    ├── 05b7adf420bf445c7f127849b261b847a1c895f5.nq.gz
    ├── 05e711cb5a79767a09c520ea9c92ea36f72324b9.nq.gz
    ├── 060d39ae501447ed1966025761912569fae5cae6.nq.gz
    ├── 061f657a843222157822706ff7cc457eee0fc83a.nq.gz
    ├── 0640144970061082be77eb2fa453ee1e1355f67b.nq.gz
    ├── 064b820dc1ebe9d9ac0069a5f2a616a10b36995c.nq.gz
    ├── 06a579b2d945ffa3fdd798b848bc72e10905dd6b.nq.gz
    ├── 06b35f6763b03e2b142f2d00467b1b710bb039d1.nq.gz
    ├── 07122e9a09b43c69739dd54309240ef20be9081b.nq.gz
    ├── 0726a9aa4ab44e1b32289dd8f063e5658cd231d1.nq.gz
    ├── 073c09d64cf5554b0145bf15b5d5c9da86208e70.nq.gz
    ├── 0744b85fa600d1d7c88f676ecf8ea8f8388a4963.nq.gz
    ├── 07491f70ac7bf75790cf195293b9f482e49a30f9.nq.gz
    ├── 075a9f8be0e4a4815ebe2f55376f3c573a50af9f.nq.gz
    ├── 0761f652cf6aeb58d0fcdf4606158e5eb0722e91.nq.gz
    ├── 0780c18c85b97a9f27839ca33e59a88597334191.nq.gz
    ├── 0806d26b3449e20f932107e237a3b36d1e653fcf.nq.gz
    ├── 08098a7eeaa1dbbea51f8b2683e32baa356a0acb.nq.gz
    ├── 083727156de9039b060d2f2090dd8f4f36e5b233.nq.gz
    ├── 085aa8836bc65151634cf7744841b4b9d4caa20a.nq.gz
    ├── 0871cb1c446b644d3c9af7847775ff6aa89c1def.nq.gz
    ├── 089247b10d992e44f1c6cbd641badd0f0d7a53ee.nq.gz
    ├── 08a639fdcbdb28c28bcaf749d3d5549bedad415b.nq.gz
    ├── 08f7e5569e74a46b0dfbb9bedc0e15496ea0c1a8.nq.gz
    ├── 0909cb02b2603ba9a43c82c8d4de28528a87b49c.nq.gz
    ├── 090b19a1c66e1e3750b62fb910201216ba589264.nq.gz
    ├── 09288c344db010cbf985fb3616ec553347de694a.nq.gz
    ├── 0928ff5b04b09d5b11ab8ee005684ad97597b80f.nq.gz
    ├── 0934d9402b19e7bed61d4c4c915e1a4b381307f5.nq.gz
    ├── 0995358d4d43ac9fd098de497b89b4a68f419afe.nq.gz
    ├── 09ec92c37d67a36e7add568683927adb0c10e4e5.nq.gz
    ├── 0a17962afafc35ae77a55828c6b9ebbd6ff0d282.nq.gz
    ├── 0a6244e1e7c0ec5d02dff7f5b57ebc8a557878e5.nq.gz
    ├── 0a79cc06ab091e10d4f4353235d529d5d9c30739.nq.gz
    ├── 0af1ea3810cd7ed19ebdacd5ab0db28976d54bca.nq.gz
    ├── 0b09e915bba29dcc5dad9e65b74dd55b09f07c23.nq.gz
    ├── 0b5569480f600b4e2e64431ee85ef156466deeb7.nq.gz
    ├── 0b6441c3fec36a73cdc1d474a41599432ca0b5a2.nq.gz
    ├── 0b85c9bff274e940a8db90163876dce71e5324d2.nq.gz
    ├── 0b9410feab7936244f48d1a18afd94877e1189bd.nq.gz
    ├── 0b9822a9c3fa8124cb574c773e2d54f9a4c1a88b.nq.gz
    ├── 0bcbd208c627acf4bb77783db9ef9c36ded31408.nq.gz
    ├── 0beb20790127d21fdae1ff55d3cc4b119a56f1cb.nq.gz
    ├── 0c0cce7da13b4c86d365cc6b317cabb4359c2071.nq.gz
    ├── 0c2390e191ccae090fc4e35b872aa9cee5229c45.nq.gz
    ├── 0c33d62351031ace7aa6b522576294da3c2e7c9c.nq.gz
    ├── 0c50f727dd8d4ae5dfccf19c45d735f57768aa28.nq.gz
    ├── 0c605661c069ac398485feec5752af6bf845d826.nq.gz
    ├── 0c63eafc769e0c4d1de1d74949cde80ee6070b72.nq.gz
    ├── 0cb0b36976f7244078704215e91a9003a700ed73.nq.gz
    ├── 0cc13766478f947bebe710ed584f27f6f6abdd75.nq.gz
    ├── 0ce96ff529c6d600d42e35c94d6e38e990659b31.nq.gz
    ├── 0d045ecf2931e6ecc137224ff7fa50953ca230d7.nq.gz
    ├── 0d0cbca20da310e4c09a83cd8b682439991be1f7.nq.gz
    ├── 0d6afa96c41be067578bf945999b6b553641b5fb.nq.gz
    ├── 0d9cd08c748ed5113a22cfb1f1dadb5c63af2303.nq.gz
    ├── 0dab083b77cc4b9f546d6d4883f38fa651914bc4.nq.gz
    ├── 0db2181c862d8c8da4979dd64630fdd4c950d67e.nq.gz
    ├── 0dfee1cbac5035858ec28a8d88d831093a90e246.nq.gz
    ├── 0e0836a1fedd98d8f6c1054361d6b04ce6471541.nq.gz
    ├── 0e119533cc90fbbff805d326105ab0ca52c1a5ad.nq.gz
    ├── 0e1bc3c0d15d17ca3c87541cc01951b1b5bfb45a.nq.gz
    ├── 0e30ac4bd7396d52982112ee4f5078a858ee67c8.nq.gz
    ├── 0e6cf281c51bd59a7239da54765880cb564e7677.nq.gz
    ├── 0e706ffb2f2132f1c696acd00e4d0385589c974e.nq.gz
    ├── 0e8ab55d4267969cffc7e45a05a1c1b7502220e3.nq.gz
    ├── 0ea0376edbf9e8ccf85a88c61a812dc26042cf19.nq.gz
    ├── 0ef93db93619bbc92a3fb7030470ea3aad59a90f.nq.gz
    ├── 0f21745d4faa5488ca9dbc4ab479417d1a29b24f.nq.gz
    ├── 0f4f0798fed0b6dc4d4ec9aa95313db79c944058.nq.gz
    ├── 0f8f4ae31a276b019e19fc9afde0135aad091000.nq.gz
    ├── 0fa4825e8f86df15b2fe550b0f34559a9de3c1bd.nq.gz
    ├── 0ffb33ec0d4b1d17a02569c171a0d84478293df9.nq.gz
    ├── 10216cd12342638a5dd2ff62ebbf603ba7f4e07a.nq.gz
    ├── 1024216a13e8998d9ce86a977e2e0e2f0e4009d5.nq.gz
    ├── 10246564202ff3f613d515444a266280ce5b5c16.nq.gz
    ├── 107250ec06afbb299c3405d930a64970ae7c5312.nq.gz
    ├── 107f093bc83bef585c6d96f665d079b0ea0275fa.nq.gz
    ├── 10b6ef46f37b6aaa1a8bd890dde2631fc4ae0ad4.nq.gz
    ├── 10e5029a0aa8963d518daa4ed6827c7ca64b071e.nq.gz
    ├── 1110d83a72178ed6b0b09db6b1ee40f4b8b0cbb2.nq.gz
    ├── 111491f5356651aa15aff3de64c2a62eb5050200.nq.gz
    ├── 1130deef45a26ac1f38d9f2bb48188c5caf12413.nq.gz
    ├── 1130dfd8b9e8911cc4876788976fca4911f8a037.nq.gz
    ├── 114e4f9babc0b1882bd6e03b1361849e8c978d0f.nq.gz
    ├── 117eab458afb78140030188694ac01d0b32f71cd.nq.gz
    ├── 118f681807589f3e2c18891e0dad8496f20cf164.nq.gz
    ├── 11b9108da221f4e5c0b83dde9fc9d14a6c01ddb5.nq.gz
    ├── 11d3dc08643f0c08d3dd56a82ba2e59ac9a8dc30.nq.gz
    ├── 11f9817bd28c836aedc6f45dcd80a07bba774a93.nq.gz
    ├── 1235589009ecb1adb7630f0a6ec77cbbccf40a34.nq.gz
    ├── 125de6a8e18b420eb4d73afecf815cb247c0a17a.nq.gz
    ├── 12618459bd1cbfa17cc1579bf6c02853d8839a6f.nq.gz
    ├── 127909bfba81ef429de3c51fe7ecd0e35be1c366.nq.gz
    ├── 129cdcbfe7920b7d1a65faf690b9d5f53d007e7d.nq.gz
    ├── 12cdeabe2252471c569579e9fb97daf175a95ea5.nq.gz
    ├── 12fdbc25a746cb86c1dd449bc0c029fe5ba3cf24.nq.gz
    ├── 1307572e185dca13ff24ad953d0175c4dfd24317.nq.gz
    ├── 132ace9bef45828b95e61beaec4f915c42a299e0.nq.gz
    ├── 132b5c518702fe2c6b942f034993a89dc35fdba7.nq.gz
    ├── 133c5e3cda245756be3a34edcb05ef13c0c634db.nq.gz
    ├── 13428c0d1bf1ce951a3b85a0975a10866b6e17b1.nq.gz
    ├── 137148ae98634df3a5f60beef9d0b69eea506a9c.nq.gz
    ├── 138e3fd852bb3f543025b5afa903c0705106c60c.nq.gz
    ├── 139c25bdc05b49c5e91842d8c55a429fc556de69.nq.gz
    ├── 13a30a441ba0e0a4ef153bbffbb0e00beebe61c4.nq.gz
    ├── 1407397e7dacde396a20566dba5e5a9cb70dde26.nq.gz
    ├── 14281fb5f2184f0e5ff4948ffc6b86dba8e1af12.nq.gz
    ├── 142d1bcdaaafde927fb536258d24a143f5015cc9.nq.gz
    ├── 142d6c9740d7d44254bc113930c74d7f2c16b8c3.nq.gz
    ├── 144311429eb6141e21b9f61050e515b9db15e87b.nq.gz
    ├── 14509547269776155684d7b4e2093e32306799d9.nq.gz
    ├── 147f8e56aec7454acb65262073e2732cd0e558a4.nq.gz
    ├── 147fbcaba377045f26560c482136f0752805977b.nq.gz
    ├── 149a4c0904cc5e447c153697ee39c10d844b060d.nq.gz
    ├── 14ada42508ae54eebb509c05c8b07a39cf8487ee.nq.gz
    ├── 14c0357d9a7c929d50ba48d944f15b345a5d72e8.nq.gz
    ├── 14c859df2bcda08c4d1973c3614f8626bf22bc06.nq.gz
    ├── 14efcc57f63ce4f22b6b322687f1052f4ef96b85.nq.gz
    ├── 14f759a951efd764bd220e9a4fe14fb1baf9e648.nq.gz
    ├── 15061581444cd2813d05c537dbc7c47a7bf29afb.nq.gz
    ├── 153ffc72f0ffe7bdd778d38cca3d06f1a022b098.nq.gz
    ├── 158940dbd5ab6e69a3b472f52172727bdfecfb5b.nq.gz
    ├── 15d07b8ab0526e41d8a64e1b451075e6c5f06667.nq.gz
    ├── 15e3db5b9f6ae85c064804426ccc7c62697ae476.nq.gz
    ├── 160abfd680f4c2f4807b2cca6f91d03ca110467e.nq.gz
    ├── 160ac7ca2f2ea10f4e8fb9457caea056e1c9e796.nq.gz
    ├── 1641a4e9224f8225ea8894f9fc4c4b3a722c2720.nq.gz
    ├── 1664f298833b672ec7b4f6f7e4af0191fe0de87f.nq.gz
    ├── 167d5dca5b5ba9d05d008552ff846864488169f2.nq.gz
    ├── 167db887c85a6e6391a1ff4e5959acbd8475739d.nq.gz
    ├── 1688f7d0415adfa27637fe5da22f8d2312a7f3b5.nq.gz
    ├── 1697009e8955ef4e3336abb32ead7932a424598a.nq.gz
    ├── 16aa5c23585e50865e11b541ed2e41e9e842bcd5.nq.gz
    ├── 1714a53459676c8875961e4c0fa1aeefac0c41af.nq.gz
    ├── 1734d0ccd3d6c1aeb36ecf686b4abe8848a3d040.nq.gz
    ├── 1745704e4b7c452d61cbd7c8dfd79eab6d69185e.nq.gz
    ├── 175e98540a5b81dc69ea61ea6ff1961bb3533867.nq.gz
    ├── 1782f588c3bc9c2d664a30f2e7ad3af405c0b384.nq.gz
    ├── 17fdf07919a32354f03ff8a846e72a50fab5e682.nq.gz
    ├── 18055ef0c49a4b07d0a792df70509d36046aec8b.nq.gz
    ├── 180f52f64c7ac2cd52bc985e07a6acbe729ad60c.nq.gz
    ├── 183cc7d314efcaa913a7dc3b6f21dc3351ffadbd.nq.gz
    ├── 185209ddf31bc3b6e9893b414c06df449bc4c698.nq.gz
    ├── 18566a2078f95272180c3b9936cb282d711ad4d1.nq.gz
    └── 1860999e401b6cc84e035b41b4e9fb8060d7641e.nq.gz

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

[rubocop-hq/rubocop](https://github.com/rubocop-hq/rubocop)

---
*Parsed on 2026-04-11 by [repolex](https://repolex.ai)*
