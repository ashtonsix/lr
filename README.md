# lezer

Lezer ("reader" in Dutch, pronounced pretty much as laser) is an
incremental GLR parser intended for use in an editor or similar
system, which needs to keep a representation of the program current
during changes and in the face of syntax errors.

It prioritizes speed and compactness (both of parser table files and
of syntax tree) over having a highly usable parse tree—trees nodes are
just blobs with a start, end, tag, and set of child nodes, with no
further labeling of child nodes or extra metadata.

This project was hugely inspired by
[tree-sitter](http://tree-sitter.github.io/tree-sitter/).

The code is licensed under an MIT license.

Proper docs will follow when the system stabilizes.