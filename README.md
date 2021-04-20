# GonMap Helm Chart
**Note: Currently in Alpha**

![Logo](https://github.com/clobaa/gonmap/blob/main/logo.svg)
<img src="https://github.com/clobaa/gonmap/blob/main/logo.svg">

This repo holds the chart and helm repo for [GonMap](https://github.com/clobaa/gonmap).

# Installation
```
$ helm repo add gm https://clobaa.github.io/gonmap-helm
$ helm repo update
```

To check if the repo has been added correctly,
```
$ helm search repo gm/gonmap
NAME      	CHART VERSION	APP VERSION	DESCRIPTION                              
gm/gonmap	0.1.0        	0.1.0      	A Helm chart for Gonmap Global ConfigMap
```

Finally, to install
```
$ helm install gonmap gm/gonmap
```

# Uninstallation
```
$ helm uninstall gonmap
```

# Dev Info
`docs` folder is the helm repo (gh-pages only serves `docs` or `root` folder).
`chart` is the actual chart folder. 