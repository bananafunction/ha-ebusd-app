# Home Assistant App: ebusd

This app creates a Home Assistant OS (HAOS) app to run [ebusd](http://ebusd.eu). Configure ebusd commandline arguments using configuration options.

Use ebusd's built-in MQTT client and the [mosquitto](https://github.com/home-assistant/addons/tree/master/mosquitto) app to get data from ebusd into Home Assistant core.

See [repository readme](https://github.com/bananafunction/ha-ebusd-app#how-to-install) on how to install ebusd app in HAOS.

See [docs](https://github.com/bananafunction/ha-ebusd-app/blob/main/ebusd/DOCS.md#how-to-run-ebusd) on how to run ebusd in HAOS.

## Support

**Issues in Configuration and Usage**
Many issues result from incomplete [ebusd configuration](https://github.com/john30/ebusd/wiki/4.-Configuration) files. This project only runs ebusd, configuration files are **not** managed by this project. Please see the offical [ebusd project](https://ebusd.eu) and [community](https://github.com/john30/ebusd/discussions) for more information. 

**If you have questions or feedback on running ebusd via HAOS**
- use [Issues](https://github.com/bananafunction/ha-ebusd-app/issues) and [pull requests](https://github.com/bananafunction/ha-ebusd-app/pulls) in the Github repository

## Versioning Scheme

This app is versioned in a way that [mirrors the `ebusd` version](https://github.com/john30/ebusd/releases).
App specific iterations are denoted by the patch number.

- **<ebusd Major>.<ebusd Minor>.<app-specific Iteration> **: Mirrors the [corresponding `ebusd` version](https://github.com/john30/ebusd/releases). while the `App-specific Iteration` denote app-specific iterations.

**Example**: `26.1.0`
