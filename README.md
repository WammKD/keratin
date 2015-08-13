keratin is a fork of clipmenu, a simple clipboard manager using [dmenu][] and [xsel][]/[xclip][].

To use it, start the `keratin-d` daemon by calling `keratin -d` and then call `keratin` to launch
`dmenu`. Upon choosing an entry, it is copied to the clipboard. Entries can also be deleted via the
command `keratin -D`.

Some of the flags for customizing dmenu (-fn, -nb, -nf, -sb, -sf) are available to use with keratin.
You invoke them in the same way you would with dmenu (e.g. `keratin -nb '#000000' -nf '#FFFFFF'`).

[dmenu]: http://tools.suckless.org/dmenu/
[xsel]: http://www.vergenet.net/~conrad/software/xsel/
[xclip]: http://sourceforge.net/projects/xclip/
