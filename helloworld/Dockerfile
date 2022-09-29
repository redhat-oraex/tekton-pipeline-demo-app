#iniciando pela imagem eap74-openjdk11-openshift-rhel8
FROM registry.redhat.io/jboss-eap-7/eap74-openjdk11-openshift-rhel8

#mudar para usuario root
USER root

#criando diretório para receber o copy do source da aplicação
RUN mkdir -p /opt/eap/standalone/deployments/

#copiando source da aplicação
COPY /target/helloworld.war /opt/eap/standalone/deployments/
