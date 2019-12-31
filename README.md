# create-etherum-wallet
In this Exercise we are going to be learning how to create Ethereum wallet with C#, .NET Core, and Nethereum libraries. During the exercise you will install several NuGet packages, write the source code for different functionalities and in the end, you will send and receive ether coins with your wallet.   

What I did to create the repo:
1. Created the empty repo in github.
2. Clone the empty repo to my local box.
3. Run dotnet new console
4. Run dotnet run -- This should run the code and print out "Hello World!"
5. Copy the Program.cs code from the exercise template directory to the Program.cs in the project.
6. Run dotnet add package for the following imports:
using System;
using static System.Console;
using System.Collections;
using System.IO;
using System.Linq;
using System.Threading.Tasks;
using Nethereum.HdWallet;
using Nethereum.Web3;
using Nethereum.Web3.Accounts;
using Newtonsoft.Json;
using NBitcoin;
using Rijndael256

History of what I actually ran:
  501  dotnet add package System
  502  dotnet add package System.Console
  503  dotnet add package System.Collections
  504  dotnet add package System.IO
  505  dotnet add package System.Linq
  506  dotnet add package Threading.Tasks
  507  dotnet add package Nethereum.HdWallet
  508  dotnet add package Nethereum.Web3
  509  dotnet add package Nethereum.Web3.Accounts
  510  dotnet add package Newtonsoft.Json
  511  dotnet add package Rijindael256 -- mispelled package neme.  don't use this.
  512  dotnet restore
  513  dotnet add package Rijindael256.Core -- mispelled package neme.  don't use this.
  514  dotnet add package Nethereum.KeyStore
  515  dotnet add package Nethereum.Accounts
  516  dotnet add package Rijndael256.Core 

Wallet saved in file: EthereumWallet_2019-12-31_11-35-59-5555.json
New Wallet was created successfully!
Write down the following mnemonic words and keep them in the save place.
smoke return heart pool skate siren pistol faith miss person sister rack
Seed: 
53f2c9ce2499758ddf6852ccfd88eb3d5c3acf4516359a8ba69a44a33ff8113563c139fbe5653ec478fba466fcce577e4e7a053222354926543c6d888174ec07

Addresses:
0x9245de533D68b4580F6dF707bDBB00A5757719eB
0xdfA14362F3D37C5BACd5D4f8680441eAc187f020
0x4b41e8900d00A3Cf8859b54Bf0156dBCC6dE98B3
0xd3ecDB21d654Bab3CE86Ac26F9d63A8A7b03dA3D
0x31603dC0BF6ef2D75ECe75EAA15AfCDD9aB2fE81
0x1e9A7A9AD551B1282B2D64a9F0957261a928FfeB
0x26630F2fd724C20960B30C738A898C81719F3aE6
0x9cf9CF17b8ecedf727DA2B03F2E83346B3D2ae32
0xbFA0308eF9846A9a2DFb0F1375C0e08dA8447547
0x84CD12563C2c69cAd057062B968433A68f943F5b
0xa70EA0A627802F9B903e2Cb9287f9407cd97F5fB
0x7c0C14C43438afd2EDD33c344db640840062F4fD
0x94936c0889d891F2559936A548B2475F9b8184Fc
0x4469d70472A6354389620B38EAd132A92e335fa5
0x57af3DcE4beE737eCe6290AC0f018d6A66724542
0xDDBef69D49F623Fb87BDf2947F62D12c75580710
0x14310c6d67b14ba3C5985E26427d6d2b362B279a
0x2d5866C3fB2432fC0D99b5BB47e68fFc25e8f91f
0xaE7b50c5C2D9bB286D5EB6A5714615bB029C5fa5
0x65D9dE7AEaF85401f1317D3064acE73e1F27D29F

Private Keys:
0x37f5cf134b6bd2882dc987d5d5997b1df97fe33351c5b74428cea31db423dcab
0xbe11d9f36d610e73d42eb3cd2d143f3b03f3cad877e3e98488eb8c11ceb05197
0xcaf9faa6556be9231f4e9d95f57a31df4f53410d63944503989e7c7ec3ae8d43
0x35355578de378897b0df6aeab7b54a2c3f96ef0b09e45abbe0787e3a40bebab5
0xd0952e20726b2cc25f1f7542d4c3acec9637faec1633030eee4ec275364d99f7
0x200d202ddffdb9569ae63ea81bd477114121f4ba7c343c8888e1eded82959f4b
0x75d3e54aa88ca9238ff7a6a7910a5592b92a1f2252b1e241898d0f95611292ae
0xfcb3dece678d9e3f2d8fbbcb9602e7e5b1f42eaea81b9cb14ceeb1c788c9217d
0x35978f398c69cbdb1220841e107cafafb903fcdd04c5ca939d5ed440620ecf1b
0x0ef91859d52e2a7bf99d4d86acb01aabb8889cf0848e95e10daf59294a8be36e
0x5aabcaeca8edae0e30a50f07c5eb2c337f5b3ade0db7d0c41aec4efabf6607f0
0x31f264b619f0cd12f62f2be4d24d5acc20dd02d9637b228db3f39ec24ff90c70
0x9bcce54af46434e3b148401fa7614e123a4992c6dc4fbd7035245895a6162600
0x14d02d3f13a96546b068d959b58a0f15db37547046dae4fa7a86e0d1452645ad
0xf2a1d53882d02197d62fbc2290cacf1037def34d41d24c71e14180c0ad48ec92
0x7dfa7d2839d1e8943397778c21b1e473c8740af1ab75205946b9cfd4c424f22b
0x77d66cc426af377920476bc0ee129bc860306b2e2c7a9a4f5af37d7f6c3b12eb
0xe146e0c0d49fe7986c415aa283faf0a70ca49e360ad77c0b363e3b7f5f564556
0x9a99a844b86e2371539828359c2164cd1416924cdb5da7d5250f4960bfd1def8
0x253e62f2a72e9ea06ae1344f20a07dc8487cc082f3de4a17c268c1d304d4c8b4
