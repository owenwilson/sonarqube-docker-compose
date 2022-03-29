# sonarqube - docker compose file

### Files

- postgresql.yml is an example file of postgres alpine
- sonarqube.yml file is principal example

### Download sonar-scanner for linux

- [sonar-scanner](https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/)

```sh
unzip sonar-scanner-file.zip
```

### Create a symbolic link

```sh
sudo ln -s $PWD/sonar-scanner-file/bin/sonar-scanner /usr/sbin/sonar-scanner
```

### Create folders

```sh
mkdir postgresql
mkdir postgresql_data
mkdir sonarquber_data
mkdir sonarquber_extensions
mkdir sonarquber_logs
```

### Docker compose

```sh
docker-compose -f sonarqube.yml pull
```

```sh
docker-compose -f sonarqube.yml
```

### Contributions to example sonarqube tool

- [owenwilson](https://github.com/owenwilson)
