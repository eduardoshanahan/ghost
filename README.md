# Ghost

A Docker image with [Ghost](https://ghost.org).

## Building

```bash
docker build -t eduardoshanahan/ghost .
```

## Running a test

```bash
docker run --rm -p 2068:2068 eduardoshanahan/ghost:latest
```

Or you can use Docker Compose:

```bash
docker-compose up
```

Then you can curl to:

```bash
curl localhost:2068
```

## Development

If you want to make some changes and version it, [bumpversion](https://pypi.python.org/pypi/bumpversion) is available

```bash
bumpversion patch
```
