# codenarc-cli
codenarc-cli


```bash
java -classpath "lib/CodeNarc-1.5.jar:%GROOVY_HOME%/groovy-3.0.3.jar:%GROOVY_HOME%/groovy-templates-3.0.3.jar:%GROOVY_HOME%/groovy-xml-3.0.3.jar:%GROOVY_HOME%/groovy-json-3.0.3.jar:lib/slf4j-api-1.7.9.jar:lib/log4j-slf4j-impl-2.13.0.jar:lib/log4j-api-2.13.0.jar:lib/log4j-core-2.13.0.jar:lib/GMetrics-0.7.jar:lib/*" org.codenarc.CodeNarc -basedir="path/to/my/files" -files="**/*.groovy,**/Jenkinsfile,**/*.gradle" -title="MyCodeNarcReport" -maxPriority1Violations=0 -report=xml:"/tmp/ReportTestCodenarc.xml"
```

```bash
~/Documents/gitContent/pollochang/codenarc-cli/bin/codenarc -rulesetfiles="file:./codenarc-rules.groovy"
```