# Development Notes

## Project Structure

List of Deno projects:

* https://github.com/denolib/awesome-deno

I picked the project structure of these:

* https://github.com/denodrivers/mysql
* https://github.com/drashland/wocket


## ex package.json

There's no package.json in (pure) deno projects, so where do we put all these informations?
{
  "name": "quickfix-ts",
  "version": "0.0.1",
  "description": "QuickFIX engine implementation in Typescript for Deno runtime",
  "main": "index.ts",
  "dependencies": {
    "typescript": "^4.1.2"
  },
  "devDependencies": {
    "@typescript-eslint/eslint-plugin": "^4.8.1",
    "@typescript-eslint/parser": "^4.8.1",
    "eslint": "^7.14.0"
  },
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/thorstenhirsch/quickfix-ts.git"
  },
  "author": "",
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/thorstenhirsch/quickfix-ts/issues"
  },
  "homepage": "https://github.com/thorstenhirsch/quickfix-ts#readme"
}