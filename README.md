# manga_site_fastapi

Восстановить бд

docker exec -it postgresdb bash
psql -U postgres -h db -p 5432 -d postgres -f /database_backups/release.sql
Пароль postgres