## 扩展
[validators](https://solana.com/validators)
```
First, install home-brew by running:

1. xcode-select --install
2. /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
3. Then follow “Next Steps” in output

Then run the following: 

1. brew install pkg-config cairo pango libpng jpeg giflib librsvg
2. brew doctor 
3. npm uninstall canvas
4. npm i -S canvas
```
##
```
solana config set --keypair ~/.config/solana/devnet.json
solana-keygen new --outfile ~/.config/solana/devnet.json

solana config get
solana balance

solana airdrop 2

// upload our NFTs
ts-node ~/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts upload -e devnet -k ~/.config/solana/devnet.json -cp config.json ./assets
// verify your NFTs
ts-node ~/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts verify_upload -e devnet -k ~/.config/solana/devnet.json
```
## 其他
[GIF support for Candy Machine](https://github.com/metaplex-foundation/metaplex/issues/511)
[a decentralized file-store](https://www.arweave.org/)
