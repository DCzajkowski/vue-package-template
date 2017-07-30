# Vue package ES6 boilerplate
This is a simple boilerplate for your next Vue plugin.

## Table of contents:
* [Installation](#installation)
* [How it works](#how-it-works)
    * [NPM usage](#npm-usage)
    * [Browser usage](#browser-usage)
* [Contributing](#contributing)
* [License](#license)
* [Issues](#issues)

## Installation
1. Fork this repo
2. Clone it to your local development machine
3. Open `package.json` file. Find and replace following keys:
    * `package-name` - Package name with dashes
    * `package-description` - Full package description
    * `package-git-url` - Full url to the git folder, e.g. https://github.com/user/package.git
    * `package-repo-url` - Full url to the repo, e.g. https://github.com/user/package
    * `package-autor` - Your name is enough
4. Run `npm install`
5. Run `npm login`
6. Write your package code in `src/main.js`
7. Remove `README.md` and rename `README.example.md` to `README.md`
8. Edit your new README file accordingly
9. Run `npm publish`

## How it works
This template uses two different build systems.

### NPM usage
All code meant for npm usage is compiled with Webpack. All code goes into `dist-module/` folder.

It is ignored by Git, but is being published to npm.

### Browser usage
All code meant for browser usage ie. `<script>` import is compiled with Browserify + Vueify. All code goes to `dist/` folder.

It is ignored by Git, but is being published to npm.

## Contributing
You are welcome to contribute to this package in any way or form you want. New issues and pull requests are welcome.

I am not a JavaScript expert and some things may not be made in the best way possible. Feel free to point out anything that sticks out.

## License
Just use it. For free. Forever.

## Issues
If you find any bug or problem with the template please open an issue or create a pull request on the [Github repo](https://github.com/DCzajkowski/vue-lightbox).
