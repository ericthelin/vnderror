* 2.0.0 (2014-02-26)
  * BC-breaking release, targeting version [e88d5cd1ad][] of the vnd.error specification
  * VndError is now simplified and extends Nocarrier\Hal for much of its functionality
  * Break: `VndError::__construct` now requires `$message` as its first parameter
  * Break: `VndError::addError` has been removed
  * Break: Removed the `Rhumsaa\VndError\Error` class
  * Break: Removed the renderer classes; Nocarrier\Hal handles this now
* 1.0.0 (2012-07-17)
  * Initial release, targeting version [1b9174148c][] of the vnd.error specification


[1b9174148c]: https://github.com/blongden/vnd.error/blob/1b9174148ca3164e0bc8888eef46def7527c3db1/README.md
[e88d5cd1ad]: https://github.com/blongden/vnd.error/blob/e88d5cd1ad467b653573471f0c859428bddaece8/README.md
