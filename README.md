# jira-issues-importer

**Usage:**

``` 
java -jar jira-issues-importer-0.0.1-SNAPSHOT.jar 
     --jira.host=<your_jira_hostname> 
     --jira.search.api.endpoint=/rest/api/latest/search?jql= 
     --output.dir=<path_to_write_issue_files> 
     --username=<username> 
     --password=<password> 
     --batch.size=100 
     --jql=filter=123456 
```
You can add default values for these properties inside ```application.properties``` file or pass them using command line (as shown in above usage) to override the default values as required.