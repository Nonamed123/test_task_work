build:
docker/podman build -t mdzivakou/jira-software:9.6.0 .
run:
docker/podman run -v jiraVolume:/var/atlassian/application-data/jira --name="jira" -d -p 8080:8080 localhost/mdzivakou/jira-software:9.6.0

