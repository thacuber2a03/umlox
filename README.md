# umlox
a Lox interpreter written in Umka

it's the bytecode interpreter (chapter 3), but some parts are planned to
be modified to be more high level (no Table struct, strings are Values and not Objs).
some other things will also be hard to make (like GCing, which, since Umka uses reference
counting, I'll have to make something up)

not yet done, current state is the one shown in "Local Variables" ("Hash Tables" was skipped and "Strings"
was skimmed through, but to make up for it there's a stub object.um file)
