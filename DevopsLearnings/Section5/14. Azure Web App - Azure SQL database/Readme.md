Provision SQL database
    - While creating , Use sql authentication,
         Firewall rules :
            Connectivity method: public end point
            Allow azure services and resources to access this server : Yes
 
1. Build Asp.net core app and push to azure repos
2. Release pipeline - 2 tasks
   - 2a. Deploy table and data in the azure sql database
   - 2b. Deploy the dotnet application to azure web app
