# diogenes
Manage real things

This app allows you to manage collections of real things and add context information to it.

**This application is in development, so be patient and see our progress in next list**

- [ ] Manage a hierarchy of containers where things are stored
- [ ] Manage things
  - [ ] Add photo, description, tags,...
  - [ ] Add related documentation/files (manual, whitepaper of an electronic component,...)
  - [ ] Add other related metadata information like urls
- [ ] Integrate a search engine to find things quickly
- [ ] Manage borrow things


## Configurations

> To inject configurations in dev environment you can use direnv or a docker-compose.override.xml file

* DEBUG: False by default but set on docker-compose.xml
* ALLOWED_HOSTS: Void by default. A list of hosts (example "localhost,web")
* SECRET_KEY: *required* Set anyone if you can see app work
* DATABASE_URL: set to psql://postgres:postgres@db/postgres on docker-compose.xml