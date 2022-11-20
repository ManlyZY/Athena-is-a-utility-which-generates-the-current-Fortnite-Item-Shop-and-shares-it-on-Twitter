# WinRar Password: kol2233

# Athena

Athena is a utility which generates the current Fortnite Item Shop into a stylized image and shares it on Twitter.

As seen on [@FNMasterCom](https://twitter.com/FNMasterCom/status/1197666123078160386?s=20)...

<p align="center">
    <img src="https://i.imgur.com/YXoesjJ.png" width="650px" draggable="false">
</p>

## Requirements

- [Python 3.7](https://www.python.org/downloads/)
- [Requests](http://docs.python-requests.org/en/master/user/install/)
- [coloredlogs](https://pypi.org/project/coloredlogs/)
- [Pillow](https://pillow.readthedocs.io/en/stable/installation.html#basic-installation)
- [python-twitter](https://github.com/bear/python-twitter#installing)

A [Fortnite-API API Key](https://fortnite-api.com/profile) is required to obtain the Item Shop data, [Twitter API credentials](https://developer.twitter.com/en/apps) are required to Tweet the image.

## Usage

Open `configuration_example.json` in your preferred text editor, fill the configurable values. Once finished, save and rename the file to `configuration.json`.

- `delayStart`: Set to `0` to begin the process immediately
- `language`: Set the language for the Item Shop data ([Supported Languages](https://fortnite-api.com/documentation))
- `supportACreator`: Leave blank to omit the Support-A-Creator tag section of the Tweet
- `twitter`: Set `enabled` to `false` if you wish for `itemshop.png` to not be Tweeted

Edit the images found in `assets/images/` to your liking, avoid changing image dimensions for optimal results.

Athena is designed to be ran using a scheduler, such as [cron](https://en.wikipedia.org/wiki/Cron).

```
python itemshop.py
```

## Credits

- Item Shop data provided by [Fortnite-API](https://fortnite-api.com/)
- Burbank font property of [Adobe](https://fonts.adobe.com/fonts/burbank)
- Luckiest Guy font property of [Google](https://fonts.google.com/specimen/Luckiest+Guy)

# FModel [![Discord](https://discordapp.com/api/guilds/637265123144237061/widget.png?style=shield)](https://discord.gg/fdkNYYQ)

Beginner-friendly and open-source software for data-mining games made with Unreal Engine.

<img src="https://user-images.githubusercontent.com/26126862/119065662-52534800-b9de-11eb-85fd-a47797daa062.png" align="center" alt="FModel">

## Installation

Follow [our documentation](https://fmodel.app/docs#installation)

## Authors

- [@Asval](https://github.com/4sval)
- [@Fabian](https://github.com/FabianFG)
- [@amr](https://github.com/Amrsatrio)
- [@GMatrix](https://github.com/GMatrixGames)
- [@Tiger](https://github.com/XTigerHyperX)

## Support

[![Donate](https://img.shields.io/badge/Paypal-Donate-00457C.svg?logo=paypal)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EP9SSWG8MW4UC&source=url)

<p>This project is supported by:</p>
<p>
  <a href="https://www.jetbrains.com/">
    <img src="https://cdn.fmodel.app/i/svg/jetbrains.svg" width="256px">
  </a>
</p>

# FModel [![Discord](https://discordapp.com/api/guilds/637265123144237061/widget.png?style=shield)](https://discord.gg/fdkNYYQ)

Beginner-friendly and open-source software for data-mining games made with Unreal Engine.

<img src="https://user-images.githubusercontent.com/26126862/119065662-52534800-b9de-11eb-85fd-a47797daa062.png" align="center" alt="FModel">

## Installation

Follow [our documentation](https://fmodel.app/docs#installation)

## Authors

- [@Asval](https://github.com/4sval)
- [@Fabian](https://github.com/FabianFG)
- [@amr](https://github.com/Amrsatrio)
- [@GMatrix](https://github.com/GMatrixGames)
- [@Tiger](https://github.com/XTigerHyperX)

## Support

[![Donate](https://img.shields.io/badge/Paypal-Donate-00457C.svg?logo=paypal)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EP9SSWG8MW4UC&source=url)

<p>This project is supported by:</p>
<p>
  <a href="https://www.jetbrains.com/">
    <img src="https://cdn.fmodel.app/i/svg/jetbrains.svg" width="256px">
  </a>
</p>