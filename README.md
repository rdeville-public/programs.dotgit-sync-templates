<!-- BEGIN DOTGIT-SYNC BLOCK MANAGED -->
# 👋 Welcome to dotgit-sync-templates

<center>

[![Licenses: (MIT OR BEERWARE)][license_badge]][license_url]
[![Changelog][changelog_badge]][changelog_badge_url]
[![Build][build_badge]][build_badge_url]
[![Release][release_badge]][release_badge_url]

</center>

[build_badge]: https://framagit.org/rdeville-public/programs/dotgit-sync-templates/badges/main/pipeline.svg
[build_badge_url]: https://framagit.org/rdeville-public/programs/dotgit-sync-templates/-/commits/main
[release_badge]: https://framagit.org/rdeville-public/programs/dotgit-sync-templates/-/badges/release.svg
[release_badge_url]: https://framagit.org/rdeville-public/programs/dotgit-sync-templates/-/releases/
[license_badge]: https://img.shields.io/badge/Licenses-MIT%20OR%20BEERWARE-blue
[license_url]: https://framagit.org/rdeville-public/programs/dotgit-sync-templates/blob/main/LICENSE
[changelog_badge]: https://img.shields.io/badge/Changelog-Python%20Semantic%20Release-yellow
[changelog_badge_url]: https://github.com/python-semantic-release/python-semantic-release

> Repository of templated files to used in combination with [dotgit-sync](https://framagit.org/rdeville-public/programs/dotgit-sync)

---

<!-- BEGIN DOTGIT-SYNC BLOCK EXCLUDED CUSTOM_README -->
## 📌 Prerequisites

This repo provides sets of templated files to used in combination with
[dotgit-sync](https://framagit.org/rdeville-public/programs/dotgit-sync).

To use it, you'll need [dotgit-sync](https://framagit.org/rdeville-public/programs/dotgit-sync).

```bash
# I have not release dotgit-sync now
pip3 install git+https://framagit.org/rdeville-public/programs/dotgit-sync
```

## 🚀 Usage

Write a file `.config.yaml` as describe in the documentation of
[dotgit-sync](https://framagit.org/rdeville-public/programs/dotgit-sync).

Then, if you have defined the source of this template in your `.config.yaml`,
simply run :

```bash
dotgit-sync
```

If you want to override your `.config.yaml`, you can use the `-d` or `-g`
option of `dotgit-sync`

```bash
# Provide the URL of the git repo
dotgit-sync -g "https://framagit.org/rdeville-public/programs/dotgit-sync-templates"
# If you clone it locally, provide path directly, either absolute or relative
dotgit-sync -d "../path/to/your/local/clone"
```

If you want to automate update of your dotgit files, you can check file
`./statics/common/.gitlab/dotgit-sync.yaml` to see an example of a Gitlab CI
that automatically upgrade dotgit files if this template is updated.

<!-- END DOTGIT-SYNC BLOCK EXCLUDED CUSTOM_README -->

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check [issues page][issues_pages].

You can also take a look at the [CONTRIBUTING.md][contributing].

[issues_pages]: https://framagit.org/rdeville-public/programs/dotgit-sync-templates/-/issues
[contributing]: https://framagit.org/rdeville-public/programs/dotgit-sync-templates/blob/main/CONTRIBUTING.md

## 👤 Maintainers

  * 📧 [**Romain Deville** \<code@romaindeville.fr\>](mailto:code@romaindeville.fr)
    * Website: [https://romaindeville.fr](https://romaindeville.fr)
    * Github: [@rdeville](https://github.com/rdeville)
    * Gitlab: [@r.deville](https://gitlab.com/r.deville)
    * Framagit: [@rdeville](https://framagit.org/rdeville)

## 📝 License

Copyright © 2024 [Romain Deville](code@romaindeville.fr)

This project is under following licenses (**OR**) :

  * [MIT][main_license]
  * [BEERWARE][beerware_license]

[main_license]: https://framagit.org/rdeville-public/programs/dotgit-sync-templates/blob/main/LICENSE
[beerware_license]: https://framagit.org/rdeville-public/programs/dotgit-sync-templates/blob/main/LICENSE.BEERWARE

<!-- END DOTGIT-SYNC BLOCK MANAGED -->