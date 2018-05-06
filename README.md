# Steam Authentication & Integration

A XenForo 1.x connected account provider and integration add-on
for Valve's Steam platform.

## Support the project

Want to contribute? If you've got the time and ability, code contributions are always welcome.
Feel free to submit a pull request on GitHub!

Want to help in other ways? I've got a [Patreon](https://www.patreon.com/Assadi) you can contribute to as well!

[![Orange Patreon logo](https://c5.patreon.com/external/logo/downloads_wordmark_white_on_coral.png)](https://www.patreon.com/Assadi)

## Compatibility notice

Steam Authentication & Integration 1.6.0+ only works with XenForo 1.5.0+.

## Features

* Authentication via Steam

* Statistics

* Notices

* Steam profiles

## Requirements

* BCMath

* [Steam API key](http://steamcommunity.com/dev/apikey)

* allow_url_fopen = 1 (usually enabled by default)

### Recommended

* cURL

## Upgrading from previous versions

### Versions below 1.5.0

1. Delete ```root/js/steam/```.

2. Upload the contents of the ```upload/``` folder to your XenForo directory.

3. Upgrade the add-on using the ```addon-Steam.xml``` file.

## Configuration and installation

If you wish to display the Steam banners, statistics tab or other features,
ensure you have given your users the correct permissions required to
view them.

You can set permissions in the users section of the XF admin control panel.

## Support

* Slack: [Join](https://join.slack.com/t/s70/shared_invite/enQtMzAyMjM4MTA2MjEwLTJkZTY5YTg4NWIyYzQ5YjJlZmYzMGJlN2Q3YTYwZTRmMjJmMmI3MTVhZDQwYTY0MzEwZDUyMDZjZmMxZmU2ZWQ)

* Telegram: https://t.me/Studio70

* Private Message: [Start a chat](https://xenforo.com/community/conversations/add?to=Assadi,^Alex)

* E-Mai: [Send a message](mailto:omar@assadi.co.il)


## Legal

This add-on is a fork of Michael Linback Jr.'s continuation of the Steam module by Morgan Humes.

Everything in this repository prior to commit 33d1b2b is licensed under
the GPL v3. However, all legally compatible changes starting from commit 33d1b2b are considered to be licensed under the AGPL v3.

You can find a [TL;DR version of the AGPL here](https://tldrlegal.com/license/gnu-affero-general-public-license-v3-(agpl-3.0)). You can read a full copy at
[legal/fork/LICENSE.txt](legal/fork/LICENSE.txt).
Additionally, the original GPL license files can be found in the [legal/original/](legal/original/) directory.

Essentially, the major difference between the GPL and the AGPL is that if
you make changes to AGPL code, you must make the changes publicly available
upon distribution of your software. The difference between the AGPL and GPL
in that regard is the meaning of distribution; the AGPL considers networked
usage of software to be distribution.

So, what this means for most of you is that when you make changes to AGPL
code, if it is running on your forum, you must contribute the changes
back.
