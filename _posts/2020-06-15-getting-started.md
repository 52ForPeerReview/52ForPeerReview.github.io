---
layout: post
title:  "Getting Started"
date:   2020-06-15 18:09:28 -0700
categories: introduction
---



Make a directory for organizing repositories from this Organization...


```bash
mkdir -vp ~/git/hub/52ForPeerReview
```


Use the [GitHub Pages Template][repository__template] to generate a new repository named after your Account name within this Organization, eg. _`52ForPeerReview/S0AndS0`_


Then clone your fork, the URL syntax is _`git@github.com:52ForPeerReview/<account>.git`_ eg...


```bash
cd ~/git/hub/52ForPeerReview

git clone --recurse-submodules git@github.com:52ForPeerReview/<account>.git
```


Run the `after-fork.sh` script to automatically edit various references to _`gh-pages-template`_ to your account name, eg...


```bash
# cd ~/git/hub/52ForPeerReview/<acount>
cd ~/git/hub/52ForPeerReview/S0AndS0

# ./after-fork.sh '<acount>'
./after-fork.sh 'S0AndS0'
```


The `after-fork.sh` script will edit the `_config.yml` file, specifically the `baseurl` property...


**`_config.yml` (snip)**


```yaml
title: 52 For Peer Review
description: >- # this means to ignore newlines until "baseurl:"
  Challenge to publish one project per weak for peer review for a whole year.
baseurl: "S0AndS0" # the subpath of your site, ie. your account name
```


Run the `re-init-submodules.sh` script...


```bash
./re-init-submodules.sh
```


... this will parse the `.gitmodules` file and re-initialize Git Submodules that where broken by GitHub's handling of Submodules within Template the repository.


Add a post under the `rounds/_r000` sub-directory describing what you have published each weak...


```bash
# ./add-post.sh '<title>' '<description>'
./add-post.sh '<title>' '<description>'
```


...following is a copy of the example post...


**`rounds/_r000/language-repository-name.md`**


{% raw %}
```markdown
---
layout: post
title: "<language> -- <repository-name>"
date: 2020-06-15 13:52:36 -0700
---


Published new project, [<repository-name>][repository__source] that does stuff...


{% highlight bash %}
git clone git@github.com:<organization>/<repository>.git
{% endhighlight %}


... describe what this project does, and how to utilize it.


Then describe any bits that:


- you believe could be improved
- you'd like help with
- and/or questions that arose during development
- etc...


[repository__source]: https://github.com/<org>/<repository>
```
{% endraw %}


Commit changes/additions, and push to GitHub...


```bash
cd ~/git/hub/52ForPeerReview/<account>

git add .

git commit -m 'Adds post about awesome new project'

git push origin gh-pages
```


Share a link to your new post with the `#52ForPeerReview` Hash-Tag on Twitter, or other social media outlets, and invite others to offer suggestions on how to improve. eg...


```tweet
Published a new awesome new #coding project that does something...

<link>

... Pull Requests and/or new Issues are very welcomed!

#52ForPeerReview
```



[repository__template]: https://github.com/52ForPeerReview/gh-pages-template/generate
