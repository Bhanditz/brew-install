Changelog
===========

* next on Feb 2, 2018
  * NEW -O - Java option aliases (append if multiple)
  * NEW -M - clojure.main option aliases (replace if multiple)
  * NEW -A - generic alias can combine any kind of alias and all are applied
  * FIX - if multiple alias switches supplied, they combine
  * FIX - whitespace in help fixed
* 1.9.0.315 on Jan 23, 2018
  * NEW -Stree to print dependency tree
  * NEW -Sdeps to supply a deps.edn on the command line as data
  * FIX bug with git deps using :deps/root writing File objects to libs files
* 1.9.0.309 on Jan 18, 2018
  * NEW -Spom emits dep exclusions and classifier
  * NEW pom file reader for local and git deps
  * FIX git deps now use :deps/root if specified
  * FIX major updates to improve transitive version selection
  * ENHANCE git version resolution uses stricter rules in comparison
  * ENHANCE dump stack on unexpected errors for debugging
* 1.9.0.302 on Jan 8, 2018
  * CHANGE git dep attributes (removed :rev, added :tag and :sha)
  * FIX Java 9 warning with -Spom
  * NEW -Sresolve-tags
* 1.9.0.297 on Jan 4, 2018
  * NEW git deps
  * NEW Updated -Spom to include repositories in the pom
* 1.9.0.273 on Dec 8, 2017
  * Initial release for 1.9