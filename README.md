# Lab8-Starter

Team: Christos Enotiadis

https://bisbouras.github.io/Lab8_Starter/

Service workers make graceful degradation possible by caching resources and intercepting network requests. When users have a good internet connection, the app works at full capacity with live data. But when the network is slow or unavailable, service workers automatically serve cached content instead, allowing the app to keep working with reduced functionality rather than breaking completely. In our recipe app, this means users can still browse recipes offline even if they can't fetch new ones - the app degrades gracefully from "full online experience" to "basic offline functionality" without the user having to do anything.

![PWA Screenshot](pwa.png)
