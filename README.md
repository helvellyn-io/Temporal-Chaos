# chaos
Temporal Chaos Experiments 



```
BRANCH DETAILS: 

Master -

This project randomly deletes pods of a specified deployment. 
It uses the Temporal platform to run a singletask to delete a pod. 

Cron -

This project randomly deletes pods of a specified deployment. 
It uses the Temporal platform to run the task.
The schedule is determined via the CRON specifications.

```
```
RUNNING: 
go run ./worker/main.go
go run ./start/main.go

```
```
TODO:
write tests.
redis integration to log chaos experiments.

```
