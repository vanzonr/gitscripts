# gitscripts
A collection of bash scripts that may be useful when using git.

## git2swup

Shows the branches, the last commits and its data and any remote repos.
Optional arguments is the name of a (non-bare) repository.

## git2zip

Create a zip file with the content of the .git repository. Can be
useful when transferring repos when "git clone" is not an option
(e.g. online homework submission).

## zip2git

Unzip the file created by git2zip and checkout the material in it.
