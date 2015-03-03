Idris Empty Code Generator
--------------------------

This is an code non-generator for Idris. That is, it's a project which builds
an idris back end which doesn't actually do anything. You can use this as
a starting point for a real back end, by:

* Forking this repository (with a more descriptive name)
* Filling out `src/IRTS/CodegenEmpty.hs`, probably also renaming it
* Renaming the binary from `idris-emptycg` to something appropriate for
  your back end
* Putting any relevant run time support in `rts/`

