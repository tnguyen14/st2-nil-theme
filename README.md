Nil Theme
------------------------------------------------------------------------

![Nil theme](https://github.com/tnguyen14/st2-nil-theme/raw/master/dark.png)
_Nil UI theme for Sublime Text 2_

This theme is a fork from [nilium/st2-nil-theme](https://github.com/nilium/st2-nil-theme), with some changes in color schemes that makes more sense to me.

This customized color scheme only supports the dark version, `Nil.sublime-theme`


Installation
------------------------------------------------------------------------


#### Installation via Git

You can download or clone the repository into your Sublime Text 2
`Packages` directory. To do this, simply navigate to
`~/Library/Application Support/Sublime Text 2/Packages` (or wherever it
is on your particular operating system) and run the following command:

	git clone git://github.com/tnguyen14/st2-nil-theme.git 'Theme - Nil'

It's **very important** you clone the repository into the `Theme - Nil`
directory otherwise the theme won't locate its assets and will take on
an eldritch appearance. You don't want [Shub-Niggurath][shubby] crawling
out of your screen, so remember, put it in the right directory.

[shubby]: http://en.wikipedia.org/wiki/Shub-Niggurath


#### Manually Downloading

If you choose to download an archive of this repo from GitHub, you must
rename the extracted folder to `Theme - Nil` and put it in your
`Packages` directory.  That's it -- simple.


Activating
------------------------------------------------------------------------

In your `Settings - User` file (hit ⌘, on Mac OS to open it), set the
`"theme"` key to `"Nil.sublime-theme"`, like
so:

    {
        "theme": "Nil.sublime-theme"
    }


Assuming you have then installed it correctly, it should show the theme.
Due to what I assume is settings from previous themes surviving, you may
wish to restart Sublime Text 2 as well, but otherwise you should be good
to go.
