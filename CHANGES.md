# Changes since last version

## Introduced in version 1.0.5

* Explicitly start with "/usr/bin/env python3" instead of "/usr/bin/env python". Hoping that will
  help users that have not yet migrated to v3.
* Added v3 requirement in setup.py as well, using advice from Tobias Jakobi. Solves issue #1 on github.com.


## v1.1.0

* Implemented format guessing. By default, `alv` tries to identify the alignment format. You can still override if there are parsing problems.
* You can specify what part of accessions to view with -as. This way you can avoid common prefixes and easily shorten long accessions.
* View only the first and last N characters of accessions with option -aa.