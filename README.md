# Open Source Checklist for JavaScript Project
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

A few tooling and other checks needed for your Open-Source JavaScript Project:

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
5. [Husky](https://typicode.github.io/husky/#/)
    ```bash
    npm install husky --save-dev
    ```
    ```bash
    npx husky install
    ```
    ```bash
    npx husky add .husky/commit-msg 'npx --no-install commitlint --edit $1'
    ```
6. [Lint Staged](https://github.com/okonet/lint-staged#readme)
    ```bash
    npx mrm lint-staged
    ```

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://shhdharmen.me"><img src="https://avatars.githubusercontent.com/u/6831283?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dharmen Shah</b></sub></a><br /><a href="#content-shhdharmen" title="Content">🖋</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
