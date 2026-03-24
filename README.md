# obs-switch-at-time
An OBS Browser Source that switches scenes at the given clock time

To use, add a browser source, and add the query parameter `t` with a 24-hour target time for the scene to switch.

Update `window.obsstudio.setCurrentScene` to the name of the scene to switch to.

The countdown timer uses `hh:mm:ss` format if the time is >1 hour in the future, else `mm:ss` format.

Currently uses the "Rubik" font available from Google Fonts, and with tabular numbers configured.

When changing the font, it is best to use a font that's either monospaced or uses tabular numbers to avoid layout shift.
