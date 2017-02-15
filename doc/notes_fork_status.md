# Fork status notes

> This fork have been made on the *no-longer maintained* sourceforge [CVS PHP/Java bridge repository](https://sourceforge.net/p/php-java-bridge/code/) and
> is based on the latest official release (6.2.1) excluding all previous versions and history (cleanup from the CVS repo).

## Status

Latest version 6.2.1 has been released long ago but, AFAIK, proved stable and mature. Here are some plans and statuses of the fork:  

- [x] Migration from sourceforge CVS to github.
- [x] Support for PHP7 and rewrite of the client `Java.inc`, see [soluble-japha](https://github.com/belgattitude/soluble-japha)
- [x] Gradle support for project builds.
- [x] Ensure support of Tomcat 8+, JDK 8.
- [x] Prepare a starter project to customize builds, see [pjb-starter-springboot](https://github.com/belgattitude/pjb-starter-springboot).
- [x] Update namespace to `io.soluble.pjb` and host [Java API doc](http://docs.soluble.io/php-java-bridge/api)
- [x] License to Apache 2.0 and drop GPL code, see [#10](https://github.com/belgattitude/php-java-bridge/issues/10)
- [x] Artifact published and available on maven central. 
- [x] Port and convert most of `./test.php5` in [soluble-japha](https://github.com/belgattitude/soluble-japha).
- [x] Travis CI support with soluble-japha client suite [tests](https://github.com/belgattitude/php-java-bridge/blob/master/.travis/run_soluble_japha_phpunit_tests.sh)
- [x] Clean-up of obsolete code and unused resources.
- [x] Releases starting at 6.2.10 
- [ ] Deprecate and remove completely the `Java.inc` client.
- [ ] Security review and safe practices.
- [ ] Documentation (always a wip)

## Changelog

Changes are documented in the [CHANGELOG.md](https://github.com/belgattitude/php-java-bridge/blob/master/CHANGELOG.md) file.
 
For a complete list of changes from the original 6.2.1 version see the [CHANGESET](https://github.com/belgattitude/php-java-bridge/compare/Original-6.2.1...master).

## Original version

A copy of the original 6.2.1 release is available on a [separate branch](https://github.com/belgattitude/php-java-bridge/tree/Original-6.2.1). All new changes are currently made on the master branch, releases starting at 6.2.10.

## Legacy resources

Most of the original resources have been dropped, some exceptions are still present in the `./doc/legacy` folder and
will be progressively removed.

## Credits to the original developers

As stated on the sourceforge page

- Jost Boekemeier
- Andre Felipe Machado 
- Sam Ruby 
- Kai Londenberg 
- Nandika Jayawardana 
- Sanka Samaranayake 
