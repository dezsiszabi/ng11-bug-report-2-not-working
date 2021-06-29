# Reproduction steps

- Clone the repo
- run `npm install` in `angular12` folder.
- run `npm run start`

Expected:

- No errors on console.
- Website works.

What happens instead:

- Error on console: `./node_modules/isobject/index.js:3:14-32 - Error: Module not found: Error: Can't resolve 'isarray' in '/home/dezsiszabi/ng12-bug-repro'`.
- Website doesn't work.
