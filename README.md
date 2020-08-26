# javascript-query-pack
JavaScript Query Pack for GitHub Advanced Security Code Scanning

### [More on QL Packs](https://help.semmle.com/codeql/codeql-cli/reference/qlpack-overview.html)

QL packs are used to organize the fioles used in the CodeQL analysis.

The [CodeQL repository](https://github.com/github/codeql) contains QL packs for C/C++, C#, Java, JavaScript, and Python. The CodeQL for Go repository contains a QL pack for Go analysis. You can also make custom QL packs to contain your own queries and libraries.

### QL Pack Structure
A QL pack must contain a file called `qlpack.yml` in its root directory. The other files and directories within the pack should be logically organized. For example, typically:

* Queries are organized into directories for specific categories.
* Queries for specific products, libraries, and frameworks are organized into their own top-level directories.
* There is a top-level directory named <owner>/<language> for query library (.qll) files. Within this directory, .qll files should be organized into subdirectories for specific categories.
  
