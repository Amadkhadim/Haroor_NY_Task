# Haroor NY Task

A simple app to hit the NY Times Most Popular Articles API and show a list of articles, that shows details when items on the list are tapped (a typical master/detail app). 
<br>
App is built with MVVM architecture using Hilt, Retrofit, Coroutines, LiveData, RoomDatabase, Database Debugging, DataBinding.

<br>

<br>

## The app has following packages:
1. **data**: It contains all the data accessing, repositories and manipulating components.
2. **di**: Dependency providing classes using Hilt.
3. **model**: It contains data classes and or models.
4. **ui**: View classes along with their corresponding ViewModels.
5. **utils**: Utility classes.

<br>

## Run below command for test cases and coverage report in teminal.

./gradlew createDebugCoverageReport

