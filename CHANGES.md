# Change Log

* Unreleased

* 0.3.2
    * Improve handling when custom buildDir is used

* 0.3.1
    * Fix extension support for configuring encoding
    * Make default encoding UTF-8

* 0.3.0
    * IntelliJ: register generated source directories even if they don't already exist.
    * Add avro-base plugin, which exposes tasks and the extension without creating tasks, defaults, etc.

* 0.2.0
    * Build against Gradle 1.12
    * Compile using Avro 1.7.6
    * Support for qualified plugin ID
    * Deprecate unqualified plugin ID

* 0.1.3
    * Always regenerate all Java classes when any schema file changes to avoid some classes having outdated schema information.

* 0.1.2
    * Eliminate dependency on guava, make dependency on commons-io explicit

* 0.1.1
    * Fixed NullPointerException when performing clean builds

* 0.1.0
    * Add support for converting IDL files to JSON protocol declaration files
    * Add support for generating Java classes from JSON protocol declaration files
    * Add support for generating Java classes from JSON schema declaration files
    * Add support for inter-dependent JSON schema declaration files
    * Add support for tweaking source/exclude directories in IntelliJ
    * Add support for specifying the string type to use in generated classes
