# Repolex Knowledge Graph of canonical/vault-k8s-operator

RDF knowledge graph data for [canonical/vault-k8s-operator](https://github.com/canonical/vault-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/vault-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1e34b07b5420792768f498e79ea54d566ff28df2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1e34b07b5420792768f498e79ea54d566ff28df2
│           └── chunk-001.nq.gz
└── blob
    ├── 00eabd73fd5dfa67a9940ba021abf3c008147e19.nq.gz
    ├── 0124f27d851dca57886af88a15fd715ac2be2ca6.nq.gz
    ├── 024082231f8aed00de5990dacec4df5f8977b7d2.nq.gz
    ├── 04ff0e0cbfec26732b084f00e74cc2b0717caf62.nq.gz
    ├── 0798da9ef2a86e38052fed805cfab0b6e6537b58.nq.gz
    ├── 07e0b48cbd1569fbf0e610fa77b6a4e96330574f.nq.gz
    ├── 097265fa4a55f77c594ad944ae3f18b4e323f402.nq.gz
    ├── 0a5117663e598de8aad04629b04218cc0c91edcc.nq.gz
    ├── 0a74478a0868a246e5fae34dfb80264a21347234.nq.gz
    ├── 0a89e26719ede3be5d17f74fe4c92d697f5bb197.nq.gz
    ├── 136eb0b2cd3b5f7e72c7a2b2a23613456c28ff03.nq.gz
    ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
    ├── 15457f89d95d11a24437cd69d26db3a21dc6c1a4.nq.gz
    ├── 1892b7cbc15107a5cae104bc3e2a4f6b0d09a9cb.nq.gz
    ├── 18bd002c8a423dacd0761cbfabb844df092e56ce.nq.gz
    ├── 19081ff581d036fa9031035cef69e51d0bc120ed.nq.gz
    ├── 195165c724a7c5a1deb7c4a9d3cc71da9e1b9971.nq.gz
    ├── 1b0f8edf9757ef1e5c658fe487f37d7ecce054b1.nq.gz
    ├── 1bc75a12c9ef432d82914648d1cee8b6cdddff79.nq.gz
    ├── 1d78fdb83b327174326933eb8f3584b2fbe152c9.nq.gz
    ├── 1dfb83b060a04ec39e22bcdb38f5949ff3f5aba5.nq.gz
    ├── 1e1f8151fde544533412137e3ba40b1a7a8fd4d1.nq.gz
    ├── 2150618d474e31790b3fdc64f8f3ac88c3318301.nq.gz
    ├── 23a65f8295b129ee0d376d1530a9b4133caaec3d.nq.gz
    ├── 23b14dc09f46a8dbe8540f6acb5d68c41e6aa725.nq.gz
    ├── 23ba110c9c7fc3c18b0ee682bb8844aa20fbb2ba.nq.gz
    ├── 24386294dd048642c3729581b380396216a27503.nq.gz
    ├── 25df5f102a55a8926fe5bdbefd56054543e1b359.nq.gz
    ├── 25f217edfdb8dbdaead1ad8bd9b52e4d544c37f1.nq.gz
    ├── 2652398737ab7bb447699e16285e5456d86624f7.nq.gz
    ├── 285d029c7c3bc8816356def39e5cb4ffe75f8d43.nq.gz
    ├── 29618ad83a08653a2b58f95155fb95bacb6865ae.nq.gz
    ├── 2ab001c8ea61ab035c48c6175228181b20a2fb65.nq.gz
    ├── 2c050374f244e0b9c84bf76a349ce0c7cd39ec77.nq.gz
    ├── 2e1e78719a4af668955e16a5a45d0694ab740f5d.nq.gz
    ├── 2eae080ded555d42e52f538acd12604ddc20e1a6.nq.gz
    ├── 3014a84f49e5da629a320e61b44bb11e73fea385.nq.gz
    ├── 3273f93ad3633572e01c6674c261e1ad6731d918.nq.gz
    ├── 32795ab7fca4511444170eaf8facebdd1a76b4c3.nq.gz
    ├── 32e60fea8f1b692eba07f94641adf7de2f12ce56.nq.gz
    ├── 3395115f031d2897f7d190a1716935b4b290c21c.nq.gz
    ├── 33e8c1e54664224e755c536c4c2cf47cc16244be.nq.gz
    ├── 35c6866a7bb4ec8e796321fe69a2d5d01a3f05cb.nq.gz
    ├── 38945df62ea35c49748755949e31c982c94523f1.nq.gz
    ├── 3898084eee149cc8f995150f3fa26bb2e4bab507.nq.gz
    ├── 3899470154dd9a0b63b513c2f1aae950caac123d.nq.gz
    ├── 38c41125667e0c329b13f98eb312898ee7f50b88.nq.gz
    ├── 393dd8d5da31b3f078f20301b9fc6ea06e38a175.nq.gz
    ├── 3ad9db254645c52aaf1585fd9518783880af70c1.nq.gz
    ├── 3ca99d9106bd9451d4d197e3d4a30e04114a3656.nq.gz
    ├── 4015f329ccd3ff53df15a91c9988e49b9986f1e6.nq.gz
    ├── 4162545c8469e09d9a6a27030c0a0119976ff3d4.nq.gz
    ├── 4339f4fd3059f155950a13a635544aeb3c976bb0.nq.gz
    ├── 43942c19f7157c2888bbcdfc9bbad04b9ef3482a.nq.gz
    ├── 44b00be20208f6b3359d61aede2e887e18141b7a.nq.gz
    ├── 44b41f1661efff7fcb70904e14ed44b387f9ee3f.nq.gz
    ├── 44cf8ca4167d19c2e7dc2f3d8f7a7635ce8861de.nq.gz
    ├── 453b4f7a07b459809c15121d634ef4d05397fe11.nq.gz
    ├── 4802e6f484dd4eb89f25d8cfcd294699e149f9a9.nq.gz
    ├── 4ca89de5c9bb72d6a73e8ebe5236d74d37ecea94.nq.gz
    ├── 4e17f6c2dadf206c068cb4f4b6eaf3a980175180.nq.gz
    ├── 4f2f823c82f89ee7fed91b835db038d4fa3d0a17.nq.gz
    ├── 507dd24042d3948b37b17fa4c62c2384d34d4019.nq.gz
    ├── 5128cd234a1e0c89fe0b10b6320baa52d6064b1b.nq.gz
    ├── 5145f06642119310a4066379488be8cdce819e02.nq.gz
    ├── 51f0596525f7c77572e316a4c5d1fb6da0417e86.nq.gz
    ├── 5235247b69b9f5b71c50e013b667f4ab41bc7b5a.nq.gz
    ├── 53b74b36df4ad9f4b0d1961b91f4d103470fbb04.nq.gz
    ├── 55032410f062cd082bc275819abf067fd303fbff.nq.gz
    ├── 55efa58a6e2221902e19781ee7b54452cb25d654.nq.gz
    ├── 575d13bde5386f4974ec611d7e9a56f674882819.nq.gz
    ├── 57cdb8e1c9743db7352b749b9893b41c547f4d28.nq.gz
    ├── 58079e9ccedfebad15c95d8861bf9dc03a1b2b8b.nq.gz
    ├── 59733e80e6c650cfa355dd0fea1e785c141d1407.nq.gz
    ├── 598c32d46bb4d9f1fdbd7d4fdee908f3ca934f90.nq.gz
    ├── 5c131146898bda7f61486d79786880d120e8c7e2.nq.gz
    ├── 6255455f8f011f811fc7735bb3f782c4c85d89f3.nq.gz
    ├── 626485947cf404030ede5bbcdb3951e7f333565f.nq.gz
    ├── 62d674f52069707757299f3ed7445227682ac72a.nq.gz
    ├── 6415534ff0382f8c7849aeb522e5c3206317d615.nq.gz
    ├── 6505a48b4ea514fa190ec6e5ea0f71b9d3e38e72.nq.gz
    ├── 65f1630f942d0591b94fc6a14cd9c9280289dfbd.nq.gz
    ├── 6637f918f9f54cdcab68276de5d2677308f7085a.nq.gz
    ├── 6664bec3559d35eda1a4a89106a83bf3f3df56dc.nq.gz
    ├── 675a74b2923efabf12aea917eabd7fe6a80e5381.nq.gz
    ├── 681f1bf9352b74ed914e777b8580986f5c1623dc.nq.gz
    ├── 693aacd70dfeafa1349c1d38168537eab7035878.nq.gz
    ├── 693abecf905b9a759f6d1101e7dd942f31591fa0.nq.gz
    ├── 69a79bc3c7074205945b86bcbc71cb7f906d2bc0.nq.gz
    ├── 6a828674e60cb2088e1e2d9b55f656ae2245cc7a.nq.gz
    ├── 6bb16afc519c7cedd91dc63ddd37e229b4540a98.nq.gz
    ├── 6c347f61564b26cf67784a322128c97833c391a0.nq.gz
    ├── 6d312b6f6665aea06e325b3ed658d1136196c2b8.nq.gz
    ├── 6de7bec9b4f98ecfbcc13981d4189e4331d8fe04.nq.gz
    ├── 6ee9b40a268b6e47433280b648d7e1bfeae670ca.nq.gz
    ├── 6efca8dbfc4249e41884881f4e2287260f3d37dd.nq.gz
    ├── 6ff2c83b6f0178d12d6caf00ea4e73bebdf5efbe.nq.gz
    ├── 7118087b4f1822b634007668f8df90cb6001709e.nq.gz
    ├── 718b55febcc896a3cfa181258afa2bf0dbcad223.nq.gz
    ├── 73b324c4ce8447c7ba28ebd6036e034bb2d37304.nq.gz
    ├── 749ce1217149cd7c3356ed38f18ad0473979e7a5.nq.gz
    ├── 752005fd5adafd6b1a78b124a4c27f6b5dad0f40.nq.gz
    ├── 76ff70a96e77f9b00eda727129b7ba720ca4649c.nq.gz
    ├── 77d8eb3a6507fc98fc219e5e7fc12091aa14ad84.nq.gz
    ├── 78f3a0b28cb810af18708416249ec4dcfc0b00c5.nq.gz
    ├── 7b4a9bf3c17ab45b5effaef27d375b7a4863de81.nq.gz
    ├── 7b852262227c81eba3f73f1ace94a66bcfefd473.nq.gz
    ├── 7c14c4d0fce12c33ed8a87cbd4e1dd07dd1e7e2e.nq.gz
    ├── 7c61e5851814f492dda9e93b45493ccbf9b9f573.nq.gz
    ├── 7cc5a3de8482bf229047c18b90158c996d064dc7.nq.gz
    ├── 7de130876e9d8da851002a5d056a15ae491edc15.nq.gz
    ├── 7e3cc4242a663c3227f90a4c7c5aedb8636a4eb9.nq.gz
    ├── 7f9b5003b02c21962bf9de68a23297116fd4539c.nq.gz
    ├── 803669cbfa34b12b733867914c25dab06c3a46fd.nq.gz
    ├── 8056e128afeee37077fbc1ca8574f551757a6963.nq.gz
    ├── 80bd71e0b4a04f7aea31ef2d083b599a769163d8.nq.gz
    ├── 832d699e7d7dad88affefedf707f4d4afe78ece4.nq.gz
    ├── 83fdaa62f165aeacd8a1dae35caf2fb9a3c901b0.nq.gz
    ├── 844ba116f2d0e801e424f40ade3d462e60217dbb.nq.gz
    ├── 856fa7dd4dd2adb5d14ce097902700c7f5a71b24.nq.gz
    ├── 856fef69fd7c6647ab20b981ad2643d3e5807f19.nq.gz
    ├── 861e6de07647dfff0cb219c626d0fd59b247b843.nq.gz
    ├── 872e14486066b17c73ded08efb9295787f343e63.nq.gz
    ├── 8b17ec65cdc092d47f4d4098193c7ff16a46c08a.nq.gz
    ├── 8b46b610ee760cec61c2afd9f15b1d62d752d25d.nq.gz
    ├── 8c61ac97df7f93d184f5d2194082124a1c80950e.nq.gz
    ├── 8d771e187ba4b2ced1b643c804548e5c014bab70.nq.gz
    ├── 8e79e83ae607a07d78d9948362a5c543bd70fe08.nq.gz
    ├── 90c72273c3c5158b74d8a6f301927e4889975a61.nq.gz
    ├── 92f6ea4186fb2bdfc9594b0dd06ca7961f8e053d.nq.gz
    ├── 93a30a0bc106aecafa492024d2e48d2f1f681fec.nq.gz
    ├── 94306076d70a825ff4eaa71fbda55ddfeb473917.nq.gz
    ├── 94e7044eb352e8ac8c2b3320befd42338d93ada3.nq.gz
    ├── 963fbe1817cfec698a7047a20216b4aaaba32bce.nq.gz
    ├── 9678c93f2a99d621cbcf1f2f6ad33dfa7df1cb2a.nq.gz
    ├── 9841311346737214f59fd7c9e25ffb284029f3fa.nq.gz
    ├── 993fe7c02f7925308b7f13c52a85d88b3f182cc5.nq.gz
    ├── 9af8e723c7a3ab5c5235e37112acaf47ab096088.nq.gz
    ├── 9ba21b19645762e0443660116151152a5c102fc6.nq.gz
    ├── 9d8ebf44493d7f877037ff4a14a7227c219ac2e4.nq.gz
    ├── 9eca8cf705b1c07527231c0e8aecb09f339e00f1.nq.gz
    ├── 9f098ec47f1f25316cd3ee938f1d03e296b74cbd.nq.gz
    ├── 9f3a7f746c034a0c0ec570e95baaf7cde4003248.nq.gz
    ├── 9f5e570e61bcb4cf135785ad7c2fabd104d1c506.nq.gz
    ├── a1d3f0cb995ec226ffe6787cc2230616e2c29df4.nq.gz
    ├── a2a270d78bfbeb0945f9094140cb756e30814a13.nq.gz
    ├── a5b811dd97f5167fba41e131fc8a1356ddbdfdd7.nq.gz
    ├── a687d98480e94cb70b2ffca75a5166560196b7f8.nq.gz
    ├── a6af4cbafe901a3f570ea1c877452578224cc441.nq.gz
    ├── a823978e88572f1cd94d0a5a27cf8d83d2bd6399.nq.gz
    ├── ab36c3a88ee9af920b5c19f677cd3df625ee515b.nq.gz
    ├── ab7acd2beab5a45d664099b625050f810f6d6042.nq.gz
    ├── ad58cd01140c7c88fd7cf5af5e27d591b55b233a.nq.gz
    ├── aeb188014d7f0a04a5799802e41709972aa68441.nq.gz
    ├── af7718dd5ffb6c53aa212669dc46323307d824bd.nq.gz
    ├── b091fce2b0b8d52cbea77c66ca74ec790de6514c.nq.gz
    ├── b09404ae6f93e66ea326ea68268b6c34c7a62fa8.nq.gz
    ├── b09e7d7f32444794b36dd07c9a5cd14674fbe7c4.nq.gz
    ├── b368333d2b9fc8a3b1077e589ce838a7dd924a4e.nq.gz
    ├── b5c00a4eb5a79f7174bd44c643e295bbc0eaa8e5.nq.gz
    ├── b68deb45fcf6d8646e219524c770326f310ecc06.nq.gz
    ├── b961a37430760486a8143cd50de518d71dfaa6cc.nq.gz
    ├── bac83f919bc08412740fc1c93954c6ec230dd253.nq.gz
    ├── bc31d922399666b4c3701505815af04cee4bcf30.nq.gz
    ├── bc646543a19993fb2913ece6c54e91706574ff95.nq.gz
    ├── bc73adbedd91a5a113fbb29ab43b84e24b61eb69.nq.gz
    ├── bd87fcd2857abb1f7e365043c90d6e73d9942878.nq.gz
    ├── beb2367cb0437653dc3bc9aeb644449c2e9da9d7.nq.gz
    ├── bef1b8f0437207e8b265dc233fbe68e4db577869.nq.gz
    ├── bf23c0750c5cbaae2121779674fd9a190159cb6c.nq.gz
    ├── bf4e35cbdd71068088d9c40e22b16949d1c29a9b.nq.gz
    ├── c1a119f7e40b23af4d871a19ccbdcf3c8749dceb.nq.gz
    ├── c6d16ebdab59fb93f885e68e703a6ee017c82656.nq.gz
    ├── c81f048ab6a6d5f3849970d305fc0828612cb88f.nq.gz
    ├── c82291c4781866d055a32f490b387b1f0cbeb363.nq.gz
    ├── c869bb5778f7e3d92d63c00cec49616c0aa8d9f0.nq.gz
    ├── c877fc343e5d0d6cb11d8bc658746f15131950b1.nq.gz
    ├── ca65c470fc26b0c5cf9d29e38f59893c2b9345a4.nq.gz
    ├── cc89a45acc730c46e2c9b1a34a271e73c8b987df.nq.gz
    ├── ccc5504830f5efa059e171841a7965701f04bf85.nq.gz
    ├── cd0570dd30ceaa919e47cd855e2ea70c5fcd0548.nq.gz
    ├── cd5ac039d67e0bdadb17976e4ac39f0ffe6bb6e4.nq.gz
    ├── ce46db8e81ce4875e97640e1462de8c0b7d59003.nq.gz
    ├── d0a7695899c4572f564a79beafd358f4d8536278.nq.gz
    ├── d0db1c9af03eb5791dfeca885b10783895e3ed2f.nq.gz
    ├── d1c82b7acf4f83363d72b22adfea3fe544e51f18.nq.gz
    ├── d2a31d0ceafb5bc313cbe3b9f5212ae5ec2a7cd4.nq.gz
    ├── d2eeb29a409e669be01fff77732fbbe8e7d16522.nq.gz
    ├── d5ed39ed07514e30844e8a65a10cb0f8d21b9584.nq.gz
    ├── d60c06711bdd3c7d9fadfad72a68fbf954240055.nq.gz
    ├── d6b5cfcd0c9adc494173e22d8ee8822309f60368.nq.gz
    ├── d726b230005ad461cfa22757a75bb340adc0d317.nq.gz
    ├── da06d28b2f78f8e3473d929fe6a8778be0a5d6f4.nq.gz
    ├── da38ad47055f3b7afa333b123515988cb887b4f0.nq.gz
    ├── db39a9f1e86f2eb5a7860b08dc1016031e765265.nq.gz
    ├── dbfca323f285ee0c6a4883d7a5ed0d8dea2ade24.nq.gz
    ├── def184c90893b56dd5599f14cf89a6a11bf43559.nq.gz
    └── e03c52eca7a4c1d700605e00861585e53e8caecb.nq.gz

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

[canonical/vault-k8s-operator](https://github.com/canonical/vault-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
