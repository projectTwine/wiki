#Serverless & MapReduce Prime
Adaptation of Mapreduce model by using FaaS
Use the Serverless framework since you can eject into Project Flourish (SAM) templates but helps us get off the ground on bleeding-edge.
May have to review this when Lambda becomes the mainstream way to compute



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

