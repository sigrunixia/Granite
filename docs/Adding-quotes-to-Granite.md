
# Adding quotes to Granite Plugin

Currently, all quotes are handled in [Quotes,ts](src/quotes/Quotes.ts). 
This file is a JSON array of objects, with each section controlling a certain character.

Quotes are grouped under `Base Quotes`, and individual `Character Quotes`.
They are then grouped further by `General`, `Idle`, and `Writing Mode` quotes.

## Adding quotes to an existing character

1. Open up [Quotes.ts](src/quotes/Quotes.ts) and find the character you want to edit.
2. Determine if you are editing a general quote, idle quote, or writing mode quote.
3. In the section that you want to add your line to, use the following formatting to add your line:

```json
   	`You are a background character in your own life.`,
```




## Adding a new character
