# Drydock

**Everything you need to play Archipelago, in one place.**

Drydock is a one-stop companion app for the [Archipelago](https://archipelago.gg) multiworld
randomizer. Today, playing a world means checking a spreadsheet, hunting down a client, an
`.apworld`, and a PopTracker pack, putting each one in the right place, hand-editing a YAML, and
only then generating a seed. Drydock collapses that into one flow:

- **Discover** — browse the ~1000 worlds in development and see what each one offers.
- **Acquire** — fetch the game client, apworld, and PopTracker pack automatically.
- **Install** — put every component in the right place, every time.
- **Configure** — build a seed's options with a real UI instead of a text file.
- **Generate & play** — generate the multiworld and launch straight into the game.

## Status

Just getting started. Name and repo created; nothing built yet. This project is built in the
open — issues, ideas, and PRs are welcome as it takes shape.

## License

[MIT](LICENSE). Archipelago itself is MIT, so Drydock stays in the same permissive family as the
framework it manages.

PopTracker is GPL-3.0. Drydock downloads and launches PopTracker as a separate program rather
than linking against it, so that license does not extend to Drydock.
