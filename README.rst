Flow
====

This is a django app extracted from the source of EasyDMP.

It stores the states and transitions of an FSA in a database, and was designed
to not rely on anything except Django.

Other apps needing the support of an FSA can add ForeignKeys or similar that
points to Node and Edge.
