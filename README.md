# PostgresSql Replication for Docker

Jalankan docker dengan 1 master write dan 2 slave read

```sh
docker compose up -d
```

## Ports

Akses master and slave dengan port berikut

```
master (write)    : localhost:54320
replica_1 (read)  : localhost:54321
replica_2 (read)  : localhost:54322
```
