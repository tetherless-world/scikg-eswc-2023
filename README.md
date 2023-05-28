# SciKG: Tutorial Building Scientific Knowledge Graphs from Data, Data Dictionaries, and Codebooks

## Installing The Human-Aware Data Acquisition Framework (HADatAc)

Clone HADatAC repo:
```
$ git clone https://github.com/paulopinheiro1234/hadatac.git
```

Clone NHANES SDDs and configs:
```
$ git clone https://github.com/tetherless-world/nhanes-hadatac.git
```

Clone this repo:
```
$ git clone https://github.com/tetherless-world/scikg-eswc-2023.git
```

Move NHANES config files to HADatAc dir:
```
$ mv nhanes-hadatac/conf/namespaces.properties hadatac/conf/namespaces.properties
$ mv mv scikg-eswc-2023/hadatac/conf/hadatac-docker.conf hadatac/conf/hadatac-docker.conf
```

Build and run HADatAc with Docker:
```
$ cd hadatac/
$ docker compose up -d
```
