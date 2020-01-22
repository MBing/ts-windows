# Test TypeScript on Windows 10 (with Debian)

## Setup
- install nvm `apt-get install nvm`
- install node v13 `nvm install 13`
- install typescript `npm install -g typescript`
- install nodemon `npm install -g nodemon` ( It did not work to install it as a package in a project)

## Scripts
```bash
npm start:build     # transpile/build the typescript into javascript and watch for changes
npm start:run       # serve the javascript code 
npm start           # concurrently starts to watch the tsc files and serves the build
                    # make sure to have run at least once the npm start:build before running this one
tsc                 # command to transpile with typescript -> `typescript compile`
```

_This project was setup with Windows 10 in IntelliJ IDEA. Using zsh within a Debian environment._
