# Subgraph Creation Demo for Geneva Node

This guide will walk you through the setup and associations necessary to create a subgraph for a Geneva node.

## Node Mapping 

Below is the mapping of nodes to their respective web services:

## Graph Domain
- MXCZkEVM Mainnet mxc-graph.mxc.com
- Wannsee Testnet mxc-graph-node.mxc.com
- Geneva Testnet geneva-graph-node.moonchain.com

## Deploy

1. graph create <graph-name> --node geneva-graph-node.moonchain.com:8020

2. graph deploy <graph-name> --ipfs geneva-graph-node.moonchain.com:5001 --node geneva-graph-node.moonchain.com:8020

## Endpoints
- **Admin Node**: 
    - Web UI: [Admin](http://geneva-graph-node.moonchain.com)
    - Service endpoint: geneva-graph-node.moonchain.com:8020
    
- **IPFS Node**: 
    - Service endpoint: geneva-graph-node.moonchain.com:5001
    
- **Playground Node**: 
    - Web UI: [Playground](http://geneva-graph-node.moonchain.com:8030/graphql/playground)
    - Example Subgraph: geneva-graph-node.moonchain.com/subgraphs/name/simpleStore/First
    
