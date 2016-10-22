GA4GH Repo Admin
================

Example usage, interacting with a server container:

```
docker run --user 1002 -e GA4GH_DATA_SOURCE=/data/registry.db -v /mnt/data/ga4gh-data/:/data:rw -it --name ga4gh_repo --link ga4gh_server:server --rm tacc/ga4gh-repo:latest
```

