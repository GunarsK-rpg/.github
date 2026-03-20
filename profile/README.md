# Cosmere RPG Character Sheet Manager

A character sheet management application for the **Cosmere RPG (Stormlight Campaign Setting)**.

Built with **Go**, **Vue 3**, and **PostgreSQL** following a stored-function architecture where all business logic lives in the database.

[![Live App](https://img.shields.io/badge/Live_App-rpg.gunarsk.com-blue?style=for-the-badge)](https://rpg.gunarsk.com/)

---

## Tech Stack

`Go 1.26` `Gin` `Vue 3` `Quasar` `Pinia` `PostgreSQL` `Flyway` `Redis` `Docker` `Traefik` `Terraform` `AWS`

---

## Repositories

### Application

| | Repository | Stack | Description |
|---|------------|-------|-------------|
| :globe_with_meridians: | [**public-web**](https://github.com/GunarsK-rpg/public-web) | Vue 3 / Quasar / Pinia | Character sheet PWA with 85+ colocated test files |
| :gear: | [**public-api**](https://github.com/GunarsK-rpg/public-api) | Go / Gin / pgx | REST API — thin HTTP-to-DB bridge with JWT auth |

### Data

| | Repository | Stack | Description |
|---|------------|-------|-------------|
| :floppy_disk: | [**database**](https://github.com/GunarsK-rpg/database) | PostgreSQL / Flyway | Schema, versioned migrations, stored functions, audit logging |

### Infrastructure & Reference

| | Repository | Stack | Description |
|---|------------|-------|-------------|
| :whale: | [**infrastructure**](https://github.com/GunarsK-rpg/infrastructure) | Docker Compose / Traefik | Local development environment |
