# CapX Tech Smart Contract
The smart contract for the sale of the CAPC ERC-20 token.
Based on https://github.com/TokenMarketNet/ico
See installation instructions there.

Once 'populus compile' works, 

deploy-contracts \
  --address=[account_0_address] \
  --deployment-file=capx/capx-crowdsale.yml \
  --deployment-name=local-token
