# Papirus Colorizer

A simple PHP script to switch out filesystem icon colors for the Papirus icon set.

## Requirements
- Papirus icon set installed: https://www.xfce-look.org/p/1166289/
- PHP 5.4 or above.

## Notes
If you use `Papirus-Dark` you should run this tool on both the main `Papirus` and `Papirus-Dark`.

## Usage
```
Arguments:
--dest          Destination of Papirus icons. (Required)
--color         Which color you want to switch to. (Required)
--help          This help message.

Color Options:
blue, black, bluegrey, brown, custom, cyan, deeporange, green, grey, indigo, magenta, nordic, orange, pink, red, teal, violet, white, yaro, yellow

Example Usage:
./papirus-colorizer --dest=~/.icons/Papirus --color=pink
```

## Support
There is none: https://www.youtube.com/watch?v=HiLkMgYQ2qM