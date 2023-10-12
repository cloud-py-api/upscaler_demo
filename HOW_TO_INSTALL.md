How To Install
==============

1. Install **AppAPI** from [Appstore](https://apps.nextcloud.com/apps/app_api).
2. Create a deployment daemon following the [instructions](https://cloud-py-api.github.io/app_api/CreationOfDeployDaemon.html) provided by AppAPI. _(If you are using AIO, it will be created automatically)_
3. Navigate to the `External Apps` menu from your Nextcloud instance, find this example, and click the `Install` button.
4. After successful installation, the "Upscale" action is added to the file's context menu for images.
5. After clicking on the "Upscale" button, the file is sent to the application, which, after processing, 
will create a new file next to it with the suffix "_upscaled.png" and send the user a notification that its work has completed.
