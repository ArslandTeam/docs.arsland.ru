# GriefLogger
::: info
Below is the functionality available to players from the [GriefLogger](https://modrinth.com/mod/grieflogger) mod
:::

## Commands

Enables or disables the inspection mode:
```
/grieflogger inspect
```
![Example inspect](https://imgur.com/Z1nXsAq.gif)


Shows all data available based on filters:
```
/grieflogger lookup <filters>
```
![Example lookup](https://imgur.com/gK7Hj9l.gif)

Shows a certain page number. Can also be achieved by clicking on the arrows in the chat message.
```
/grieflogger page <page number>
```

## Filters

| Filter  | Example                         | Explanation                                                       |
| ------- | ------------------------------- | ----------------------------------------------------------------- |
| action  | action:place_block,break_block  | Only shows places and broken blocks.                              |
| exclude | exclude:sand                    | Exludes the sand block from the search results.                   |
| include | include:sand,dirt               | Only shows dirt and sand interactions.                            |
| radius  | radius:100                      | Shows all interactions in a radius of 100 blocks from the player. |
| time    | time:1d                         | Shows all interactions in the last day.                           |
| user    | user:Player1                    | Shows all interactions made by Player1.                           |