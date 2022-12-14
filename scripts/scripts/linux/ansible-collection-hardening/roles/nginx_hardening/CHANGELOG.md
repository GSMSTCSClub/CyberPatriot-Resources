# Changelog

## [2.1.0](https://github.com/dev-sec/ansible-nginx-hardening/tree/2.1.0) (2018-11-18)

[Full Changelog](https://github.com/dev-sec/ansible-nginx-hardening/compare/2.0.0...2.1.0)

**Merged pull requests:**

- add ubuntu 18.04 support [#20](https://github.com/dev-sec/ansible-nginx-hardening/pull/20) ([rndmh3ro](https://github.com/rndmh3ro))
- updated minimum required ansible version to 2.5 in README, as the used 'loop' keyword was introduced in version 2.5 [#19](https://github.com/dev-sec/ansible-nginx-hardening/pull/19) ([szEvEz](https://github.com/szEvEz))

## [2.0.0](https://github.com/dev-sec/ansible-nginx-hardening/tree/2.0.0) (2018-09-08)

[Full Changelog](https://github.com/dev-sec/ansible-nginx-hardening/compare/1.0.2...2.0.0)

**Implemented enhancements:**

- Update readme to include baselines [#10](https://github.com/dev-sec/ansible-nginx-hardening/issues/10)
- Update testing, remove useless params, style update [#18](https://github.com/dev-sec/ansible-nginx-hardening/pull/18) ([rndmh3ro](https://github.com/rndmh3ro))
- Update README.md [#14](https://github.com/dev-sec/ansible-nginx-hardening/pull/14) ([vishesh92](https://github.com/vishesh92))
- Add comment filter to {{ansible_managed}} string [#12](https://github.com/dev-sec/ansible-nginx-hardening/pull/12) ([fazlearefin](https://github.com/fazlearefin))
- use new Docker images [#8](https://github.com/dev-sec/ansible-nginx-hardening/pull/8) ([rndmh3ro](https://github.com/rndmh3ro))

**Fixed bugs:**

- Running kitchen verify asks for 'roots' password [#11](https://github.com/dev-sec/ansible-nginx-hardening/issues/11)
- Fix duplicate ssl_prefer_server_ciphers error [#16](https://github.com/dev-sec/ansible-nginx-hardening/pull/16) ([oakey-b1](https://github.com/oakey-b1))

## [1.0.2](https://github.com/dev-sec/ansible-nginx-hardening/tree/1.0.2) (2016-10-24)

[Full Changelog](https://github.com/dev-sec/ansible-nginx-hardening/compare/1.0.1...1.0.2)

**Fixed bugs:**

- Syntax Error while loading YAML in defaults/main.yml [#6](https://github.com/dev-sec/ansible-nginx-hardening/issues/6)

**Merged pull requests:**

- remove tabs. fix #6 [#7](https://github.com/dev-sec/ansible-nginx-hardening/pull/7) ([rndmh3ro](https://github.com/rndmh3ro))

## [1.0.1](https://github.com/dev-sec/ansible-nginx-hardening/tree/1.0.1) (2016-09-23)

[Full Changelog](https://github.com/dev-sec/ansible-nginx-hardening/compare/1.0.0...1.0.1)

**Fixed bugs:**

- ssl_dhparam [#4](https://github.com/dev-sec/ansible-nginx-hardening/issues/4)

**Closed issues:**

- Make the owner /etc/nginx configurabe [#3](https://github.com/dev-sec/ansible-nginx-hardening/issues/3)
- Running worker process as non-privileged user (1 failed) [#2](https://github.com/dev-sec/ansible-nginx-hardening/issues/2)

**Merged pull requests:**

- create dhparam file. fix #4 [#5](https://github.com/dev-sec/ansible-nginx-hardening/pull/5) ([rndmh3ro](https://github.com/rndmh3ro))
- improve gemfile, update readme for local tests [#1](https://github.com/dev-sec/ansible-nginx-hardening/pull/1) ([chris-rock](https://github.com/chris-rock))

## [1.0.0](https://github.com/dev-sec/ansible-nginx-hardening/tree/1.0.0) (2016-08-11)

[Full Changelog](https://github.com/dev-sec/ansible-nginx-hardening/compare/1b9dcf16cfbf45ff5f50cd83509245d1527f9fd0...1.0.0)

\* _This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)_
