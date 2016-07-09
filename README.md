This is boilerplate for [docker-sync](https://github.com/EugenMayer/docker_sync)
Either start from here to implement fast volume-shares for you project or simply test
its performance

Start with

```
gem install docker-sync
git clone https://github.com/EugenMayer/docker-sync-boilerplate
cd docker-sync-boilerplate
```

Now start the sync, first choose either unison or rsync ( you can actually mix both in a single docker-sync.yml


```
cd rsync
docker-sync start
```

In a new shell, enter into docker-sync-boilerplate/rsync and start our app-server

```
docker-compose up
```