# Flutter App ReName

A command-line tool that makes it trivial to set the launcher name for iOS and Android Flutter apps. Works with Flutter 3.

# Usage

1. Set your dev dependencies and your app's name and id (aka bundleId or applicationId, previously: package name)

```
dev_dependencies:
  sp_flutter_rename_app: ^last_version

flutter_app_name:
  name: "My App"
  id: "com.spisoft.my_app_name"
```

2. Run sp_flutter_rename_app in your project's directory

```
flutter pub get
flutter pub run sp_flutter_rename_app
```

