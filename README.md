# Generate vocabulary list
This is for generating vocabulary list.

## Usage

```
$ python3 python3 main.py 
```

### FYI

```
# Set symbolic link of Bookmark for Mac User
$ cp /Users/$USER/Library/Application\ Support/Google/Chrome/Default/Bookmarks backend/data/Bookmarks
```
## Environment
Based on https://qiita.com/jhorikawa_err/items/fb9c03c0982c29c5b6d5

### Docker Command
```
# build
$ docker-compose up -d --build

# down
$ docker-compose down
```

### Into to container
```
# python3 server
$ docker-compose exec python3 bash
```

### test
```
# Hello world
$ docker compose exec python3 python src/sample.py
```

### Ruine the world
```
$  docker-compose down --rmi all --volumes --remove-orphans 
```