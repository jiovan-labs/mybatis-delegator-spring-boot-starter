[English](README.md) | [簡體中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md)

# Mybatis 代理 Spring Boot Starter

讓 Spring Boot 應用快速整合 `mybatis`，支援多個 mybatis Bean 例項，通常用於多 `DataSource` 場景。

## 快速開始

- 匯入相依性

```xml
    <dependency>
        <groupId>com.jiovan.spring.starter</groupId>
        <artifactId>mybatis-delegator-spring-boot-starter</artifactId>
        <version>LATEST</version>
    </dependency>
```

> 預設情況下，此 starter 會自動生效，你可以透過 `jiovan.mybatis-delegator.enabled = false` 關閉它。

- 透過建構函式或 `@Autowired`/`@Resource` 註解注入一個 `MybatisConfigurationDelegator` Bean，然後即可用它建立如下 Bean：

| 方法返回值 | 方法名 |
|--------------------|--------------------|
| SqlSessionFactory | sqlSessionFactory |
| SqlSessionTemplate | sqlSessionTemplate |

## 文件

- GitHub：https://github.com/jiovan-labs/mybatis-delegator-spring-boot-starter
- MyBatis 主頁：https://mybatis.org/mybatis-3
- MyBatis GitHub：https://github.com/mybatis/mybatis-3

## 環境要求

- jdk 17+

## 許可證

本專案採用 [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) 許可證。

請參閱 `NOTICE.txt` 檔案瞭解所需的宣告與歸屬資訊。

## 捐贈

喜歡這個工具包嗎？歡迎[向我們捐贈](https://jiovan.com/donation)以支援開發。

## 版權

北京玖漫科技有限公司

## 網站

- 玖漫：https://jiovan.com
