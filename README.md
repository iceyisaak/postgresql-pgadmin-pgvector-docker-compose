# PosgreSQL pgAdmin pgVector Docker Compose
##### Repo Link: https://github.com/iceyisaak/postgresql-pgadmin-pgvector-docker-compose

This compose file creates for a single project:
- PostgreSQL
- pgAdmin
- pgVector

---

### 🚀 Docker Compose Cheat Sheet

| Command | Best Used For... | Data Status | Pro-Tip / Impact |
| :--- | :--- | :--- | :--- |
| **`docker-compose up -d`** | **Starting/Updating.** Build the setup or apply `.yaml` changes. | **Preserved** | Use `-d` (detached) to keep the DB running after closing the terminal. |
| **`docker-compose stop`** | **Taking a break.** Shuts down processes to save RAM/CPU. | **Safe** | Fast way to free up system resources without removing containers. |
| **`docker-compose start`** | **Resuming.** Quickly wake up stopped containers. | **Safe** | Much faster than `up` because it doesn't check for config changes. |
| **`docker-compose down`** | **Cleaning up.** Removes containers and internal networks. | **Safe** | Use this when you're done with the project but want to keep the data. |
| **`docker-compose down -v`** | **Hard Reset.** Deletes containers AND volumes. | 🔥 **DELETED** | **Danger:** This wipes your entire database and pgAdmin configurations. |
