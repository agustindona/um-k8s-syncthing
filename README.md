# um-k8s-syncthing
Project synthing cloud with kubernetes

Step 1:
Make syncthing statefull

Step 2:
Add HTTPS

Step 3:
Implement oauth2-proxy

Google Auth Provider
For Google, the registration steps are:

Create a new project: https://console.developers.google.com/project
Choose the new project from the top right project dropdown (only if another project is selected)
In the project Dashboard center pane, choose “API Manager”
In the left Nav pane, choose “Credentials”
In the center pane, choose “OAuth consent screen” tab. Fill in “Product name shown to users” and hit save.
In the center pane, choose “Credentials” tab.
Open the “New credentials” drop down
Choose “OAuth client ID”
Choose “Web application”
Application name is freeform, choose something appropriate
Authorized JavaScript origins is your domain ex: https://internal.yourcompany.com
Authorized redirect URIs is the location of oauth2/callback ex: https://internal.yourcompany.com/oauth2/callback
Choose “Create”
Take note of the Client ID and Client Secret

Step 4: peerID
