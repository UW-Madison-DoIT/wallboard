# Wallboard

A basic JavaScript page for cycling through a set of remote pages to display as a wallboard/radiator.

## Configuration

Edit the `dashboards` array in `jiradash.html` to setup the pages you want to display.

## Usage
Since the dashboard tries to do cross-domain javascript via iframes this must be loaded into a browser with cross-domain security disabled. For Safari and Chrome this can be done by passing the `-disable-web-security` flag.

### OSX Safari Example

`open -a '/Applications/Safari.app' - -args - -disable-web-security`