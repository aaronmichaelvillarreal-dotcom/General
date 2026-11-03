# Rocket Prospector

A side-scrolling jetpack runner for phones, built as a single HTML file with no dependencies besides Google Fonts.

You play a prospector with a copper jetpack, flying through an endless mine shaft.

## How to play

- **Hold** anywhere on the screen to fire the jetpack. **Let go** to fall. On a computer, use Space, the Up arrow or W.
- Collect **gold nuggets**. They're saved between flights and you spend them at the Outfitter.
- Avoid these hazards:
  - **Arc fences**: electric beams between two copper posts. Some stand still and some spin.
  - **Runaway drills**: a red warning appears at the right edge, follows your height, then locks on just before the drill fires.
  - **Steam blasts**: pipes on both edges hiss and charge, then fire a blast across the whole shaft. Stay in the gaps.
- Fly into the purple **? capsules** to get a power-up:
  - **Lamp Bubble**: a shield that blocks one hit.
  - **Lodestone**: pulls nearby gold to you for 12 seconds.
  - **Gravity Rig**: tap to flip between the floor and the ceiling. It soaks up one hit.
- The shaft speeds up the further you go. A red flag marks your best distance.

## Flyers and worlds

On the title screen or the game-over screen, tap **Flyer & world → Change** to choose who flies and where. The scene behind the menu updates as you pick.

Flyers (looks only, every flyer plays the same):
- **Dusty**: a prospector with a headlamp.
- **Rosa**: a pipe welder with goggles and a ponytail.
- **Bolt**: a robot with a searchlight eye.
- **Whiskers**: a cat pilot in a scarf.
- **Astra**: an astronaut.

Worlds:
- **Crystal Mine**: timber supports, lanterns and glowing crystals.
- **Lava Forge**: iron catwalks over molten rock, with rising embers.
- **Frozen Cavern**: icicles, snow and an aurora.
- **Sunset Canyon**: an outdoor desert with mesas, cacti and telegraph wires.
- **Sunken Reef**: underwater, with kelp, coral, fish and bubbles.
- **Surprise me**: a random world each flight.

Everything is free to pick and your choice is remembered.

## Outfitter

- Jetpack exhaust styles: Frostfire, Swamp Gas, Prism Plume and Gold Rush.
- Supplies for your next flight:
  - **Dynamite Dash**: a head start where nothing can hurt you.
  - **Spare Lamp Bubble**: start the flight with a shield.

Progress (best distance, gold, unlocks) is saved in the browser's local storage on that device.

## Running it

Open `index.html` in any modern mobile or desktop browser. To host it, serve the folder as static files. One option is GitHub Pages: in Settings → Pages, deploy from this branch, then open `/rocket-prospector/` on your phone. You can then use your browser's "Add to Home Screen" to launch it like an app.

The game plays best in landscape. Portrait works too, with a narrower view.
