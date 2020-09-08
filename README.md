Ballerina String Utils Library
==============================

  [![Build](https://github.com/ballerina-platform/module-ballerina-stringutils/workflows/Build/badge.svg)](https://github.com/ballerina-platform/module-ballerina-stringutils/actions?query=workflow%3ABuild)
  [![Daily build](https://github.com/ballerina-platform/module-ballerina-stringutils/workflows/Daily%20build/badge.svg)](https://github.com/ballerina-platform/module-ballerina-stringutils/actions?query=workflow%3A%22Daily+build)
  [![GitHub Last Commit](https://img.shields.io/github/last-commit/ballerina-platform/module-ballerina-stringutils.svg)](https://github.com/ballerina-platform/module-ballerina-stringutils/commits/master)
  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This String utils library is one of the standard libraries of <a target="_blank" href="https://ballerina.io/">Ballerina</a> language.

For more information on all the functions supported by the `stringutils`, which includes the below mentioned functions, see [API Docs](https://ballerina.io/swan-lake/learn/api-docs/ballerina/stringutils/). 

Please note that these functions are different from what is provided by [lang.string] (https://ballerina.io/swan-lake/learn/api-docs/ballerina/lang.string/index.html) module.

1. `contains`
1. `equalsIgnoreCase`
1. `hashCode`
1. `lastIndexOf`
1. `matches`
1. `replace`
1. `replaceAll`
1. `replaceFirst`
1. `split`
1. `toBoolean`

For a quick sample on demonstrating the usage see [Ballerina By Example](https://ballerina.io/swan-lake/learn/by-example/).

## Building from the Source

1. To build the library:
        
        ./gradlew clean build

2. To debug:

        ./gradlew clean build -PdebugBallerina=<port>

3. To build the module without the tests:

        ./gradlew clean build -PskipBallerinaTests

## Contributing to Ballerina

As an open source project, Ballerina welcomes contributions from the community. To start contributing, read these [contribution guidelines](https://github.com/ballerina-platform/ballerina-lang/blob/master/CONTRIBUTING.md) for information on how you should go about contributing to our project.

Check the issue tracker for open issues that interest you. We look forward to receiving your contributions.

## Code of Conduct

All contributors are encouraged to read [Ballerina Code of Conduct](https://ballerina.io/code-of-conduct).

## Useful Links

* The ballerina-dev@googlegroups.com mailing list is for discussing code changes to the Ballerina project.
* Chat live with us on our [Slack channel](https://ballerina.io/community/slack/).
* Technical questions should be posted on Stack Overflow with the [#ballerina](https://stackoverflow.com/questions/tagged/ballerina) tag.
