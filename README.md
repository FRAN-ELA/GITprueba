# GITprueba

git remote rm origin
As for the filter-branch question - just add --prune-empty to your filter branch command and it'll remove any revision that doesn't actually contain any changes in your resulting repo:

git filter-branch --prune-empty --subdirectory-filter path/to/subtree HEAD
