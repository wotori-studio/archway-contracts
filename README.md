# Archway smart contracts sandbox

- cw20
- increment
- cw721(in progress)

- currently cw20 & cw721 copied from [cw-plus](https://github.com/CosmWasm/cw-plus) and [cw-nft](https://github.com/CosmWasm/cw-nfts)

- increment just auto generated code taken from [Archway repo](https://github.com/archway-network/archway-templates/tree/main/increment)

for better use read this:
[Anatomy of a Smart Contract](https://docs.cosmwasm.com/dev-academy/develop-smart-contract/intro/)

# Keep in mind

- when doing `% archway deploy`, CLI looks in config.json - title. This name will be used while deployng and should be the same as generated wasm files in folder `artifacts`