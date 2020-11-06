# graphviz

*Erlang interface to the GraphViz graph visualisation tool*

[![Build Status][gh-actions-badge]][gh-actions]
[![LFE Versions][lfe-badge]][lfe]
[![Erlang Versions][erlang-badge]][versions]
[![Tag][github-tag-badge]][github-tag]

[![Project Logo][logo]][logo-large]

## Dependencies

This library utilises Erlang's `os:cmd` to call out to the GraphViz `dot`
exectuable. As such, use of this library requires that one first have GraphViz
installed on one's system.

## Usage

```erlang
graphviz:graph("G").
graphviz:add_edge("A", "B").
graphviz:add_edge("B", "C").
graphviz:add_edge("B", "D").
graphviz:to_file("test2.png", "png").
```

## Licence

Copyright © 2011, Grégoire Lejeune

Copyright © 2020, Duncan McGreggor


[//]: ---Named-Links---

[logo]: priv/images/graphviz-logo.png
[logo-large]: priv/images/graphviz-logo-thumb.png
[github]: https://github.com/lfex/graphviz
[gitlab]: https://gitlab.com/lfex/graphviz
[gh-actions-badge]: https://github.com/lfex/graphviz/workflows/ci%2Fcd/badge.svg
[gh-actions]: https://github.com/lfex/graphviz/actions
[lfe]: https://github.com/rvirding/lfe
[lfe-badge]: https://img.shields.io/badge/lfe-2.0-blue.svg
[erlang-badge]: https://img.shields.io/badge/erlang-19%20to%2023-blue.svg
[versions]: https://github.com/lfex/graphviz/blob/master/.github/workflows/cicd.yml
[github-tag]: https://github.com/lfex/graphviz/tags
[github-tag-badge]: https://img.shields.io/github/tag/lfex/graphviz.svg
[github-downloads]: https://img.shields.io/github/downloads/lfex/graphviz/total.svg
