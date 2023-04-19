 Spring Framework 3.0 introduced this java config
# The Spring bean can created in two ways
      - ```Eager ``` (by default beans are eager initializer )
      - ```Lazy ```  (we can manullay specfy @Lazy(true) )
## Example :
-----
```
@Component
@Lazy(false) // Eager initialization (default behavior)
public class MyEagerBean {
    // ...
}

@Component
@Lazy(true) // Lazy initialization
public class MyLazyBean {
    // ...
}
```


# @Configuration
- ```To indicate that a class is a configuration class @Configuration is used to mark a Java class that provides one or more @Bean methods  ```
- 
