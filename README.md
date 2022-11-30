## Rest test

### How to reproduce:
* Create a Jmix-addon project.
* Add Jmix Rest
```groovy
api 'io.jmix.rest:jmix-rest-starter'
api 'io.jmix.security:jmix-security-oauth2-starter'
```
* Try to launch a test for which Spring will build an ApplicationContext. (RtTest#contextLoads)
* You will get a stacktrace, similar to PROJECT_ROOT/docs/stacktrace.txt