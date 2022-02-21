### Imports must be ordered in lexicographic order without any empty lines in-between with "java", "javax", "kotlin" and aliases in the end

>Problem: you get above error when run this command: gradle build

```
1- create .editorconfig on the project root

2- put below codes on it

[*.{kt,kts}]
disabled_rules = import-ordering

```
