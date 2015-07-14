---
layout: page
title: Blog
permalink: /blog/
---

#### 2015-07-14: New version available

* Fixed problem where users got stuck on a waiting page
* Added `otree runprodserver` command
* Made timeout work even if browser window is closed
* Implemented `Group.in_all_rounds()` and `Group.in_previous_rounds()`
* Fixed bug in MTurk payment
* Made time limit always display
* Cleaned up MTurk settings
* Several other MTurk fixes

To upgrade, open the launcher and click "Version select" and select the most recent version in the menu.
(Only works on launcher version 0.7.5 and above.)

Otherwise, modify the `otree-core` version number in `requirements_base.txt` (the
latest version is
[here](https://github.com/oTree-org/oTree/blob/master/requirements_base.txt)),
then run:

```
pip install -r requirements_base.txt
```

Thanks to the users who reported the above issues,
and to those who contributed translations to different languages!


#### 2015-06-11: New version available

There is a new version of otree-core with the following improvements/bugfixes:

* oTree localized to French, Spanish, and Russian (see [docs]({{ site.url_localization }}))
* Fixed bug with `group_by_arrival_time`
* Minor improvements and bugfixes


#### 2015-05-29: New version available

There is a new version of otree-core with the following improvements/bugfixes:

* Values in `session.vars` were sometimes not being saved
* Multi-field validation (`error_message`) was not properly displaying the error message to the user
* `get_players()` was sometimes returning players in the wrong order
* Better warning if database is not created
* Validate apps before publishing to MTurk
* Validation of min= and max= were not being done in Safari


#### 2015-05-11: Glossary: z-Tree to oTree

For those coming from a z-Tree background, we posted a "z-Tree to oTree" glossary [here]({{ site.url_ztree }}).

#### 2015-05-06: Tutorial posted

We created a [tutorial]({{ site.url_tutorial }}) showing how to create some simple games.