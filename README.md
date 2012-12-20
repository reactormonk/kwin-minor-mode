kwin-minor-mode
===============

A minor mode to communicate with KWin. Type `M-x kwin-minor-mode` to
attach it to your javascript buffer. I don't recommend binding it to
`javascript-mode` by default, as this mode is very specific.

Bindings:

- `C-c C-r` to send a region
- `C-c C-l` to send the whole buffer

All output is redirected to the `Inf-KWin` buffer.
