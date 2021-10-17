# tenacity-flatpak-nightly

Nightly Flatpak builds for [Tenacity](https://github.com/tenacityteam/tenacity/).

## Installation

Make sure to have the [Flathub remote](https://flatpak.org/setup/) added.

```
flatpak remote-add tenacity oci+https://tenacityteam.github.io/tenacity-flatpak-nightly
flatpak install tenacity org.tenacityaudio.Tenacity
```

(Use `--user` flag in all commands to install per user.)
