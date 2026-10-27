# dwl-build

Customized build of dwl with patches.

## Building dwl

Dependencies:

- `libinput-devel`
- `wayland-devel`
- `wlroots0.20-devel`
- `libxkbcommon-devel`
- `wayland-protocols`
- `pkg-config`
- `base-devel`

Additional dependencies for XWayland support:

- `libxcb-devel`
- `xcb-util-wm-devel`
- `xorg-server-xwayland`

Additional dependencies for patches:

- `tllist`
- `fcft`
- `fcft-devel`
- `pixman`

Build and install with `doas make clean install`.

## Patches

- [bar](https://codeberg.org/dwl/dwl-patches/src/branch/main/patches/bar)
- [alwayscenter](https://codeberg.org/dwl/dwl-patches/src/branch/main/patches/alwayscenter)
- [cursortheme](https://codeberg.org/dwl/dwl-patches/src/branch/main/patches/cursortheme)
- [autostart](https://codeberg.org/dwl/dwl-patches/src/branch/main/patches/autostart)

## Acknowledgements

- [dwl](https://codeberg.org/dwl/dwl) - A compact, hackable compositor for Wayland.
- [dwm](https://dwm.suckless.org/) - The original inspiration from suckless.org.
