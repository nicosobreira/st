# My build of st

st with a few patches added to it:

- Transparency
- Improved box drawing and glyph rendering
- External pipe
- Support for multiple fonts
- Wide glyph support
- Scroll back (with `ctrl+shift+j` and `ctrl+shift+k`)
- Ligature support

## Install

To install make sure that you have xlib and harfbuzz installed.

``` bash
git clone https://github.com/nicosobreira/st.git st
cd st
sudo make install
```

## Outro

Original [build](https://git.sr.ht/~bpv/st)
