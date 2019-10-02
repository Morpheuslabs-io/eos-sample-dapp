# EOS dApp development

## Setup development environment on `localhost`

### Deploy local blockchain network

`git clone https://github.com/Morpheuslabs-io/eos-private-network.git`

Follow the below sections in README:
  - `System start`
  - `Log`
  - `System stop and cleanup`

Blockchain API endpoint: http://127.0.0.1:8888

Explorer tool endpoint: http://localhost:3039

### Install `eosio-explorer` as a professional explorer tool for development

The tool `eosio-explorer` is shipped with an executable binary that can easily be installed:

`npm i -g eosio-explorer`

To start, run this cmd:

`eosio-explorer start_gui --clear-browser-storage node=http://127.0.0.1:8888 db=mongodb://localhost:27788/eosio_nodeos_mongodb_plugin`

The tool URL: http://localhost:5111

Use cases:
  - Network config/management: point to any custome blockchain network
  - Contract deployment
  - Account management



