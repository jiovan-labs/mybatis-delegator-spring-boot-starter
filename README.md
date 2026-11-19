# Mybatis Delegator Spring Boot Starter

Spring Boot application integrates `mybatis` quickly, to support several mybatis bean instances, typically with multiple `DataSource`.

## Quickstart

- Import dependencies

```xml
    <dependency>
        <groupId>com.jiovan.spring.starter</groupId>
        <artifactId>mybatis-delegator-spring-boot-starter</artifactId>
        <version>LATEST</version>
    </dependency>
```

> By default, this starter will auto take effect, you can turn it off by `jiovan.mybatis-delegator.enabled = false`

- Configure your beans with a `MybatisConfigurationDelegator` bean by constructor or `@Autowired`/`@Resource` annotation, then you can create beans with it as following:

| Method Return      | Method Name        |
|--------------------|--------------------|
| SqlSessionFactory  | sqlSessionFactory  |
| SqlSessionTemplate | sqlSessionTemplate |

## Document

- Github: https://github.com/jiovan-labs/mybatis-delegator-spring-boot-starter
- Mybatis homepage: https://mybatis.org/mybatis-3
- Mybatis github: https://github.com/mybatis/mybatis-3

## Requirement

- jdk 17+

## License

This project is under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

See the `NOTICE.txt` file for required notices and attributions.

## Donation

You like this package? Then [donate to us](https://jiovan.com/donation) to support the development.

## Copyright

Beijing Jiovan Technology Ltd.

## Website

- Jiovan: https://jiovan.com
