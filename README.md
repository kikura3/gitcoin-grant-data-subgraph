# gitcoin-grant-data-subgraph

This subgraph is currently configured to pull grant applications & votes data for gitcoin alpha round.
To add new round, Please modify the [subgraph](https://github.com/kikura3/gitcoin-grant-data-subgraph/blob/main/gitcoin-grants/subgraph.yaml) to include the below information for the new round

  - round address
  - voting contract address

TODO: Fix the subgraph to auto pickup new rounds using dynamic templates.

This subgraph is deployed at [Deployment URL](https://api.studio.thegraph.com/query/41140/gitcoin-grants/v0.0.7)
