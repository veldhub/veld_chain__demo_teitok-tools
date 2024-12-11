# demo veld chain of teitok-tools

This chain integrates the code veld https://github.com/veldhub/veld_code__teitok-tools on sample
data provided by https://github.com/COST-ELTeC/ELTeC-deu/

## how to reproduce

**requirements: docker compose and git (note, depending on your docker / compose version, you might need to run `docker-compose ...` instead of `docker compose ...`**

Clone this repo with all submodules:

```
git clone --recurse-submodules https://github.com/veldhub/veld_chain__demo_teitok-tools.git
```

And execute a veld chain with:
```
docker compose -f <chain yaml> up
```
e.g.
```
docker compose -f veld_udpipe2teitok.yaml up
```

See inside the respective chain yaml files within this repo, or the code veld yaml files within the
submodule, for more information.

