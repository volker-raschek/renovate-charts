# renovate-charts

[![Build Status](https://drone.cryptic.systems/api/badges/volker.raschek/renovate-charts/status.svg)](https://drone.cryptic.systems/volker.raschek/renovate-charts)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/volker-raschek)](https://artifacthub.io/packages/search?repo=volker-raschek)

This is an inofficial helm chart for
[renovate](https://github.com/renovatebot/renovate/). Goal of this chart is to
be more lightweight than the official one.

This helm chart can be found on [artifacthub.io](https://artifacthub.io/) and
can be installed via helm.

```bash
helm repo add volker.raschek https://charts.cryptic.systems/volker.raschek
helm install renovate volker.raschek/renovate
```

## Customization

All [configuration
options](https://docs.renovatebot.com/self-hosted-configuration/) can
be defined in the `values.yml` file below the `config` section. Alternatively
can be the options passed via the `--set` flag of the `helm install` command.
