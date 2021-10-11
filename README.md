Bootstrap 3 and 4 date time picker
==================================

This repo is a fork and adaptation of the code of [this repository](https://github.com/smalot/bootstrap-datetimepicker)
that was developped for Bootstrap 3 and which is not maintained anymore by its owner.

It contains :

- a slightly modified version for Bootstrap 3 (in the `bootstrap3/` directory)
- a rewrite version for Bootstrap 4 (in the `bootstrap4/` directory)

Building & publishing
---------------------

This requires that you have node.js installed.

Bump the version number in:

- `package.json`
- `bootstrap3/js/bootstrap-datetimepicker.js`
- `bootstrap4/js/bootstrap-datetimepicker.js`

Prepare:

	npm install

Build for **Bootstrap 3**:

	npm run build3

Build for **Bootstrap 4**:

	npm run build4

Build for **Bootstrap 5**:

	npm run build5

Publish to NPM registry:

	npm publish
