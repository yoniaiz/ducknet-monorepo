# The ducknet monorepo

we have here a pointers to all the submodules
ducknet and ducknet-cms

when cloning/pulling/pushing we need to add
a flag --recurse-submodules to let git know
that we want to update also the submodules in the project.

if you cloned the project without the flag
you can run command git submodule update --init
to update all submodules.
