```bash
helm install artifactory ./artifactory --set artifactory.replicaCount=1 --set artifactory.masterKey=ac09f7558f2c3b04bc4ece96e552baebf04f90801eae886527cc71974e238e2f --set artifactory.joinKey=32416ae55a8b04999b70c054d2d64ab230b67b1d872302d6ea5503ab17b7158d --namespace artifactory
```