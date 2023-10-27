# Spicetify Installation Guide + spicetify marketplace (Arch)

This is a quick guide to [Spicetify](https://github.com/spicetify) your Spotify

Sources: [Official Spicetify Installation Guide](https://spicetify.app/docs/advanced-usage/installation/) & [Spicetify Marketplace Wiki](https://github.com/spicetify/spicetify-marketplace/wiki/Installation)

## Clean spicetify config if it exists

```shell
rm -rf ~/.spicetify
rm -rf ~/.config/spicetify
```

## Install spicetify-cli

```shell
curl -fsSL https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.sh | sh
```

or

```shell
yay -S spicetify-cli
```

> **Note**:
> [If Spotify was installed from AUR](https://spicetify.app/docs/advanced-usage/installation#spotify-installed-from-aur)
>
>```shell
>sudo chmod a+wr /opt/spotify
>sudo chmod a+wr /opt/spotify/Apps -R
>```
>
> **Flatpak**, **Snap** or **other versions**, see documentation: [Note for Linux users](https://spicetify.app/docs/advanced-usage/installation#note-for-linux-users)

## Spicetify Marketplace

```shell
curl -fsSL https://raw.githubusercontent.com/spicetify/spicetify-marketplace/main/resources/install.sh | sh
```

### Now run

```shell
spicetify backup apply
```

Run `Spotify` and you should see **Marketplace** below Search on the sidebar. <br>
![Marketplace location](/assets/image.png)

***If you like my work, please consider:***

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J3J1QJINW)
