- Learn about the task PublishPipelineArtifact@1 and how it works
- Set up release pipeline and choose build artifact
-   CHoose task as below
  - task: AzureWebApp@1
    displayName: 'Azure Web App Deploy: webappkaruna234'
    inputs:
      azureSubscription: 'My Visual Studio Professional Subscription'
      appType: webApp
      appName: webappkaruna234
