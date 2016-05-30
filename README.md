# batch-template
Java Batch Template

## Create BUNDLE jar
```
mvn package
```
## Run
```
run-batch.bat 2016-05-30
```
### Example Output
```
[13:53:39.257 ICT] INFO  [main] com.company.app.MainApp.main() - [ BATCH START: Mon May 30 13:53:39 ICT 2016]
[13:53:39.276 ICT] DEBUG [main] com.company.app.MainApp.main() - args 1: 2016-05-30
[13:53:39.277 ICT] INFO  [main] com.company.app.module.ModuleService.sayHello() - Hello BAY
[13:53:39.277 ICT] INFO  [main] com.company.app.MainApp.main() - [   BATCH END: Mon May 30 13:53:39 ICT 2016]
EXIT CODE: 0
```

### Maven to Eclipse project
```
mvn eclipse:eclipse
```
