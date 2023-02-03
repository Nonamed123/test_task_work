build:
podman build -t mdzivakou/jira-software:9.2.0 .
run:
podman run -v jiraVolume:/var/atlassian/application-data/jira --name="jira" -d -p 8080:8080 localhost/mdzivakou/jira-software:9.2.0

