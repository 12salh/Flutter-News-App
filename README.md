[![Codemagic build status](https://api.codemagic.io/apps/5e93249b1838ac3d3e52a5bc/5e93249b1838ac3d3e52a5bb/status_badge.svg)](https://codemagic.io/apps/5e93249b1838ac3d3e52a5bc/5e93249b1838ac3d3e52a5bb/latest_build)
[![codecov](https://codecov.io/gh/CoderJava/Flutter-News-App/branch/dev-v2.0.0/graph/badge.svg)](https://codecov.io/gh/CoderJava/Flutter-News-App)
[![style: effective dart](https://img.shields.io/badge/style-effective_dart-40c4ff.svg)](https://github.com/tenhobi/effective_dart)
[![License: MIT](https://img.shields.io/badge/license-MIT-purple.svg)](https://opensource.org/licenses/MIT)

![Flutter News App](https://github.com/CoderJava/Flutter-News-App/blob/master/screenshots/social%20media%20preview.png)

# Flutter News App
News App developed with Flutter and API from [News API](https://newsapi.org)

## Versions
- [v1.0.0](https://github.com/CoderJava/Flutter-News-App/tree/v1.0.0)
- [v2.0.0](https://github.com/CoderJava/Flutter-News-App/tree/v2.0.0)
- v3.0.0 under development. You can check the progress [in here](https://trello.com/b/5whQTw74/flutter-news-app-v3)

## Usage
1. Please open file **constant_config.dart** and change `YOUR API KEY` in the variable `keyNewsApi` with your own.
2. In development mode, I'm used fake json server. So, the data is not realtime. 
3. Build flavor only work for Android. So, if you want to run as development mode you can use this command.
```
flutter run -t lib/main_development.dart --flavor development -d <device_id>
```
or in production mode.
```
flutter run --release -t lib/main_production.dart --flavor production -d <device_id>
```
*Note: If you want to build and release this app to Play Store. Please use this command.*
```
flutter build appbundle --release --flavor production -t lib/main_production.dart
```
4. For iOS, you can use this command as development mode.
```
flutter run -t lib/main_development.dart -d <device_id>
```
or in production mode.
```
flutter run --release -t lib/main_production.dart -d <device_id>
```
For iOS, to build and release there is no configuration. Just follow the instructions from the [documentation](https://flutter.dev/docs/deployment/ios).

## Feature
- [X] List daily new.
- [X] Refresh list daily news with pull to refresh style.
- [X] Go to detail news website.
- [X] Search news.
- [X] Dark mode support.

## Technology

