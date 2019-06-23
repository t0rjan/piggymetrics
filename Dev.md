[![Build Status](https://travis-ci.org/sqshq/PiggyMetrics.svg?branch=master)](https://travis-ci.org/sqshq/PiggyMetrics)
[![codecov.io](https://codecov.io/github/sqshq/PiggyMetrics/coverage.svg?branch=master)](https://codecov.io/github/sqshq/PiggyMetrics?branch=master)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/sqshq/PiggyMetrics/blob/master/LICENCE)
[![Join the chat at https://gitter.im/sqshq/PiggyMetrics](https://badges.gitter.im/sqshq/PiggyMetrics.svg)](https://gitter.im/sqshq/PiggyMetrics?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# Piggy Metrics

**A simple way to deal with personal finances**

This is a [proof-of-concept application](https://piggymetrics.tk), which demonstrates [Microservice Architecture Pattern](http://martinfowler.com/microservices/) using Spring Boot, Spring Cloud and Docker.
With a pretty neat user interface, by the way.

![](https://cloud.githubusercontent.com/assets/6069066/13864234/442d6faa-ecb9-11e5-9929-34a9539acde0.png)
![Piggy Metrics](https://cloud.githubusercontent.com/assets/6069066/13830155/572e7552-ebe4-11e5-918f-637a49dff9a2.gif)

## Developer Command

### Windows
```

docker-compose.exe -f docker-compose.yml -f docker-compose.dev.yml down && docker-compose.exe -f docker-compose.yml -f docker-compose.dev.yml up -d --build


docker-compose.exe -f docker-compose.yml -f docker-compose.dev.yml restart


docker-compose.exe -f docker-compose.yml -f docker-compose.dev.yml up -d 

```

### Linux/Mac
```

docker-compose -f docker-compose.yml -f docker-compose.dev.yml down && docker-compose -f docker-compose.yml -f docker-compose.dev.yml up -d --build


docker-compose -f docker-compose.yml -f docker-compose.dev.yml restart


docker-compose -f docker-compose.yml -f docker-compose.dev.yml up -d 

```




