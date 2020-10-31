How to set up in AntiX Linux (most popular distro for [old computers](https://distrowatch.com/search.php?category=Old+Computers)):

1. [Menu -> Control Centre -> Desktop tab -> Edit IceWM Settings -> startup](https://www.reddit.com/r/linuxquestions/comments/2vaf3y/keyboard_layouts_antix_linux/)

2. Add this [line](https://wiki.archlinux.org/index.php/Xorg/Keyboard_configuration#Configuring_compose_key):
`setxkbmap -option compose:menu`

## Key sequences ([Monniaux](https://cgit.freedesktop.org/xorg/lib/libX11/plain/nls/en_US.UTF-8/Compose.pre))

Hungarian
Result | Press 'compose' and
-------|--------------------
acute `ó` | `'` `o`
double acute `ő` | `=` `o`
diaeresis `ö` | `"` `o`

General
Result | Press 'compose' and
-------|--------------------
em dash `—` | `-` `-` `-`
arrow `→` | `-` `>`
guillemot `«` | `<` `<`
circled `⑫ ` | `(` `1` `2` `)`
section `§` | `s` `o`
ellipsis `…` | `.` `.`
heart `♥` | `<` `3`
eighth note `♪` | `#` `e`
smile `☺` | `:` `)`
frown `☹` | `:` `(`
multiply `×` | `x` `x`
divide `÷` | `:` `-`
super `²` | `^` `2`

For subscript, only numbers seem supported (→ html `<sub>i</sub>`).
