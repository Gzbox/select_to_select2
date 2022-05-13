# Fork form [sf-cola/select_to_select2](https://github.com/sf-cola/select_to_select2)

## Select To Select2 Plugin

This is a repository of 「Select To Select2 Plugin」 which is a Redmine plugin.

## Description of this warehouse

- Upgrade the select2 from `3.4.5` to `3.4.6`.
- Fix incompatible `redmine 4.2.3`.
- Optimize the multi-selection state switching, the problem that the interface is not refreshed in time.
- Fix the problem that the content of the select option will exceed the visible area of the screen when it is too long.
- Self-test `redmine 4.2.3` operates normally. Other versions are not tested.

## Features

Replace all select tag to select2 in all Redmine's Pages.

![2017-10-09 21 50 40](https://user-images.githubusercontent.com/12267699/31339056-998c52f0-ad3c-11e7-88ea-bc7acf8cdf96.png)

## Installation

1.`git clone https://github.com/Gzbox/select_to_select2`

2.Copy to `apps/redmine/plugins`

3.`bundle exec rake redmine:plugins:migrate NAME=select_to_select2 RAILS_ENV=production`
