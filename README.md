# Papiere

A modified version of Paper, without telemetry.

## Download

[Download the JAR here](https://nightly.link/charles19132/papiere/workflows/build/main/paperclip-jar.zip).

It will function exactly like a Paper JAR except that it won't have telemetry. Plugins can still have their own.

## Plugin compatibility

All plugins should work. As far as we know, the built-in bStats in Paper is simply used by Paper itself. Plugins can use their own bStats version.

### bStats.yml is present

This is almost certainly coming from a plugin. Check your plugin JARs for any files named "Metrics.class".

Also, copy the JAR file into a new server, accept the EULA, and run it. If the bStats.yml file is still present, please report it as a bug.

## Build

```sh
./clone-and-patch
cd Paper
# follow the official Paper build guide
```
