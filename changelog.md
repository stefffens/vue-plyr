# Changelog

#### 5.0.0
- Major change because of breaking fix.
- Change import scheme to be more common (`Vue.use(VuePlyr)`)
- Remove sass/scss from dependencies because it wasn't needed.
- Update dependencies to latest versions.
- Remove demo build
- Remove 1440p video from demo (CDN no longer hosted video file)
- Add and refactor some tests
- Streamline installation by adding from NPM.
- Streamline installation by including in `<script>` tag
- Change link on demo from `Home` to `Video`.

#### 4.0.0
- Renamed main component from `<plyr>` to `<vue-plyr>`.
- Removed other components in favour of the main component.
- Added SSR support.
- Used `this.$el` instead of `document.getElementById('plyr-container-' + this.idNumber)` for element selection.
- Removed `this.idNumber` from ID and computed (related to above).
- Covert to vue cli 3 except for building.
- Update plyr dependency from `3.0.2` to `3.3.22`.
- Move testing to jest.
- Change import procedure from `import VuePlyr from 'vue-plyr'` & `Vue.use(VuePlyr)` to just `import 'vue-plyr'`.
- Update some eslint rules.
- Removed storybook in favour of of vue cli 3's serve and a demo app.
- Added `hideYouTubeDOMError` option.

#### 3.0.0
- Update to plyr v3.
- Add progressive enhancement support.

#### 2.1.1
- Add event emitting.
- Fix some prop validation.

#### 2.0.0
- Convert from old vue-plyr to currently maintained version.
