## Wayland support
By default, X11 is the preferred option. This behavior can be changed by passing an additional `--socket=wayland` option:
```sh
flatpak run --socket=wayland com.surfshark.Surfshark
```

To persist Wayland as a default:
```sh
flatpak override --socket=wayland com.surfshark.Surfshark
```

To revert the action above:
```sh
flatpak override --nosocket=wayland com.surfshark.Surfshark
```

## Other resources
Check our privacy policy: https://surfshark.com/privacy
Check our ToS: https://surfshark.com/terms-of-service
