SFZero
=====

SFZero is/was a player of SFZ and SF2 files, as an AU plugin.

If you're looking to use the SFZ/SF2 code, you should instead look at the
"SFZPlayer" directory of [sfzq](https://github.com/stevefolta/sfzq) -- it
supports a little more of the SFZ format, and has been freed from the clutches
of Juce.

Why the AmateurTools fork?
=====

Refx seemed to have a more recent fork, repairing an off 1 error
and I tried to compile it and it wouldn't because of a hash generator error.
I 'fixed' that and also the file browser was using a deprecated method
which I changed to a more up to date method. It compiles for me and works
so I thought I'd share it.

there's a bunch of issues to work out, i'm keeping up with it in case i
want to expand on it later. 
