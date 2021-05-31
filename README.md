# Open Source Checklist for JavaScript Project

1. [Pre-launch checklist](https://opensource.guide/starting-a-project/#your-pre-launch-checklist)
2. [ESLint](https://eslint.org/)
    ```bash
    npm install eslint --save-dev
    ```
    ```bash
    npx eslint --init
    ```
3. [Prettier](https://prettier.io/)
    ```bash
    npm install --save-dev --save-exact prettier
    ```
    ```bash
    echo {}> .prettierrc.json
    ```
4. [Commitlint](https://commitlint.js.org/#/)
    ```bash
    npm install --save-dev @commitlint/cli
    ```
    ```bash
    npm install --save-dev @commitlint/config-conventional
    ```
    ```bash
    echo "module.exports = { extends: ['@commitlint/config-conventional'] };" > commitlint.config.js
    ```
    ```bash
    # Husky
    npm install husky --save-dev
    ```
    ```bash
    npx husky install
    ```
    ```bash
    npx husky add .husky/commit-msg 'npx --no-install commitlint --edit $1'
    ```
5. [Lint Staged](https://github.com/okonet/lint-staged#readme)
    ```bash
    npx mrm lint-staged
    ```
