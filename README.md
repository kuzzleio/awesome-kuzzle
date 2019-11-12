# Awesome Kuzzle

![logo](https://kuzzle.io/static/public/images/logo_black.png)

> A curated list of awesome things related to [Kuzzle](https://github.com/kuzzleio/kuzzle).

[Add your project](#add-your-project)

**Table of Content**

- [Administration Tools](#administration-tools)
- [SDKs](#sdks)
- [Plugins](#plugins)
  - [External services plugins](#external-services-plugins)
  - [Authentication plugins](#authentication-plugins)
  - [Others](#others)
  - [Boilerplates & examples](#boilerplates--examples)
- [Javascript](#javascript)
  - [Browser](#browser)
  - [Vue.js](#vuejs)
  - [React.js](#reactjs)
- [Typescript](#typescript)
- [Dart](#dart)
  - [Flutter](#flutter)
- [Python](#python)
- [Devops](#devops)
  - [Install scripts](#install-scripts)
  - [Docker & Docker-Compose](#docker--docker-compose)
  - [Others](#others)
- [Publications](#publications)
  - [Tech Articles](#tech-articles)
  - [Tutorials](#tutorials)

*Link with ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) logo are official projects.*

## Administration Tools

- [Kuzzle Admin Console](https://github.com/kuzzleio/kuzzle-admin-console) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): An SPA to administrate your Kuzzle: index and collection management, document creation, realtime subscription and permissions management.
- [Kuzzle CLI](https://github.com/kuzzleio/kuzzle-cli) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): A CLI to administrate and manage your Kuzzle.

## SDKs

- [Javascript](https://github.com/kuzzleio/sdk-javascript) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Javascript SDK for both Node.js and the browser including multi-protocol support and offline resiliency.
- [Golang](https://github.com/kuzzleio/sdk-go) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Golang SDK using the WebSocket protocol to communicate with Kuzzle API and including offline resiliency.
- [Java](https://github.com/kuzzleio/sdk-java) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Java SDK using the WebSocket protocol to communicate with Kuzzle API and including offline resiliency.
- [Android](https://github.com/kuzzleio/sdk-android) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Android SDK using the WebSocket protocol to communicate with Kuzzle API and including offline resiliency.
- [C#](https://github.com/kuzzleio/sdk-csharp) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): C# SDK using the WebSocket protocol to communicate with Kuzzle API and including offline resiliency.
- [PHP](https://github.com/kuzzleio/sdk-php) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): PHP SDK using the Http protocol to communicate with Kuzzle API.
- [Dart](https://github.com/prijindal/kuzzle_dart): Dart SDK using the WebSocket protocol to communicate with Kuzzle API and including offline resiliency.
- [Rust](https://github.com/alexandrebouthinon/kuzzle-sdk-rust): Rust SDK using the Http protocol to communicate with Kuzzle API.

## Plugins

### External services plugins
- [S3](https://github.com/kuzzleio/kuzzle-plugin-s3) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Upload and manage files with [S3 protocol](https://help.servmask.com/knowledgebase/list-of-s3-compatible-storage-providers/).
- [Prometheus](https://github.com/kuzzleio/kuzzle-plugin-prometheus) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Monitor your Kuzzle application with [Prometheus](https://prometheus.io).
- [Cloudinary](https://github.com/kuzzleio/kuzzle-plugin-cloudinary) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Manage your images with [Cloudinary](https://cloudinary.com).
- [Freeboard IoT Dashboard](https://github.com/kuzzleio/kuzzle-freeboard-plugin) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Freeboard plugin to help integrating data from a Kuzzle Server to your [Freeboard IoT Dashboard](https://freeboard.io).
- [Probe BigQuery Connector](https://github.com/kuzzleio/kdc-bigquery-connector) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Plugin forwarding Probe measures to Google [BigQuery](https://cloud.google.com/bigquery/) 

### Authentication plugins
- [Local](https://github.com/kuzzleio/kuzzle-plugin-auth-passport-local) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Provide local authentication with username/password for Kuzzle.
- [0Auth](https://github.com/kuzzleio/kuzzle-plugin-auth-passport-oauth) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Authentication plugin with 0Auth services like Google, Facebook, etc.

### Others
- [Cluster](https://github.com/kuzzleio/kuzzle-plugin-cluster) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Enable to deploy your Kuzzle application as a resilient and scalable masterless cluster
- [Logger](https://github.com/kuzzleio/kuzzle-plugin-logger) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Handle logging and use Winston to transport them anywhere.
- [Computed Fields](https://github.com/kuzzleio/computed-fields-plugin) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Allow definition and usage of computed fields in documents.
- [Probe](https://github.com/kuzzleio/kuzzle-plugin-probe) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Statistical probe plugin.
- [Probe Listener](https://github.com/kuzzleio/kuzzle-plugin-probe-listener) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Statistical probe listener plugin.

### Boilerplates & Examples
- [Core Plugin Boilerplate](https://github.com/kuzzleio/kuzzle-core-plugin-boilerplate) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Simple boilerplate and example code to build a Kuzzle Plugin. 
- [Advanced Boilerplate](https://github.com/kuzzleio/kuzzle-plugin-advanced-boilerplate) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Advanced boilerplate for a core plugin with better modularity.
- [TOTP 2Factor Authentication Example](https://github.com/kuzzleio/kuzzle-plugin-auth-totp) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Example of 2Factor authentication with TOTP.
- [External Authentication Example](https://github.com/kuzzleio/kuzzle-plugin-sample-custom-authstrategy) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Example of using an external system to authenticate users with Kuzzle.
- [Custom Policies Example](https://github.com/kuzzleio/kuzzle-plugin-sample-custom-policies) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Example of advanced permission management with a Kuzzle plugin.
- [Geofenced Read Restriction Example](https://github.com/kuzzleio/kuzzle-plugin-sample-user-location-policies) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Example of restricting read access based on user location 
- [Typescript Plugin Boilerplate](https://github.com/ScreamZ/kuzzle-typescript-plugin-starter): A starter kit for Kuzzle.io using the marvellous Typescript.

## Javascript 

- [Javascript SDK](https://github.com/kuzzleio/sdk-javascript) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Javascript SDK for both Node.js and the browser including multi-protocol and offline resiliency.

### Browser

- [SDK 0Auth Login Popup](https://github.com/kuzzleio/kuzzle-sdk-login-oauth-popup) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Open a popup for 0Auth authentication using the 0Auth plugin.

### Vue.js

- [Vue Kuzzle](https://github.com/kuzzleio/vue-kuzzle) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): A Vue.js plugin shipping the Kuzzle SDK in your components.
- [Vue.js/CoreUI Boilerplate](https://github.com/kuzzleio/kuzzle-vuejs-coreui-boilerplate) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): A fully fledged boilerplate to kickoff your Kuzzle projects with VueJS, CoreUI and i18n.
- [Getting Started with Vue.js & Javascript SDK](https://docs.kuzzle.io/sdk/js/6/getting-started/vuejs/standalone/) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Learn how to use the Javascript SDK inside a Vue.js application.
- [Todo App Example](https://github.com/kuzzleio/kuzzle-how-to/tree/master/todo-MVC-Kuzzle-VueJS) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Example of a Todo application with Vue.js and the Javascript SDK.
- [Kuzzle for Vue.js](https://github.com/thenikso/vue-kuzzle): Integrates Kuzzle with Vue usign declarative queries.
- [Geo Ads App Example](https://github.com/kuzzleio/kuzzle-geoads-example) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Example application of an application displaying ads depending of a user location.

### React.js

- [React.js & Redux Boilerplate](https://github.com/kuzzleio/kuzzle-react-redux-boilerplate) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): A fully fledged boilerplate to kickoff your Kuzzle projects with React and Redux.
- [Getting Started with React.js & Javascript SDK](https://docs.kuzzle.io/sdk/js/6/getting-started/react/with-redux/) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Learn how to use the Javascript SDK inside a React/Redux application.

## Typescript

- [Types Definition for Plugin Context](https://github.com/dbengsch/types-kuzzle-plugin-context): Types definition for the plugin context. (`accessors`, `constructors`, etc.)
- [Types Definition for Kuzzle Common Objects](https://github.com/dbengsch/types-kuzzle-common-objects): Types definitions for Kuzzle common objects. (`request`, `KuzzleError`, etc.)
- [Typescript Plugin Boilerplate](https://github.com/ScreamZ/kuzzle-typescript-plugin-starter): A starter kit for Kuzzle.io using the marvellous Typescript.

## Dart

- [Dart SDK](https://github.com/prijindal/kuzzle_dart): Dart SDK using the WebSocket protocol to communicate with Kuzzle API and including offline resiliency.

### Flutter

- [Kuzzle Go App Example](https://github.com/kuzzleio/flutter-demo) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Pokemon Go like application made with Dart SDK, Flutter and Kuzzle.
- [Kuzzle Flutter Admin](https://github.com/prijindal/kuzzle_flutter_admin): A kuzzle admin app built using kuzzle_dart and Flutter.

## Python

- [py-kuzzle-iot](https://github.com/etrousset/py-kuzzle-iot): Minimalist client to publish states and subscribe to changes.

## Devops

### Install scripts

- [Kuzzle Setup.sh](https://get.kuzzle.io) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Download and run a Kuzzle stack with a bash oneliner `bash -c "$(curl https://get.kuzzle.io)"`.
- [Kuzzle Stack on Ubuntu Setup](https://github.com/TitanKing/KuzzleKickoffBoilerplate): Install a Kuzzle Stack with a SSL proxy on Ubuntu.

### Docker & Docker-Compose

- [Production Image](https://hub.docker.com/r/kuzzleio/kuzzle) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Production image for Kuzzle.
- [Elasticsearch Image](https://hub.docker.com/r/kuzzleio/elasticsearch) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Preconfigured Elasticsearch Image to work with Kuzzle.
- [Plugin Development Image](https://hub.docker.com/r/kuzzleio/plugin-dev) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Image containing all necessary tools to develop Kuzzle plugin.
- [Kuzzle Admin Console Image](https://github.com/gpulido/kuzzle-admin-console-docker): Kuzzle Admin Console in a Docker Image.
- [Kuzzle & Kibana](https://github.com/Njuelle/kuzzle-kibana): A Docker-Compose file for running Kuzzle and Kibana together.

### Others

- [SSL Proxy for Kuzzle](https://blog.kuzzle.io/secure-kuzzle-nginx-and-ssl) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Setup an SSL proxy using Nginx and Lets Encrypt.
- [Kuzzle AMI on AWS Marketplace](https://aws.amazon.com/marketplace/pp/B07GVNXQP9) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Kuzzle AMI image to quickly launch a Kuzzle stack for developing purpose.

## Publications

### Tech Articles

- [Complete Backend Solution vs Backend Framework](https://medium.com/kuzzle/complete-backend-solution-vs-backend-framework-7eccf7906ac6) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Differences between Complete Backend solution like Kuzzle and Backend Framework like Symfony or Rails.
- [Beyond 15,000 queries per second with geomarketing and Kuzzle](https://medium.com/kuzzle/beyond-15-000-queries-per-second-with-geomarketing-and-kuzzle-1c8b1250e681) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Use Kuzzle for realtime geomarketing backend with very good performances.
- [Pub/Sub: key concepts and its usage for real-time application](https://medium.com/kuzzle/pub-sub-key-concepts-and-its-usage-for-real-time-application-f8900f618846) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): What is Pub/Sub and how to do it with Kuzzle.
- [Develop a new Generation of apps with Kuzzle real-time engine](https://medium.com/kuzzle/develop-a-new-generation-of-apps-with-kuzzle-real-time-engine-77b0062de786) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): What are the advantages of Kuzzle real-time engine and use it to build easy real-time apps.

### Tutorials

- [Keep Only Warm Data](https://github.com/kuzzleio/kuzzle-how-to/tree/master/keep-only-warm-data) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Clean old data from Kuzzle.
- [Massive Data Import](https://github.com/kuzzleio/kuzzle-how-to/tree/master/massive-data-import) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Quickly import massive amount of data into Kuzzle.
- [Synchronize Kuzzle with Another Database](https://github.com/kuzzleio/kuzzle-how-to/tree/master/sync-data-to-another-database) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Realtime synchronization of Kuzzle data into another database ([Cassandra](https://cassandra.apache.org)).
- [Create Realtime IoT Dashboard with Freeboard](https://blog.kuzzle.io/how-to-create-a-realtime-iot-dashboard-for-kuzzle) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Create a real-time visualization for Kuzzle by adding a simple plugin to [Freeboard](https://freeboard.io), an open source dashboard.
- [Use Kuzzle as an IoT backend With ESP32](https://blog.kuzzle.io/use-kuzzle-as-an-iot-backend-with-esp32-mcu) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Develop an IoT application using an ESP32 module and Kuzzle, communicating using MQTT.
- [Visualize Kuzzle Data with Google Data Studio](https://blog.kuzzle.io/how-to-visualizing-data-with-kuzzle-analytics-google-data-studio) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Use Google Data Studio to visualize Kuzzle data.
- [Visualize Kuzzle Data with Kibana](https://blog.kuzzle.io/visualizing-data-with-kuzzle-analytics-using-kibana) ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Use Kibana to visualize Kuzzle data.

## Add your project

Feel free to add you project by forking this repository and making a pull request.  
If you don't find any category for your project, you can also propose a new one.
