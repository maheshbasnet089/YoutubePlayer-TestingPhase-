First , Install Node_modules =>Create .eslint.rc.json if u Use it (option)

To run, you must have gulp-cli version 4 installed globally. Do this by running:
> npm install -g gulp-cli 

You must also install all required NPM packages by running the following in this directory:
> npm install

To be able to add videos, you also need a YouTube Data API key, which you can get at:
https://console.developers.google.com/

Then, replace the string "{fixme}" in src/server/server.js with the key.

To run a development server, simply run
> gulp dev

To create a production build, run
> gulp prod

Thanks !
