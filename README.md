# Luke's dmenu (with my patches)

Extra stuff added to vanilla dmenu:

- ~~reads Xresources (ergo pywal compatible)~~ I disabled it
- alpha patch, which importantly allows this build to be embedded in transparent st
- can view color characters like emoji (libxft-bgra is required for this reason)
- `-P` for password mode: hide user input
- `-r` to reject non-matching input
- dmenu options are mouse clickable
- (NEW) Centered in the screen (like rofi)
- (NEW) Border patch

## Installation

You must have `libxft-bgra` installed until the libxft upstream is fixed.

After making any config changes that you want, but `make`, `sudo make install` it.
