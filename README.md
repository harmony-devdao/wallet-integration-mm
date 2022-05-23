# wallet-integration-mm
Example of a wallet integration into a DAPP using the MetaMask wallet as example.

What does it cover?

+ Checks if wallet is installed: `checkIfMetaMaskIsInstalled()`
+ Connection via Button: `buttonConnect()`
+ Concurrent connections on page load: `connect()`
+ Detects changing of network from extension UI: `onChainChanged()`
+ Detects changing of account from extension UI: `onAccountChanged()`
+ List of supported Networks, which allows for:
    + Changing network on button press: `changeChain()`
    + Adding networks on button press: `changeChain()`