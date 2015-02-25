This is a fork of [ui-select2]().  It was forked so that a workaround
for flickering style issue can be added to v0.0.5.

This workaround comes from a
[Stackoverflow posting](http://stackoverflow.com/questions/24999108/angular-ui-select2-hide-initial-drawing-rendering-of-component).
It is applied to a branch created from v0.0.5 tag.  It is named
'[delayed_visibility](https://github.com/Bjond/ui-select2/tree/delayed_visibility)'.

The workaround is committed here: [51c241a Make visible after style is applied](https://github.com/Bjond/ui-select2/commit/51c241aa2599679e659c3785343be7a09e2bfd1d).

Ui-select2 is a deprecated library.  We should eventually replace it
with [ui-select](https://github.com/angular-ui/ui-select).  Until
then, we'll use ui-select2 v0.0.5 with this workaround added.

