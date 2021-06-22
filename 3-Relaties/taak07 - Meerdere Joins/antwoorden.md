# Antwoorden

1. Copy paste je gemaakte SQL query hieronder
   SELECT game.name, platform.platform, genre.genre FROM game LEFT JOIN platform ON platform.id = game.platform_id LEFT JOIN genre ON genre.id = game.genre_id WHERE game.name LIKE "b%"; 
   
2. Copy paste je gemaakte SQL query hieronder
    SELECT game.name, platform.platform, publisher.publisher, game.year FROM game LEFT JOIN platform ON platform.id = game.platform_id LEFT JOIN publisher ON publisher.id = game.publisher_id WHERE year = 2013; 

3. Copy paste je gemaakte SQL query hieronder
    SELECT game.name, genre.genre, game.year,game.global_sales FROM game LEFT JOIN genre ON genre.id = game.genre_id WHERE genre = "Puzzle" AND year > 2000; 

4. Copy paste je gemaakte SQL query hieronder
    SELECT game.name,platform.platform,game.year, genre.genre,publisher.publisher, game.jp_sales FROM game LEFT JOIN platform ON platform.id = game.platform_id LEFT JOIN genre ON genre.id = game.genre_id LEFT JOIN publisher ON publisher.id = game.publisher_id WHERE game.name LIKE "Mario%"; 

5. Copy paste je gemaakte SQL query hieronder
   SELECT game.name,genre.genre,publisher.publisher,game.year FROM game LEFT JOIN genre ON genre.id = game.genre_id LEFT JOIN publisher ON publisher.id = game.publisher_id LEFT JOIN platform ON platform.id = game.platform_id WHERE platform = "PC"; 
