# iOS Library Sample App: TunneledWebRequest

## Configuring, Building, Running

The sample app requires some extra files and configuration before building.

### Get the framework.

1. Get the latest iOS release from the project's [Releases](https://github.com/Psiphon-Labs/psiphon-tunnel-core/releases) page.
2. Extract the archive. 
2. Copy `PsiphonTunnel.framework` into the `TunneledWebRequest` directory.

### Get the configuration.

1. Contact Psiphon Inc. to obtain configuration values to use in your app. 
   (This is requried to use the Psiphon network.)
2. Make a copy of `TunneledWebRequest/psiphon-config.json.stub`, 
   removing the `.stub` extension.
3. Edit `psiphon-config.json`. Remove the comments and fill in the values with 
   those received from Psiphon Inc. The `"ClientVersion"` value is up to you.

### Ready!

TunneledWebRequest should now compile and run.

## License

See the [LICENSE](../LICENSE) file.
