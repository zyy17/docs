# Pre-built Binaries

You can try out GreptimeDB with our test builds.
released on
[Github](https://github.com/GreptimeTeam/greptimedb/releases)
and [Docker hub](https://hub.docker.com/r/greptime/greptimedb). Note that
GreptimeDB is currently under intense development.
So these binaries are not ready to be used under production environment at the moment.

## Local Install

For Linux and MacOS users, you can download latest build of GreptimeDB using:

```shell
curl -L https://raw.githubusercontent.com/GreptimeTeam/greptimedb/develop/scripts/install.sh | sh
```

```shell
./greptime standalone start
```

## Docker

```shell
docker run -p 4000-4004:4000-4004 -p 4242:4242 -v "greptime-vol:/tmp/greptimedb" --name greptime --rm greptime/greptimedb standalone start
```

## Next Steps

Now you have greptimedb up and running locally, check our [Getting
Started](../getting-started/overview.md) guide to create your first table.
