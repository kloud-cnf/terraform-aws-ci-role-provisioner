## [1.0.5](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/compare/v1.0.4...v1.0.5) (2023-06-17)


### Bug Fixes

* **ci:** remove lock file ([5420635](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/commit/54206352cc32f931ac9e298bbf42d7c6ffaf254c))

## [1.0.4](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/compare/v1.0.3...v1.0.4) (2023-06-17)


### Bug Fixes

* **iam:** increase permissions on ci-role-provisoner to enable IAM role managment via IAC ([226696a](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/commit/226696a11d3589843f87be90905e8d6ebcee9d8c))
* **iam:** increase permissions on ci-role-provisoner to enable IAM role managment via IAC ([b6560f4](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/commit/b6560f4feab00e63ca050a5a4ba1d6f33d262ca3))

## [1.0.3](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/compare/v1.0.2...v1.0.3) (2023-06-16)


### Bug Fixes

* **outputs:** add some outputs to share info about provider deployments to root+OU targets ([3eb3c58](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/commit/3eb3c58b599566466494a63c0e65c6c6ce2aee0b))

## [1.0.2](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/compare/v1.0.1...v1.0.2) (2023-06-11)


### Bug Fixes

* **iam:** support OIDC pull_request event claim for github provider ([a07dc20](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/commit/a07dc20a846085cc414c10591965e1a6ec9b9cae))
* **iam:** support OIDC pull_request event claim for github provider ([6d18fab](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/commit/6d18fab41dff416ad031fc4adde691d8efb7f489))

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Contents

- [1.0.1 (2023-06-07)](#101-2023-06-07)
    - [Bug Fixes](#bug-fixes)
- [1.0.0 (2023-05-23)](#100-2023-05-23)
    - [Features](#features)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# [1.0.1](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/compare/v1.0.0...v1.0.1) (2023-06-07)


### Bug Fixes

* **iam:** format input refs based on platform ([ce14d07](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/commit/ce14d07598fc67a0d5cae6afe00fdecbdfa0ec3b))

# 1.0.0 (2023-05-23)


### Features

* **oidc:** module support for deploying CI OIDC providers with IAM role provisoner via Cloudformation ([6363118](https://github.com/kloud-cnf/terraform-aws-ci-role-provisioner/commit/63631184ff60f5a068bac6ab10ee4247976c49cb))
