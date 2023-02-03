# Inventory management system

Hi, everyone
Some time ago I decide to create a trading app inspire by the game Anno 2070. The project never ended so now I have other approach. Here I will create backend for the app that could be used by warehouse in the game. Wish me luck.

## Assumptions / motivation

There are few management levels to focuses on.

```
global 
  |
  |- island
       |
       |- main warehouse (only one on the island)
       |
       |- other warehouses
```

- In the global view you are able to see all rapports from all the warhorses all together and manage transports between main ones. 
- In the island views rapports from that specific island will be visible as well as local and global transactions.
- In the individual warehouse you will will find its transaction history and stock rapport. Here you also will be able to make purchase.

The system all in all might not be similar to the one present in the game, but keep in mind that it is just inspiration and not 1:1 copy ;-)

