# spring_learn_2
COGNIZANT DEEP SKILLING 
# Exercise 2 - Spring Core XML Configuration

## Objective
Configure a Spring bean using XML configuration and retrieve it using ApplicationContext.

## Technologies Used
- Java 21
- Spring Framework
- Maven
- VS Code

## Project Structure

src/main/java/com/cognizant/spring_core_xml/
└── SpringCoreXmlApplication.java

src/main/resources/
└── date-format.xml

## Bean Configuration

```xml
<bean id="dateFormat" class="java.text.SimpleDateFormat">
    <constructor-arg value="dd/MM/yyyy"/>
</bean>
```

## Output

```text
Parsed Date: Mon Dec 31 00:00:00 IST 2018
```

## Concepts Covered
- Spring Core
- XML Configuration
- Bean Management
- ApplicationContext
- Dependency Injection

## Author
Anzna
