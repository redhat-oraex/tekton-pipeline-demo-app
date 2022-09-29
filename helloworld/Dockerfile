#iniciando pela imagem eap74-openjdk11-openshift-rhel8
FROM registry.access.redhat.com/jboss-eap-7/eap74-openjdk11-openshift-rhel8

#definindo autoria do container
MAINTAINER "David S. Ferreira" "dferreira.academia@oraex.com.br"

#criando diretório para receber o copy do source da aplicação
RUN mkdir -p /opt/eap/standalone/deployments/

#copiando source da aplicação
COPY ROOT.war /opt/eap/standalone/deployments/
