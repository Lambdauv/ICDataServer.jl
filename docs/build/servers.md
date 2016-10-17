
<a id='Servers-1'></a>

## Servers

<a id='ICDataServer.newserver' href='#ICDataServer.newserver'>#</a>
**`ICDataServer.newserver`** &mdash; *Function*.



```
newserver(dsn, name, addr, port::Integer=-1)
```

Create a new server in the `servers` table.


<a target='_blank' href='https://github.com/PainterQubits/ICDataServer.jl/tree/9a39f602079c0f0ff1289692f15e7d5ecbb4976d/src/servers.jl#L1-L7' class='documenter-source'>source</a><br>

<a id='ICDataServer.updateserver' href='#ICDataServer.updateserver'>#</a>
**`ICDataServer.updateserver`** &mdash; *Function*.



```
updateserver(dsn, name; kwargs...)
```

Update a server in the `servers` table using keyword arguments (`name`, `addr`, `port`).


<a target='_blank' href='https://github.com/PainterQubits/ICDataServer.jl/tree/9a39f602079c0f0ff1289692f15e7d5ecbb4976d/src/servers.jl#L20-L27' class='documenter-source'>source</a><br>

<a id='ICDataServer.deleteserver' href='#ICDataServer.deleteserver'>#</a>
**`ICDataServer.deleteserver`** &mdash; *Function*.



```
deleteserver(dsn, name)
```

Remove a server from the `servers` table by passing its `name`.


<a target='_blank' href='https://github.com/PainterQubits/ICDataServer.jl/tree/9a39f602079c0f0ff1289692f15e7d5ecbb4976d/src/servers.jl#L36-L42' class='documenter-source'>source</a><br>

<a id='ICDataServer.listservers' href='#ICDataServer.listservers'>#</a>
**`ICDataServer.listservers`** &mdash; *Function*.



```
listservers(dsn, name)
```

List all servers in the `servers` table.


<a target='_blank' href='https://github.com/PainterQubits/ICDataServer.jl/tree/9a39f602079c0f0ff1289692f15e7d5ecbb4976d/src/servers.jl#L47-L53' class='documenter-source'>source</a><br>

