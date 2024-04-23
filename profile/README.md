# Verv

Verv is a lightweight container management system based on docker containers.

## Velez

![Docker Image Version](https://img.shields.io/docker/v/godverv/velez?style=for-the-badge&logo=docker&label=Velez%20image&labelColor=white&color=blue)



Velez is an application to manage a node on a physical server  

## Matreshka
Matreshka is a boy (based on yaml) configuration manager  

Matreshka allows you to specify
- Resources for your application (postgres, redis etc.)
- Server API of your application (grpc, rest etc.)
- Basic verv configuration (name, startup timeout, version)
- Environment variables (for more specific configuration)

### matreshka-be (Configuration server)

---

![Docker Image Version](https://img.shields.io/docker/v/godverv/matreshka-be?style=for-the-badge&logo=docker&label=%20matreshka-be%20image&labelColor=white&color=blue)


Server that will store your configurations and allow you to modify it though api

### Matreshka (Golang configuration package)

---

Golang package that will automatically parse:
- Matreshka Api
- Environment variables
- Configuration files

And merge them into one configuration (priority by given order)

![GitHub Tag](https://img.shields.io/github/v/tag/godverv/Matreshka?style=for-the-badge&logo=github&label=Matreshka%20version&labelColor=gray&color=green)


