# Microsoft keyboard layout

This repo contains the source and binaries for a customer UK keyboard layout or Microsoft windows (8,10,11)

The layout is mostly similar to the UK Extended layout other than the fact that the '`' key acts as both a non dead key and a dead key.

#### Huh

By defaut in the `UK Extended Layout` when wanting to type  a single backtick (``` ` ```) you need press 2 keys, the ``` ` ``` key and the `<space>` key.

I found this anonnoying as I use the single back tick much more regularly than accented chanarters (for coding, markdown etc.), but still need the accented characters.

This layout makes the backtick key act as both a regular key **and** as a dead key so you can type ``` ` ``` with a single key press, yet still get accented characters like `àèÀÈ ` via the dead key.


### Installation

* Download the zip file from [Releases](https://github.com/jtnord/uk-extended-keyboard-layout/releases/)
* Unpack the zip and run as an administrator `setup.exe`
* The keyboard should be auto registered (at least on windows 11, older versions you may have to restart and select the `United Kingdom Extended - dead keys` layout)
* Restart windows
  

### Building 

If you do not trust random unsigned binaries from the internet you can build this yourself from the source.

To do so you will need the [Microsoft Keyboard Layout Creator (MSKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134)
  
