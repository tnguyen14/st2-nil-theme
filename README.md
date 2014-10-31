Nil Theme
------------------------------------------------------------------------

![Nil theme](https://github.com/tnguyen14/st2-nil-theme/raw/master/dark.png)
_Nil UI theme for Sublime Text 2_

This theme is a fork from [nilium/st2-nil-theme](https://github.com/nilium/st2-nil-theme), with some changes in color schemes that makes more sense to me.

This customized color scheme only supports the dark version, `Nil.sublime-theme`

Styles
------------------------------------------------------------------------

### Colors
The main colors used in this theme are:
- **Sun** (dark orange): `#f38630` or `rgb(243, 134, 48)`
- **Chardonnay** (light orange): `#ffc887` or `rgb(255, 200, 135)`

#### Indentation guide
In order to draw indentation guides, add the following to User Preferences (`⌘,`)
```json
{
	"indent_guide_options": ["draw_normal", "draw_active"]
}
```

Then add the following in the color scheme, under `settings/settings`
```xml
<key>guide</key>
<string>#555555</string>
<key>activeGuide</key>
<string>#FFC887</string>
<key>stackGuide</key>
<string>#734017</string>
```

#### Brackets
Add the following in the color scheme to update bracket color
```xml
<key>bracketsForeground</key>
<string>#F38630</string>
<key>bracketsOptions</key>
<string>underline</string>
<key>bracketContentsForeground</key>
<string>#FFC887</string>
<key>bracketContentsOptions</key>
<string>underline</string>
```

Installation
------------------------------------------------------------------------


#### Installation via Git
You can download or clone the repository into your Sublime Text 2
`Packages` directory. To do this, simply navigate to
`~/Library/Application Support/Sublime Text 2/Packages` (or wherever it
is on your particular operating system) and run the following command:
```sh
$ git clone git://github.com/tnguyen14/st2-nil-theme.git 'Theme - Nil'
```

#### Manually Downloading
If you choose to download an archive of this repo from GitHub, you must
rename the extracted folder to `Theme - Nil` and put it in your
`Packages` directory.  That's it -- simple.

Activating
------------------------------------------------------------------------

In your User Preferences (`⌘,`), set:
```json
{
	"theme": "Nil.sublime-theme"
}
```
