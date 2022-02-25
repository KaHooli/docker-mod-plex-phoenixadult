# PhoenixAdult metadata agent - Docker mod for plex

This mod adds [PhoenixAdult metadata agent](https://github.com/PAhelper/PhoenixAdult.bundle) to Plex, to be downloaded/updated during container start.

In plex docker arguments, set an environment variable `DOCKER_MODS=ghcr.io/kahooli/plex-phoenixadult`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=ghcr.io/kahooli/plex-phoenixadult|linuxserver/mods:plex-mod2`
