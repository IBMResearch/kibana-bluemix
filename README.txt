# Kibana for Bluemix

Custom [Kibana Download Page](https://www.elastic.co/downloads/kibana) with some little changes ready to deploy in Bluemix. The version is 5.6.3 due to compatibility with the addon provided one.

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
