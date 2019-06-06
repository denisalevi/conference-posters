# Conference posters
## 2019
### [Conference on Cognitive Computional Neuroscience (CCN)](https://ccneuro.org/2019/) in Barcelona
- Here is our [poster](CCN-2019-Barcelona/poster.pdf) and its [abstract](CCN-2019-Barcelona/abstract.pdf).


# Adding a new conference poster
1. Create a copy of the [template](template) folder, naming it `<CONFERENCE>-<year>-<City>`.
2. Create new repositories for abstract and poster on GitHub.
3. Add those as submodules in the source folder of the conference folder,
   tracking the tip of the master branches.
```
git submodule add -b master [URL to Git repo]
```
4. If abstract of poster are created with latex and should be shared with
   others, link the GitHub projects with Overleaf.
5. Add the final `poster.pdf` and `abstract.pdf` into the conference folder.
