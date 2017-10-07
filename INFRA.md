#ECS
##Services
1. Relational DB - Connect via `psql`
2. Graph DB - Connect using the browser `:7474`
Prefer to use alpine-linux images for consistency



##Security Groups
Only one so far for knowledge-graph also uses the postgres one

##
```
psql -h 54.175.83.43 -U postgres;
psql -h 52.72.6.185 -U admin -d twine;
```

