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
