<p align="center">
  <img src="https://github.com/Park-Wonbin/rss-live-slider/blob/master/images/icon.png" width="25%" height="25%"/>
</p>

# RSS Live Slider

This is a repository for 2019 D2 Fest mini. We're participating in development of 'Live Slider Android Application'. The main purpose is providing an awesome UX to users when watching a collection of subscribed rss.

## Repos

- [Android RSS Viewer](https://github.com/Park-Wonbin/android-rss-viewer) - Android application that provides rss feeds with live slider.
- [Android Live Slider](https://github.com/shhj1998/android-live-slider) - Android library that provides components for constructing a slide view with live animations.
- [RSS Search API](https://github.com/shhj1998/rss-search-api) - Provides useful apis for fetching and creating rss feeds and news which is written in Golang.

## Architecture
<p align="center">
  <img src="https://github.com/Park-Wonbin/rss-live-slider/blob/master/images/architecture.png"/>
</p>

We divided the application into two parts - front end and back end. In the application(front end), it fetch rss data from the api server(back end). The api server not only provides rss data, it updates the database periodically. Every 25 minutes, it fetch the current rss data and insert into the database. 

## Features

> RSS feeds in a slide view with live, rich animations

<p align="center">
  <img src="https://github.com/Park-Wonbin/rss-live-slider/blob/master/images/new-rss-viewer-1.gif" width="30%"/>
  <img src="https://github.com/Park-Wonbin/rss-live-slider/blob/master/images/new-rss-viewer-2.gif" width="30%"/>
  <img src="https://github.com/Park-Wonbin/rss-live-slider/blob/master/images/new-rss-viewer-5.gif" width="30%"/>
</p>

> You can subscribe RSS contents, and search by words

<p align="center">
  <img src="https://github.com/Park-Wonbin/rss-live-slider/blob/master/images/new-rss-viewer-3.gif" width="30%"/>
  <img src="https://github.com/Park-Wonbin/rss-live-slider/blob/master/images/new-rss-viewer-4.gif" width="30%"/>
</p>

> Powerful RSS API Server

<p align="center">
  <img src="https://github.com/Park-Wonbin/rss-live-slider/blob/master/images/api-server.gif"/>
</p>

> All of these features are now available to others as an open source with awesome documents!

<p align="center">
  <img src="https://github.com/Park-Wonbin/rss-live-slider/blob/master/images/server-library.png" width="32%"/>
  <img src="https://github.com/Park-Wonbin/rss-live-slider/blob/master/images/android-library.png" width="60%"/>
</p>

## See Also

- [Performance](https://github.com/shhj1998/rss-search-api#performance) : We made a report about our api server performance.
- [Data Model](https://github.com/shhj1998/rss-search-api#schema) : More details about our data model(schema) is available.
