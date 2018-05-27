# platziverse-mqtt

## `agent/connected`


``` js
{
agent: {

    uuid,
    username,
    name,
    hostname,
    pid
}

}

## `agent disconectedd`

``` js
{
    agent: {
        uuid
    }
}
```

## `agent-message`


``` js
{
    agent,
    metrics:[
        {
            type,
            value
        }
    ],
    timestamp
}
```
    