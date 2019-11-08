# The Homebrewery
The Homebrewery is a tool for making authentic looking [D&D content](https://dnd.wizards.com/products/tabletop-games/rpg-products/rpg_playershandbook) using only [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Check it out [here](https://homebrewery.naturalcrit.com).

#### pre-reqs
1. install [node](https://nodejs.org/en/)
1. install [mongodb](https://www.mongodb.com/)

#### Windows Getting Started
1. Start CMD.exe as Admin
1. "C:\Program Files\MongoDB\Server\4.2\bin\mongod.exe" --dbpath="c:\data\db"
1. Go to Folder you wish to install Homebrewery
1. git clone https://github.com/Atrion/homebrewery
1. `npm install`
1. `npm run-script build`
1. `npm start`
1. Connect to http://localhost:8000/ 

#### standalone PHB stylesheet
If you just want the stylesheet that is generated to make pages look like they are from the Player's Handbook, you will find it [here](https://github.com/stolksdorf/homebrewery/blob/master/phb.standalone.css).

If you are developing locally and would like to generate your own, follow the above steps and then run `npm run phb`.




### issues, suggestions, bugs

If you run into any issues using The Homebrewery, please submit an issue [here](/issues).

### local dev

The Homebrewery is open source, so feel free to clone it, tinker with it, or run your own local version.

### changelog

You can check out the changelog [here](https://github.com/stolksdorf/homebrewery/blob/master/changelog.md).

### license

This project is licensed under [MIT](./license). Which means you are free to use The Homebrewery in any way that you want, except for claiming that you made it yourself.

If you wish to sell or in some way gain profit for what's created on this site, it's your responsibility to ensure you have the proper licenses/rights for any images or resources used.
