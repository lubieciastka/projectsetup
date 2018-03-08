# Basic Frontend Project Config Setup

## lint:css

## lint:js

## lint:wcag

## precommit hooks

```
touch .git/hooks/pre-commit
vim .git/hooks/pre-commit

```
Tresc pliku pre-commit:

```
#!/bin/bash
./node_modules/pre-commit/hook
RESULT=$?
[ $RESULT -ne 0 ] && exit 1
exit 0
```
