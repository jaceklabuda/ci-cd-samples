# CI/CD Samples

## GitLab CI/CD - Basic GitFlow

Configuration file:

> git-flow.sample.gitlab-ci.yml

Idea:

- Run build & tests for `feature branches`, `develop` and `tags`

- Run deploy on dev & test environment for `develop` and `tags`

- Allow manual deploy on production for `tags`

- Allow schedule tests for `e2e tests`
