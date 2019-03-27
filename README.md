# sqlite-dialect
## Usage maven:
```
....
<repositories>
        <repository>
            <id>jitpack.io</id>
            <url>https://jitpack.io</url>
        </repository>
</repositories>
...
<dependencies>
    <dependency>
          <groupId>com.github.lemanoman</groupId>
          <artifactId>sqlite-dialect</artifactId>
          <version>1.0-SNAPSHOT</version>
    </dependency>
</dependencies
```

## Dialect package:

```org.lemanoman.sqllitedialect.SQLiteDialect```

## Spring application.properties example

```spring.jpa.properties.hibernate.dialect=org.lemanoman.sqllitedialect.SQLiteDialect```
