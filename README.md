# 5G-all-in-one Helm

***5G-all-in-one-helm*** is an open-source project implemented to provide helm charts in order deploy on one click a 5G system (RAN+SA 5G core) without using a lot, that is, exclusively on top of the kubernetes network plugin, like Calico.  It currently relies on Free5GC  for the core  network and UERANSIM  to simulate Radio Access Network. In furure will be added suport to [my5G-RANTester](https://github.com/my5G/my5G-RANTester)

## TL;DR
```console
helm repo add towards5gs 'https://raw.githubusercontent.com/zanattabruno/5G-all-in-one-helm/main/repo/'
helm repo update
helm search repo
```

## Motivations
Please consult this [link](/motivations.md) to see the motivations that have led to this project.

## Acknowledgement
Thanks to both Orange towards5GS, Free5GC and UERANSIM teams for their great efforts.

## License
***5G-all-in-one-helm*** is under [Apache 2.0](./LICENSE) license.
