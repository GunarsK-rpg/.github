# Cosmere RPG Character Sheet Manager

A character sheet management application for the **Cosmere RPG (Stormlight Campaign Setting)**. Built with Go, Vue 3, and PostgreSQL following a stored-function architecture where all business logic lives in the database.

[rpg.gunarsk.com](https://rpg.gunarsk.com/)

---

## Repositories

| Repository | Stack | Purpose |
|------------|-------|---------|
| [public-web](https://github.com/GunarsK-rpg/public-web) | Vue 3/Quasar | Character sheet PWA |
| [public-api](https://github.com/GunarsK-rpg/public-api) | Go/Gin | REST API |
| [database](https://github.com/GunarsK-rpg/database) | PostgreSQL/Flyway | Schema, migrations, stored functions |
| [database-seeds](https://github.com/GunarsK-rpg/database-seeds) | SQL | Classifier and NPC seed data |
| [infrastructure](https://github.com/GunarsK-rpg/infrastructure) | Docker Compose/Traefik | Local development environment |
| [fabrials](https://github.com/GunarsK-rpg/fabrials) | Markdown | Game world reference documents |
