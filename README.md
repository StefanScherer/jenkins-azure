# jenkins-azure
Jenkins in Azure [https://jenkins.schererstefan.xyz](https://jenkins.schererstefan.xyz)

## Blue Ocean
- Create GitHub repo with `Jenkinsfile`: https://jenkins.io/doc/book/pipeline/jenkinsfile/
- Create a GitHub access token with:
  - repo (All)
  - admin:repo_hook(All)
  - admin:org_hook
  - user:email
- Add pipeline in Jenkins, select GitHub, add token, select repo, done.

## GitHub WebHook
- Set Up a Blue Ocean Pipeline with Github
  - https://serversforhackers.com/c/set-up-a-blue-ocean-pipeline-with-github

## Azure VM agents
- Scale your Jenkins deployments to meet demand with Azure VM agents
  - https://docs.microsoft.com/en-us/azure/jenkins/jenkins-azure-vm-agents
  
## Monitoring
- Prometheus metrics plugin
  - https://grafana.com/dashboards/306
  
