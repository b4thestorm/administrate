# Contributing Guide

## Code of Conduct

We welcome pull requests from everyone. By participating in this project, you
agree to abide by the thoughtbot [code of conduct].

We expect everyone to follow the code of conduct anywhere in thoughtbot's
project codebases, issue trackers, chat-rooms, and mailing lists.

[code of conduct]: https://thoughtbot.com/open-source-code-of-conduct

## Getting Started

TBD

## Issue Triage

TBD

## Releasing

New releases (and the time period between them) is arbitrary, but usually
motivated by a new Rails release or enough bug fixes and/or features that
there's significant enough changes.

A new release involves cutting and pushing a new version to [Ruby Gems][] and
then deploying that version of the example application and documentation. This
means that [the demo application][demo] always matches the current release,
whilst [the pre-release application][pre-release] can track current `master`.

[Ruby Gems]: https://rubygems.org/gems/administrate
[demo]: https://administrate-demo.herokuapp.com/
[pre-release]: https://administrate-demo-prerelease.herokuapp.com/

## Label Taxonomy

Issues and PRs are split into two levels of labels, at the higher level:

* `feature`: new functionality that’s not yet implemented,
* `bug`: breakages in functionality that is implemented,
* `maintenance`: to keep up with changes around us

…and then to more specific themes:

* `namespacing`: models with a namespace,
* `installing`: initial setup, first-run experience, generators,
* `i18n`: translations and language support,
* `views-and-styles`: how administrate looks and is interacted with,
* `dashboards`: how administrate presents fields and displays data,
* `search`: finding things through our models,
* `sorting`: ordering things on dashboards,
* `pagination`: how we handle lots of data in small chunks,
* `security`: controlling data access through authorisation,
* `fields`: new fields, displaying and editing data,
* `models`: models, associations and fetching the underlying data,
* `documentation`: how to use Administrate, examples and common usage,
* `dependencies`: changes or issues relating to a dependency

## Security

For security inquiries or vulnerability reports, please email
<security@thoughtbot.com>.
If you'd like, you can use our [PGP key] when reporting vulnerabilities.

[PGP key]: https://thoughtbot.com/thoughtbot.asc
