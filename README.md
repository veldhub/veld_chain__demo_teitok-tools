# veld_chain__demo_teitok-tools/

This repo contains [chain velds](https://zenodo.org/records/13322913) encapsulating demos of code 
velds from https://github.com/veldhub/veld_code__teitok-tools applied on sample data provided by 
https://github.com/COST-ELTeC/ELTeC-deu/ .

## requirements

- git
- docker compose (note: older docker compose versions require running `docker-compose` instead of 
  `docker compose`)

Clone this repo with all its submodules
```
git clone --recurse-submodules https://github.com/veldhub/veld_chain__demo_teitok-tools.git
```

## how to reproduce

The following chain velds were used. Open the respective veld yaml file for more information.

**[./veld_parseudpipe.yaml](./veld_parseudpipe.yaml)**

```
docker compose -f veld_parseudpipe.yaml up
```

**[./veld_udpipe2teitok.yaml](./veld_udpipe2teitok.yaml)**

```
docker compose -f veld_udpipe2teitok.yaml up
```

**[./veld_xmltokenize.yaml](./veld_xmltokenize.yaml)**

```
docker compose -f veld_xmltokenize.yaml up
```

