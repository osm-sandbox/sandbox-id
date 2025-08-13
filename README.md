# iD Editor for OSM Sandbox

This is a fork of the [iD editor](https://github.com/openstreetmap/iD) intended for use with [OSM Sandbox](https://github.com/osm-sandbox/).

## Differences from iD

Sandbox-iD has a few modifications compared to the upstream iD editor, in order to meet our needs for editing in Sandbox environments:

### License configuration

The editor can be configured on launch to show only those data sources (imagery, overlays, etc.) compatible for mapping public domain data (typically [CC0](https://creativecommons.org/public-domain/cc0/)). This can be done by setting `license=cc0` in the URL hash or programmatically by running `context.license('cc0')`. The default license is `odbl`, suitable for editing OpenStreetMap extracts in a sandbox.

### Rebranding

To avoid confusion, references to "OpenStreetMap" in the UI have been replaced with "OSM Sandbox". Information and links specific to OSM have been removed or replaced.

## Contributing

* Questions or comments? Feel free to [open an issue](https://github.com/osm-sandbox/sandbox-iD/issues)
* Before participating, please read the [Code of Conduct](CODE_OF_CONDUCT.md) and remember to be nice

## License

This fork is available under the same [ISC License](https://opensource.org/licenses/ISC) used [by iD](https://github.com/openstreetmap/iD#License). See [LICENSE.md](LICENSE.md) for more details.
