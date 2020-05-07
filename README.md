# codenarc-cli
Conveniently run [Codenarc](https://codenarc.github.io/CodeNarc/) from the command-line.

### Prequisites

* [Groovy](http://groovy-lang.org/install.html)

### Install

1) [Download the codenarc-cli zip](https://github.com/dansomething/codenarc-cli/archive/master.zip)
2) Unzip codenarc-cli-master.zip

### Example

    # Display the command-line help
    /path/to/unzipped/codenarc-cli/codenarc -help

    # Analyze the current directory using the rules configured in `.codenarcrc`
    /path/to/unzipped/codenarc-cli/codenarc -basedir=. -rulesetfiles=file:.codenarcrc -report=console

### Platforms

Only tested on MacOS

### Links

* [CodeNarc Command-Line Parameters](https://codenarc.github.io/CodeNarc/codenarc-command-line.html)
* [CodeNarc Starter RuleSet](https://codenarc.github.io/CodeNarc/StarterRuleSet-AllRulesByCategory.groovy.txt)
