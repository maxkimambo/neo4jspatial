Combines Neo4J v 3.3.1 and Geospatial plugin.

To run

```
docker run \
   --publish=7474:7474 --publish=7687:7687 \
    --volume=$HOME/neo4j/data:/data \
    maxkimambo/neo4jspatial
```

or short version

-v mounts current directory to data

```
docker run -p 7474:7474 -p 7687:7687 -v $(pwd):/data maxkimambo/neo4jspatial
```
