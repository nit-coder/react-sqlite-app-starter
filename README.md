<p align="center"><br><img src="https://avatars3.githubusercontent.com/u/16580653?v=4" width="128" height="128" /></p>

<h3 align="center">Ionic/React SQLite App Starter</h3>
<p align="center"><strong><code>react-sqlite-app-starter</code></strong></p><br>
<p align="center">
  A Ionic/React application demonstrating the use of the <strong><code>@capacitor-community/sqlite@latest</code></strong> plugin and may be use as an application starter.

</p>


## Installation 🚧

To start building your App using this Starter App, clone this repo to a new directory:

```bash
git clone url
cd react-sqlite-app-starter
git remote rm origin
```

 - then install it

```bash
npm install
```

 - then go to the building process

```bash
npm run build
npx cap sync
npm run build
npx cap copy
npx cap copy web
```

the capacitor config parameters are:

```
  "appId": "com.example.app.capacitor",
  "appName": "react-sqlite-app-starter",
```

### Building Web Code

The ```@capacitor-community/sqlite``` is not implemented for Web Browsers.
if you run

```bash
npx cap serve
```
you will get the following messages:
```
SQLite Plugin not available for Web Platform
```

### Building Native Project

#### IOS

```bash
npx cap open ios
```
Once Xcode launches, you can build your finally app binary through the standard Xcode workflow.

#### Android

```bash
npx cap open android
```
Once Android Studio launches, you can build your app through the standard Android Studio workflow.

## Usage


The `@capacitor-community/sqlite` test is accessible in the Tab2 of the Application by clicking on several SQLite test button :

 - SQLite No Encryption Test
 - SQLite Two DBs Tests
 - SQLite Encryption Test    (iOS && Android only)
 - SQLite Upgrade Version Test
 - SQLite Json Import Export Test

After having run the `SQLite Two DBs Tests` another test becomes accessible `SQLite Existing Test` which is using the existing connections created in `SQLite Two DBs Tests`.



