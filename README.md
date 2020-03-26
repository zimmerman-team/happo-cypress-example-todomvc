# A demo of using Happo.io with Cypress

This repo is a fork of [the `cypress-io/cypress-example-todomvc`
repo](https://github.com/cypress-io/cypress-example-todomvc). It demonstrates
how to integrate Happo.io screenshot testing with Cypress. Circle CI is used
for testing in CI, but you can integrate with most other services as well.

These two commits demonstrate the steps required to get a fully working
Happo+Cypress setup:

- [`21e551c6 - Add Happo integration via the happo-cypress
  library`](https://github.com/happo/happo-cypress-example-todomvc/commit/21e551c6fb55349c3d0e6b3369ca1135fc34042d)
- [`9badf030 - Add
  .circleci/config.yml`](https://github.com/happo/happo-cypress-example-todomvc/commit/9badf030a7af671ec2012d5b67c57d8cafb62e40)

[Here'a a PR](https://github.com/happo/happo-cypress-example-todomvc/pull/2)
that introduces a styling change. It demonstrates how Happo updates the build
status with visual diffs introduced. [The resulting Happo
report](https://happo.io/a/288/p/345/compare/7802bcbc1b084a47972e7311da629931eb589170/3ac6c1bf15cfb9d8d13f00727e977f5447519a1d)
is linked to from the build status.
