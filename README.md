# ERC20 Subgraph
This subgraph is prepared with the help of code from [openzeppelin-subgraphs](https://github.com/OpenZeppelin/openzeppelin-subgraphs)

## Existing deployments
**Base Mainnet** - [erc20-subgraph-base](https://thegraph.com/explorer/subgraphs/7N6hxverxf75LnXRjAahUQ658jPSSzxb9ucxVYD7DHcT?view=Query&chain=arbitrum-one)</br>
**Hemi Mainnet** - [erc20-subgraph-hemi](https://thegraph.com/explorer/subgraphs/CxA7MEpEqJJPa5AWoTwo8cWx3unHzxtUXarqckHqQeq6?view=Query&chain=arbitrum-one)</br>
**Optimism mainnet** - [erc20-subgraph-optimism](https://thegraph.com/explorer/subgraphs/9mtdshzQ3ZYJm8nGE3S6GU8snivWFW97YTkRaADzNUnV?view=Query&chain=arbitrum-one)


## Setup
Run `yarn install`

## Generate code from Graphql schema and ABI
Run `yarn codegen`


## Deploy
Follow deployment guide [here](https://thegraph.com/docs/en/subgraphs/developing/deploying/using-subgraph-studio/) to understand the process of deployment.

**Graph auth**
- Get the graph deploy key, follow steps [here](https://thegraph.com/docs/en/subgraphs/developing/deploying/using-subgraph-studio/#graph-auth).
- Run `yarn graph auth <Deploy Key>`
  
**Deploy Subgraph**
- Run `yarn deploy`
> This command is going to ask subgraph name. As a rule of thumb you should follow "erc20-subgraph-${chainName}" pattern for subgraph name.
