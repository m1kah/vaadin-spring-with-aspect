Vaadin with Spring integration
=========================

This is a simple example that shows how to @Autwire Spring beans with Vaadin
application.

Vaadin UI is @Configurable which is enabled with load-time weaving Spring
aspects. This means that servlet container must support load-time weaving.

For example, use Tomcat to run the example. Jetty does not support load-time
weaving. For more information see [Spring Reference: Environment specific configuration](http://docs.spring.io/spring/docs/current/spring-framework-reference/htmlsingle/#aop-aj-ltw-environments)
