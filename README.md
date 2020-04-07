# Adonis API application

This is the boilerplate for creating an API server in AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Authentication
3. CORS
4. Lucid ORM
5. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick --api-only
```

or manually clone the repo and then run `npm install`.


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```

# MySQL [DOCKER]
Creation: 
    docker run -e MYSQL_ROOT_PASSWORD=1234 -d -p 3306:3306 mysql:5.7.13
    
Connection command: 
    docker exec -it container-name mysql -u root -p

