<h3>Technical problems that you encountered during installation of the software development environment and how you have solved them</h3>
<li>My computer is running on Windows, and thus I had some difficulties downloading SDKman, which I solved by not downloading SDKman. Instead, I downloaded Gradle following this installation guide: 'https://gradle.org/install/'.</li>

<h3>How you have validated (checked) that the software development environment is working</h3>
<li>I have tried building and running the project several times, validating that the software is working.</li>
<li>I have also tried pulling the software from the docker image available in dockerhub, and validated that it works as it should</li>

<h3>Technical problems and how you (tried to) solve them</h3>
<li>A problem which I encountered was after adding the ""io.javalin:javalin:5.6.2""-dependency to the build.gradle.kts file. At first the import in the App.java file did not compile, I tried to fix this by building from the terminal with "./gradlew.bat build", however, this did not help, eventually I figured out how to load gradle changes in intellij, which soved the problem.</li>
<li>I also struggled a bit with pushing my local image to dockerhub, because the instructions provided did not work, instead, I used the following commands: <p><b>"docker tag unit-converter thomasthunes/dat250:unit-converter"</b> and <p><b>"docker push thomasthunes/dat250:unit-converter"</b>, which solved my problems. </li>

<h3>Any pending issues with this assignment which you did not manage to solve.</h3>
<li><b>No</b></li> 

<h3>Please add the URL to your published container on DockerHub in the report.</h3>
<li>https://hub.docker.com/r/thomasthunes/dat250/tags</li>