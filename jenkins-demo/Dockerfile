FROM jenkins/jenkins:2.182

COPY plugins.txt /Users/mihai.urzica/jenkins/ref/plugins.txt
RUN /Users/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugins.txt

ENV JAVA_OPTS -Djenkins.install.runSetupWizard=false