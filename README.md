# Streamdeck profiles

* `streamdeck-xl` - Profiles for the 32 button Stream Deck XL
  * `profiles`
    * `Traktor.streamDeckProfile` - Controls features of Traktor Pro that aren't covered by my S8 controller
    * `Traktor Remix Deck Slots 1-1 to 4-2.streamDeckProfile` - Controls features of Traktor Pro's Remix Decks that aren't covered by my S8 controller
  * `backups`
    * Backups generated using *Preferences > Backup All*
  * `icons`
    * `button-creator` - Button icons generated using [Button Creator for Stream Deck](https://apps.apple.com/us/app/button-creator-for-stream-deck/id1559303865?mt=12), which uses [SF Symbols](https://developer.apple.com/sf-symbols/) (macOS)
    * `sources` - Source files for button icons
  * `plugins` - Configuration files for Stream Deck plugins
    * `streamdeck-midi-plugin` - [StreamDeck Midi plugin](https://trevligaspel.se/streamdeck/midi/index.html)

## Notes

When Settings > Remix Decks > Auto Enable Deck Play on Sample Trigger = unchecked, selecting a deck slot on the S8 changes the waveform but the Advanced Panel on the Remix Deck does not reflect the settings of the clip in the selected slot.

The [streamdeck-clicker](https://github.com/dotherightthing/streamdeck-clicker) plugin automates mouse clicks on the 16 Remix Deck slots visible in the software, to ensure that the Advanced Panel on the Remix Deck exposes the per-slot controls and displays the settings relative to the clip in that slot.
