# Smart Connect

## What is Smart Connect?

Smart Connect aims to be a collection of tools to control your smart home on top of [ioBroker](https://github.com/ioBroker/ioBroker).
The core functionality is provided by [Smart Connect Firestore Sync](https://github.com/kosimst-smart-connect/iobroker.smart-connect-firestore-sync),
which allows you to sync states from your ioBroker-instance to firestore. From there, all individual Smart Connect Services can access your smart home securely and reliable, enhancing it with additional features.

## Why are many repos still empty?

Smart Connect originated in a personal project which is therefore tailored to a specific environment.
In order to deploy and adapt it easily to the most different smart homes, it still needs to be adapted, which is currently not finished.

## What's in the box?

On top of the Firestore Sync ioBroker-Adapter, 
you can choose from the following additional services, which can all be found in this GitHub-Organization:

Please note that all of those repos are currently still in development as I am about to convert them from just personal-fitting projects to more widely deployable solutions.

### Already implemented:

#### [Smart Connect Frontend](https://github.com/kosimst-smart-connect/smart-connect-frontend)
A PWA to control your smart home from everywhere.

#### [Smart Connect BQ Stream](https://github.com/kosimst-smart-connect/smart-connect-bq-stream)
A cloudfunction to snapshot your smart home to BigQuery for Machine Learning or just to view the history of e.g. sensors.

#### [Smart Connect Actions](https://github.com/kosimst-smart-connect/smart-connect-actions
Use Google Assistant to control your smart home.

### In Progress

#### [Smart Connect Geofencing](https://github.com/kosimst-smart-connect/smart-connect-geofencing)
Enhance ioBroker and Smart Connect with geofencing.

### Coming

#### Smart Connect BQ API

### Ideas

Please feel free to contribute your own ideas or even working solutions on top of Firestore Sync.
