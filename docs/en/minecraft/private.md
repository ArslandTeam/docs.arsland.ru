# Privates
::: info
Below is the available functionality for players from the [Open Parties and Claims]((https://modrinth.com/mod/open-parties-and-claims)) mod.
:::

## Commands
::: info
The symbol **~** denotes the coordinate to which you want to apply the command.
:::

Command to privatize a chunk:
```
/openpac-claims claim ~ ~
```

Command to remove privatization from a chunk:
```
/openpac-claims unclaim ~ ~
```

::: info
The **party** system is set up so that you can only join one of them.
:::

The team creating the party.
```
/openpac-parties create
```

Command to view information about a player's party:
```
/openpac-parties about
```

A command that adds a player to your party:
```
/openpac-parties member invite <UserName>
```

A command that adds a player to your party and gives him a rank in it:
```
/openpac-parties member rank <ADMIN | MODERATOR | MEMBER>
```

Transferring the owner of a private to another participant of the private:
```
/openpac-parties transfer <UserName> confirm
```

Command to leave someone else's party:
```
/openpac-parties leave
```

Team that deletes a party:
```
/openpac-parties destroy confirm
```