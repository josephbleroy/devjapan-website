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

### Deploying

1. After running the `gulp build` command, there will be a directory called `build`.
2. Do normal git related tasks to keep src updated locally and remote (Github).
3. Use `rsync -a build username@server:/var/www/devjapan.jp/html`

### To Do

Modify [CircleCI] configuration to prevent building when non src directory files are modified and pushed to master.

[Dev Japan Tokyo]: https://devjapan.jp
[Node.js]: https://nodejs.org
[CircleCI]: https://circleci.com
