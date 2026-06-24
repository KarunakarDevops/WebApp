1. In gut hub repo, create .github/workflows folder in the root diectory of git repo
2. Keep this workflow.yml file here
3. Generate PAT token in azure devops with scope Build, read, Read&Execute
4. Go to github oraganisation account -> secrets-> action -> new organisation secret with name AZURE_DEVOPS_TOKEN and value is the PAT created in azure devops
