# test_react
#class-1
  -npm init
  -Pushing to github
#class-2
  -.editorconfig & .eslintrc.js
#class-3
  -Commitlint
      -#Install
        npm install --save-dev @commitlint/config-conventional @commitlint/cli husky

      #Configure husky

        "husky": { "hooks": { "commit-msg": "commitlint -E HUSKY_GIT_PARAMS" } }

      #Configure commitlint

        -Create a file called commitlint.config.js with the following content:

          module.exports = { extends: [ '@commitlint/config-conventional' ] };
