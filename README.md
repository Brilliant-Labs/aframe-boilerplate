# Guide

## HTML Primer

![image of html syntax](https://serveon.site/lingo.jpg)

## Local Development

this workflow depends on npm and node :)

signing up at [github.com](https://github.com) is a good idea too!

To serve the site from a simple Node development server:

    npm start

(this runs the script in package.json called start)

Then launch the site from your favourite browser:

[__http://localhost:3000/__](http://localhost:3000/)

If you wish to serve the site from a different port:

    PORT=8000 npm start

## Deployment via now.sh

make an account at [now.sh](https://now.sh), preferably through github :)

install the [now](https://zeit.co/download) client

run the `now` command in the root folder of the project repository to host its contents!

this readme file is in the root of the project repository :)

## Alternative deployment strategies

hosting the static files in this directory on any static server will also work, but be careful when choosing which files to upload. files listed in .gitignore should not be hosted

## License

This program is free software and is distributed under an [MIT License](LICENSE).
