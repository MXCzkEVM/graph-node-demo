# Subgraph Creation Demo for Wannsee Node

This guide will walk you through the setup and associations necessary to create a subgraph for a Wannsee node.

## Node Mapping 

Below is the mapping of nodes to their respective web services:

## Graph Domain
MXCZkEVM Mainnet mxc-graph.mxc.com
Wannsee Testnet mxc-graph-node.mxc.com

## Deploy

1. graph create <graph-name> --node http://mxc-graph-node.mxc.com:8020

2. graph deploy <graph-name> --ipfs http://mxc-graph-node.mxc.com:5001 --node http://mxc-graph-node.mxc.com:8020

- **Admin Node**: 
    - Web UI: [Admin](http://mxc-graph-node.mxc.com)
    - Service endpoint: mxc-graph-node.mxc.com:8020
    
- **IPFS Node**: 
    - Service endpoint: mxc-graph-node.mxc.com:5001
    
- **Playground Node**: 
    - Web UI: [Playground](http://mxc-graph-node.mxc.com:8030/graphql/playground)
    - Example Subgraph: mxc-graph-node.mxc.com/subgraphs/name/simpleStore/First
    
