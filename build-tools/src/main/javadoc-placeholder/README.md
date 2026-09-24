# com.loudsight:build-tools

This module carries only shared static-analysis rule resources (PMD rulesets, SpotBugs exclude
filters) consumed off the plugin classpath by `com.loudsight:parent`'s `maven-pmd-plugin` and
`spotbugs-maven-plugin` configuration. It has no compiled Java API, so there is no real Javadoc to
generate — this jar is a placeholder to satisfy Maven Central's javadoc-jar requirement for
jar-packaging artifacts.

For the project itself, see https://github.com/loudsight/parent and https://loudsight.com/.
