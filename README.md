````markdown
# itbl-websdk-app

Iterable Web SDK demo app.

## Install

```bash
npm install
````

## Build & Run with NPM

### Clean and build

```bash
npm run clean && npm run build
```

### Run app

```
npm start
```

Open your browser and navigate to `http://localhost:9000` to see your fitness app in action.

## Update Token/API

Add `jwtToken` and `apikey` in `main.ts`.

## Add Your Own `placementId` and `appPackageName`

* Update `placementId` with your own value (supports a single value or an array of values).
* Update `appPackageName` with your website package name.

## Add Email in Query Param to Reflect Eligible Users

```text
http://localhost:9000/?email=test@example.com
```

## Current Implementation

The code works for the Out-of-the-Box view (Banner) with a carousel effect implemented through CSS/JS.

Reference:
[https://support.iterable.com/hc/en-us/articles/27537816889108-Embedded-Messages-with-Iterable-s-Web-SDK#out-of-the-box-views](https://support.iterable.com/hc/en-us/articles/27537816889108-Embedded-Messages-with-Iterable-s-Web-SDK#out-of-the-box-views)

```
```
