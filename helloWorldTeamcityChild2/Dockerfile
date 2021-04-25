FROM openjdk:8
COPY src helloWorldTeamcity/helloWorldTeamcityChild2
WORKDIR helloWorldTeamcity/helloWorldTeamcityChild2
RUN mkdir -p bin
RUN javac -d bin ./main/java/HelloWorldChild2.java
WORKDIR bin
CMD ["java","HelloWorldChild2"]