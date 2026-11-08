# Repolex Knowledge Graph of deepset-ai/haystack

RDF knowledge graph data for [deepset-ai/haystack](https://github.com/deepset-ai/haystack), parsed by [repolex](https://repolex.ai).

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
rlex download deepset-ai/haystack
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0ad74747ffd7d9f9b092db97ba2e222080992c2e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0ad74747ffd7d9f9b092db97ba2e222080992c2e
│           └── chunk-001.nq.gz
└── blob
    ├── 003a69d346437a8500ab8c1bb51a7dded526357e.nq.gz
    ├── 00424b14880bac8ce249e9e9d2e5eac1197a18e3.nq.gz
    ├── 0116836fc9d8364340864e2cb01f5456c85adc99.nq.gz
    ├── 01d92d3a8d7eb41d8906896ac3a9e4414d048b60.nq.gz
    ├── 020b2e064cedefe29d144f84cabd4e500a9d6775.nq.gz
    ├── 023f15931eb98f60c44a68887a912f6694cc6a4e.nq.gz
    ├── 02c5464648082dad8be41196acff512d005cee69.nq.gz
    ├── 030346eee9539b04278aaadf8449dbf4d0d90a73.nq.gz
    ├── 03af41a0e641935777a7bc4ad73be8a24e7f4ab3.nq.gz
    ├── 05426fc06d6bfcd4ecc7986700031b7b57fc4894.nq.gz
    ├── 0648f4c10350dc186d835e05765bb477fde1b8dc.nq.gz
    ├── 0690020a1d2fa7d0585b98109e7abe38a9495401.nq.gz
    ├── 0713ec6df51411b55bc0c26018f64912ab652d41.nq.gz
    ├── 08b0da0931ee6f32eaca3720875a5c264fea50ba.nq.gz
    ├── 08cb01d80267ce987acefbea8bef306c1ef6c186.nq.gz
    ├── 08ef1007d87d3b323ab55cd46e0a8a7dab430ecc.nq.gz
    ├── 093571d408f2d1c604f3b42f499c189432860c08.nq.gz
    ├── 09925c4fcd2cfbab05e4d28160f14f2ab53535ab.nq.gz
    ├── 0a3ac62f07580fc272868c1b6e1630ef0a0386fe.nq.gz
    ├── 0bcc5bf533d1434df764d9509e5d571dfdce5da7.nq.gz
    ├── 0c5c8e8e09b85fcd90c568a29bff5f76ffd15f38.nq.gz
    ├── 0d539ffb69311e29618bac1defcfed0e75384065.nq.gz
    ├── 0d6e63371b03ae9b55a5290394d60fd89f70fa5c.nq.gz
    ├── 0dfddd4adb5dbb667736176af3c5e51d9469b013.nq.gz
    ├── 0ea56196f74a5273ab997e54e918d15ba5813a6a.nq.gz
    ├── 0f30a4738cddce63de24b37b8fbc78955d6db705.nq.gz
    ├── 0f5b5f310428bcaf08bf92449fd481e6bca66c24.nq.gz
    ├── 0f8e23e6bace5997582764e0f7d7590fbfb93eb1.nq.gz
    ├── 0f9aaba08342ab2b0d8107fd570909d7ee36719b.nq.gz
    ├── 11b8501bb066c6e1d380578b13d3913989c928e8.nq.gz
    ├── 122468655702f8129e99863a7e8bd0be29680ae9.nq.gz
    ├── 12d251e2705b370e6a4c4144ec3971d2307c63b3.nq.gz
    ├── 12e230917b1959527f92684c730afcd9fd8616e4.nq.gz
    ├── 13391fe1ebf0bfd8128060362ace264c33181f78.nq.gz
    ├── 137e52cf3303f70bbdf620cf90e798fd2ab5b7f2.nq.gz
    ├── 140747613ae535405b71ca6a0f7e2c52d1bda519.nq.gz
    ├── 142af4ec3530b7dc18e64d6623c744a83794587d.nq.gz
    ├── 14bcc92eb98d77ea1749a5fa90b4078e9172b163.nq.gz
    ├── 14f000a9ae2b852b799eb252e14c287c7dcd5520.nq.gz
    ├── 1601e747ba0ea6fee4280742e3eb35233e54135c.nq.gz
    ├── 165cfefacb01d4cb281daa5ba47212e26751ad71.nq.gz
    ├── 17b7fc5c395858343feb103bc19339072c220863.nq.gz
    ├── 1844b6d716f0f6754f81095c2d5e6d5f2984b189.nq.gz
    ├── 19003d90f538f5c0845789b6d71f6ed841cbd1e3.nq.gz
    ├── 19b203d2fba615f5ac0826cf3b1d45b5173a54ad.nq.gz
    ├── 1ab1e481eece351992ce629e80582b0b95da5593.nq.gz
    ├── 1b1a2e06efd01d74428f45559ba38953621094ff.nq.gz
    ├── 1bb8f8d5ee20ac7658a2cf66c8430c557cc7fa43.nq.gz
    ├── 1beb12e3dfe3edf3feca00b259f314452dc0a8fc.nq.gz
    ├── 1cb27b949266e99a2aa81fd7ae35e73f82037b70.nq.gz
    ├── 1ccdf9c273aac4f2270adb1c1fdd45d8867ddafb.nq.gz
    ├── 1d0709143eeb93acec0d52086048cf34a87abed5.nq.gz
    ├── 1d33dcd680a17336f77fea7b5cf2776b80b8e228.nq.gz
    ├── 1e8c9922187e018f296f76c9b7f82397324b06c7.nq.gz
    ├── 1e9ef32e1335b3491be4af4c7de03cc2b0a17418.nq.gz
    ├── 1ed7962b4c0d896b07f3e2a1fc13dfd2d180e19b.nq.gz
    ├── 1f8c751dc193d330abdd232464d4c45317f6785e.nq.gz
    ├── 1fdbfe2e598b39597619c06ed12770d1f99d2b34.nq.gz
    ├── 202e498204e4bd64120e25b339d73255ac622e7a.nq.gz
    ├── 2056bbae7b38d4b968cfc705d163d4489fd21adc.nq.gz
    ├── 210860a909916ef64a2e4e50d8829563dbef6a8f.nq.gz
    ├── 21532869c2a151015afa03cbc0f5b0485c719183.nq.gz
    ├── 215a09f6803361e902cd46953c929943f84087cb.nq.gz
    ├── 21991c97892edf1de19f273178ff0abfb2f6f921.nq.gz
    ├── 220043d0ece18ab239b242085feb68a57316cd19.nq.gz
    ├── 228cdd0b6358da0b6e9e2ee7c1f1bf6c1fa30521.nq.gz
    ├── 22a4d4c3910e303b07bf1712032456f3a2d8d74f.nq.gz
    ├── 22bbf014b2b84b8a5d0e6edc9d5a1f3d958c3d7d.nq.gz
    ├── 22cdb875206f37295d51f55822031075c514d2fb.nq.gz
    ├── 22d0e506fcb9440758c2dbdda6e3c6c02082ffa0.nq.gz
    ├── 2540deb3cbead259d666d8c5b1793f338adbefc6.nq.gz
    ├── 259d175df0dff2db7f42c5006c95bb6ea5863875.nq.gz
    ├── 25b397ce3abb4cd4aeea262bcef9cac7c87913e0.nq.gz
    ├── 263b4995778ad76ce5759314f78bcc5feb707402.nq.gz
    ├── 268c0d9f1cb75ae4d566075c19259366aa689de3.nq.gz
    ├── 270753c1c235f07c6bf3b99146de0f235f9cb583.nq.gz
    ├── 2732ffc3ba35f88bd6404c85bda93e58a665e388.nq.gz
    ├── 27cde7a3088aa190df6f5655ce0db7c41e05d39f.nq.gz
    ├── 27f1ef5ed03ddca4f0cd30fcf2e491a2a226dedd.nq.gz
    ├── 281c13042c390d938d5dfa19127a03500b7c797b.nq.gz
    ├── 289113a523b074101233310c2e9b03c45fc4b703.nq.gz
    ├── 29500e7bd06f62d62770911dda4a2e5beeffaa09.nq.gz
    ├── 29aae96538a637068eef615d13f76e5e438f3a2e.nq.gz
    ├── 2a69ce6c6ddedfc8e7936255d1db11049f305b9d.nq.gz
    ├── 2ae67b6078e593d47d5be61b1faec648f5fb691c.nq.gz
    ├── 2cb16e8d0590cec346492507f1a1365eba68f905.nq.gz
    ├── 2cfe45e9edd7ac9699e4384eb35e5b549ac693d3.nq.gz
    ├── 2d601cef711509ac52c6caf402e65ca0c588aad2.nq.gz
    ├── 2deed8f4553aa0ac4df8aa320235f61aeb23b706.nq.gz
    ├── 2f422f08b96bff1be68064204e511850e33c3030.nq.gz
    ├── 2f7980dadb5f3747f2f7f5cad40510122cc1c5d6.nq.gz
    ├── 2fc0637f159ec98ed1f55677c1175903c7fa1e15.nq.gz
    ├── 311a521e650ca99a28f6e8aaed3714f03262ad95.nq.gz
    ├── 3167e5073628bf8aa15f69af6649e2e96934cfa9.nq.gz
    ├── 31f4349cde0249a8a386cac5be55ee349a3eca0d.nq.gz
    ├── 3234d3a85e58f38c403550e992100e7b57121f09.nq.gz
    ├── 323c78c2667bbe0dc92e4035ddc2dc6a0b0dc8dd.nq.gz
    ├── 32aa20cd59219843b93c404ef564a3f4193fa490.nq.gz
    ├── 3301ed43b4f1956dbda6a511f2f1113400e5336b.nq.gz
    ├── 331e14bba7dbab6763a02495156cb276c81c0d84.nq.gz
    ├── 34bd0f39ad78e4cc6a349440f267cd8e8a1bda91.nq.gz
    ├── 358ff41c79bfb27a2d82d8dea50365597dee6d3d.nq.gz
    ├── 36937b2aa183aa40a5ddf8952226d9549c3f02e6.nq.gz
    ├── 370f2f2cb0cac039e4423cd02ea4b9df4badd8a0.nq.gz
    ├── 37cbedd3f2d85ae2b2bacf6dc4b50a9d9e07e247.nq.gz
    ├── 38a0a9ab8fba7891f016ec7425d8e6ebef0b2a39.nq.gz
    ├── 39624204ce669d58bba690e6b415387b70acb3ef.nq.gz
    ├── 39b0e29bae130f189ab0148a9fdf56052655c398.nq.gz
    ├── 3a1a0f7b5694a361f9f5c9fff6f3fc5f81ad1bed.nq.gz
    ├── 3a7459869cbec5e9d87c1d589081e71534c9a029.nq.gz
    ├── 3aa6b3c60e66cac8da01e0e31599b885ac7362bf.nq.gz
    ├── 3ab6215e0fa91f98798c964f38fc686be29245f4.nq.gz
    ├── 3b9d97acc745e3fccf1ed4887c0cce0491e0c874.nq.gz
    ├── 3ba4d6340595d45f7773f7a6a47a24f3dd171f32.nq.gz
    ├── 3e42dfacab7b3cfb2a4d000ff0926f3fc6b6bbc0.nq.gz
    ├── 3f2f77f72d0710cf73fc8b8d31011c93ff484018.nq.gz
    ├── 407980b81366d06f82632c31f80bf8113a5706e9.nq.gz
    ├── 41b9149242fd057e3418c5d693dc0a1c06714540.nq.gz
    ├── 421a5d571ce5dad9df71f2818104c314360764b9.nq.gz
    ├── 43594b648f6ba1e216e1b8a31743ed25c5dfe8fa.nq.gz
    ├── 43a76011d0c14b58bf6e8b2ca4dc111f1392fef7.nq.gz
    ├── 43d1d8a2a4b0fd56ca930084649ca32ee953e923.nq.gz
    ├── 43d47d7ddc2da7ab942a7bc4b25c67e128ef7213.nq.gz
    ├── 44329497baedd232c68040213346cd936875a5dd.nq.gz
    ├── 443569b271aa80ae9133dc43ac4e1fd07e1aaa2e.nq.gz
    ├── 44d175312bdfe5b1fcf077a9d2ddaa3508604d3f.nq.gz
    ├── 44f1ea23a17cc2bdd0909ba17a6844495eefa7b9.nq.gz
    ├── 44f43393a943f6935b7e61ff902b61dbcdec4258.nq.gz
    ├── 4653fc3d26db3970ce81f8f39e86d077bf31122c.nq.gz
    ├── 47bfed387523d3afdd33052da36041a779a15c4d.nq.gz
    ├── 47e8afa854d378a0f30a55daca4b8b19b762feea.nq.gz
    ├── 48836f1a773e12b73e450a136f2b8ef65ef70dd2.nq.gz
    ├── 49f03827ce7267558d09ebcf4c065d14de5084f3.nq.gz
    ├── 4a17ae7d3420c60e8810974036e9424a7171557a.nq.gz
    ├── 4aa301d5e5bf9ba244b5d997e2a1556d4bc36164.nq.gz
    ├── 4c2f46ae8d694ca289ab8667cbb979cd7237e818.nq.gz
    ├── 4cf9c334ea0312f71cfc765d4f6b40cf4f4e4158.nq.gz
    ├── 4e0bdb8322cb3b2b4c91159d36545031ac76b977.nq.gz
    ├── 4e56f69cc01f71429c6c0732cb8f3153e7949197.nq.gz
    ├── 4e95ed3881a6354d905800c660ceabaa0e91f269.nq.gz
    ├── 4f84f8044357f3bc7a8c3e843b95bed35862efa5.nq.gz
    ├── 4fa929892ee2c599acebe11f990dd80b2c81c68b.nq.gz
    ├── 50371edabfde4e613fd1c270dd774164f15a8500.nq.gz
    ├── 504e738a3b72e67b5c29d84a7ecab8777380e1ae.nq.gz
    ├── 506c94f2f94b58b658e865f2b2d62fcdede13afc.nq.gz
    ├── 508c8b33c81d797fb6827e6e2741d952815ff5a7.nq.gz
    ├── 50c6fcba60b491eace0996d1a1b047fb81b356dc.nq.gz
    ├── 511bb9bbd7ca972b0be543d253e7884fed7eb324.nq.gz
    ├── 5174ddc729e444b3f6337ece9c1e03c3c7366ddc.nq.gz
    ├── 51dc973fda32e3a1879dfb22a60c3a94ff4fa9e1.nq.gz
    ├── 51f12d638d7f2f00e652e6370530357589f620f1.nq.gz
    ├── 5332228bb3f6ba6850c9afa254950d435b990d97.nq.gz
    ├── 545cfc4e6e4945cfc73e95e256031f51d68c109f.nq.gz
    ├── 558c65684c755c66a3c2608b5999a2040b5e70cd.nq.gz
    ├── 561316176a39cef89a527c6ae612aa442511e923.nq.gz
    ├── 566301f72efa6b74505d2c92b689c3eecc6ab98d.nq.gz
    ├── 576586719393f732b9e0169152844e37cc839a66.nq.gz
    ├── 576c9f62214b6a2b19ccdd8325e5edef29064116.nq.gz
    ├── 5785ad31d6a3d356f594af83c4963afe8b1ada2a.nq.gz
    ├── 579be24b057da071c7baf009781948a9b8468e5c.nq.gz
    ├── 583c5b54ebdf2ef7a450858216e55309e10260c4.nq.gz
    ├── 585d9a5cb13bd3481fc98816b1e44d016e32ca24.nq.gz
    ├── 592d93f56328ac864ab47535cdeee2dca84e25b3.nq.gz
    ├── 5ac990b0e958be6d49ce3e36ac126e3e5cde9760.nq.gz
    ├── 5b89505073b7a9bbe4d0b33afc5efea79aa0ed3f.nq.gz
    ├── 5b9839150b6684b0e292f122ea7561f327928702.nq.gz
    ├── 5be5ba03579d3499c64f48b0c9785801019f8af7.nq.gz
    ├── 5c3fb605c1ce621bfefcf8199370af585e2bca3d.nq.gz
    ├── 5d788b37fee95a94df01a5748ad4c6740ae32ccd.nq.gz
    ├── 5d8356a75e162dbe237e819f900a313c7162043c.nq.gz
    ├── 5dd72f065832282ac5664babf644ab2e8edfcf08.nq.gz
    ├── 5f14420bf3ada240e4ad8a793aef66b0a804af84.nq.gz
    ├── 5faba9aa647e92a36f4d220d1b1c0b1c01661301.nq.gz
    ├── 60c2b9f1c7e0ce857f902c115a6498287a3e4a41.nq.gz
    ├── 618dbc78e195c6031068f0dd62ca79d200bae44f.nq.gz
    ├── 62805f7a7715a1e3cef4a5cb809923ef8e327410.nq.gz
    ├── 62c40dc20625dba7b82304e7ab9bc64df205cdf0.nq.gz
    ├── 62e33cc716d547aa1c34083e041dc7e83478cfdf.nq.gz
    ├── 636fa5fd34c380c29e058388052abfe3cc385a6d.nq.gz
    ├── 63bebe960c0de9d83319b488b7f1c27c14237be9.nq.gz
    ├── 6418824a44c16e71eeeac0d3bab99f7a0d4c301f.nq.gz
    ├── 643cb15c2b789a79622985bad911386bc8b20fa6.nq.gz
    ├── 6459164aca1fafb0ab44e29ea5deb23f3c62b397.nq.gz
    ├── 64b3eb8235704526ba2719a091ec804606570777.nq.gz
    ├── 6583471da400d37046f023655784c55a24055031.nq.gz
    ├── 65a0e912116b565c9fc5a83b730c49f55edd3708.nq.gz
    ├── 65c2ad9858c3deeac97bb6170d26401f3646b036.nq.gz
    ├── 65dbd114947bc3f96d708b0181552e2925ac4069.nq.gz
    ├── 66b77772f60ceac0da35b21c1aa5c059a82e4a56.nq.gz
    ├── 671d0697ce7480dd5aff40349c021fbc44e17bb4.nq.gz
    ├── 681a869186910b370ea97dce69d6471dfb42e7aa.nq.gz
    ├── 693da9f507849d151335e20acc8a19baf3ae134a.nq.gz
    ├── 697ac6e98c4150123a7af7ed939dd908f2cb4245.nq.gz
    ├── 69e60edfcc19bc5f0931fb0b64d55a0ba3b34248.nq.gz
    ├── 6aacf295e29dc09c7f81b91c41729b709dafefdb.nq.gz
    ├── 6c5a4b82e5158a51adabf5966c550ac5ed1e53d9.nq.gz
    ├── 6cab754881168406534f80ee98b306a94f7fbea1.nq.gz
    └── 6cf2a112863484be5765d87b31d8abac67a63ebc.nq.gz

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

[deepset-ai/haystack](https://github.com/deepset-ai/haystack)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
