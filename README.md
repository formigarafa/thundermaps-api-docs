# Thundermaps Api Docs

A Restlet Backup documenting available Thundermaps APIs

## Requirements
- [Chrome Browser](https://www.google.com/chrome/)
- [Restlet Client extension](https://chrome.google.com/webstore/detail/restlet-client-rest-api-t/aejoelaoggembcahagimdiliamlcdmfm)
- Api Token from [Thundermaps](https://www.thundermaps.com)

## Steps
1. Download the file `tm-apis.json` from this repository.
1. Open the Restlet extension on Chrome.
1. Click Import and select "Import Restlet Client Repository".
1. Select the file `tm-apis.json` downloaded from this repository.
1. Select the apis and settings you want to import and confirm.
1. Add your `api token` to the `settings` environment.
1. Add a random string to `installation_id` to the `settings` environment.
1. Optionally, change the `app_id` on the `settings` environment.

> Note: Certains api requests will need parameters. They are now set as variables that you can
add to the environment or simply overwrite them as required.
