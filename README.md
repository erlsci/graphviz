# graphviz

*Erlang interface to the GraphViz graph visuzlization tool*

[![Project Logo][logo]][logo-large]

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


[//]: ---Named-Links---

[logo]: priv/images/graphviz-logo.png
[logo-large]: priv/images/graphviz-logo-thumb.png
