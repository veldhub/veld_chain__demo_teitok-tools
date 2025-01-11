# demo veld chain of teitok-tools

This chain veld integrates the code veld https://github.com/veldhub/veld_code__teitok-tools on 
sample data provided by https://github.com/COST-ELTeC/ELTeC-deu/

## requirements

- git
- docker compose

## how to reproduce

Clone this repo with all submodules:
```
git clone --recurse-submodules https://github.com/veldhub/veld_chain__demo_teitok-tools.git
```

This repo contains three demo chain velds:

- [./veld_parseudpipe.yaml](./veld_parseudpipe.yaml)
- [./veld_udpipe2teitok.yaml](./veld_udpipe2teitok.yaml)
- [./veld_xmltokenize.yaml](./veld_xmltokenize.yaml)

Execute a veld chain with:
```
docker compose -f <chain yaml> up
```
e.g.
```
docker compose -f veld_udpipe2teitok.yaml up
```

See inside the respective chain yaml files within this repo, or the code veld yaml files within the
submodule, for more information.

