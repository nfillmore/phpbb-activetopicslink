This extension simply adds a prominent "Active topics" link to phpBB's
prosilver template. I developed the extension using phpBB-3.1.3.

The extension is dead simple; it boils down to a single line in a single file.
The reason to use this extension instead of just editing the prosilver template
directly is that using an extension will make upgrades easier.

Here's what it looks like:

![Screenshot](https://github.com/nfillmore/phpbb-activetopicslink/raw/master/screenshot.png "Screenshot")

To install the extension:

* Copy this repo's `ext/nfillmore` subdirectory into the `ext` subdirectory of
  your phpBB installation.
* Go to the Administration Control Panel, then the Customise tab. Enable the
  extension "Add prominent 'Active topics' link".

To tweak the appearance of the link, edit
`ext/nfillmore/activetopicslink/styles/prosilver/template/event/overall_header_navigation_append.html`.
(You might then need to disable and re-enable the extension.)

The extension might work for other templates, after renaming the directory
`ext/nfillmore/activetopicslink/styles/prosilver` to
`ext/nfillmore/activetopicslink/styles/all`.
