# Jekyll Azure Deploy

Deployment files for building Jekyll on Azure Web Apps.

## Installation

Download the `.deployment`, `deploy.cmd`, and `getruby.cmd` files into your repository root folder.

One way to do this is to `cd` into the repository root folder. Then, using `curl`:

```
curl -O https://raw.githubusercontent.com/ritterim/jekyll-azure-deploy/master/.deployment && curl -O https://raw.githubusercontent.com/ritterim/jekyll-azure-deploy/master/deploy.cmd && curl -O https://raw.githubusercontent.com/ritterim/jekyll-azure-deploy/master/getruby.cmd
```

If you encounter timeout issues on deployment, add a `SCM_COMMAND_IDLE_TIMEOUT` app setting in the Azure portal and set it to `3600` or similar.

## Additional information

For additional information, see [Deploying Jekyll to Windows Azure App Services](http://rimdev.io/deploying-jekyll-to-windows-azure-app-services/).

## License

MIT
