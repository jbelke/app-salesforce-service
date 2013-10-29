app-salesforce-svc
==================

This app uses a salesforce DSP service to pull the 5 newest accounts using the salesforce REST API. To try out this app on your own DSP you can import the file salesforcesvc.dfpkg directly into your DSP by going to the Apps tab in the admin console and clicking the "Import New App" button in the upper right. Select salesforcesvc.dfpkg in the file picker then click the Import button to import into your DSP.

After that you should go to the services tab and create a service named "salesforce". Set the type to Salesforce and enter the credentials and security token for the desired Salesforce user.

Now go to the Apps tab and preview the app, or you can run it from LaunchPad by clicking the app list button at the top of the screen.
