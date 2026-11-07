# Yeah Claims Android

Standalone Android project for the Yeah Claims website.

## App behaviour
The app opens the official Yeah Claims website in an Android WebView. This keeps the website's current pages, copy, forms, terms, privacy information, and site-side functionality in one place rather than duplicating or silently changing legal/business content.

## Build
The Codemagic workflow is defined in `codemagic.yaml`. It runs:

```sh
gradle --no-daemon assembleDebug
```

The debug APK is produced at `app/build/outputs/apk/debug/app-debug.apk`.

## Branding
The website is the source of truth for the in-app branding. The launcher icon is a temporary vector approximation and should be replaced with the original supplied Yeah Claims logo asset before release.
