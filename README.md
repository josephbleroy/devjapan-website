# devjapan-website

This is the repository for the [Dev Japan Tokyo] website!

## Development

### Requirements

1. Have [node.js] installed
2. [Fork] and clone the repository to your machine
3. `npm install` to install the relevant node packages

### Making changes

Make your changes in the relevant files within the `src` directory.
Then, to compile your changes do `gulp build`. Check out the compiled files
in the git ignored `build` directory.

If you want to make multiple changes and have the files rebuilt on every
change that you do, use `gulp dev`.

### To Do

Modify [CircleCI] configuration to prevent building when non src directory files are modified and pushed to master.

[Dev Japan Tokyo]: https://devjapan.jp
[Node.js]: https://nodejs.org
[CircleCI]: https://circleci.com
