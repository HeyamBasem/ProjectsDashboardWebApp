FROM openjdk:16
RUN mkdir -p /webapp
COPY ./target/ProjectDashboardtest2-1.0-SNAPSHOT.war /webapp
WORKDIR /webapp
RUN mv *.war webapp.war
ENTRYPOINT ["java","-war","webapp.war"]
