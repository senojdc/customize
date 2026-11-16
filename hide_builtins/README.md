# Omarchy Opinionless Panels Config

## Menu Changes
- Changes at /usr/share/omarchy/default/omarchy/omarchy-menu.jsonc
- Hides installations specific to services, gaming, development, code editors, browsers, font, ai, and preinstalls
- Only shows setting default to what comes with omarchy by default

## Network Changes
- Changes at /usr/share/omarchy/shell/plugins/panels/network/Panel.qml
- Hides setup for all Network other than DNS and custom

> [!NOTE]
> This does not remove any configuration, only changes what appears in the panels

To apply config run `./hide_builtins.sh`
