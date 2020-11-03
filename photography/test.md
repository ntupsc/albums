---
layout: gallery
title: A Very Basic Example
no_menu_item: true # required only for this example website because of menu construction
support: [jquery, gallery]
---

This is an example gallery. All images licensed under [CC-BY-NC-SA license][license]. Check the [Git Repo][repo] for a copy of this license.

{% include gallery-layout.html gallery=site.data.galleries.test %}

[license]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[repo]: https://github.com/ntupsc/albums
