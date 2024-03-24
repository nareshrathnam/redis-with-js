# Redis-with-JS

### Introduction

- Redis (REmote DIctionary Server) is an open-source, NoSQL, in-memory database that stores data as key-value pairs in **RAM**.
- It's used as an application cache or quick-response database and is known as a "data structure server".
- Redis is an open source (BSD licensed), in-memory data structure store used as a database, cache, message broker, and streaming engine.

### Installation

[Redis for Windows](https://github.com/tporadowski/redis)

[RedisInsight - Workbench for Redis](https://redis.com/redis-enterprise/redis-insight/)

> After installation, set bin folder to environment variable.


#### Redis Basic Commands
```bash
#starting redis cli
redis-cli

#setting key value
set name yonk

#getting key
get name

#setting another key value
set age 23

#getting newly created key
get age

#deleting key age
del age

#getting all keys
keys *

#checking keys exists
exists

#delete all keys
flushall

#clearing the screen
clear

#quitting
quit

```

#### Expiration Commands
```bash
#to check the expire time of the "key"- time to live
ttl name

#expire key in 10 seconds
expire name 10

#now check again
ttl name

#set expiration while creating the key
setex name 10 homie

```
