Docker Blazegraph
=================

Run Blazegraph 1.5.3 in Docker.

**Quickstart**

```bash
$ docker run --name blazegraph -d -p 8889:8080 oosidat/docker-blazegraph:latest
$ docker logs -f blazegraph
```

**Other versions:**

* oosidat/docker-blazegraph:1.5.1
* oosidat/docker-blazegraph:1.5.3 (same as latest) 

*(might need updating)*

**Local builds**

```
$ docker build -t blazegraph:1.5.3 1.5.3/
$ docker run --name blazegraph -d -p 8889:8080 blazegraph:1.5.3
$ docker logs -f blazegraph
```

---
