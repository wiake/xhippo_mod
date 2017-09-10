# xhippo_mod
modified xhippo source and binary to use gtk2 and button icons and more

xhippo is a very resource-efficient versatile and extensible media player both in terms of its tiny download size and RAM usage. xhippo, in its original form, was first introduced to Puppy forum many years ago by forum member tempestuous, as far as I know. In its current form, the main binary was compiled on an early Puppy Slacko and the included backends and recording frontend created on DebianDog, where the overall system is used as a core media player/recording application.

More details including xhippo usage instructions can be found here:

http://www.murga-linux.com/puppy/viewtopic.php?p=842271#842271

Note that you can optionally use DoMyFile in conjunction with xhippo to create xhippo format streaming media playlists from the likes of Pmusic or Simple GTK radio playlists. A dotpet of DoMyFile is here:

http://www.murga-linux.com/puppy/viewtopic.php?t=94909

In practice, xhippo uses less system resources than any gtkdialog-based media player, so works nicely on low-powered systems, but is nice to have on any system in my opinion. Some reasons are provided below.

The attached xhippo dotpet contains a modified version of xhippo, a generic playlist manager program/process control program (source in C).

xhippo (with the included backends: xhplay, and xhrecord) can play all sorts of audio and video media (the playlist can contain a mix of audio and video types) and also record audio (mp3, wav, ogg, aac, and flac) via the included xhrecord (with xrecord gui frontend) assuming the appropriate commandline encoders are available. It can also save and load playlists, and play streaming media such as Internet radio streams.
