# Ansible Local Setup

This repository was created to make local environment setup as easy as possible. By using a simple bootstrap script in conjunction with Ansible, we can easily provision all of the local tools necessary for developing as part of the Open Commerce Data Team.

## Prerequisites

Before you get started, you will need to have set your [Git credentials](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) in the OSX keychain.  You can do so by running the following command:

```security add-internet-password -a <GITHUB USERNAME> -w <GITHUB TOKEN> -s github.com -r htps```

## Getting Started

To start the install and configuration of your local environment, simply run the bootstrap script via terminal using `bin/bootstrap`.

## What Apps/Packages Are Installed?

At this time, this repository currently installs the following packages:

- [1password](https://1password.com)
- [AWS CLI](https://aws.amazon.com/cli/)
- [chezmoi](https://chezmoi.io)
- coreutils
- [dbeaver-community](https://dbeaver.io)
- [drone-cli](https://drone.auto.oc.ai)
- freetype
- grep
- jq
- [iterm2](https://iterm2.com)
- [txn2/tap/kubefwd](https://kubefwd.com/install/mac/)
- [kubectl](https://kubernetes.io/docs/reference/kubectl/)
- libpq
- [nvm](https://github.com/nvm-sh/nvm)
- Java 11 (OpenJDK Variant)
- [openlens](https://github.com/lensapp/lens)
- [parquet-cli](https://github.com/chhantyal/parquet-cli)
- [pycharm-ce](https://www.jetbrains.com/pycharm/)
- python@3.9
- [session-manager-plugin](https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager-working-with-install-plugin.html)
- slack
- terraform-docs
- [tfenv](https://github.com/tfutils/tfenv)
- [tflint](https://github.com/terraform-linters/tflint)
- virtualenv
- VS Code
- yq
- zoom
- zsh

## What Projects Are Cloned?

The following repositories are cloned and initialized as part of this setup package:

- oc-data-pipelines
- oc-databricks
- oc-databricks-altria
- oc-databricks-cefco
- oc-databricks-chevron
- oc-databricks-delek
- oc-databricks-gulf
- oc-databricks-marathon
- oc-databricks-yesway
- oc-stacks
- oc-terraform
- oc-tf-data-lake
- sprak
- stuzo-aws-python
- stuzo-dba-python
- stuzo-common-python   