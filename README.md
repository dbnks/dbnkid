# dBnkID
dBnkID is a JavaScript API used by [dBnk](https://github.com/dbnks/dbnk) to enable the import and usage of ```outside accounts``` that didn't derive from dBnk itself. dBnkID makes this possible by combining the functionality of Scatter (EOS), MetaMask (Ethereum), ArisenID (Arisen) and TronLink (TRON) into one library, so that users of these outside blockchain identity platforms have the ability to join dApps like dBnk with their current account on EOS, TRON, Ethereum and Arisen, while also allowing dApps that utilize dBnk for payments, to also utilize these outside, already existent accounts.

## Outside Accounts
Within dBnk ` ``outside accounts``` are defined as accounts that didn't derive from a ```dBnk DEN```, they instead derived from an outside identity management platform such as Scatter (EOS), TronLink (TRON), MetaMask (ETH) or ArisenID (RSN). 

**EXAMPLE:**
```outside accounts``` are stored within the ```outside_accounts``` table, within the ```accounts``` SCOPE of the  ```dbnk ``` smart contract. ```outside accounts``` appear within dBnk just as ```native accounts```, except ```outside accounts have an icon of the identity platform they derive from, next to the ```account_label```.

## One Login. One Bnk.
dBnkID allows holders of EOS, TRON, RSN and ETH to login to dApps that utilize dBnkID with their EOS, TRON, Arisen and Ethereum accounts. This makes on boarding much easier for dApps that utilize dBnk's powerful foundation as a way of building a completely decentralized ecosystem, because not only can they use the network they prefer, along with the identity management software they trust, they can also spend their digital holdings from these networks within any dBnk-integrated dApp with ease. While dBnk itself allows for the creation of accounts on over 20+ blockchains, dBnkID allows dBnk users to manage digital assets from accounts that didn't derive from the dBnk account creation process (accounts that were created outside the dBnk account creation process), without exposing the private keys of these accounts or worsening the overall user experience.

dBnkID helps dBnk consolidate a user's online identities down to a single login and brings all of your wallets into one application, that ultimately becomes your very own "crypto bank". 

## Development Underway
We're currently working on completing the following milestones:
- Combining MetaMask, Scatter, ArisenID and TronLink APIs into one cohesive and uniform API. 
- Capability to interface with [dBnkJS](https://github.com/dbnks/dbnkjs) so that dBnkID can run transactions against the [dBnk smart contract](https://github.com/dbnks/dbnk-contract), when storing data related to ` ``outside accounts``` on-chain. 
- Development of the dbnkid:// protocol for dApps like dBnk to interface with other protocols like scatter://, arisenid://, metamask:// and tronlink://. 

## License
```dBnkID``` is covered under the [MIT LICENSE](LICENSE.md) and is a copyright of [Peeps](https://dpeeps.com).

## Important
See LICENSE for copyright and license terms. Peeps makes its contribution on a voluntary basis as a member of the Arisen and dBnk communities and is not responsible for ensuring the overall performance of the software or any related applications. We make no representation, warranty, guarantee or undertaking in respect of the software or any related documentation, whether expressed or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall we be liable for any claim, damages or other liability, whether in an act ion of contract, tort or otherwise, arising from, out of or in connection with the software or documentation or the user or other dealings in the software or documentation. Any test results or performance figures are indicative and will not reflect performance under all conditions. Any reference to any third party or third-party product, service or other resource is not an endorsement  or recommendation by Peeps. We are not responsible, and disclaim any and all responsibility and liability, for your user of or reliance on any of these resources. Third-party resources may be updated, changed or terminated at any time, so the information here may be out of date or inaccurate. Any person using or offering this software in connect ion with providing software, goods or services to third parties shall advise such third parties of these license terms, disclaimers and exclusions of liability. Peeps, Peeps Labs, dBnk, Arisen and associated logos are copyright of Peeps. 

Wallets and related components are complex software that requires the highest levels of security. If incorrectly built or used, they may compromise users' private keys and digital assets. Wallet applications and related components should undergo thorough security evaluations before being used. Only experienced developers should work with this software.
