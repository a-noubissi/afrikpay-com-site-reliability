FROM prom/alertmanager:v0.27.0
ADD alertmanager.yml /etc/alertmanager/
ADD ./templates/alertmanager-template.tmpl /etc/alertmanager/templates/
ADD ./slack_config/key.json /etc/alertmanager/