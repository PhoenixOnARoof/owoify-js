# Note:
This is a fork of https://www.npmjs.com/package/owoify-js. I made one simple change to the code for my needs. Feel free to use it if you like the change that I did.

# owoify-js
Turning my worst nightmare into a NPM package. This nifty little library helps you turn any string into nonsensical babyspeak similar to the infamous Chrome extension by LeafySweets (which has been deleted unfortunately). Three levels are available:
- owo (default): pretty vanilla. Not much else to say about it.
- uwu: moderately infuses the text but it gets wose and wose
- uvu: litewawwy unweadabwal

## Demo
[CodePen.io](https://codepen.io/newbeetf2/pen/yLLaNPZ)

## Installation instructions
`npm install --save owoify-js-ant`

## Usage
```js
const owoify = require('owoify-js').default

owoify('oh dear god please help me, save me from this hell that is owo');
// oh dear gwod pwalase help mwe, save mwe fwom this heww that is owo

owoify('oh dear god please help me, save me from this hell that is uwu', 'uwu');
// oh deaw gwod pwease hewp mwe (・`ω´・) sawe mwe fwom fwis heww dat is uwu

owoify('oh dear god please help me, save me from this hell that is uvu', 'uvu');
// owoh deaw gwod pwease hewp mwe ＼(＾▽＾)／ sawe mwe fwowom fwis heww dat is uvu
```
