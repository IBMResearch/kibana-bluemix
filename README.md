# Kibana for Bluemix

Custom [Kibana](https://www.elastic.co/downloads/kibana) release with some little changes ready to deploy in the IBM cloud. The version is 5.6.3 due to compatibility with the Elastic addon one.

## Use

Just setup your `kibana.yml` file as always, but do not use the `server.port` property.

To try it locally:

```sh
npm start
```

To deploy:

```sh
bx app push YOUR_APP_NAME
```
