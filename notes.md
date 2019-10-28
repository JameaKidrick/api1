# Node API 1 Notes

- created repo on GH
- cloned it
- opened it in editor
- add `.gitignore` ==> `npx gitignore node`
  - npx allows you to run something with out having the it downloaded to local comp
  - purpose of gitignore: ignore adding certain files to the repo to not upload bloat/tells git to ignore unnecessary files when pushing
- add `package.json` ==> `npm init -y` // -y means give all defaults
  - purpose of package.json: it tells npm or yarn what packages to download
- added "server" script (removed test script) inside `package.json`
- install `nodemon` as a development dependency ==> `npm i -D nodemon`
add an `index.js` file to root folder with a console.log
-run the API using `npm run server`