FROM jenkins/jenkins:2.182

COPY plugins.txt /Users/Mihai/jenkins/ref/plugins.txt
RUN /usr/local/bin/install-plugins.sh < /Users/Mihai/jenkins/ref/plugins.txt

ENV JAVA_OPTS -Djenkins.install.runSetupWizard=false