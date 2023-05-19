FROM openjdk:11
ADD target/StockPricesApp-0.0.1-SNAPSHOT.jar StockPricesApp.jar
ENTRYPOINT ["java", "-jar", "StockPricesApp.jar"]
EXPOSE 9999
ENV spring.datasource.url=jdbc:mysql://databaserds.c4rchtkxwvqe.ap-south-1.rds.amazonaws.com:3306/databaseRDS
ENV spring.datasource.username=root
ENV spring.datasource.password=root1234
