### Run app

```bash
cd docker
docker compose up -d
docker exec -it test-fpm php artisan migrate
```

### Credentials

```
admin@admin.com
admin
```

[Link](http://127.0.0.1/admin/users/1/edit)
