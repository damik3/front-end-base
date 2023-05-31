### Setup
1. Run `npm install`.
2. Run `npm run prepare` for husky setup.

### Checks
 - To check for typescript errors, run `npm run lint`.
 - To check for what prettier would format if you executed it, run `npm run format:check`.
 - To format files with prettier, run `npm run format`.

### Pre commit hooks
 - Every time you make a commit, eslint and prettier will run a check. If there are errors they will not allow the commit to happen. 
 - So you should manually run `npm run format` before each commit.
 - You can view and config these hooks in the `.husky/pre-commit` file.

### Rules and config
 - Their rules can be configured in `.eslintrc.json` and `.prettierrc.json`.
 - Eslint rules: [https://eslint.org/docs/latest/rules/](https://eslint.org/docs/latest/rules/)
 - Prettier rules: [https://prettier.io/docs/en/options.html](https://prettier.io/docs/en/options.html)
 - You can also configure which files each one should ignore in `.eslintignore ` and `.prettierignore`.

### Sources
 - [https://github.com/eslint/eslint](https://github.com/eslint/eslint)
 - [https://github.com/prettier/prettier](https://github.com/prettier/prettier)
 - [https://github.com/typicode/husky](https://github.com/typicode/husky)
 - [https://github.com/prettier/eslint-config-prettier](https://github.com/prettier/eslint-config-prettier)
