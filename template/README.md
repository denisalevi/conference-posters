# Template folder for conference posters and abstracts
To add a new conference, follow these instructions:
1. Create a copy of this folder, naming it `<CONFERENCE>-<year>-<City>`.
2. Create new repositories for abstract and poster on GitHub.
3. Add those as submodules in the source folder of the conference folder,
   tracking the tip of the master branches.
```
git submodule add -b master <CONFERENCE>-<year>-<City>/source/[URL to Git repo]
```
4. If abstract or poster are created with Latex and should be shared with
   others, link the GitHub projects with Overleaf.
5. Add the final `poster.pdf` and `abstract.pdf` to the conference folder (e.g.
   `<CONFERENCE>-<year>-<City>/poster.pdf`).
6. Change this README file to name and link the conference.
