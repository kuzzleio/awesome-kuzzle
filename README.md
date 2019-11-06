# Awesome Kuzzle

![logo](https://kuzzle.io/static/public/images/logo_black.png)

> A curated list of awesome things related to [Kuzzle](https://github.com/kuzzleio/kuzzle).

Link with ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) logo are official projects.

## Administration Tools

- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Kuzzle Admin Console](https://github.com/kuzzleio/kuzzle-admin-console): An SPA to administrate your Kuzzle: index and collection management, document creation, realtime subscription and permissions management.
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Kuzzle CLI](https://github.com/kuzzleio/kuzzle-cli): A CLI to administrate and manage your Kuzzle.

## SDKs

- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Javascript](https://github.com/kuzzleio/sdk-javascript): Javascript SDK for both Node.js and the browser including multi-protocol and offline resiliency.
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Golang](https://github.com/kuzzleio/sdk-go): Golang SDK using the WebSocket protocol to communicate with Kuzzle API including offline resiliency.
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Java](https://github.com/kuzzleio/sdk-java) 
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Android](https://github.com/kuzzleio/sdk-android) 
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [C#](https://github.com/kuzzleio/sdk-csharp) 
- [Dart](https://github.com/prijindal/kuzzle_dart)
- [Rust](https://github.com/alexandrebouthinon/kuzzle-sdk-rust)

## Plugins

### External services plugins
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [S3](https://github.com/kuzzleio/kuzzle-plugin-s3): Upload and manage files with [S3 protocol](https://help.servmask.com/knowledgebase/list-of-s3-compatible-storage-providers/).
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Prometheus](https://github.com/kuzzleio/kuzzle-plugin-prometheus): Monitor your Kuzzle application with [Prometheus](https://prometheus.io).
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Cloudinary](https://github.com/kuzzleio/kuzzle-plugin-cloudinary): Manage your images with [Cloudinary](https://cloudinary.com).
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Freeboard IoT Dashboard](https://github.com/kuzzleio/kuzzle-freeboard-plugin): Freeboard plugin to help integrating data from a Kuzzle Server to your [Freeboard IoT Dashboard](https://freeboard.io).
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Probe BigQuery Connector](https://github.com/kuzzleio/kdc-bigquery-connector): Plugin forwarding Probe measures to Google [BigQuery](https://cloud.google.com/bigquery/) 

### Authentication plugins
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Local](https://github.com/kuzzleio/kuzzle-plugin-auth-passport-local): Provide local authentication with username/password for Kuzzle.
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [0Auth](https://github.com/kuzzleio/kuzzle-plugin-auth-passport-oauth): Authentication plugin with 0Auth services like Google, Facebook, etc.

### Boilerplates & Examples
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Core Plugin Boilerplate](https://github.com/kuzzleio/kuzzle-core-plugin-boilerplate): Simple boilerplate and example code to build a Kuzzle Plugin. 
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Advanced Boilerplate](https://github.com/kuzzleio/kuzzle-plugin-advanced-boilerplate): Advanced boilerplate for a core plugin with better modularity.
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [TOTP 2Factor Authentication Example](https://github.com/kuzzleio/kuzzle-plugin-auth-totp): Example of 2Factor authentication with TOTP.
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Custom Policies Example](https://github.com/kuzzleio/kuzzle-plugin-sample-custom-policies) Example of advanced permission management with a Kuzzle plugin.
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Geofenced Read Restriction Example](https://github.com/kuzzleio/kuzzle-plugin-sample-user-location-policies): Example of restricting read access based on user location 

### Others
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Cluster](https://github.com/kuzzleio/kuzzle-plugin-cluster): Enable to deploy your Kuzzle application as a resilient and scalable masterless cluster
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Logger](https://github.com/kuzzleio/kuzzle-plugin-logger): Handle logging and use Winston to transport them anywhere.
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Computed Fields](https://github.com/kuzzleio/computed-fields-plugin): Allow definition and usage of computed fields in documents.
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Probe](https://github.com/kuzzleio/kuzzle-plugin-probe): Statistical probe plugin.
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Probe Listener](https://github.com/kuzzleio/kuzzle-plugin-probe-listener): Statistical probe listener plugin.

## Frontend 

### Vue.js

- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Vue Kuzzle](https://github.com/kuzzleio/vue-kuzzle): A Vue.js plugin shipping the Kuzzle SDK in your components
- ![logo](https://raw.githubusercontent.com/kuzzleio/awesome-kuzzle/master/img/logo_black-25x16.png) [Vue.js/CoreUI Boilerplate](https://github.com/kuzzleio/kuzzle-vuejs-coreui-boilerplate): A fully fledged boilerplate to kickoff your Kuzzle projects with VueJS, CoreUI and i18n 

### React.js

## Publications

### Tech Articles

### Tutorials