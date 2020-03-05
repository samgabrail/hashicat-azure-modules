# hashicat-azure-modules
show off our modules capabilities on Azure

## Steps to running the demo

0. Make sure myresource group is implemented (you can run a manual apply with the module commented out) otherwise you get an error that the module doesn't have myresource group
1. Show the modules section and show how you add a module and different versions
2. Walk through Design Configuration and show the preview code
3. Rename the main.tf.start file to main.tf in VS Code then uncomment the module section
4. Show the code that is very similar to the preview code
5. Commit and push. This deploys a web app on a container into Azure's App Service
6. Show the app via the link that shows up in the Apply log
7. Destroy the environment