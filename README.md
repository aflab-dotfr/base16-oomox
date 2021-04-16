# base16-oomox

Generate [oomox](https://github.com/themix-project/oomox) colors file.

## Installation

You can import the generated colors file from the GUI or simply use the shells scripts named `change_color.sh` found in `/opt/oomox/plugins`.

You can list all the scripts with this command:
```shell
$ find /opt/oomox/plugins -name change.color.sh
```

```
/opt/oomox/plugins/icons_suruplus/change_color.sh
/opt/oomox/plugins/icons_suruplus_aspromauros/change_color.sh
/opt/oomox/plugins/theme_materia/materia-theme/change_color.sh
/opt/oomox/plugins/theme_arc/arc-theme/change_color.sh
/opt/oomox/plugins/icons_archdroid/archdroid-icon-theme/change_color.sh
/opt/oomox/plugins/icons_papirus/change_color.sh
/opt/oomox/plugins/icons_gnomecolors/gnome-colors-icon-theme/change_color.sh
/opt/oomox/plugins/theme_oomox/gtk-theme/change_color.sh
/opt/oomox/plugins/icons_numix/change_color.sh
```

## Example

Here's an example how to generate an oomox theme with numix incons using the morio color scheme.

```
$ /opt/oomox/plugins/theme_oomox/gtk-theme/change_color.sh output/oomox/default/base16-morio -o morio

$ /opt/oomox/plugins/icons_numix/change_color.sh output/oomox/default/base16-morio -o morio
```
