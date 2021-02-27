Multi-platform Boilerplate provides:

- Web app using [Angular](https://angular.io/)
- Desktop app using [Electron](https://www.electronjs.org/)
- Mobile app using [NativeScript](https://nativescript.org/)

# Install
1. Clone the repo via git and install dependencies:
```
git clone https://github.com/deniskutovskiy/angular-electron-nativescript-boilerplate.git your-project-name
cd your-project-name
yarn
```

2. Replace all occurances of `angular-electron-nativescript-boilerplate` with `your-project-name` and all occurances of `angularElectronNativescriptBoilerplate` with `yourProjectName`.

# Starting Development
## Web

```
yarn start
```

## Desktop

```
yarn electron
```

> Hot Reloading for Electron is not available right now

## Mobile
### Android

```
yarn android
```

### IOS
```
yarn ios
```

# Packaging for Production
## Web
See [Building and hosting your application](https://angular.io/start/start-deployment#building-and-hosting-your-application) section of Angular Documentation

## Desktop
See [Application Distribution](https://www.electronjs.org/docs/tutorial/application-distribution) page of Electron Documentation

## Mobile
### Android
See [Publishing a NativeScript Android App in Google Play](https://docs.nativescript.org/angular/tooling/publishing/publishing-android-apps) page of NativeScript Documentation

### IOS
See [Publishing a NativeScript iOS App in the App Store](https://docs.nativescript.org/angular/tooling/publishing/publishing-ios-apps) page of NativeScript Documentation

# TODO's

- [ ] Tests
- [ ] Compatible versions
- [ ] Code of conduct
- [ ] Contributing guidelines
- [ ] Issue templates
- [ ] Pull request template
- [ ] Configure Dependabot
