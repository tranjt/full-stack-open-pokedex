## Dart

### Lint
A common use for the dart language is in Flutter for native mobile apps. Usage of Lint here via a yaml configuration file. Developer of Flutter have a premade rules file you can download from https://github.com/flutter/flutter/blob/master/analysis_options .yaml Usage instruction are to drop the file into the root of the project and the IDE should automatically take care of the rest.

### Test

Testing in Flutter is done via the test or flutter_test dependency. The process requires you to create a test file and a class to test. Then write a test, you can group multiple tests in a group. After that you run the test.

### Build 
Enter the directory of the app you want to build and run flutter build appbundle for dart used in flutter.

## CI alternative
CircleCI is an alternative to Jenkins and GitHub Actions. 

## self-hosted or a cloud-based environment
A lot of factor plays into the decisions but I think cost is the most important. Of course there might be some case where cost has less impact, when time is a bigger important factor that yields more profit in the end. For smaller team self-host might not be ideal because of the overhead cost and you might need staff to upkeep. While larger companies with more staff and self-host would payoff in the end in terms of cost.