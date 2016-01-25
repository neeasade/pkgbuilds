Misc aur packages.

aur-push initially came from [here](https://github.com/EvanPurkhiser/PKGBUILDs), but depended on the ability to force push to the AUR in the event of a fast forward, which was disabled in the AUR config mid 2015. So I edited it to just clone, replace files, and autocommit with the git remote of this repo. Either way you will need the `pkgbuild-introspection` for the mksrcinfo command.

A note on gtkrc-reload: I initially found it in AUR3, with the small c file contained within it. Thanks to the original maintainer (who I assume is the writer) Speps.

[How to AUR/AUR4 for dummies](https://www.reddit.com/r/archlinux/comments/3c3c1m/how_to_aur_aur4_for_dummies/)
