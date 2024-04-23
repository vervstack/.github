# Verv

---

Verv is a lightweight container management system based on docker containers.

## Velez

---

[![Docker Image Version (tag)](https://img.shields.io/docker/v/godverv/velez/latest?logo=docker)](https://hub.docker.com/r/godverv/velez/tags)

Velez is an application to manage a node on a physical server  

## Matreshka
Matreshka is a Boy (based on yaml) configuration manager  

Matreshka allows you to specify
- Resources for your application (postgres, redis etc.)
- Server API of your application (grpc, rest etc.)
- Basic verv configuration (name, startup timeout, version)
- Environment variables (for more specific configuration)

### matreshka-be (Configuration server)

---

[![Docker Image Version (tag)](https://img.shields.io/docker/v/godverv/matreshka-be/latest?logo=docker)](https://hub.docker.com/r/godverv/matreshka-be/tags)

Server that will store your configurations and allow you to modify it though api

### Matreshka (Golang configuration package)

---

Golang package that will automatically parse:
- Matreshka Api
- Environment variables
- Configuration files

And merge them into one configuration (priority by given order)

[![GitHub Tag](https://img.shields.io/github/v/tag/godverv/Matreshka)](https://github.com/godverv/Matreshka/releases/latest)

