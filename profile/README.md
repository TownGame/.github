# Town

This is the organisation for a gamed called *Town*.
It's a social deduction game similar to Mafia or Werewolves.
15 townies start in a town with a group of evil people known as the mafia.
Nobody knows who is part of the mafia, except for the mafia themselves.
The town must try to eliminate all the mafia before the mafia kills all of them and gains majority.
Every single night the townies can get closer to the truth by gaining information using their abilities.
They can then discuss their results with everyone else the next day and lynch someone if necessary.


# Contributing

The repository for the server (C#, ASP.NET) can be found [here](https://github.com/TownGame/Town.Server) and the repository for the client (TypeScript, React Native) can be found [here](https://github.com/TownGame/Town.UI.ReactNative).
These two are separated so their contents can be shipped individually.
When contributing to either one of them you have to create a pull request in the desired repository.
Said pull request may then be reviewed by other contributors and the members of this organisation.

A list of all packets for communication between the server and the client can be found [here](https://github.com/TownGame/.github/blob/master/Packets.md).
This list **must** be updated whenever a new packet gets added or modified.
Please create a second pull request [here](https://github.com/TownGame/.github/pulls) with these changes and refer to it in your original pull request, so it can be reviewed at the same time.
