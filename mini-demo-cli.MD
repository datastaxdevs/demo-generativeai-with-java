### Demo Charter 10

### 1. Multi Environment Support

- List DB  in prod

```
astra db list
```

- List configurations

```console
astra config list
```

- Create a new config

```
astra config create demodev \
    --env dev \
    --token AAA
```

- Execute a particular command enforcing a config

``console
astra db list --config dev
```

- Select a configuration

```console
astra db config use dev
```

- Create a new DB

```console
astra db create test
```

- Region lists

```console
astra db list-regions-vector
```

- Create a new DB

```console
```


# Support for dev

