## Spring

### Spring

- Spring是分层的 Java SE/EE应用 full-stack 轻量级开源框架，以 IoC（Inverse Of Control：反转控制）和
  AOP（Aspect Oriented Programming：面向切面编程）为内核。
  提供了展现层 SpringMVC和持久层 Spring JDBCTemplate以及业务层事务管理等众多的企业级应用技术，还能整
  合开源世界众多著名的第三方框架和类库，逐渐成为使用最多的Java EE 企业应用开源框架

### 优势

- 方便解耦，简化开发
- AOP 编程的支持
- 声明式事务的支持
- 方便程序的测试

### Spring快速入门

1. 程序开发步骤

   ①导入 Spring 开发的基本包坐标
   ②编写 Dao 接口和实现类
   ③创建 Spring 核心配置文件
   ④在 Spring 配置文件中配置 UserDaoImpl
   ⑤使用 Spring 的 API 获得 Bean 实例

2. 导入Spring开发的基本包坐标

   <properties>
       <spring.version>5.0.5.RELEASE</spring.version>
   </properties>
   <!--导入spring的context坐标，context依赖core、beans、expression-->
   <dependencies> 
       <dependency>  
           <groupId>org.springframework</groupId> 
           <artifactId>spring-context</artifactId> 
           <version>${spring.version}</version>
       </dependency>
   </dependencies>