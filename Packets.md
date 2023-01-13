This is a table with all the packets for in the game.
Both should always be available on the [client](https://github.com/TownGame/Town.UI.ReactNative), as well as the [server](https://github.com/TownGame/Town.Server).
Not all packets should be sent from either of them, though.
The table also contains a field to indicate the direction of a packet: either to the client or to the server.

| ID | Direction | Descrption | Payload |
| - | - | - | - |
| 1 | Client | A townie joins a lobby. | int: The current player count |
| 2 | Client | A townie joined a lobby. | |
