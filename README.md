# Tools


## Usage

```bash
# Get all Docker versions availabl in Debian apt (desc order)
curl -sS https://raw.githubusercontent.com/cytopia/tools/master/docker-apt-versions | sh

# Get second latest Docker version availabl in Debian apt
curl -sS https://raw.githubusercontent.com/cytopia/tools/master/docker-apt-versions | sh -s 2
```

```bash
# Get all released Docker versions (desc order)
curl -sS https://raw.githubusercontent.com/cytopia/tools/master/docker-versions | sh

# Get third latest released Docker version
curl -sS https://raw.githubusercontent.com/cytopia/tools/master/docker-versions | sh -s 3
```

```bash
# Get all released Docker Compose versions (desc order)
curl -sS https://raw.githubusercontent.com/cytopia/tools/master/docker-compose-versions | sh

# Get fourth latest released Docker Compose version
curl -sS https://raw.githubusercontent.com/cytopia/tools/master/docker-compose-versions | sh -s 4
```
