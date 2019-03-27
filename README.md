# sqlite-dialect
## Usage maven:
Download the sqlite-dialect-0.1.jar, then run the command:

``` 
mvn install:install-file -Dfile=/pathtofile/sqlite-dialect-0.1.jar -DgroupId=org.lemanoman -DartifactId=sqlite-dialect -Dversion=0.1
```

Then add the dependency
...
<dependencies>
    <dependency>
          <groupId>org.lemanoman</groupId>
          <artifactId>sqlite-dialect</artifactId>
          <version>0.1</version>
    </dependency>
</dependencies>
```

## Dialect package:

```org.lemanoman.sqlite.dialect.SQLiteDialect```

## Spring application.properties example

```spring.jpa.properties.hibernate.dialect=org.lemanoman.sqlite.dialect.SQLiteDialect```
