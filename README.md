This project is built for hype-beast code challenge.

## Requirement

- PHP

## Start

Deploy to web server, or use

`php -S localhost:4080 -t /path/to/folder`

## API Config

To change the API hostname, change `SUBMIT_END_POINT` in ad.html

## Assumption

The project have the following assumptions:

- We have full control on ad.html
- Client have full access on CDN library
- It would be better to have the javascript transpiled. I assume that there is some limitation thus cannot use babel to transpile.

## Limitation

- Only work on modern browsers. Does not work on IE 11
- Test work on FireFox and Chrome 