# Tracy bindings for Zig

This repo contains bindings to tracy that I share across some of my projects.

The main file, `tracy.zig` was stolen by Zig's codebase.

You are free to use this module as you see fit, but if you're not using macOS you might need to patch the linking code. PRs are welcome.

Ideally this package should depend on another package, maybe hosted on allyourcodebase, that builds all of Tracy.
