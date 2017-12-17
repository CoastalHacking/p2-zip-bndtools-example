
# p2 Zipped Repositories Example

This example bndtools workspace + project does the following:

* Downloads a zipped p2 repository
* Verifies the repository's MD5 signature
* Unzips the repository and refreshes the "Emf" repository configured in [build.bnd](build.bnd).
* Optionally delete the downloaded files

See [build.gradle](build.gradle) for details.

## Improvements

* Use a map / properties to contain the necessary information for downloading, etc., and then use that map in the tasks
