Package Specs for the Arch Linux User Repository (AUR)
========

This is a collection of package specifications (PKGBUILDs, patches, and misc. files) for Arch Linux organised under four folders:

- official: packages that I'm officially maintaining in the AUR;
- unofficial: packages maintained by someone else in either the AUR or official repos, which I've customised (usually to reflect the latest upstream release);
- wip: packages for upstream software that has no representation in either the official Arch Linux repos or AUR that I'm intending to complete and contribute to the AUR; and
- retired: packages that are now obsolete and/or superseded by other packages.

Packages are usually only temporarily labelled WIP until they are completed (and moved to the official folder after being contributed to the AUR). Unofficial packages are mostly packages found in the AUR (as TU-maintained packages are usually up-to-date and aligned to Arch Linux's packaging guidelines) and those specs are orked from their AUR repo mostly to either upgrade the package to its latest upstream release or modify the spec to better reflect Arch Linux's current packaging guidelines and accepted practices.

All official packages should be a clone of its AUR Git repository represented here as a Git submodule. Unofficial and WIP packages should also be represented by submodules that either clone an AUR repo, a repo under the github.com/jamesan-unofficial-aur-pkgs group, or some other third-party repository.
