# Prime Custom App

The Prime Custom App is based on the minimum Boilerplate Theme which model is based on the VTEX IO Store Framework.

Until now there is only the "beneficios" component, which does not use any react file.

### Uninstalling any existing theme

By running `vtex list`,  you can verify if any theme is installed.

It is common to already have a `vtex.store-theme`  installed when you start the store's front development process. 

Therefore, if you find it in the app's list, copy its name and use it together with the command `vtex uninstall`. For example:

```json
vtex uninstall vtex.store-theme
```

### Run

Then time has come to upload all the changes you made in your local files to the platform. For that, use the `vtex link` command. 

If the process runs without any errors, the following message will be displayed: `App linked successfully`. Then, run the `vtex browse` command to open a browser window having your linked store in it.

This will enable you to see the applied changes in real time, through the account and workspace in which you are working.

### Preview

To enable the theme changes on Prime page, go to yourworkspace.yourstore.myvtex.com/admin/cms/pages and change the active theme on your page or create a new one with this theme.
