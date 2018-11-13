launch Web Sercie
./gradlew bootRun 
browse to http://localhost:8080/greeting and http://localhost:8080/greeting?name=wansk

Test for API
./gradlew test --tests "name.wansk.springbootdemo.e2e.*"
Test for Controller intergration
./gradlew test --tests "name.wansk.springbootdemo.integration.*"
Test for Controller unit
./gradlew test --tests "name.huhao.springbootdemo.unit.*"
