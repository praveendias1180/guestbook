# Symfony - Fast Track

![](public/github/symfony-fast-track.png)

https://symfony.com/doc/6.2/the-fast-track/en/index.html

# Hello, Praveen

![](public/github/symfony-cli-installed.png)
![](public/github/ready-to-start-book.png)
![](public/github/hello-praveen.png)
![](public/github/symfony-book-checkout.png)

# Postgres

```bash
docker run -p 5432:5432 -e POSTGRES_PASSWORD=secret -e POSTGRES_USER=app --name db -d postgres:15-alpine
```

```bash
psql -h localhost -U app
```

![](public/github/phpstorm-db.png)

# EasyAdmin 4

![](public/github/easy-admin.png)

# UI

![](public/github/guestbook.png)

# Update existing table with NOT NULL

```
public function up(Schema $schema): void
{
    $this->addSql('ALTER TABLE conference ADD slug VARCHAR(255)');
    $this->addSql("UPDATE conference SET slug=CONCAT(LOWER(city), '-', year)");
    $this->addSql('ALTER TABLE conference ALTER COLUMN slug SET NOT NULL ');
}
```

# Api Platform

https://api-platform.com/

![](public/github/api.png)

![](public/github/api-platform.png)

![](public/github/api-platform-2.png)

