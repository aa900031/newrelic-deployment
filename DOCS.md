Write your plugin documentation here.

The following parameters are used to configuration the plugin's behavior:

* **url** - The URL to POST the webhook to.

The following is a sample newrelic-deployment configuration in your 
.drone.yml file:

```yaml
notify:
  newrelic-deployment:
    image: CityFurniture/newrelic-deployment
    url: http://mockbin.org/
```