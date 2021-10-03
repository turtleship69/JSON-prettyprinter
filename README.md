# JSON-prettyprinter
Simple script to pretty print a local json file or json file from the internet.  
Useful for when you need to deal with json data (especially when it's in large chunks) but it's not served to you formatted.  

Simply use as follows:  
python -m JsonPPrinter {type} {path}  
For example:  
python -m JsonPPrinter URL https://static.nvidiagrid.net/supported-public-game-list/locales/gfnpc-en-GB.json
