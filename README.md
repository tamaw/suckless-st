# st - simple terminal - custom patches

A simple terminal created by suckess.org with custom patches applied.

**Version:** [0.8.3](https://git.suckless.org/st/commit/43a395ae91f7d67ce694e65edeaa7bbc720dd027.html)

## Configuration

- SauceCodePro Nerd Font - main font
- JoyPixels - fallback font for more emojis
- Colours
  - #f4faff
  - #0f133c
  - #055cb9

## Installation

1. `git clone https://github.com/tamaw/suckless-st.git`
2. `make && make clean install`
3. `st` # to run

## Patches Applied

- [Alpha+Focus](https://st.suckless.org/patches/alpha_focus_highlight/) - focused and unfocused window opacity
- [W3M](https://st.suckless.org/patches/w3m/) - display images in the terminal e.g. w3mimgdisplay
- [font2](https://st.suckless.org/patches/font2/) - specify a fallback font
- [scrollback+scrollback-mouse+scrollback-alt](https://st.suckless.org/patches/scrollback/) - can
scrollback with the mouse and scrolls within content e.g. less
- [Ligatures](https://st.suckless.org/patches/ligatures/) - adds support for ligatures
- [sync+application-sync](https://st.suckless.org/patches/sync/) - better drawing to improve TUI apps

## Credit

suckless terminal https://st.suckless.org/

