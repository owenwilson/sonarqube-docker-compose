# Sonarqube simple deploy

## Vm linux

```sh
sysctl -w vm.max_map_count=262144
```

### Files

- sonarqube.yml is a simple example

### Download sonar-scanner for linux

- [sonar-scanner](https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/)

```sh
unzip sonar-scanner-file.zip
```

### Docker compose

```sh
docker compose -f sonarqube.yml pull
```

```sh
docker compose -f sonarqube.yml up -d 
```
