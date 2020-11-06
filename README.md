# graphviz

Erlang interface to the GraphViz graph visuzlization tool

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

