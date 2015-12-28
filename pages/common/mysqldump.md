# mysqldump

> Backups mysql databases

- creating a backup

`mysqldump -u {{user}} --password {{database_name}} > {{filename.sql}}`

- restoring a backup

`mysql -u {{user}} --password {{database_name}} < {{filename.sql}}`
