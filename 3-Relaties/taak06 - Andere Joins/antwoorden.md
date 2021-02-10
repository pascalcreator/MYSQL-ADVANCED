# Antwoorden

1. Copy paste je gemaakte SQL query hieronder
   SELECT name, platform FROM game LEFT JOIN platform ON platform.id = game.platform_id WHERE name LIKE 'Grand Theft Auto%'
2. Copy paste je gemaakte SQL query hieronder
   SELECT name, platform FROM platform RIGHT JOIN game ON platform_id = game.platform_id WHERE platform='SCD'
