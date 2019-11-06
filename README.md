# Awesome Kuzzle

![logo](https://kuzzle.io/static/public/images/logo_black.png)

> A curated list of awesome things related to [Kuzzle](https://github.com/kuzzleio/kuzzle).

Link with ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) logo are official projects.

## Administration Tools

- [Kuzzle Admin Console](https://github.com/kuzzleio/kuzzle-admin-console)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): An SPA to administrate your Kuzzle: index and collection management, document creation, realtime subscription and permissions management.
- [Kuzzle CLI](https://github.com/kuzzleio/kuzzle-cli)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): A CLI to administrate and manage your Kuzzle.

## SDKs

- [Javascript](https://github.com/kuzzleio/sdk-javascript)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Javascript SDK for both Node.js and the browser including multi-protocol and offline resiliency.
- [Golang](https://github.com/kuzzleio/sdk-go)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Golang SDK using the WebSocket protocol to communicate with Kuzzle API including offline resiliency.
- [Java](https://github.com/kuzzleio/sdk-java)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png)
- [Android](https://github.com/kuzzleio/sdk-android)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png)
- [C#](https://github.com/kuzzleio/sdk-csharp)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png)
- [PHP](https://github.com/kuzzleio/sdk-php)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png)
- [Dart](https://github.com/prijindal/kuzzle_dart)
- [Rust](https://github.com/alexandrebouthinon/kuzzle-sdk-rust)

## Plugins

### External services plugins
- [S3](https://github.com/kuzzleio/kuzzle-plugin-s3)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Upload and manage files with [S3 protocol](https://help.servmask.com/knowledgebase/list-of-s3-compatible-storage-providers/).
- [Prometheus](https://github.com/kuzzleio/kuzzle-plugin-prometheus)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Monitor your Kuzzle application with [Prometheus](https://prometheus.io).
- [Cloudinary](https://github.com/kuzzleio/kuzzle-plugin-cloudinary)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Manage your images with [Cloudinary](https://cloudinary.com).
- [Freeboard IoT Dashboard](https://github.com/kuzzleio/kuzzle-freeboard-plugin)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Freeboard plugin to help integrating data from a Kuzzle Server to your [Freeboard IoT Dashboard](https://freeboard.io).
- [Probe BigQuery Connector](https://github.com/kuzzleio/kdc-bigquery-connector)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Plugin forwarding Probe measures to Google [BigQuery](https://cloud.google.com/bigquery/) 

### Authentication plugins
- [Local](https://github.com/kuzzleio/kuzzle-plugin-auth-passport-local)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Provide local authentication with username/password for Kuzzle.
- [0Auth](https://github.com/kuzzleio/kuzzle-plugin-auth-passport-oauth)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Authentication plugin with 0Auth services like Google, Facebook, etc.

### Boilerplates & Examples
- [Core Plugin Boilerplate](https://github.com/kuzzleio/kuzzle-core-plugin-boilerplate)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Simple boilerplate and example code to build a Kuzzle Plugin. 
- [Advanced Boilerplate](https://github.com/kuzzleio/kuzzle-plugin-advanced-boilerplate)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Advanced boilerplate for a core plugin with better modularity.
- [TOTP 2Factor Authentication Example](https://github.com/kuzzleio/kuzzle-plugin-auth-totp)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Example of 2Factor authentication with TOTP.
- [Custom Policies Example](https://github.com/kuzzleio/kuzzle-plugin-sample-custom-policies)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Example of advanced permission management with a Kuzzle plugin.
- [Geofenced Read Restriction Example](https://github.com/kuzzleio/kuzzle-plugin-sample-user-location-policies)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Example of restricting read access based on user location 

### Others
- [Cluster](https://github.com/kuzzleio/kuzzle-plugin-cluster)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Enable to deploy your Kuzzle application as a resilient and scalable masterless cluster
- [Logger](https://github.com/kuzzleio/kuzzle-plugin-logger)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Handle logging and use Winston to transport them anywhere.
- [Computed Fields](https://github.com/kuzzleio/computed-fields-plugin)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Allow definition and usage of computed fields in documents.
- [Probe](https://github.com/kuzzleio/kuzzle-plugin-probe)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Statistical probe plugin.
- [Probe Listener](https://github.com/kuzzleio/kuzzle-plugin-probe-listener)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Statistical probe listener plugin.

## Frontend 

### Vue.js

- [Vue Kuzzle](https://github.com/kuzzleio/vue-kuzzle)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): A Vue.js plugin shipping the Kuzzle SDK in your components.
- [Vue.js/CoreUI Boilerplate](https://github.com/kuzzleio/kuzzle-vuejs-coreui-boilerplate)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): A fully fledged boilerplate to kickoff your Kuzzle projects with VueJS, CoreUI and i18n.
- [Getting Started with Vue.js & Javascript SDK](https://docs.kuzzle.io/sdk/js/6/getting-started/vuejs/standalone/)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Learn how to use the Javascript SDK inside a Vue.js application.
- [Todo App Example](https://github.com/kuzzleio/kuzzle-how-to/tree/master/todo-MVC-Kuzzle-VueJS): Example of a Todo application with Vue.js and the Javascript SDK.

### React.js

- [React.js & Redux Boilerplate](https://github.com/kuzzleio/kuzzle-react-redux-boilerplate): A fully fledged boilerplate to kickoff your Kuzzle projects with React and Redux.
- [Getting Started with React.js & Javascript SDK](https://docs.kuzzle.io/sdk/js/6/getting-started/react/with-redux/)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Learn how to use the Javascript SDK inside a React/Redux application.

### Flutter

- [Kuzzle Go](https://github.com/kuzzleio/flutter-demo)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Pokemon Go like application made with Dart SDK, Flutter and Kuzzle.

## Docker Images

## Publications

### Tech Articles

### Tutorials

- [Keep Only Warm Data](https://github.com/kuzzleio/kuzzle-how-to/tree/master/keep-only-warm-data)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Clean old data from Kuzzle.
- [Massive Data Import](https://github.com/kuzzleio/kuzzle-how-to/tree/master/massive-data-import)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Quickly import massive amount of data into Kuzzle.
- [Synchronize Kuzzle with Another Database](https://github.com/kuzzleio/kuzzle-how-to/tree/master/sync-data-to-another-database)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Realtime synchronization of Kuzzle data into another database ([Cassandra](https://cassandra.apache.org)).
- [Create Realtime IoT Dashboard with Freeboard](https://github.com/kuzzleio/kuzzle-how-to/tree/master/monitor-iot-data-with-freeboard)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Create a real-time visualization for Kuzzle by adding a simple plugin to [Freeboard](https://freeboard.io), an open source dashboard.
- [Use Kuzzle as an IoT backend With ESP32](https://docs.kuzzle.io/how-to/1/kuzzle-esp32/)![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x8.png): Develop an IoT application using an ESP32 module and Kuzzle, communicating using MQTT.