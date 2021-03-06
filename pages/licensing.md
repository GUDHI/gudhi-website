---
layout: page
title: "The GUDHI License"
meta_title: "Licensing"
subheadline: ""
teaser: ""
permalink: "/licensing/"

---


The GUDHI library is a C++ library, with a Python interface (via Cython). It is available under a [MIT][1] license in order to ease the external contributions.
There are still [GPLv3][2] and [LGPL][3] dependencies for many modules.

### Third-party libraries license

Some of the GUDHI modules depend on third-party libraries that are under a [GPLv3][2] or a [LGPL][3] license ([CGAL][4], [Miniball][5], [PyKeOps][6]).
In the documentation "Copyright: MIT (GPL v3)" in the package list stands for exactly the situation described: GUDHI code is MIT, but there is a dependency on GPL code, so for practical purposes for a user it is as if this package was [GPLv3][2].

If you want to use a GUDHI package identified as "Copyright: MIT (GPL v3)" and [GPLv3][2]
does not fit your development requirements, do not hesitate to contact them for a commercial license.

The directory `ext/`, at the root of the source tree, contains a copy of some third-party libraries for convenience. They are not part of GUDHI and have their own license.

 [1]: https://opensource.org/
 [2]: http://www.gnu.org/copyleft/gpl.html
 [3]: http://www.gnu.org/copyleft/lgpl.html
 [4]: https://www.cgal.org/
 [5]: https://people.inf.ethz.ch/gaertner/subdir/software/miniball.html
 [6]: https://www.kernel-operations.io/keops/python/
