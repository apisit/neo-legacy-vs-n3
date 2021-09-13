# NEO Legacy vs NEO 3 (N3)

If you are like me who haven't followed much closely about NEO 3 (N3) but you are quite familiar with NEO (Legacy), You might find yourself trying to find more information about N3 and wanting to see what's the difference, what has changed. I have gone through that process and summarized what I find from both developer perspective and consumer(Crypto Investor) perspective. Start with the basic questions such as does the number of NEO or GAS change?, Is NEO divisible now in N3?, etc. I hope this post helps you get a better understanding of what N3 offers and answer some of the questions you might have.



---


| Item                                             | N3                                                                              | Neo legacy                                                                                                  | Note                                                                         |
|--------------------------------------------------|---------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| Source                                           | [Github](https://github.com/neo-project/neo)                                                                          | [Github](https://github.com/neo-project/neo/tree/2.13.0)                                                                                                      |                                                                              |
| Max supply of NEO                              | 100 millions                                                                    | 100 millions                                                                                                | unchange                                                                     |
| Minimum unit of NEO                              | 1                                                                               | 1                                                                                                           | unchange                                                                     |
| Max supply of GAS                              | [No max supply](https://docs.neo.org/docs/en-us/basic/governance.html#gas)                                                                    | 100 millions                                                                                                |                                                                      |
| Minimum unit of GAS                              | 0.00000001                                                                      | 0.00000001                                                                                                  | unchange                                                                     |
| Account                                          | Native contract                                                                 | UTXO                                                                                                        |                                                                              |
| Number of consensus nodes                        | 7                                                                               | 7                                                                                                           |                                                                              |
| Block finality                                   | 1 block                                                                         | 1 block                                                                                                     | unchange                                                                     |
| Neo Node                                         | neo-cli                                                                         | neo-cli                                                                                                     | https://docs.neo.org/docs/en-us/node/introduction.html#neo-node-introduction |
| Address                                          | Starts with N                                                                   | Starts with A                                                                                               |                                                                              |
| Private key                                      | Compatible with N3                                                              | Compatible with N3                                                                                          |                                                                              |
| Wallet file                                      | NEP6                                                                            | NEP6                                                                                                        | unchange                                                                     |
| Gas distribution                                 | [5 GAS per block](https://docs.neo.org/docs/en-us/basic/governance.html#gas)                                                                 | Distributed over 22 years through a decaying-rate algorithm.                                                | https://neo.org/neogas#tokens                                                |
| Consensus                                        | dBFT 2.0                                                                        | dBFT                                                                                                        |                                                                              |
| Governance                                       | https://docs.neo.org/docs/en-us/basic/governance.html#governance-and-incentives |                                                                                                             |                                                                              |
| **Protocol**                                         |                                                                                 |                                                                                                             |                                                                              |
| NFT Standard                                     | [NEP11](https://github.com/neo-project/proposals/blob/master/nep-11.mediawiki)                                                                           | ??                                                                                                          |                                                                              |
| Token Standard                                   | [NEP17](https://github.com/neo-project/proposals/blob/master/nep-17.mediawiki)                                                                           | NEP5                                                                                                        |                                                                              |
| Smart Contract Manifest                          | [NEP15](https://github.com/neo-project/proposals/blob/master/nep-15.mediawiki)                                                                           | ??                                                                                                          |                                                                              |
| Executable format                                | [NEP16](https://github.com/neo-project/proposals/blob/master/nep-16.mediawiki)                                                                           | .avm file                                                                                                   |                                                                              |
| **Fees**                                             |                                                                                 |                                                                                                             |                                                                              |
| System fees                                      | https://docs.neo.org/docs/en-us/reference/fees.html                             | https://docs.neo.org/v2/docs/en-us/tooldev/concept/charging_model.html#system-fee                           |                                                                              |
| Network fees                                     | https://docs.neo.org/docs/en-us/reference/fees.html#network-fee                 |  Up to 20 free transactions in a block |                                                                              |
| **Technology**                                       |                                                                                 |                                                                                                             |                                                                              |
| Oracle                                           | [Native](https://docs.neo.org/docs/en-us/advanced/oracle.html)                                                                          | -                                                                                                           |                                                                              |
| Storage                                          | Native — [NeoFS](https://fs.neo.org/network)                                                                  | -                                                                                                           |                                                                              |
| Cryptography                                     |                                                                                 |                                                                                                             |                                                                              |
| Encode algorithm                                 | Base58                                                                          | Base58                                                                                                      | unchange                                                                     |
| Hash algorithm                                   | RIPEMD160,SHA256                                                                | RIPEMD160,SHA256                                                                                            | unchange                                                                     |
| Encryption Algorithm                             | ECC                                                                             | ECC                                                                                                         | unchange                                                                     |
| **Smart contract**                                   |                                                                                 |                                                                                                             |                                                                              |
| Token sale in Smart contract                     | Simply send asset to smart contract address                                     | Complicate because of UTXO                                                                                  |                                                                              |
| Cost to deploy a smart contract (Token contract) | 10 GAS                                                                          | Up to 1,000 GAS                                                                                             |                                                                              |
| Error handling & debugging                                   | [This](https://c.tenor.com/50hyInZwYp4AAAAC/breeze-nicolas-cage.gif)                                                                           | [This](https://c.tenor.com/L66gfL1eMUsAAAAC/computer-throw.gif)                                                                                                   |                                                                              |



### Useful links


https://neonewstoday.com/general/the-evolution-of-gas-in-the-neo-n3-blockchain-ecosystem/
