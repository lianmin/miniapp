# Changelog

## [4.2.1] - 2021-03-31

### Changed

- Add modify `document` callback front of wrapper chunk

## [4.2.1] - 2021-03-31

### Changed

- Not require `webpack-runtime.js` in page js file

## [4.2.0] - 2021-03-30

### Added

- Support config native miniapp dependencies in build.json

### Fixed

- Native component template generation in ali miniapp
- Miss `onGetAuthorize` and `onError` events in ali miniapp button template
- Miss `animation` props in wechat miniapp view template


## [4.1.1] - 2021-03-25

### Added

- Add `data-params` in ali miniapp button template
## [4.1.0] - 2021-03-23

### Added
- Support using plugin ans native components in sub packages
- Support import native app config
- Add `disable-scroll` in ali miniapp view template
- Add contact-button  in ali miniapp
- Add `data-params` in wechat miniprogram button template
## [4.0.2] - 2021-03-15

### Fixed

- Miss click event in image component
- Check whether events exist in miniapp native components before deleting
- Set animation default value to `null` in h-element

## [4.0.1] - 2021-03-12

### Fixed

- Can't use nested scroll-view in wechat
- Generate wrong usingComponents for npm native components in page json

## [4.0.0] - 2021-03-11

### Changed

- Refact the template generation