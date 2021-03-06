# GO-Bot
Automation platform (auto farmer, bot, etc.) for the popular game Pokemon GO. This project is in it's infancy stages and continuing to evolve as time goes on.

Discord chat: https://discord.gg/EHMyv

## Features
- Loot Pokestops for XP and items
- Catch Pokemon
- Human like walking algorithm
- Transfers duplicate Pokemon
- Contributes to the distance required to hatch eggs
- Customizable latitude/longitude as default location
- Configuration screen for things such as sending duplicate Pokemon, evolving, minimum CP/IV, etc.
- More to come!

## Requirements
Windows operating system with .NET 4.5 or higher installed. Mac users will have to use a Windows virtual machine (recommend Virtualbox).

## Usage
For those who want the standalone application and not the source you can download the latest release from the releases tab at the top. Direct link: https://github.com/AnthonyOSX/GO-Bot/releases

![alt tag](https://i.gyazo.com/1313a2121266352b1510ea7c038b6221.png)

![alt tag](https://i.gyazo.com/bbe43e2574f85b18a21ede0c1177e987.png)

![alt tag](https://i.gyazo.com/108520afef24eded5906a2e4b9df59d1.png)

## FAQ
**1. The bot keeps trying to log in?**
You may have invalid credentials or the login servers could be down. Verify your login details are correct and/or try again later.

**2. I can't read the log fast enough, can you slow it down?**
All log messages are saved to a text file on your computer at "C:\Users\{Your username}\GO Bot\Logs\Output\output.txt".

**3. Pokemon keep getting away and Pokestops give no XP and items?**
Pokestops are more than likely a problem with the response the bot received. You did in fact get xp/items but the bot just didn't recognize it. With Pokemon, you may just be getting unlucky.

**4. The bot keeps crashing on startup?**
This is something I can't solve within the bot. Please follow the instructions within the answer here: http://stackoverflow.com/questions/17980178/cannot-load-counter-name-data-because-an-invalid-index-exception

## Donations
[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3WXQX4UE94MWY)

## Credits
Huge thanks to FeroxRev as without his work on PokemonGO.RocketAPI this would not be possible.
