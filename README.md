# Repolex Knowledge Graph of fthomas/refined

RDF knowledge graph data for [fthomas/refined](https://github.com/fthomas/refined), parsed by [repolex](https://repolex.ai).

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
rlex download fthomas/refined
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2d9cd42102e2936a725e7bdcea254883d533dab8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2d9cd42102e2936a725e7bdcea254883d533dab8
│           └── chunk-001.nq.gz
└── blob
    ├── 00a5dfd64f861d02b56d38e5c0fe23ac74de7e49.nq.gz
    ├── 00adb17433b4957bfd3e162d28efc836ee9d1537.nq.gz
    ├── 02498f898842d78bf9f07f14f63019dd9a2c79bf.nq.gz
    ├── 044794bccc7af07dce1e9da40c6c1683e0ecc645.nq.gz
    ├── 0482a961ee086f58bbab391bbaefb3759c9c374b.nq.gz
    ├── 0653f25e2462a4e7dac6b8a9d88e11e3cadc466a.nq.gz
    ├── 0669cd4437c84ba9a12c6ce9bf4622da34fd73a0.nq.gz
    ├── 06ce1475a7ea012873785c218ce338d430e8af87.nq.gz
    ├── 08192f6b8b416b57d2939490c4ca6c7b91085bca.nq.gz
    ├── 08abfd4756635e1d61673856709da8c56d649e15.nq.gz
    ├── 0d7290da6e61abe834ffe1527a184c8067c0e28f.nq.gz
    ├── 0de523b35c37cce4ad97f9160602d915941754a5.nq.gz
    ├── 0e4619681886d77565ee0fc1b717b1606052d9ae.nq.gz
    ├── 0e52a9ee9dcce8ac8f55d5ad09a4a630fd89c5b5.nq.gz
    ├── 115d06b4b2790babd4bed131711bfb720262c535.nq.gz
    ├── 119adf8346e6081448b60a71b3a5b9c0c675269f.nq.gz
    ├── 11aacf5f222bd67a5a1b139eb9f5c329132c2ecf.nq.gz
    ├── 11c0a30008386158222ca94ad90694e6482d9f8e.nq.gz
    ├── 13a7b64ddb27191c926ee38eb395f0eada69315d.nq.gz
    ├── 15e2485e3d716b2328d85d28a08f7a41e6c87ac4.nq.gz
    ├── 1808933550b2fe8868e1bb4b8ffc092c2a7f8672.nq.gz
    ├── 1b0d7dc4b9c61ab82caa57707f0a701105abe44a.nq.gz
    ├── 1d9e2c19480091c1cbaa0856b5f9f15f9c4c52e9.nq.gz
    ├── 20424ac5f7bf36ca9b1007329c4dcaa82fe3a6c3.nq.gz
    ├── 206d5c0669ebc440ff9bb0ac60383ea763da5b7b.nq.gz
    ├── 2083593e7f9acd2070bb7a6a6eb9146192671765.nq.gz
    ├── 21750362d64a9e8e57cd0fb575889eca72342770.nq.gz
    ├── 2220a86cd94f31d79fd10414b83538f12b0fd32c.nq.gz
    ├── 23a07aae27db3a00e36a4cb711ef7f7c1af39c62.nq.gz
    ├── 24637d09edcff1c1028aadd3d054dbeae77f511c.nq.gz
    ├── 2470ed593f1eea4b7c11de9f045d8c16c80e36b3.nq.gz
    ├── 257c5b3ecc6ab8e2bf6b9976afae1481b2ac1397.nq.gz
    ├── 275a7bca719c69f3f404eadec5c93ff3adaf83e5.nq.gz
    ├── 27cb6c142c9d6281c5b3894fae9f6d9b7c68412d.nq.gz
    ├── 295d02655760509b23430efc3105a7726b209899.nq.gz
    ├── 2972633f552b1353999d3e673f22289ab46198e8.nq.gz
    ├── 2987185acf972e936cc82b63e22e02f6a93ebda9.nq.gz
    ├── 29b9752b81b5e54165368e5996446f4e093512eb.nq.gz
    ├── 2b4624e9da4e63eef13fc7da4151f694161f8fcb.nq.gz
    ├── 2b829ff3727b00116e1fe55a0f3e73f090256435.nq.gz
    ├── 2b87b23edea3ce76785c7c80e0746aae0d83e980.nq.gz
    ├── 2c136a8e317769bf1010f1c082355f589037b21b.nq.gz
    ├── 2c57a12a0863f155e1cf84d6d5a85e2a7f85793a.nq.gz
    ├── 2ddf6c4b1052fce6fd7dc725a49907a9afdc8dc7.nq.gz
    ├── 2e4bd010d5b018e13fbb5a6ea544ceef198ee198.nq.gz
    ├── 2ecbba2758f8d34605694aecc72e8d1877b9de65.nq.gz
    ├── 2f3529fbcdca6176836002adbb5231d2209ec1a3.nq.gz
    ├── 303f667268b37d50effba9edfeea7cf7b482006d.nq.gz
    ├── 305a77c0a92616703ef544f81a797ace06f9fc1b.nq.gz
    ├── 31db65a3cc2aa2af9fb80afb4f98a46d5794b4b6.nq.gz
    ├── 3248098ca978e49a5efcc6452dfc603b14bfc1f7.nq.gz
    ├── 3368c2e827c21a274755170e65fb1c02b8c8b467.nq.gz
    ├── 3373fa80f838157dfb272a0d5c1e40afe76856d5.nq.gz
    ├── 343566c9c97f00c30bc41cd814cbe136c7491e45.nq.gz
    ├── 348cfc8d5136a68f77c230a6a2bebb237ad833e6.nq.gz
    ├── 359218d1605214ef7edbf8c204ca2e4f7df8cfdd.nq.gz
    ├── 363ec429b3c8e6597a83d6811a3392cafae40924.nq.gz
    ├── 37522f869265fa3a6313d4d78f9b5fa2bd3693bf.nq.gz
    ├── 37b6638a6a11d668483527c14ff7c4edad5dce53.nq.gz
    ├── 381a600aacf922f7cbc1c3eea5657124e1173d3d.nq.gz
    ├── 3a0b8f3dd6d2221e4598efc4a708b15cba2d74e5.nq.gz
    ├── 3a0e575a389d79f134c01281101406ea1999e57b.nq.gz
    ├── 3aba6c0089037242d5f2a9ba9f24680c216d4568.nq.gz
    ├── 3c0bb7a58895e8740a1eaf32e83a9a055efa037a.nq.gz
    ├── 3c1530f1e7f5d5b33ffbd0a2d1df0d4a42bc143b.nq.gz
    ├── 3d6da939feb704b8cbb6060858e525657000f1f1.nq.gz
    ├── 3e18c498f3bae8a7a3dc34092177c3636426c54b.nq.gz
    ├── 3f85d2295352284a7a5feb5f322a1049fe2f8ec6.nq.gz
    ├── 40779de6bac766826a902407b0dad4171c5513c0.nq.gz
    ├── 424152213d28ff29320a32da084d3026be9054c3.nq.gz
    ├── 445e62f10afc05e6d36ebf54e4b051e6f230e3dd.nq.gz
    ├── 44726698446742aec924a479d8951d65bc95de83.nq.gz
    ├── 44d85b305fb84dc0b02b815cd29de10ae336de71.nq.gz
    ├── 44f4136a20fadfa53b3a7dcbbac6a5375dd0407e.nq.gz
    ├── 460b1a3e9ce69b0db0b9d6329ca4ca1c7919d91e.nq.gz
    ├── 464ca4949183810a801e0ae9d709fafcb84d3daf.nq.gz
    ├── 47633cbfec0a6426e7d81ab55459a03c9697bb26.nq.gz
    ├── 4859f5adffa8c9e224b00f7dd0abf242a351453d.nq.gz
    ├── 48fda1aef0d6e3f2c2d3906e15286d8a49426a64.nq.gz
    ├── 4945cf062f1943f3f86e6b2d6042690f87c39c93.nq.gz
    ├── 49a00c6246049a63105299c0b9e5d2bc4a58d1b8.nq.gz
    ├── 4ac4be621b1ef7c899d8564fb82506743e7dc851.nq.gz
    ├── 4bbcf1edc7d0a6f35df60e29f87260381e63ee02.nq.gz
    ├── 516443dcc8f677040e07faeb6674c120c0150458.nq.gz
    ├── 52606178360c680eaa45cbfc22f5e7264ec1952c.nq.gz
    ├── 547aaa43e25de692092b602bb308642221a6cd77.nq.gz
    ├── 5558d7002d3d337e46f9770d47de829aaeef24b3.nq.gz
    ├── 55d5738be607b9078e906316661cc23de8b54b5f.nq.gz
    ├── 562f43c885ff0cd60b429a042f256151ce8c4079.nq.gz
    ├── 56369372c82ceefd18417e0f7145707d9172de75.nq.gz
    ├── 572723747e752a5d86c09089467aa16332757721.nq.gz
    ├── 58355f1d237a2f6d9c24119f752d3ccc58011b11.nq.gz
    ├── 58e75d357916e7fbe1d976e3738badeeed093e16.nq.gz
    ├── 5967d893c54966f9624d9ab584b0832f3778a046.nq.gz
    ├── 5b678caf8078167c75a9d243f89da2f140b07400.nq.gz
    ├── 5bdfc3c4ada7a54eb19307d2c74c347aa25953ce.nq.gz
    ├── 5be3486b38612e0727faec2ae635fe91ec2d8afd.nq.gz
    ├── 5cffd99d254e9139ff8f557e07d02b2f0918ad52.nq.gz
    ├── 5d4ec4c38c989cfa1e37dc691b98bcdaa3d6d17b.nq.gz
    ├── 5eb1f79f5b355c99c925b4c6456095b4f5bc16af.nq.gz
    ├── 5ed0e3d0fc84cb437636ecde724de769365cabda.nq.gz
    ├── 5fa03e5de5643fd99c10317b727f4e009956fb81.nq.gz
    ├── 6080514465a79a2f8bdc03a4cd31bb5f0a964268.nq.gz
    ├── 60d359dfa83d6f647b92957ec2e3a1925eae5ec0.nq.gz
    ├── 619a1a350f43ee9ffe751c8352c7d4e67a3655b9.nq.gz
    ├── 6367c5d7f09629ff52aedf0909898195fc6336f4.nq.gz
    ├── 65a6cc0042bf28b0205512aa2294bbd7079ed1cc.nq.gz
    ├── 65e3cab627d2508276d31b027378c5dd66886066.nq.gz
    ├── 6637875ac8cd64c19936811add0fad9fc4ae69e5.nq.gz
    ├── 66c87508f50d65a0158b8d0bd19be29924acfc3b.nq.gz
    ├── 66fc17d11f7a8ff879d71217db75fe4c2c1b43c0.nq.gz
    ├── 676c80d40ca0f5357879f6a6121895c96ca0ea90.nq.gz
    ├── 682add0c22412b0bfefc939bc0c0d67e44bf3ccc.nq.gz
    ├── 69224156b60f69ff0e5660b1faf2417f62e08206.nq.gz
    ├── 6a2e3d14da77f02d8d68a07247bbf1d30ea39ee0.nq.gz
    ├── 6bf760efa12e46d27df1ab5a7fe3fa194278c91b.nq.gz
    ├── 6eb957ac3f89b59f21b038430bdcf8cb47aee98a.nq.gz
    ├── 70dbca79862bd2ab8111df9438319ef44cea0efc.nq.gz
    ├── 71360f4303fcd61ef70b0f34f5fe361fcf16db8a.nq.gz
    ├── 71960938f41062393b64d13de7ff706106dd1ba8.nq.gz
    ├── 71a5c4c46de20358799e77b5352e09814c8d9717.nq.gz
    ├── 72f0359c4052e96c50be298763f8034e0ccec8a9.nq.gz
    ├── 7502613031a046743d424dd0d21b2f756f291146.nq.gz
    ├── 75566e01ffaa1d2c75912c59e5b74555d8a43d48.nq.gz
    ├── 7620ff1bbe727eafd01e0461cfc5a9ef1983760d.nq.gz
    ├── 7680d00ce1158d5f976eb224f3f632fd04a2226e.nq.gz
    ├── 7839e0f87af0fa9119c238569135a48547adf05e.nq.gz
    ├── 791f97cd9a0214dbbfe8aeb5f966c034d2ee8a19.nq.gz
    ├── 7957d75692d23c0d0df5ff21f61686f7e30fd449.nq.gz
    ├── 7a084937f86af9a93281974b2599f934643b51a9.nq.gz
    ├── 7bae58402011667b925c76acc8d842434a67c605.nq.gz
    ├── 7beaf62378ef5a16ce35b0e776fb143348abf266.nq.gz
    ├── 8a6613428d6274095b3cae5a08a9a72aa907890e.nq.gz
    ├── 8b466491ba896e458d2f55cfbcbb98f5e24665db.nq.gz
    ├── 8f0bf39e781da0a9b4fee17bfdc27e6f6a0aaab3.nq.gz
    ├── 91a84175bdea88a7536230084e3e57c28a74d6c3.nq.gz
    ├── 91ce8534e6f1da06f13408b96a6b05c336915386.nq.gz
    ├── 925852f6bb59e3756fad283115ab3822ca8eef59.nq.gz
    ├── 95687a6a0c5b46279685ce848f4066c5d936b974.nq.gz
    ├── 9725b41a9a62270f07eed9ef3eeebf31aa969440.nq.gz
    ├── 97987521f024b420d7e98a75be8aae972be0ef95.nq.gz
    ├── 9809f877cd3737539a9073441254d00eca58084f.nq.gz
    ├── 980e9a743c01f514a8cb7eba68b4cc7649226487.nq.gz
    ├── 9973ff1023c74dda1e460425159827525e201574.nq.gz
    ├── 9a780493ecfe1d5991abca653428448a9a7c3980.nq.gz
    ├── 9b17906e7293b51ff5ae542ffb34f0c2874d405d.nq.gz
    ├── 9c6591fcee7498832d8875e9436c74648f86b99b.nq.gz
    ├── 9c7f5f238b4b96ba899147f13f2deb229c9431fd.nq.gz
    ├── 9dd8c13d70e459c3de0a8e129f2919085fcb91b8.nq.gz
    ├── 9ebc52ec90cce6ef24dedc0bbd50cf0f10228ed9.nq.gz
    ├── a0719f36ae5e1790acbe01cbf1428298eb2eb94b.nq.gz
    ├── a0c5c9f6fec1092d598bf9f5a08cdc2efd3bd96f.nq.gz
    ├── a1ab286de6cfa2c834e754c565add045920ccedc.nq.gz
    ├── a264a46fe9f67fa98e1d880094cbf21626d1ea81.nq.gz
    ├── a310b83eb6de9e6abcf7c2417751abf63b473beb.nq.gz
    ├── a53b66a84758b4902ea735d7700bfee363d1a59c.nq.gz
    ├── a53ba7c4d368db5c777ab1917c7cff0cb4cabd43.nq.gz
    ├── a59d822063a9ef54c5196f81b018c711c6304cea.nq.gz
    ├── a654dbadf5f21e233470635271bef11662b40231.nq.gz
    ├── a6d21f604d59c1ad11b0385b927637389fe6b3dd.nq.gz
    ├── a89326701158455eb60153ba3df31ea05ae5dabd.nq.gz
    ├── aba91b466c05c863dc1c30efc8fe2ea077371efa.nq.gz
    ├── ac9a2147580e4990c4e251e284a4667e6baf9086.nq.gz
    ├── aca4d87e681aeddefd359cb3a8a554cdc5e47721.nq.gz
    ├── acfd208fb0c9cba648de8987832641a789261ef6.nq.gz
    ├── ade3e3e996a0212ea4fe1dbd07e16b5da3ad69e1.nq.gz
    ├── ae5369c1e976f57289c826f0fa1abe9c7ba1994e.nq.gz
    ├── ae88fd2ed695fc7f825d95735f34db2d5765d9df.nq.gz
    ├── af14b692e4a04f29071784b3dee8d343e196448b.nq.gz
    ├── b005daadcffe3d3bbde0ae965012dfcf85296201.nq.gz
    ├── b23a83eefb8f315c5e425bf2a46c787021f8f558.nq.gz
    ├── b269b55ca895e582b69d000cceb26b278c406a03.nq.gz
    ├── b3236fcf56383eff8974da860f3838815fbc1c59.nq.gz
    ├── b36d3a91147384161cf548536e4423dd0347460f.nq.gz
    ├── b3eddb80d429e08b7994ed2985b90b061f22abf8.nq.gz
    ├── b40d9e55a99cdba176d527c90b0f5f0278ac3e35.nq.gz
    ├── b4fba9b1a67d3858a5a548c82431dd9c65b09a00.nq.gz
    ├── b660072236d795f4581de97b5ad17690a0588f91.nq.gz
    ├── b981ed8127d4cf5d537328d4515a4e5a345cee46.nq.gz
    ├── bad0e828a04f1b522db05155c0f4e4aa5753364a.nq.gz
    ├── bb856a1ddb055c629481ccaebe0513303de2f102.nq.gz
    ├── bccb37ac17261ecab28d6c828de90aabec88c49c.nq.gz
    ├── bd21de80f6a592bb047799d976b476b5585a0cbe.nq.gz
    ├── beaee1b1bb193b60af8b330750e57cf48e68448b.nq.gz
    ├── beded81df889de7079421d949bc360cf978b805f.nq.gz
    ├── c18258a36fab5a83f3dceba63370dcca1301a543.nq.gz
    ├── c294a8d61395ab037fdd2f29cd7139ec966aae0b.nq.gz
    ├── c2cc7f8287cccdc0715a519069511cb26abfce99.nq.gz
    ├── c356f3499ca0e1a0b733f801e4c193b65be6ec74.nq.gz
    ├── c493042d68b0bf8c8e89699314e22317ec7dead8.nq.gz
    ├── c4ca41613ff11fc07e4065b58c1bea2a9b70ec6d.nq.gz
    ├── c4f220b1e324eedce3199b798deea4c11a9443a1.nq.gz
    ├── c6f29ab9505120fbb49c3322f54ec8c5575d42ff.nq.gz
    ├── c78c30deccc3888a0cbedb6d94b0326d6f8f9f3b.nq.gz
    ├── c846667fd0ba7e117c6404727b0e102522ecbc1a.nq.gz
    ├── c9237baf275eac06b5681758bbd41b6c96ee453d.nq.gz
    ├── cadf0002d43abedb2fac67615a0d7698e76fa8d6.nq.gz
    └── cae75fb09355db505d9475753f1fccb57baec602.nq.gz

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

[fthomas/refined](https://github.com/fthomas/refined)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
