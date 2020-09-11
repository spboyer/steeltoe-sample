# steeltoe-sample

## Validating everything

Once you have run `tye run` you can check each app is running by visiting it's URLs in a browser. Remember most of these things rely of successful registration and caching of the config values, so things may not run immediatly. They may restart 2 or 3 times.

Eureka: [http://localhost:8761/](http://localhost:8761/)

Zipkin: [http://localhost:9411/zipkin/](http://localhost:9411/zipkin/)

Spring Config: [http://localhost:8888/PlanetWeatherProvider/default](http://localhost:8888/PlanetWeatherProvider/default)

Planet Forecast: [http://localhost:56339/weatherforecast/mars](http://localhost:56339/weatherforecast/mars)

Solar System Forecast: [http://localhost:56351/weatherforecast](http://localhost:56351/weatherforecast)

Weather App: [http://localhost:38979/](http://localhost:38979/)