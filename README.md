## cookiecutter-molecule

A Molecule role with my personal preferences and modifications.

Generated from Molecule version `2.20.0`

### Changes

* `vagrant` is the driver
* `goss` is the verifier
  * `verify.yml` uses the `template` module instead of `copy` so that goss files can use templating
  * Operating system specific goss files are only run on the correct platform. See `test_debian.yml` and `test_redhat.yml`.
* `ansible-lint` ignores warnings for `meta/main.yml`
* Contains two instances - Ubuntu 16.04 and CentOS 7
  * Ubuntu includes an example forwarded port
