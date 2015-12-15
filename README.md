sidecar-iot-dashboard
=========

Sidecar end user dashboard -- node application

Sidecar IoT Dashboard is a Node.js application to display data from your Raspberry Pi or compatible hardware. You can customize your Dashboard, changing sensors, chart types and uploading your own logo. The Dashboard allows users to register devices and display your data in graphs.

[![Screen Preview](./preview.png)](./preview.png)

## Three Key Steps to a Working Configuration.

* Launch the IoT Dashboard
* Load Drivers to your Hardware
* Push Data

Sidecar IoT Dashboard is portable so you can quickly test and personalize it locally or on any cloud computing service such as AWS, Google Cloud, Microsoft Azure, or Heroku.

## Important Concepts

The **Sidecar Console** is used by the **Developer** (you) for creating and managing new **Applications** created on the **Sidecar API Platform**.

The **Sidecar IoT Dashboard** is a portable self hosted NodeJS application that is used by the **Developer** to create and deploy a End User facing **Application**.

It can be deployed locally or on a Cloud instance or server, all the source files are provided so you can customise or extend it to your needs.

There are two aspects to the **Sidecar IoT Dashboard**, first the admin panel which the Developer uses to configure the Dashboard for use by the End Users. The second aspect is the **End User Login Page**.

**End Users** can create an account and add **Hardware** to their Accounts, the Hardware will connect to the **Sidecar API** to push or get data.
