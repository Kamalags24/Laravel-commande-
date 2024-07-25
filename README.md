Voici une liste des commandes courantes en Laravel et leur rôle :

### Commandes Artisan
**artisan** est l'interface de ligne de commande incluse avec Laravel. Chaque commande ci-dessous est appelée en utilisant `php artisan <commande>`.

1. **make:model <ModelName>** : Crée un nouveau modèle Eloquent.
   ```bash
   php artisan make:model Post
   ```

2. **make:controller <ControllerName>** : Crée un nouveau contrôleur.
   ```bash
   php artisan make:controller PostController
   ```

3. **make:migration <MigrationName>** : Crée un nouveau fichier de migration.
   ```bash
   php artisan make:migration create_posts_table
   ```

4. **migrate** : Exécute les migrations en attente.
   ```bash
   php artisan migrate
   ```

5. **migrate:rollback** : Annule la dernière série de migrations exécutées.
   ```bash
   php artisan migrate:rollback
   ```

6. **make:seeder <SeederName>** : Crée une nouvelle classe de seeder.
   ```bash
   php artisan make:seeder PostsTableSeeder
   ```

7. **db:seed** : Exécute les seeders de la base de données.
   ```bash
   php artisan db:seed
   ```

8. **make:middleware <MiddlewareName>** : Crée un nouveau middleware.
   ```bash
   php artisan make:middleware CheckAge
   ```

9. **route:list** : Affiche une liste de toutes les routes enregistrées.
   ```bash
   php artisan route:list
   ```

10. **config:cache** : Crée un cache des fichiers de configuration pour améliorer les performances.
    ```bash
    php artisan config:cache
    ```

11. **cache:clear** : Vide le cache de l'application.
    ```bash
    php artisan cache:clear
    ```

12. **make:request <RequestName>** : Crée une nouvelle classe de formulaire de requête.
    ```bash
    php artisan make:request StorePostRequest
    ```

13. **make:job <JobName>** : Crée une nouvelle classe de job.
    ```bash
    php artisan make:job SendEmails
    ```

14. **queue:work** : Lance un job de la file d'attente.
    ```bash
    php artisan queue:work
    ```

15. **serve** : Lance le serveur de développement PHP intégré.
    ```bash
    php artisan serve
    ```

16. **tinker** : Ouvre un REPL (Read-Eval-Print Loop) pour interagir avec l'application.
    ```bash
    php artisan tinker
    ```

### Commandes de Maintenance
1. **down** : Met l'application en mode maintenance.
   ```bash
   php artisan down
   ```

2. **up** : Ramène l'application en mode en ligne.
   ```bash
   php artisan up
   ```

Ces commandes sont essentielles pour le développement et la gestion des applications Laravel. Pour voir toutes les commandes disponibles, vous pouvez utiliser :
```bash
php artisan list
```# Laravel-commande-
