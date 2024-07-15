# Daisy

> [!CAUTION]\
> This keyboard is not yet finished, and is largely in the planning phase. If
> you see this message, this keyboard has not yet been tested and confirmed as
> working.

## What is this?

Daisy is a 32-key wireless split keyboard designed for the
[ZMK Firmware](https://zmk.dev) with the following features:

- Dedicated hardware push button to leverage ZMK's
  [soft-off](https://zmk.dev/docs/features/soft-off) feature.
- Kailh Choc switch footprint using standard spacing to support profiles like
  Chicago Steno.
- Supports splitkb's
  [tenting puck](https://splitkb.com/products/tenting-puck?_pos=1&_sid=8a1687bc7&_ss=r)
  with the footprint placed to support high angles using Z-tripods.
- JST connectors for the batteries.
- Dedicated hardware push button to reset the microcontroller.

### Motivations behind Daisy

This keyboard takes heavy inspiration from the
[Berylline](https://github.com/jcmkk3/trochilidae/tree/main/berylline) by
[jcmkk3](https://github.com/jcmkk3), and aims to solve a few pain points I had
with my personal use of the board.

- Using the [aptmak](https://github.com/Apsu/aptmak) keyboard layout,
  <kbd>E</kbd> is placed on the thumb. This feels amazing to use, but does
  result in losing a dedicated thumb key with <kbd>Shift</kbd>. The solution was
  to use a combo on the index and middle fingers for each side, but I found this
  to be a hindrance as my typing speed increased.

  Since moving back to my MacBook's keyboard, I remapped <kbd>Caps Lock</kbd> to
  <kbd>Escape</kbd> for [Helix](https://helix-editor.com), and found it
  incredibly comfortable — figuring this could work perfectly as
  <kbd>Shift</kbd> keys on the outer pinky column.
- Jumper caps are used to connect and disconnect the battery to the
  microcontroller, but I found these could be a bit fiddly when travelling each
  weekday, and I quickly grew frustrated. It could have just been the jumper
  caps I was using, but the tolerances felt inconsistent, which is where ZMK's
  soft-off feature really comes in handy.

Other than these minor points, I loved this keyboard. The boxy design and
component placement was beautiful, and the amount of splay and stagger felt just
right for me.

Another huge motivation was the release of a
[silent tactile Choc switch](https://lowprokb.ca/products/ambients-silent-choc-switches)
being on the horizon, and I really wanted a board to fill these with.
