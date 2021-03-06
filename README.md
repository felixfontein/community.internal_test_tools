# Internal Test Tools Collection
[![CI](https://github.com/ansible-collections/community.internal_test_tools/workflows/CI/badge.svg?event=push)](https://github.com/ansible-collections/community.internal_test_tools/actions)
[![Codecov](https://img.shields.io/codecov/c/github/ansible-collections/community.internal_test_tools)](https://codecov.io/gh/ansible-collections/community.internal_test_tools)

This collection provides useful test tools for other collections. It is **NOT** aimed at Ansible users, but at collection developers!

Please note that this collection does **not** support Windows targets.

## Tested with Ansible

Tested with the current Ansible 2.9, ansible-base 2.10 and ansible-core 2.11 releases and the current development version of ansible-core. Ansible versions before 2.9.10 are not supported.

## Included content

- [`tests/unit/compat/` package](https://github.com/ansible-collections/community.internal_test_tools/tree/main/tests/unit/compat/)
- [`tests/unit/mock/` package](https://github.com/ansible-collections/community.internal_test_tools/tree/main/tests/unit/mock/)
- [`tests/unit/plugins/modules/utils.py`](https://github.com/ansible-collections/community.internal_test_tools/tree/main/tests/unit/plugins/modules/utils.py/)
- [`tests/unit/utils/fetch_url_module_framework.py`](https://github.com/ansible-collections/community.internal_test_tools/tree/main/tests/unit/utils/fetch_url_module_framework.py)
- [`tests/unit/utils/open_url_framework.py`](https://github.com/ansible-collections/community.internal_test_tools/tree/main/tests/unit/utils/open_url_framework.py)
- [extra sanity test runner](https://github.com/ansible-collections/community.internal_test_tools/tree/main/tools/README.md)
- [meta/runtime.yml helper](https://github.com/ansible-collections/community.internal_test_tools/tree/main/tools/README.md)

## Contributing to this collection

Please create issues to report problems or request new features, and create PRs to fix bugs or add new features. If you want to do a refactoring PR, please create an issue first to discuss the refactoring.

Please follow the general Ansible contributor guidelines; see the [Ansible Community Guide](https://docs.ansible.com/ansible/latest/community/index.html).

## Release notes

A changelog can be found [in the GitHub repository](https://github.com/ansible-collections/community.internal_test_tools/tree/main/CHANGELOG.rst).

## Releasing, Deprecation and Versioning

We release new versions once there are new features or bugfixes. Deprecations can happen, and we try to announce them a long time in advance. We currently do not plan breaking changes, so there will be no new major release anytime soon, except maybe a version 1.0.0.

## More information

- [Ansible Developer guide](https://docs.ansible.com/ansible/latest/dev_guide/index.html)
- [Developing Collections section in the Developer guide](https://docs.ansible.com/ansible/latest/dev_guide/developing_collections.html)
- [Ansible Community code of conduct](https://docs.ansible.com/ansible/latest/community/code_of_conduct.html)

## Licensing

GNU General Public License v3.0 or later.

See [COPYING](https://www.gnu.org/licenses/gpl-3.0.txt) to see the full text.
