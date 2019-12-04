# `postcss-import-issue-repro`

This project is bootstrapped by [aurelia-cli](https://github.com/aurelia/cli).

`au new postcss-import-issue-repro --unattended --select cli-bundler,typescript,postcss-typical`

The postcss-import with sourcemaps enabled runs into issues when importing a css file with no classes.
Code that is commented out does not prevent the issue from happening.

Uncomment the .btn class and the `npm run` runs without issues.
