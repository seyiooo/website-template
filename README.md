<div align="center"><h1>Website Template</h1></div>
A simple template for slash commands bot. Build in Discord.JS@13.7.0 !

# Summary
- [Requirements](#requirements)
- [Installation](#installation)
- [Setup](#setup)
- [Credits](#credits)

# Requirements
- [Node](https://nodejs.org/en/) - 16.15.0
- [NPM](https://www.npmjs.com/) - 8.5.5

# Installation
```
# Clone the repository
git clone https://github.com/seyiooo/disbot.git

# Enter into the directory
cd disbot

# Install the dependencies
npm install
```

# Setup
Open the `config.json` file and modify the token / IDs.
```json
{
  "token": "token",
  "version": "1.0.0",
  "guild": "guild id (if you run without process arguments)",
  "devs": ["your id"],
  "logs": "logs channel id",
  "color": "#color"
}
```
There are different ways to run.
```
# Run as default mode
node .

# Run as eval mode
node . eval

# Run as load mode
node . load
```

# Credits
- [sey.](https://github.com/seyiooo)
- [Sedorikku](https://github.com/Sedorikku1949) for the file structure and eval mode
