FROM sonarqube:4.5.6

MAINTAINER Istvan Palocz <istvan@palocz.hu>

ENV $SONAR_PLUGIN_HOME $SONAR_HOME/extensions/plugins

RUN set -x \
	&& curl -o $SONAR_PLUGIN_HOME/sonar-php-plugin-2.7.jar -fSL http://sonarsource.bintray.com/Distribution/sonar-php-plugin/sonar-php-plugin-2.7.jar \
	&& curl -o $SONAR_PLUGIN_HOME/sonar-javascript-plugin-2.8.jar -fSL https://sonarsource.bintray.com/Distribution/sonar-javascript-plugin/sonar-javascript-plugin-2.8.jar \
	&& curl -o $SONAR_PLUGIN_HOME/sonar-web-plugin-2.4.jar -fSL https://sonarsource.bintray.com/Distribution/sonar-web-plugin/sonar-web-plugin-2.4.jar
