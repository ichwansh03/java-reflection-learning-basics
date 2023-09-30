## Java Apache Maven Notes

* Maven hampir sama tugasnya seperti Gradle, yakni build automation tools untuk management dependency, testing dan lain-lain.
* Untuk membuat project maven di IntelliJ IDEA, pilih new project lalu maven archetype. Atur catalog ke Maven Central, kemudian pilih archetype `maven-archetype-quickstart`. Jangan lupa sesuaikan versi java yg digunakan pada file pom.xml
* Tutorial video setup apache maven di ubuntu => ![set apache maven](https://www.youtube.com/watch?v=nLZyr7jWMYg)
* `mvn compile` digunakan untuk mengcompile source code pada direktori target
* `mvn clean` digunakan untuk menghapus hasil kompilasi di folder target.
* `mvn test` digunakan untuk running unit test
* `mvn package` digunakan untuk membuat file package ke .jar
* `java -jar target/nama_file-SNAPSHOT.jar` untuk running file jar
* 