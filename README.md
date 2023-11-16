# ADP Helm Library Chart Repository

A Helm chart public repository that contains ADP helm library charts for `AKS resources` and `Azure Service Operator (ASO) resources`. It can be used by any ADP microservice Helm chart which can then import K8s object templates configured to run on the ADP platform.


## Including the library chart

Steps:
  * Update `Chart.yaml` to `apiVersion: v2`
  * Add library chart under `dependencies`. Choose the version you want. Version number can include `~` or `^` to pick up latest PATCH and MINOR versions respectively

For information on how to use `adp-aso-helm-library` templates please check the [adp-aso-helm-library repo README](https://github.com/DEFRA/adp-aso-helm-library/blob/master/README.md)

For information on how to use `adp-helm-library` templates please check the [adp-helm-library repo README](https://github.com/DEFRA/adp-helm-library/blob/master/README.md)

