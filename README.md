# Repolex Knowledge Graph of apple/ml-hypersim

RDF knowledge graph data for [apple/ml-hypersim](https://github.com/apple/ml-hypersim), parsed by [repolex](https://repolex.ai).

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
rlex download apple/ml-hypersim
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3463c5c4a75f3cbfc65ed31cfd6e87204b3a2254
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3463c5c4a75f3cbfc65ed31cfd6e87204b3a2254
│           └── chunk-001.nq.gz
└── blob
    ├── 00b7b83be0b9a436412d8ec12313b47c2c0b6518.nq.gz
    ├── 0127af60fc5f87d9f0459d4a99e5c007c0bca4f9.nq.gz
    ├── 024a6469f5a5ce97792922625c8cb5ba20952e6c.nq.gz
    ├── 026b44da419138bb38453e9f1e43c937b208df9a.nq.gz
    ├── 03573555582c25975e618cf989cb8b0ad898b63f.nq.gz
    ├── 03e762a1bd65f8c5c9b148c172c547a6a63c6b81.nq.gz
    ├── 03fa50a3256ad58c4cf510f0f915bee158aeb711.nq.gz
    ├── 03feb95a4c5bad98dc427e9be02cc81a0757e911.nq.gz
    ├── 05442f541c12f77f0bb73c32b4ffde280e5c3b25.nq.gz
    ├── 0581c9b11ead4a19e455a210faae793f86dc48d0.nq.gz
    ├── 058cbec825ecd8600b8010e6526243bda27e19d9.nq.gz
    ├── 05fff025495c9ef2b16f352d90f6c89b5bd74bc9.nq.gz
    ├── 068ef09834cf08a0eb1c2b2a9046a54badfca9cd.nq.gz
    ├── 06e079e04843d14d83e135c16f671b8edeaf18da.nq.gz
    ├── 06f774d1896fcda18704924a4e5856457b08897b.nq.gz
    ├── 0799ccc30dbf9a68e725f5032f296f6f6b3b9389.nq.gz
    ├── 08340909bedee81ad61c6fea807fcae16a6464a2.nq.gz
    ├── 086ef8db9c4e7fa976a32e7f227c19529ab81a71.nq.gz
    ├── 08acddcd4ddec6311b8187af98f37af9dd79314e.nq.gz
    ├── 090e657baa72eb5e9c5f50b88e3f0f82aa770b04.nq.gz
    ├── 0a1e691755cdad56d24beb7dccf061f2cf35a168.nq.gz
    ├── 0a213eaedcc5b58eb8712f286f83abbf27144300.nq.gz
    ├── 0be6c65fc69dafd1709c5711a77b3061a7bb906d.nq.gz
    ├── 0c0c108928994a7dc6a3210e8a5c0cf053352fe7.nq.gz
    ├── 0c30d1e182b9f0a43d92d39e6abb7856469fa960.nq.gz
    ├── 0ccf0eecdb5b029726756de49606425b392e6ad5.nq.gz
    ├── 0d168efafcbc777b4b6acc52611fd26fc003dccd.nq.gz
    ├── 0d173f7160dac7b548dfcb10d15978ca5a905f80.nq.gz
    ├── 0d2a0cfcdad43db64d7c8cf516f9eb60570d71be.nq.gz
    ├── 0e0959e24af404731961feddb38d8c9f85ac63ea.nq.gz
    ├── 0e3e7dd584de9d49798fff769db99fdc02471d10.nq.gz
    ├── 0e4b479b5d4a94693a776eb55068988adcb7cf37.nq.gz
    ├── 0f1a613563579847eafa4765ff372913a2b52914.nq.gz
    ├── 0f4891e97ce4359328d9e3569346c4ab82b9d756.nq.gz
    ├── 0fe85b549370bd6b0887c726eec06915187d0a15.nq.gz
    ├── 10e681bc8c457e369db7dc5a79c202ec4546054a.nq.gz
    ├── 115445cd73c225cf8b2fdaa68c589ca66edcf36b.nq.gz
    ├── 11555d988d07d55e40cf92297b481142ecc85aef.nq.gz
    ├── 118b4862cb81b2e0f830670e66b5e624749a6224.nq.gz
    ├── 11acdf067fd76132218024bc454a9961d2374914.nq.gz
    ├── 11b2b5424c984dce5e3a43c4b9a41a70df4a1d25.nq.gz
    ├── 11c699ee0158f6723ee7abc91a0bcdbde8afc981.nq.gz
    ├── 11f54514790d5740aee8076f53b9849a2b0b258d.nq.gz
    ├── 12016b92d300a2661d7976e912c7deeadc8e5d47.nq.gz
    ├── 12909f45b9bee328aa9f002715f538a241025aec.nq.gz
    ├── 130f4593bbc0533104ed83ff40094d9a72d926a4.nq.gz
    ├── 138f600c95d2b05c1590d8c88413292532b6de6e.nq.gz
    ├── 149db1e6e4c3cf8c9f6542f6a7a62ca8546a8716.nq.gz
    ├── 14af6d3e8919e47c26c7e97c12a263f81a0dfb06.nq.gz
    ├── 15b8f417d4dafb2e6439a9243eb662cf187a4e9c.nq.gz
    ├── 161db6d36a9b89eb6a0318e472a64a612814e72c.nq.gz
    ├── 1622397156300fd587cd871e39cc11f7e5bac4fd.nq.gz
    ├── 1630fcf326b8c407fa79ee9e7ca7f29c2c58b7a6.nq.gz
    ├── 16aad5a8f3f5b8f65c5bb733b2d1ff9dc170e80d.nq.gz
    ├── 16ea9bce45004726f1df1af943c0881ecb1e550a.nq.gz
    ├── 16fdcb3ef81882222fdf897b6af2366519099a6e.nq.gz
    ├── 177affb312b888f653e982f19abfd1caa5542d20.nq.gz
    ├── 17800e59f22c73a13f193e8f81594765ebe5325b.nq.gz
    ├── 1792063280b4b3da11ccce229722ef80df88edf4.nq.gz
    ├── 18784fba62d4c901cc30914ac96bbd4c9ba3aee2.nq.gz
    ├── 18b7bbe0de2c75bb52b90431db93f00d48351f87.nq.gz
    ├── 191ef67efc480323f4f300efbe4d32bc42c4a78b.nq.gz
    ├── 193f5ddb7a0300ca4e3b36cb1d7c8be5f485febe.nq.gz
    ├── 198354c58a0d72bab0ca9a09827ec200b878726f.nq.gz
    ├── 1a8770cbd14fa744709d6acce308c3403de60766.nq.gz
    ├── 1ad5e6038af0333bd435d940088a78fa9f286337.nq.gz
    ├── 1b3a5917ecc3c8173ca328acd346903bf248ca68.nq.gz
    ├── 1c819c9f17cb5c4d59d0377755ae2d4dd8bdc2ec.nq.gz
    ├── 1cd6bd981d4e4ef4f0b0a85139390c41cd6396e5.nq.gz
    ├── 1d22343359b14fedfb13c4d041c6f4c4df7cae04.nq.gz
    ├── 1ed3848b463851883dd8a6d0b085378f4ce59c22.nq.gz
    ├── 1f00f2f9eb71c32465cc8c3528fd3b8b208cd205.nq.gz
    ├── 1f2d5dd93669ce8af6cc57583a57835b9a582297.nq.gz
    ├── 1f3253b89f89f6cb155e3fd6d4ae1c0d47c297a8.nq.gz
    ├── 20bc92edb68560200d23039ef75c5c52877a3e26.nq.gz
    ├── 2158bc1894bffdf2fcb738c8ab093dc0e59f4d31.nq.gz
    ├── 21f34fb23ad4557488f7a929177fa1d7e20a765d.nq.gz
    ├── 22cee00062caaa2ca85deb06bb6959a8ac6dc78a.nq.gz
    ├── 23250b455827f7930ff7beaef7a3ec0f3ed29b41.nq.gz
    ├── 232e07ba45a70cd949ca8d8da22f543f7a32c2e0.nq.gz
    ├── 236220720f009c8d5fdc1f7ef8e70c6fde9410ea.nq.gz
    ├── 239070333031edf77d2af540a4707b2940fe7ccc.nq.gz
    ├── 23a057acf2578df630f2941ee95be7d7bccce3d0.nq.gz
    ├── 23dd6993d005055c6d069d501274c3efb58af4a3.nq.gz
    ├── 254991fab3cbbea32e88c1701bfb77a3c11d4a23.nq.gz
    ├── 255cf36b2e52ee2a98deb874826a9b4fe52d44ff.nq.gz
    ├── 28289b0842c732e48f07229a925469bbdbadeb2f.nq.gz
    ├── 2863fb31b70ece4a4fa7bd2bffdd416454a5f980.nq.gz
    ├── 2932f35c1c89c3643e70100436196e148e19a2cf.nq.gz
    ├── 29581e4912fcc7bc41576cb3956ad3855a4a2fb5.nq.gz
    ├── 298cb35bed6fceb294b31d895a83260e19f4b458.nq.gz
    ├── 29e66483d62bc92208dcf418d45a2e6a315a4aaf.nq.gz
    ├── 2a5b40683635202279f1f5728189d4c5cdce85ed.nq.gz
    ├── 2a693ace730a35fc7e58962487fc20a721577845.nq.gz
    ├── 2a9db85b953825ea82224570b2bf189022493f5f.nq.gz
    ├── 2b9967f9bd855772005059a4948584f4775fb222.nq.gz
    ├── 2ba010d3ec26ed312d340a6d677d6ce3c59091d3.nq.gz
    ├── 2ce7924bc36aaa043f6a7594e0ac443f60b4f20c.nq.gz
    ├── 2d0161376ae0e4af8af7260428bbd5ec41cc1de9.nq.gz
    ├── 2d48440e74c59be352b086e24cf0aa82182efa21.nq.gz
    ├── 2de69ffeb6f9362e5e70cd4afdc398d05f28d1cb.nq.gz
    ├── 2ef5f78629657e491b8df4384320879b15cb1d4a.nq.gz
    ├── 2f8eb9441bc48192f06773e57a0e72455b2a96dc.nq.gz
    ├── 2fa35c034497d44d70a7a1dd3784e7f846b34fc8.nq.gz
    ├── 309cb9572c002541588a59d5f31e1904c9c26b46.nq.gz
    ├── 30b41710d7a29b67731b1ce1abe887f60d59f26b.nq.gz
    ├── 30ecb57d5480a9d1dc791b6af5c3abfdfcb4cb3e.nq.gz
    ├── 31203d77bddfa9760b9c27da3f495d529273cb65.nq.gz
    ├── 32097547f1fe5db9008b69df1b8c4f821ae76107.nq.gz
    ├── 32127aaa4323a9a80276e56b7a812c7abbed4cb3.nq.gz
    ├── 332a4f09c2dee68375876c45e257744013a52306.nq.gz
    ├── 337ef0ec061a9ed8deaf7131ee26fdcb5e06a22c.nq.gz
    ├── 33b8f87188de4649cccd34b33fd33237ac244b47.nq.gz
    ├── 348f2d05de439fe542ce19180d4354bf1e5aee6d.nq.gz
    ├── 34aa02d4715e26ecaff951d24fd399921f96e19f.nq.gz
    ├── 34be0b047e939a47d18a1c6bf2cf811b22923224.nq.gz
    ├── 3524d245ca8f314466958d7427ff38427c32e356.nq.gz
    ├── 3571c3eb4245445b4667bda3a8c4c55c7fcd98a9.nq.gz
    ├── 35dc9d62b449b752ca054b1449bfcf67bb9a4e5f.nq.gz
    ├── 36cf0d135d72b775edc97c405476daa02fb39df3.nq.gz
    ├── 3722cf1f1d6491b2e3cf5a3372b0ba79b98a213b.nq.gz
    ├── 3744401b12e51a26f2b671afb19695725509e6e7.nq.gz
    ├── 3771ad1215c154ede555ef4f4d9b3809d3c4bbcd.nq.gz
    ├── 3839bcffe48c295a05138366f430e069b3e3b80b.nq.gz
    ├── 386942e12218f16860ee1ee42013415d36014b13.nq.gz
    ├── 387d170a54747916297a0d8373098c4feae67cd3.nq.gz
    ├── 3995b0db1bc63e47251e25b22c9e7673b145348f.nq.gz
    ├── 399b64b799e69f77a90f3fcd7da5e18c8ffc5e00.nq.gz
    ├── 399e6557a4a161f80656c8f65d777f307f1e4e0d.nq.gz
    ├── 39b050935b23cc656ed631b60fb06f373bd76c90.nq.gz
    ├── 3abb294002df51f4ee86613c566bace4fba5e7b1.nq.gz
    ├── 3ae18481db142896f6ffe5231e3746daced85f79.nq.gz
    ├── 3afac168625634434f857347275be4bfa382dfc5.nq.gz
    ├── 3b5b8614175286602924f9068b37f054a47deb50.nq.gz
    ├── 3be8fdd24598a87281b35f5cc00bcf343f8baa1a.nq.gz
    ├── 3c2d6b935817ce5b153e4fc780becde00163c7f1.nq.gz
    ├── 3da2e763330b1520b9e5ee7079ee7db021cae132.nq.gz
    ├── 3f6c0f7f7c299394943febd59180b54428e7d5fd.nq.gz
    ├── 3f932b42da9fa80bdd3bd69ac09149e5259df38e.nq.gz
    ├── 4055e4bf0c074d8419eebda128fbc3cf1bf91f50.nq.gz
    ├── 4062b445556655a97a7b92d2dbdd8e6dd7f802f6.nq.gz
    ├── 406dd5e735d8002a1e00e924a2d0c69da0d9f168.nq.gz
    ├── 42bea2010f2c833ea01e68ed9976849acbd1f8bc.nq.gz
    ├── 4316e0e8284b728b007d78a2e155799dfbd6c1ee.nq.gz
    ├── 43778fc1bf8e07d305c931302908ebda28b8a952.nq.gz
    ├── 44362e457d40f3d19709eefd964dae646410d990.nq.gz
    ├── 455d991e46d785895f9c2ae4e5bca750decf38fd.nq.gz
    ├── 45889047870dfd079af4a5219c735c07d96f5b0a.nq.gz
    ├── 4643e1c37f7636df7414685eb6b18cffbda7e989.nq.gz
    ├── 47758edaefef9a7790b9c7df0562cc869c9e21ef.nq.gz
    ├── 4879215786f771df0aed3852109f37ed338dacc3.nq.gz
    ├── 4888d3863d017948e51ccbd783a3f4321a70a6bb.nq.gz
    ├── 49742552b7fec821e37d01903e1bf6bd30085236.nq.gz
    ├── 49a10a6c376a55fd9130e7a4fa8ed8c25848d9da.nq.gz
    ├── 49af552224bd58a16ee91026771285a8dbe0b75a.nq.gz
    ├── 49af79d542c820531bb2ece65f1549eda409e775.nq.gz
    ├── 4ac6ddc153304f346daff384ec1af59d5d9b1d17.nq.gz
    ├── 4bacf5eac5a3876fe8a89e7d3fa926d5a842881f.nq.gz
    ├── 4c7d73019919773b0dee56a166477bf12479a655.nq.gz
    ├── 4c898102ca233f40afb63d3efb30006f09b57e2a.nq.gz
    ├── 4cb03775a025c31e721d9f1d1409f1c4fca05a37.nq.gz
    ├── 4ced84b70c81342ffe311ee4069735f32f21a31e.nq.gz
    ├── 4d06a54dc32736e23735301f6958564a4a9ddc4e.nq.gz
    ├── 4d50c40ce9f90d65e696a92f9cedeecbe1380e8f.nq.gz
    ├── 4e2e643aba0152edcc1d95a38f6dd179abf85b1c.nq.gz
    ├── 4e30f330dcfc60e752c9856827a301d80aed88b1.nq.gz
    ├── 4e4a9f0bb47f97635b8dcbf97d2e7028f489a399.nq.gz
    ├── 4f016d90a15affd317d6e86cabb1ce08d4fede94.nq.gz
    ├── 4f2ee2ec7f16cb2c70d8c0d8a01e6e585140aaf9.nq.gz
    ├── 51d9c6496884bea40e4555cc331eea1ae0415883.nq.gz
    ├── 523a68ffb2f61d069759d9f5db51a2dfbc8cc613.nq.gz
    ├── 54291e2fc39cdea626d9358f44c30722cb4217c3.nq.gz
    ├── 5592ea137a06d4e7442845244544dbe4480f54ff.nq.gz
    ├── 559fbc5b5d97d968a1f1ebc24fd885693fe2a210.nq.gz
    ├── 5657dc39f33b5530afe0c0501e5296c0402cb224.nq.gz
    ├── 56bd1a81419099058a63a394e420d558f0aab381.nq.gz
    ├── 58e2f4f5397e9f18e639437e6fe1d47946723a69.nq.gz
    ├── 58f7cff7e92906a0e44aa56ee9107a7d2bd45a93.nq.gz
    ├── 5a3cd496de8d80f73e07ae71fe5eabf45d6ef62d.nq.gz
    ├── 5a43a161724f5b0cfc0454150217b191bbe85c53.nq.gz
    ├── 5aa323f01ccadf74dcb7a51cd4c29fd689de496e.nq.gz
    ├── 5ae623ef5f3da7f4f4c920dd68d26df0d6da1761.nq.gz
    ├── 5b19cb91caa472818009bf25981f8f03d83e88aa.nq.gz
    ├── 5b63b0cca8376232bc532d7a227c26d65a404ef1.nq.gz
    ├── 5c4380388d0e000e196d1e47f26646542ffe809d.nq.gz
    ├── 5c513c4ac48b5821bbfc47269be2d69350d06ae8.nq.gz
    ├── 5c783a67ab4fb52eba19f6371984d7767f1e1a2d.nq.gz
    ├── 5cf91fa98470604f9dc584a3b813e0cb56bfc218.nq.gz
    ├── 5f1f3267046b11909ff42e11444cd3754baad0e2.nq.gz
    ├── 6059ef8fe458ac9439692a59204385ef621e553c.nq.gz
    ├── 608dfd0193bc9549ff9eca69fbdd44fae7ddc1fe.nq.gz
    ├── 615700106a12c2dffbd0ed90124cc8417cf9e584.nq.gz
    ├── 61ee9419aa8710ae7130669478e53c143fa44ad7.nq.gz
    ├── 627eb6bd909c0b982d50916b5a0053b2dff1a7c4.nq.gz
    ├── 6414da5bd645cb3c3fd6104d0fa1dc76827eee6f.nq.gz
    ├── 6463a6e1b5395175ef5ac5fb520f03725e2baec9.nq.gz
    ├── 65038126887d72b98c9c9d4edf2c1e3d5d20a7c9.nq.gz
    └── 650bf87a7a2dd500ff672a8d664ccb9b6111002e.nq.gz

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

[apple/ml-hypersim](https://github.com/apple/ml-hypersim)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
