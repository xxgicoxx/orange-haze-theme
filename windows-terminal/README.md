# Orange Haze for Windows Terminal
Dark theme for Windows Terminal.

![Orange Haze](https://i.imgur.com/O4NO9z5.png)

### Running
The theme run locally, just import and use.

### Run
Change profile.json settings file for Windows Terminal, to downloaded profile.json or find the defaultProfile section and change value to:
````json
"defaultProfile": "{9ed62add-2cb9-4be5-a444-72d56b888d7f}"
````

On profiles section add:
````json
{
    "guid": "{9ed62add-2cb9-4be5-a444-72d56b888d7f}",
    "colorScheme": "orange-haze",
    "name": "Orange Haze CMD",
    "useAcrylic": true,
    "acrylicOpacity": 0.7
}
````

On schemes section add:
````json
{
    "name": "orange-haze",
	"icon": "ms-appdata:///roaming/pwsh-32.png",
    "background": "#1a1b24",
    "foreground": "#F39C3F",
    "black": "#000000",
    "blue": "#0088dd",
    "cyan": "#069b7d",
    "green": "#00aa47",
    "purple": "#7813a3",
    "red": "#bf1607",
    "white": "#ffffff",
    "yellow": "#fcf535",
    "brightBlack": "#141313",
    "brightBlue": "#61b4e8",
    "brightCyan": "#0cd3ab",
    "brightGreen": "#40d67e",
    "brightPurple": "#b200ff",
    "brightRed": "#f45c4e",
    "brightWhite": "#ffffff",
    "brightYellow": "#f2ef98"
}
````

### Authors
* **Giovani de Oliveira** - [xxgicoxx](https://github.com/xxgicoxx)