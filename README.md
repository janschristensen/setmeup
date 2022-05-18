# setmeup

## Test
Run jenkins locally with command 
```
mvn hpi:run
```

Find Sample here
```
http://localhost:8080/jenkins/configure
```
look for section below called "Bankdata configurator"

## How it work
When push save, plugin code runs and updates cloud.

## Todo
Should have been with a separate button, and only run changes on buttonpush. You can find howto change to a button in
https://github.com/jenkinsci/kubernetes-plugin.git

Search for "doTestConnection". It involves as I can tell fixing the *.jelly file
and implementing action class.

## Links
Code made from this guide, and only works with maven, but a lot quicker to test.
* https://www.jenkins.io/doc/developer/tutorial/run/

