# React Project

## Prerequisites

- NodeJS ^8.9
- npm ^5.6

## Steps to Run inside CodeMix


1. From the `Quick Open`  Command Palette (ctrl/cmd + shift + p) search for:
     `Terminal: Create New Integrated Terminal`
2. From the `Quick Open` options select this project.
3. Once you are inside the Terminal, execute: `npm install`
4. Finally to run this example run `npm run start`
5. Open your browser on http://localhost:3000

To publish:
Set up a remote repo on github.
When setting up local git repository:
use:
git remote add origin https://{username}:{password}@github.com/{username}/project.git

or if running into "fatal: could not read Username for 'https://github.com': Invalid argument" error, use
git remote set-url origin https://{username}:{password}@github.com/...

if getting error:
fatal: A branch named 'gh-pages' already exists.
use 
 rm -rf node_modules/gh-pages/.cache

 Otherwise, use instructions on https://www.taniarascia.com/getting-started-with-react/
