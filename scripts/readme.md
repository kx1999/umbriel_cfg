place these scripts inside ~/.local/bin/ to make them available to shell

- `cycle-sink`: cycle the default audio sink, moving playing streams with it.
- `apply-discord-patch`: apply `patches/discord-voice.patch` to the local Discord Voice plugin and restart its bridge. Safe to re-run.
- `update-umbriel`: rebuild and install the patched Umbriel (`~/src/umbriel-middle-emu-pkg`), validate the config, then ask before logging out.
