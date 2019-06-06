Add source folders `abstract` and `poster` here. If a separate latex project
was used to create these (e.g. on Overleaf), add a submodule. Else just add the
source files in a folder. If the source files should stay private, create a
private repository, tracked it as submodule.

To add e.g. a repository as submodule, tracking its master branch, use:
```
submodule add -b master <URL to git repo containing the abstract> abstract
```
