# Frescobaldi -- LilyPond editor

## Versions of LilyPond

This flatpak package bundles the stable and the unstable versions of LilyPond.
When you launch it the first time, Frescobaldi will detect only the stable
version, installed in `/app/bin` (which has higher priority in the PATH
environment variable).
In order to use the unstable version of LilyPond, you must manually add
the path `/app/lilypond-unstable/bin/lilypond` in *LilyPond Preferences*.


## Beta branch

The beta branch of this repository will be used to test the latest unreleased
Frescobaldi (if there's anything interesting to try) and/or a peculiar
LilyPond installation (new features or dependencies).

