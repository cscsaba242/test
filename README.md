# test
./gradlew build
unset rvm_path
./gradlew clean basic:basic-01-basic-connector:build
java -jar basic/basic-01-basic-connector/build/libs/basic-connector.jar