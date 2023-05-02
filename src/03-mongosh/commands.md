## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://user:user123@localhost:27017/?authMechanism=DEFAULT&tls=false"
```
### Examples

```sh
show dbs
show collections
```


```sh
use("platsi_store")
db.products.find()
```
