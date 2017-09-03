FROM maven:3.3.9-jdk-8

ENV api_name user-api

RUN echo "==> Running: " ${api_name} 
CMD java -jar -Dspring.profiles.active=dev /opt/target/${api_name}.jar

EXPOSE 8090
