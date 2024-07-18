# Frescobaldi -- LilyPond editor

## Versions of LilyPond

This flatpak package bundles the latest stable and the unstable
versions of LilyPond.
When you launch it the first time, Frescobaldi will detect only the stable
version, installed in `/app/bin` (which has higher priority in the PATH
environment variable).
In order to use the unstable version of LilyPond, you must manually add
the path `/app/dev/bin/lilypond` in *LilyPond Preferences*.

If you want to use a particular version of LilyPond which is
not bundled in the flatpak, you should download the right binary
for your platform from lilypond.org, unpack it in a folder
(e.g. `~/.local/lilypond`) and then grant access to that
folder using either [Flatseal](https://flathub.org/apps/details/com.github.tchx84.Flatseal)
or flatpak command line.

NOTE: self-compiled LilyPond will likely not work.


## Beta branch

The beta branch of this repository will be used to test the latest unreleased
Frescobaldi (if there's anything interesting to try) and/or a peculiar
LilyPond installation (new features or dependencies).

