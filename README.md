# dwl-build

Customized build of dwl.

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

Build and install with `doas make clean install`.

## Acknowledgements

- [dwl](https://codeberg.org/dwl/dwl) - A compact, hackable compositor for Wayland.
- [dwm](https://dwm.suckless.org/) - The original inspiration from suckless.org.
