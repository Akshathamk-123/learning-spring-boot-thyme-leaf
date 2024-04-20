# learning-spring-boot-thyme-leaf

First go to spring boot initializer
![image](https://github.com/Akshathamk-123/learning-spring-boot-thyme-leaf/assets/92522733/a0c26dfb-c421-4c87-b329-a2be8d8b6dc4)

Generate the folder and extract it into the folder required

learning-spring-boot-thyme-leaf\spring-boot-thyme-leaf-learning-demo\src\main\java\com\example\springbootthymeleaflearningdemo\SpringBootThymeLeafLearningDemoApplication.java
This is the relative path of the main java class

When you run this, you will come accross this error
![image](https://github.com/Akshathamk-123/learning-spring-boot-thyme-leaf/assets/92522733/a1e2e7be-f3af-4147-b732-56c4a818d1e3)

Go to application.properties in resources and configure the db

    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
    spring.datasource.url=jdbc: mysql://localhost:3306/beststore
    spring.datasource.username=root
    spring.datasource.password=Aks@2003
    spring.jpa. show-sql=true
    spring.jpa.hibernate.ddl-auto=update


