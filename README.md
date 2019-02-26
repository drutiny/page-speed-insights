# Drutiny Pagespeed Insights Plugin
Pagespeedinsights plugin for Drutiny

## Prerequisites

As per documentation https://developers.google.com/speed/docs/insights/v4/first-app, you need to have a google account, create a project first, and then create an API key https://console.developers.google.com/apis/credentials

After you have an API key, your application can append the query parameter key=yourAPIKey to all request URLs. This will be taken in charge by page-speed-insights plugin, all you need to do is to setup your pagespeed insights credentials in drutiny, following next step.


## Installation


Install the plugin. It might be already installed by other drutiny plugins
```
composer require drutiny/page-speed-insights "2.x-dev"
```


```
# Setup API keys
drutiny plugin:setup page-speed-insights
```

