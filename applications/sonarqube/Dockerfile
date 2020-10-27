FROM openEuler
COPY sonarqube-8.4.0.35506 /opt
RUN useradd sonar;echo "openEuler12#$"|passwd --stdin sonar \
    chmod -R 777 /opt/sonarqube-8.4.0.35506 \
    su - sonar -c "./opt/sonarqube-8.4.0.35506/bin/linux-x86-64/sonar.sh start"
