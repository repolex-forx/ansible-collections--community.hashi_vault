# Repolex Knowledge Graph of ansible-collections/community.hashi_vault

RDF knowledge graph data for [ansible-collections/community.hashi_vault](https://github.com/ansible-collections/community.hashi_vault), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.hashi_vault
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2a0b75ce88e1deb08822b587461f2987b7710c72
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2a0b75ce88e1deb08822b587461f2987b7710c72
│           └── chunk-001.nq.gz
└── blob
    ├── 00477c874e555c9895e625164576f3c6a72e6293.nq.gz
    ├── 012b300f1786e4863d3823b7745b878ec61a09da.nq.gz
    ├── 019bf1647eecd55e00350b992d444c41289836c2.nq.gz
    ├── 01dbb225cf7495e970dac4ac5bb52860a3b410e0.nq.gz
    ├── 0248243d012a80758f3821256f4d8f17281d2339.nq.gz
    ├── 02685b3449a3beb603329de387048266ebf02e84.nq.gz
    ├── 0532124edf979016fcacfe677b5c0c6d719e66d8.nq.gz
    ├── 055c55e1dcfc19fd1d9546442a59440eb0215519.nq.gz
    ├── 05f9efcd30ec5a8a144c8966180d03335d3ae210.nq.gz
    ├── 067a219679c3f7f161dfff3ff5aa650f061021f9.nq.gz
    ├── 07d8674289d9b68c05888fb04598c79ce0520a95.nq.gz
    ├── 07fd051f6c206da5b2daae1ea08bf9c84646e645.nq.gz
    ├── 08e3c2ff714b6ba9692efaa8aea593b0add10293.nq.gz
    ├── 0907d3e01b4545198fb27f7e56805d3601bc95ac.nq.gz
    ├── 0a0a120ea707e8a64ab65d238a34bc2bac4f4da1.nq.gz
    ├── 0b111d5648cc1e38c8bce2db9a9ef5ff514d29ff.nq.gz
    ├── 0b13907784c47b5cfe613fe2ad15649736e2c1e7.nq.gz
    ├── 0c1bc6fcb4035a8e861c630167d0a18bbb50d3d0.nq.gz
    ├── 0e6d1007fd8fb83a7332098b2666c513daefdf47.nq.gz
    ├── 10c9432bcd07dad90ca73905a2847f36936b4fcc.nq.gz
    ├── 111ccdcf89721d3755d8ab7cb2d036fda7041304.nq.gz
    ├── 12301e0110a4c40fbbff591ac55e33b86591c1d8.nq.gz
    ├── 1240995664ccc176dbb42b49228253f9cb8056bf.nq.gz
    ├── 126af258d088e28a5ac4acdc2ee8c70f1d0372a8.nq.gz
    ├── 12763e969dfc663de61c59e267a2715584f28f07.nq.gz
    ├── 136c05e0d0290e2dc7eb89bceaa27b5f011e780a.nq.gz
    ├── 13ba3a468d119dfe4ad09200472d0d5634bf340d.nq.gz
    ├── 1406bed4fd38aa1030d17100b6cbaabb950e7578.nq.gz
    ├── 151b31e182e39431c2b74fc15eb6f1e4aee28872.nq.gz
    ├── 16540fbcde5fa0065154bb1913bfc0708dad7c4f.nq.gz
    ├── 16a491b1e80ea5b69bb6b8feec9e846679d3e94a.nq.gz
    ├── 18ff09ddca2b1fd4ac4d2312b67c07ea67448f01.nq.gz
    ├── 1900f50b30a0e64341381d53083d56b6ce0b6b05.nq.gz
    ├── 193d6fa5e555bf2b7c965d5aac7239fd44c9df19.nq.gz
    ├── 19db644bc8482c63ca418cef76ed20054573ebd7.nq.gz
    ├── 1af1cf90b6a19837bda1fc96da02900449f7e4b5.nq.gz
    ├── 1bb8bf6d7fd4c8d09aea89b47de20fb8bbb61626.nq.gz
    ├── 1cd005a2e4ca43038a1a3edde29de1f770370e8a.nq.gz
    ├── 1d12c29d165eb06af75912df338e478a885b008d.nq.gz
    ├── 1d23e79a2d41f28c6d373f9b32b5c6698cd5669d.nq.gz
    ├── 1d658037872a23baad429d12178a130511260ca2.nq.gz
    ├── 1ded0a3d5bdaeb9503823926fe69c7ce08126bd9.nq.gz
    ├── 1e2d687ad241ce7483504a392e338f5adeac7d78.nq.gz
    ├── 1e3024f118d9754830f6b9267d84875a1e9167b7.nq.gz
    ├── 1e7da87fd4081a8462854448647ae53fe37607a8.nq.gz
    ├── 1e905afc9807b924571c9f5552aba573a314493a.nq.gz
    ├── 1eb0d1ed21e5b8a3c99b630418dad32795d73905.nq.gz
    ├── 200db981190c93a8854b4c2ba20b6a19b491b5bd.nq.gz
    ├── 2017db92f5cf705633cb7421107163438f477200.nq.gz
    ├── 20fce915d07763c014b1d95164aa84b53f6a50bf.nq.gz
    ├── 210fb0ba998b94da78ad5ce9793aa5beaabf49eb.nq.gz
    ├── 224c6be6dbf710fb9297ae83d05be1b26dd7136a.nq.gz
    ├── 235d2a7b38c3b82f8036c176574a91e6c08aa437.nq.gz
    ├── 246bca94dc2bebb6fdec4a921d1d0f5f993276a3.nq.gz
    ├── 258d8d7983bc1136742f2152afbe68065a0ebdd3.nq.gz
    ├── 274a4461746f4d03f86a34342fe845358833695e.nq.gz
    ├── 27ffafb9263a0d0d7a768009895bf49aec66c8f1.nq.gz
    ├── 28137c4b71dd392e5022ed06d91f363db4bdbaef.nq.gz
    ├── 289e4ca8216c7393f60b73ef1a01fb60972557b8.nq.gz
    ├── 28ee92ddbe99f5cc9ffb45e1c191443c75008185.nq.gz
    ├── 290705e5eef63ce08f1f6f31bdc96848f82e12f3.nq.gz
    ├── 29904eb9d59337a2527694d21a17efc6474110ed.nq.gz
    ├── 29f4aff6e6ffe9de1db41661d4cac4e97a7a689b.nq.gz
    ├── 2b6694e65e69812b9eb7794b860fca494ad3ecef.nq.gz
    ├── 2c415d4b3b1d60b8ab35404f9dafd062542deb46.nq.gz
    ├── 2c929267fb9843ef97f2435e32e099a3d820213b.nq.gz
    ├── 2cbf596704f3728fdaa319381d0d794283002baa.nq.gz
    ├── 2cc0486bdd94cf815d8885ffb633bd7804038ea2.nq.gz
    ├── 2d6d16ae743d96ed57c93ce85a9af691fb54fba4.nq.gz
    ├── 2d948a9575c2e9630162d9e6b60280afb711910e.nq.gz
    ├── 2def98f083a5dd167be26ea4d071a04017c1fbb1.nq.gz
    ├── 2e6b7313b1db833ffa0f465c42293328181258d5.nq.gz
    ├── 2e9e470040df35f6f8e7e105ce54e44ac886b619.nq.gz
    ├── 2e9e730540cdce9c2590b01e0d39dc0f968a23f8.nq.gz
    ├── 2eaf842ca39313046ceef327f0629fea737f3e84.nq.gz
    ├── 2f703fbf018d74392a0e7f89e076d231f928ee8a.nq.gz
    ├── 30031f0762074bc5eb719bff76212423813cc85d.nq.gz
    ├── 30b3e707464bb86751e73cc24d548eaf39a5aaa8.nq.gz
    ├── 3116a06a3eb63948235720217d02940222ce5a15.nq.gz
    ├── 319be99bf24656a35e593263ca94cb1c79a541bc.nq.gz
    ├── 31aa868140126fc4051060e46700995102361c26.nq.gz
    ├── 329f6b94d61d7a2855be1685a015ab03f98ba15f.nq.gz
    ├── 32ccc0d36df92507c84850f779175e5e127ab878.nq.gz
    ├── 349d310e86da113041650cc190c28427e85ba4f2.nq.gz
    ├── 3512cd17121ffc9600d1a6381d96232925a483a9.nq.gz
    ├── 352428cc6469c58186bd6b9a8f2fb5eef92f8a86.nq.gz
    ├── 35a3c02f161d7fc2120ce2de02c86c0ffc87f4ea.nq.gz
    ├── 36a8a9203351b2780765a1d7b690e69275f9cdf9.nq.gz
    ├── 36dfbcec0a54e41d410e3adf2b6e4af72b1389ce.nq.gz
    ├── 372dd7ea6de062b7070c72108aa798ae54f79b57.nq.gz
    ├── 3753480e84e1fb0367cdbc598e0740ec637368d6.nq.gz
    ├── 37b3dd3f3bd44f87532ad584f08742fc3c42ac9b.nq.gz
    ├── 382997fa012de26334ed136bfdfc6945177ef014.nq.gz
    ├── 387195af9063fbb659c2d345540e103ca8e1e202.nq.gz
    ├── 38f8a532de9689ad9bcb0a711941472f7b8fc8cc.nq.gz
    ├── 3bec16d7cb8814b3418f2b327ca6365d03ec938c.nq.gz
    ├── 3c2ff255a8674ba82bf8eaa568956c371f8e7607.nq.gz
    ├── 3cc449b461fa6ed1f17482fc66ac113787d0186d.nq.gz
    ├── 3e650be6b3237ab73a0fe6de08f7a184482c4153.nq.gz
    ├── 3ed8696787bb6aedb6be75e5b4e835d85bbde4e5.nq.gz
    ├── 3f891566ea6935fc0d52d8ab5b9aa0e8e2dd6948.nq.gz
    ├── 4086901e7401f63d3b11e0f6c6ee754487154f2c.nq.gz
    ├── 40db30f3f60c0d212e9cc3f1fd7be6fd6ad34bfd.nq.gz
    ├── 4170d71f9c741a691a209acd20e4fc22bd7787ae.nq.gz
    ├── 420893c59fa17f44acca5a88677736a5a1cbc8b4.nq.gz
    ├── 420aa1b7640084bbff01e421933bc97a5ebc464e.nq.gz
    ├── 42633335beecb10d3f1120a71a0754e24efbf6c8.nq.gz
    ├── 429d401d35997c8bad32327bd5f377165069fd66.nq.gz
    ├── 42c72e891cf999dc3e1c05efe9afed50c531e446.nq.gz
    ├── 42ec2b1cad54971fce38b72adb99ae3628df899e.nq.gz
    ├── 43895af44f9d98d904d8743a3b6754f6e940e014.nq.gz
    ├── 43a28c9962983778e4c3d5489e2505c155b284c4.nq.gz
    ├── 44a6b9e2948c6e360ecbb5e81ecb808800e8c084.nq.gz
    ├── 44e2405ee8184f61790beb4baa1d45b01734dd32.nq.gz
    ├── 4507b1bd86655ae32d8e4df16b87f99f11bfa3ad.nq.gz
    ├── 456cd2adc9fa0a20253ab4ac488046a0121234e1.nq.gz
    ├── 457af229b0216cdf4a4a6dbdf62cbc2e2bd75c7b.nq.gz
    ├── 4645b5b0aab8e0adcb02ed0ef0c3bb8cc10d5f15.nq.gz
    ├── 4853d2c76f74f10ed0b49c2f9a25ed48b43e9129.nq.gz
    ├── 48671e64381359fdae01066cf5949f3c4be9b391.nq.gz
    ├── 486a49ab66b5ad7bc6dae187c55a9c027cd33869.nq.gz
    ├── 489b41e0e5eb3084201a9ab55cdc65434a590bb0.nq.gz
    ├── 48c2b10baeb9ce88344179dee5b900b055a3e63a.nq.gz
    ├── 4a1ec291abf337072265d7c72f5298326e0762a0.nq.gz
    ├── 4add1f4edc5e28fc4978b30d9762c61dff61b3f9.nq.gz
    ├── 4b058c0ce41dab3cc899acc0fd84914d0bd60bd9.nq.gz
    ├── 4b2251a283952193daf3f219f039f1230c54f5da.nq.gz
    ├── 4b3a017fd6d095140c43661ccc9a1b82df9bdf1e.nq.gz
    ├── 4bfceeddf776fe8327121938ca1d676cf4a61d9b.nq.gz
    ├── 4c598d06cd9ec6bb85f8236c54a4cceb6f446a04.nq.gz
    ├── 4d51ae24a6bc007202aeb5997a3be4b1e3fe9319.nq.gz
    ├── 4e52e7602bdf96316f4974618b9d37b876057091.nq.gz
    ├── 4e758b72e77733626be08d53199cca523b6d6f0b.nq.gz
    ├── 4f8f59614a5162d33faecb1692f511cd177677ba.nq.gz
    ├── 5003082a5b66b0967e06a71fa6a85300891a46b2.nq.gz
    ├── 50498e824c70b2513fb2b73dd4b8a9cf019e95d1.nq.gz
    ├── 50fc9cbe2f1a3e0befd2e3eb9fca0d36183bd2c5.nq.gz
    ├── 512cb5ddf7818caa79b7ea2a3bcb11da4fde7cf5.nq.gz
    ├── 5176c904c0c79981e62d5e725f0784c8f5c23950.nq.gz
    ├── 52593c0bb7abb664d55cd4f4a1b2964d5de29567.nq.gz
    ├── 5294e78f84f3b5a5aaa4a8ab547c4d3678e7e064.nq.gz
    ├── 52e03a406a20de17b3fca06332ea267522705a8e.nq.gz
    ├── 5317aa407d02f192f39a3284c0344f1f325c9b67.nq.gz
    ├── 5357addf44e444293741bba024b1fd0e51bfa078.nq.gz
    ├── 53cdbe3042755a0f62536512a4d24996d6d15181.nq.gz
    ├── 543d60c3fadc504bccefb83f168247ee6be365bc.nq.gz
    ├── 5543a7c9fc0a1afdbf59be9b2c602df48d478812.nq.gz
    ├── 55c27d4357cf7dabdef77605a6e7922a66060af5.nq.gz
    ├── 55d6e7a77e2b1f926963e68cb0b77db3bf6d8a8d.nq.gz
    ├── 55ec14d440c4d71534ffafa081fd9fd2ac2dbca7.nq.gz
    ├── 5640870ce7c40f0739b302791756bb1cd1c18d38.nq.gz
    ├── 57b27677bbdf9a6f4091e085499893e6cba1aafe.nq.gz
    ├── 57e7705262ec7827205143daec72f7f4d9b589f2.nq.gz
    ├── 5803f1e91dca9d4a991aae56be4072d5cedb71a1.nq.gz
    ├── 581e78ee3d8ea841fdc9b8dffe40f13d039ad994.nq.gz
    ├── 591abf7019ae2e9421b042e2f31bc0fe807a5ce2.nq.gz
    ├── 59ffbdabc1cbbbfcff0354dbeea42719856ef8a3.nq.gz
    ├── 5b79075ff5ca1d4a129d978dfd898c67bbfa4c12.nq.gz
    ├── 5c9d80c5d29b234aeecd1bf48589d3ac1c59fef6.nq.gz
    ├── 5d0a50d2a95ee42d57802d296949541ecbd4c07c.nq.gz
    ├── 5d31a32c302a15ba546f56b5eb366444b9783286.nq.gz
    ├── 5d602d66e51ba2766c23b96bf33c522bca2cf8f1.nq.gz
    ├── 5e4eb40479f417a3d10565f9f8905d72e183e88f.nq.gz
    ├── 5f04a155cf418a686695f6324e78bc89087aeeb6.nq.gz
    ├── 5f7da543df490bc868bcb64f30ef271eb0b63402.nq.gz
    ├── 60ec9cedf33b15b95cbf2ed41f8286deaf6246d2.nq.gz
    ├── 61056a54985217c234e5a718818b9a17b97958b0.nq.gz
    ├── 614e8f2c75446b13c915656ce23474f1c929384c.nq.gz
    ├── 617f750868d47832a3a9587cb8531ad214a1492c.nq.gz
    ├── 6237844c33b88341e01e95e9241920b57fbb81a3.nq.gz
    ├── 62a2388dbaf1293e5368aa7a0f30c03f25ecd0cd.nq.gz
    ├── 630f9f00f3a4fac866630e7eaa8cd33d25232bc9.nq.gz
    ├── 637b4fbf902ec19a92f967bade96af11f3571c1a.nq.gz
    ├── 642fd18bb4b59ed1a4d6a738e8b892892b024758.nq.gz
    ├── 648f9063b2da9b8ef9d68fe30559ee38b33b9ac8.nq.gz
    ├── 64f40d8451ad817b6a612e182d2f1d92fa72329f.nq.gz
    ├── 66546781cfab5d8ef3ed17b220f3144f110ff3ba.nq.gz
    ├── 66df9ff411bc1c64cc375e186425b189f2d402d9.nq.gz
    ├── 67b9bd61c8e21e00cf990f793e366cefd2b924cc.nq.gz
    ├── 67e9981eaca45d42436cfe4aa2974b3bee161f48.nq.gz
    ├── 68e0f2f6567246c53814bdcfca8c8d2be648aa48.nq.gz
    ├── 6a58c6e4eda6cc35ab737d9fb35b3324d077510c.nq.gz
    ├── 6a96b64e17b2ffe45544f840755cd85162e4e759.nq.gz
    ├── 6b9b827229b4ee5eb37f410bb5ae39ad54357953.nq.gz
    ├── 6cc2b7cea17199648f6f2ecf1728e38ed5e99980.nq.gz
    ├── 6d3318140d8fbc43be66138c1377d380e1586016.nq.gz
    ├── 6d38943bd924e8c390e9bce7f220b39428e23c40.nq.gz
    ├── 70d06cf10a01de96906d5c1b0ab6ed12bb0e0ace.nq.gz
    ├── 70ee0b68b0ced4fc918dc9031735658adefb4ec6.nq.gz
    ├── 70f74c603292559279c1a76f587a8d91af1cb4fe.nq.gz
    ├── 71f2fd162949949b9e0c1ceb5ab2023a9fa75cd1.nq.gz
    ├── 71f6f329a69ff0189ddd113dd77833c43279b0d0.nq.gz
    ├── 720f7bdfabd22245f110f9ce1c083e6cca0769f3.nq.gz
    ├── 7243828081571c4f6e7e63d08cdc24b35e21f71a.nq.gz
    ├── 7536fa79454b199915de05a42fb9df80aa94f2e1.nq.gz
    ├── 7595fd1d124cd436a5bdc5e61fc056107d0c1305.nq.gz
    ├── 75da5c7b132321474e20fbeac40929d891f135c2.nq.gz
    └── 7636a9a65e84e56d718fc172220440dd33a3103a.nq.gz

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

[ansible-collections/community.hashi_vault](https://github.com/ansible-collections/community.hashi_vault)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
