alternativez.py [![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/)
================================
~~[wheel (GitLab)](https://gitlab.com/KOLANICH/alternativez.py/-/jobs/artifacts/master/raw/dist/alternativez-0.CI-py3-none-any.whl?job=build)~~
~~[wheel (GHA via `nightly.link`)](https://nightly.link/KOLANICH/alternativez.py/workflows/CI/master/alternativez-0.CI-py3-none-any.whl)~~
~~![GitLab Build Status](https://gitlab.com/KOLANICH/alternativez.py/badges/master/pipeline.svg)~~
~~![GitLab Coverage](https://gitlab.com/KOLANICH/alternativez.py/badges/master/coverage.svg)~~
[![GitHub Actions](https://github.com/KOLANICH-libs/alternativez.py/workflows/CI/badge.svg)](https://github.com/KOLANICH-libs/alternativez.py/actions/)
![N∅ dependencies](https://shields.io/badge/-N∅_Ъ_deps!-0F0)
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH-libs/alternativez.py.svg)](https://libraries.io/github/KOLANICH-libs/alternativez.py)
[![Code style: antiflash](https://img.shields.io/badge/code%20style-antiflash-FFF.svg)](https://codeberg.org/KOLANICH-tools/antiflash.py)

**We have moved to https://codeberg.org/KOLANICH-libs/alternativez.py (the namespace has changed to `KFmts`, which groups packages related to parsing or serialization), grab new versions there.**

Under the disguise of "better security" Micro$oft-owned GitHub has [discriminated users of 1FA passwords](https://github.blog/2023-03-09-raising-the-bar-for-software-security-github-2fa-begins-march-13/) while having commercial interest in success and wide adoption of [FIDO 1FA specifications](https://fidoalliance.org/specifications/download/) and [Windows Hello implementation](https://support.microsoft.com/en-us/windows/passkeys-in-windows-301c8944-5ea2-452b-9886-97e4d2ef4422) which [it promotes as a replacement for passwords](https://github.blog/2023-07-12-introducing-passwordless-authentication-on-github-com/). It will result in dire consequencies and is competely inacceptable, [read why](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

If you don't want to participate in harming yourself, it is recommended to follow the lead and migrate somewhere away of GitHub and Micro$oft. Here is [the list of alternatives and rationales to do it](https://github.com/orgs/community/discussions/49869). If they delete the discussion, there are certain well-known places where you can get a copy of it. [Read why you should also leave GitHub](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

---

A tool helping managing alternatives: packages with compatible API doing the same thing, but having different IDs. The name is inspired with [Debian alternatives](https://wiki.debian.org/DebianAlternatives). They may be different forks of one package, or completely independent packages having functions with the same API and doing the same things because it was an obvious solution. This library allows you not strictly require them all, but any of them, and it also allows to import them into your app in an easy way.

