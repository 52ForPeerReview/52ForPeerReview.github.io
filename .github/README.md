# 52ForPeerReviewgithubio
[heading__top]:
  #52forpeerreviewgithubio
  "&#x2B06; Challenge to publish one project per weak for peer review for a whole year"


Challenge to publish one project per weak for peer review for a whole year


## [![Byte size of 52ForPeerReviewgithubio][badge__master__52forpeerreview.github.io__source_code]][52forpeerreview.github.io__master__source_code] [![Open Issues][badge__issues__52forpeerreview.github.io]][issues__52forpeerreview.github.io] [![Open Pull Requests][badge__pull_requests__52forpeerreview.github.io]][pull_requests__52forpeerreview.github.io] [![Latest commits][badge__commits__52forpeerreview.github.io__master]][commits__52forpeerreview.github.io__master] [![52ForPeerReview.github.io Demos][badge__gh_pages__52forpeerreview.github.io]][gh_pages__52forpeerreview.github.io]



------


- [:arrow_up: Top of Document][heading__top]

- [:building_construction: Requirements][heading__requirements]

- [:zap: Quick Start][heading__quick_start]

- [&#x1F9F0; Usage][heading__usage]

- [&#x1F5D2; Notes][heading__notes]

- [:card_index: Attribution][heading__attribution]

- [:balance_scale: Licensing][heading__license]


------



## Requirements
[heading__requirements]:
  #requirements
  "&#x1F3D7; Prerequisites and/or dependencies that this project needs to function properly"


This repository makes use of Git Submodules to track dependencies, to avoid incomplete downloads clone with the `--recurse-submodules` option...


```Bash
git clone --recurse-submodules git@github.com:52ForPeerReview/52ForPeerReview.github.io.git
```


To update tracked Git Submodules issue the following commands...


```Bash
git pull

git submodule update --init --merge --recursive
```


To force upgrade of Git Submodules...


```Bash
git submodule update --init --merge --recursive --remote
```


> Note, forcing and update of Git Submodule tracked dependencies may cause instabilities and/or merge conflicts; if however everything operates as expected after an update please consider submitting a Pull Request.


___


## Quick Start
[heading__quick_start]:
  #quick-start
  "&#9889; Perhaps as easy as one, 2.0,..."




## Usage
[heading__usage]:
  #usage
  "&#x1F9F0;"



___


## Notes
[heading__notes]:
  #notes
  "&#x1F5D2; Additional things to keep in mind when developing"


This repository may not be feature complete and/or fully functional, Pull Requests that add features or fix bugs are certainly welcomed.


- [Fork][52forpeerreview.github.io__fork_it] this repository to an account that you have write permissions for.

- Add remote for fork URL. The URL syntax is _`git@github.com:<NAME>/<REPO>.git`_...


```Bash
cd ~/git/hub/52ForPeerReview/52ForPeerReview.github.io

git remote add fork git@github.com:<NAME>/52ForPeerReview.github.io.git
```


- Commit your changes and push to your fork, eg. to fix an issue...


```Bash
cd ~/git/hub/52ForPeerReview/52ForPeerReview.github.io


git commit -F- <<'EOF'
:bug: Fixes #42 Issue


**Edits**


- `<SCRIPT-NAME>` script, fixes some bug reported in Issue #42
EOF


git push fork master
```


> Note, the `-u` option may be used to set `fork` as the default remote, eg. _`git push -u fork master`_ however, this will also default the `fork` remote for pulling from too! Meaning that pulling updates from `origin` must be done explicitly, eg. _`git pull orgin master`_


- Then on GitHub submit a Pull Request through the Web-UI, the URL syntax is _`https://github.com/<NAME>/<REPO>/pull/new/<BRANCH>`_


> Note; to decrease the chances of your Pull Request needing modifications before being accepted, please check the [dot-github](https://github.com/52ForPeerReview/.github) repository for detailed contributing guidelines.


___


## Attribution
[heading__attribution]:
  #attribution
  "&#x1F4C7; Resources that where helpful in building this project so far."


- [GitHub -- `github-utilities/make-readme`](https://github.com/github-utilities/make-readme)


___


## License
[heading__license]:
  #license
  "&#x2696; Legal side of Open Source"


```
Challenge to publish one project per weak for peer review for a whole year
Copyright (C) 2020 S0AndS0

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```


For further details review full length version of [AGPL-3.0][branch__current__license] License.



[branch__current__license]:
  /LICENSE
  "&#x2696; Full length version of AGPL-3.0 License"


[badge__commits__52forpeerreview.github.io__master]:
  https://img.shields.io/github/last-commit/52ForPeerReview/52ForPeerReview.github.io/master.svg

[commits__52forpeerreview.github.io__master]:
  https://github.com/52ForPeerReview/52ForPeerReview.github.io/commits/master
  "&#x1F4DD; History of changes on this branch"


[52forpeerreview.github.io__community]:
  https://github.com/52ForPeerReview/52ForPeerReview.github.io/community
  "&#x1F331; Dedicated to functioning code"

[52forpeerreview.github.io__gh_pages]:
  https://github.com/52ForPeerReview/52ForPeerReview.github.io/tree/
  "Source code examples hosted thanks to GitHub Pages!"

[badge__gh_pages__52forpeerreview.github.io]:
  https://img.shields.io/website/https/52ForPeerReview.github.io/52ForPeerReview.github.io/index.html.svg?down_color=darkorange&down_message=Offline&label=Demo&logo=Demo%20Site&up_color=success&up_message=Online

[gh_pages__52forpeerreview.github.io]:
  https://52ForPeerReview.github.io/52ForPeerReview.github.io/index.html
  "&#x1F52C; Check the example collection tests"

[issues__52forpeerreview.github.io]:
  https://github.com/52ForPeerReview/52ForPeerReview.github.io/issues
  "&#x2622; Search for and _bump_ existing issues or open new issues for project maintainer to address."

[52forpeerreview.github.io__fork_it]:
  https://github.com/52ForPeerReview/52ForPeerReview.github.io/
  "&#x1F531; Fork it!"

[pull_requests__52forpeerreview.github.io]:
  https://github.com/52ForPeerReview/52ForPeerReview.github.io/pulls
  "&#x1F3D7; Pull Request friendly, though please check the Community guidelines"

[52forpeerreview.github.io__master__source_code]:
  https://github.com/52ForPeerReview/52ForPeerReview.github.io/
  "&#x2328; Project source!"

[badge__issues__52forpeerreview.github.io]:
  https://img.shields.io/github/issues/52ForPeerReview/52ForPeerReview.github.io.svg

[badge__pull_requests__52forpeerreview.github.io]:
  https://img.shields.io/github/issues-pr/52ForPeerReview/52ForPeerReview.github.io.svg

[badge__master__52forpeerreview.github.io__source_code]:
  https://img.shields.io/github/repo-size/52ForPeerReview/52ForPeerReview.github.io

[jekyllrb__home]:
  https://jekyllrb.com/
  "Home page for Jekyll documentation"

[jekyll_admin__source]:
  https://github.com/S0AndS0/Jekyll_Admin
  "Scripts for setting-up local/private Jekyll build environment"
