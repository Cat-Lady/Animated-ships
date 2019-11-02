#### This plugin is a part of upcoming "Endless Sky: Captain's Edition" reboot of the base game. Stay tuned - meanwhile, installing the plugins can help to preview the experience, together or in parts.

# Undisruptive Animated Ships

This is version with less disruptive, slower animations. Non-living ships made looking less organic/making breath-like motions. Living ships made look even more organic/making breath-like motions ;)

![Star Barge Image](/../images/star%20barge.gif?raw=true "Star Barge Image")



## Features
- Every ship has been separately and carefully tweaked for best looking effect in-game.

- Unlike upstream, new ship sprites from Endless Sky 0.9.10+ are no longer replaced by animated version of old ones.

- All ships have a matching high-DPI version, generated from the source material via on-GPU upscale through neural network, trained specifically on "Endless Sky" ship sprites.

- Most animations were tweaked by hand, to get rid of minor glitches (like objects clipping through objects).

![Cruiser Image](/../images/cruiser.gif?raw=true "Cruiser Image")


## Installing

Check:
https://github.com/Cat-Lady/undisruptive-animated-ships/releases

...for latest, pre-packaged version.


**1.** Unpack ``undisruptive-animated-ships`` to your ES plugins folder. Be sure that you have single ``undisruptive-animated-ships`` directory inside your plugins folder, containing ``data`` and ``images`` directories. Directory structure should look like:

```(...)/plugins/undisruptive-animated-ships/(.../data/, /images/ and other stuff)```


It **won't** work if the directory structure will be anything like:

```(...)/plugins/undisruptive-animated-ships/undisruptive-animated-ships/(...)```


#### Warning:
This plugin doesn't work with ships purchased before the plugin installation, unless save game is edited (one-time fix) so that ships declared in save file are modified to have "sprite" section matching one in the plugin (see plugin's ```/data/ships.txt``` for syntax).

![Freighter Image](/../images/freighter.gif?raw=true "Freighter Image")


## Author

* **Cat Lady**

*Initial work* - [BeccaBunny](https://github.com/beccabunny/Animated-ships)


## License

This project is licensed under the GPL3 License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

"Endless Sky" Development Team and Michael Zahniser; For maintaining and creating the game

BeccaBunny; For making awesome base of this plugin in form of rendered animation frames.

![Deep River Image](/../images/deep%20river.gif?raw=true "Deep River Image")

