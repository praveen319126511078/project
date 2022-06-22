From openjdk:11
COPY src/register/register.java
WORKDIR /temp
RUN ["javac","register.java"]
ENTRYPOINT ["java","register"]