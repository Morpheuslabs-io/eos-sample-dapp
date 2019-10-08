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

### `eosio-explorer` as a professional explorer tool for development

Opensource link:

https://github.com/EOSIO/eosio-explorer.git

#### Install and start

  - Stop the dockerized version (because its contract-compilation function doesn't work in container environment) as it is included in the combo `start-eos-mongo-explorer`
  - Start the tool by running this cmd: `pm2 start start_explorer.sh`
  - URL: http://localhost:3000

#### Use cases

Network config/management: point to any custome blockchain network

Contract deployment

Account management

**Notice**

Before deploying smart contract, some account has to be imported by clicking tab `MANAGE ACCOUNTS` and then either click the button `CREATE ACCOUNT` for creating new account or scroll down to the section `Import Account`. Click the button `IMPORT KEYS` of any available account to import its private key.

List of available accounts with private key

```
[
  {"name":"useraaaaaaaa", "privateKey":"5K7mtrinTFrVTduSxizUc5hjXJEtTjVTsqSHeBHes1Viep86FP5", "publicKey":"EOS6kYgMTCh1iqpq9XGNQbEi8Q6k5GujefN9DSs55dcjVyFAq7B6b", "wallet":"notewal"},
  {"name":"useraaaaaaab", "privateKey":"5KLqT1UFxVnKRWkjvhFur4sECrPhciuUqsYRihc1p9rxhXQMZBg", "publicKey":"EOS78RuuHNgtmDv9jwAzhxZ9LmC6F295snyQ9eUDQ5YtVHJ1udE6p", "wallet":"notewal"},
  {"name":"useraaaaaaac", "privateKey":"5K2jun7wohStgiCDSDYjk3eteRH1KaxUQsZTEmTGPH4GS9vVFb7", "publicKey":"EOS5yd9aufDv7MqMquGcQdD6Bfmv6umqSuh9ru3kheDBqbi6vtJ58", "wallet":"notewal"},
  {"name":"useraaaaaaad", "privateKey":"5KNm1BgaopP9n5NqJDo9rbr49zJFWJTMJheLoLM5b7gjdhqAwCx", "publicKey":"EOS8LoJJUU3dhiFyJ5HmsMiAuNLGc6HMkxF4Etx6pxLRG7FU89x6X", "wallet":"notewal"},
  {"name":"useraaaaaaae", "privateKey":"5KE2UNPCZX5QepKcLpLXVCLdAw7dBfJFJnuCHhXUf61hPRMtUZg", "publicKey":"EOS7XPiPuL3jbgpfS3FFmjtXK62Th9n2WZdvJb6XLygAghfx1W7Nb", "wallet":"notewal"},
  {"name":"useraaaaaaaf", "privateKey":"5KaqYiQzKsXXXxVvrG8Q3ECZdQAj2hNcvCgGEubRvvq7CU3LySK", "publicKey":"EOS5btzHW33f9zbhkwjJTYsoyRzXUNstx1Da9X2nTzk8BQztxoP3H", "wallet":"notewal"},
  {"name":"useraaaaaaag", "privateKey":"5KFyaxQW8L6uXFB6wSgC44EsAbzC7ideyhhQ68tiYfdKQp69xKo", "publicKey":"EOS8Du668rSVDE3KkmhwKkmAyxdBd73B51FKE7SjkKe5YERBULMrw", "wallet":"notewal"}
]
```



