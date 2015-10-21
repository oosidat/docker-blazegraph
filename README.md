Docker Blazegraph
=================

Run Blazegraph 1.5.3 in Docker.

**Quickstart**

```bash
$ docker run --name blazegraph -d -p 8889:8080 vandot/blazegraph:1.5.3
$ docker logs -f blazegraph
```

**Local builds**

```
$ docker build -t blazegraph:1.5.3 1.5.3/
$ docker run --name blazegraph -d -p 8889:8080 blazegraph:1.5.3
$ docker logs -f blazegraph
```

---
