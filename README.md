## cookiecutter-molecule

Generated from Molecule version `2.20.0`

### Changes

* `goss` is the verifier
  * `verify.yml` uses the `template` module instead of `copy` so that goss files can use templating
* `ansible-lint` ignores warnings for `meta/main.yml`
* Contains two instances - Ubuntu 16.04 and CentOS 7
