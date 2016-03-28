# Application Tiles

With this module you able to customize your web application on `Android`, `Windows` and `iOS` devices with possibility to set tiles of different sizes.

## Usage

Every theme can have its own set of tiles. To customize it you'll need to put the files inside of seekable directories, for example:

- `themes/bartik/tiles/android`
- `themes/bartik/tiles/windows`
- `themes/bartik/tiles/ios`

**Note** that every file must be named as supported dimension and be in `.png` format. The list of supported dimensions listed below:

- Android: `96x96`, `192x192`, `194x194`
- Windows: `70x70`, `150x150`, `310x150`, `310x310`
- iOS: `57x57`, `60x60`, `72x72`, `76x76`, `114x114`, `120x120`, `144x144`, `152x152`

### Additional configuration (Windows only)

Additional configuration can be added inside of `*.info` file of a theme. The following parameters available:

```ini
settings[msapplication][tile][TileColor] = #444
settings[msapplication][notification][cycle] = 1
settings[msapplication][notification][frequency] = 30
settings[msapplication][notification][polling-uri][src] = /rss.xml
settings[msapplication][notification][polling-uri<N>][src] = /path/to/rss.xml
```

All these settings are not required and can be ommited.
