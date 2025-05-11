# Aylur's Gtk Shell

Install on Arch:
```
sudo pacman -S typescript npm meson gjs glib2 glib2-devel gtk3 gtk-layer-shell gnome-bluetooth-3.0 upower networkmanager gobject-introspection libdbusmenu-gtk3 libsoup3
```

```
cd /tmp
git clone --recursive https://github.com/Skiftstar/ags.git
cd ags
git checkout v1
npm install
meson setup build
meson install -C build
```

## Get started

To get started read the [wiki](https://aylur.github.io/ags-docs).
