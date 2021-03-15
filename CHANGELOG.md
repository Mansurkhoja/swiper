slideChangeTransitionEnd not work correct
# Changelog

# [6.5.0](https://github.com/nolimits4web/Swiper/compare/v6.4.15...v6.5.0) (2021-03-05)

### Bug Fixes

- **a11y:** space should trigger role button ([3d4039b](https://github.com/nolimits4web/Swiper/commit/3d4039bbfaddb60f969a35cc7bd3c2ac2121535d))
- **core:** correctly update slideIndex when other elements are present in slides wrapper ([21e7713](https://github.com/nolimits4web/Swiper/commit/21e7713861f4f08d7c1fc4142db0171e7e4abf19))
- **core:** don't toggle zoom during transition ([16f185e](https://github.com/nolimits4web/Swiper/commit/16f185e5447bc58ed78e924f283bc9ea2d6af131)), closes [#4259](https://github.com/nolimits4web/Swiper/issues/4259)
- **core:** don't try to move slider when it is locked ([51fd048](https://github.com/nolimits4web/Swiper/commit/51fd04826669c705c936c8141ea5b27a640715ce)), closes [#4284](https://github.com/nolimits4web/Swiper/issues/4284)
- **e2e:** initSwiper ([9915f8b](https://github.com/nolimits4web/Swiper/commit/9915f8b8698635e06815412c08b7d49cddba42d3))
- **lazy:** fixed issue with lazy loading when freeMode stops without momentum ([82bcc5c](https://github.com/nolimits4web/Swiper/commit/82bcc5cc2ed3dc5c7995df45cfee1d76ed170139)), closes [#4274](https://github.com/nolimits4web/Swiper/issues/4274) [#4275](https://github.com/nolimits4web/Swiper/issues/4275)
- **navigation:** don't hide navigation on pagination click ([7b7cccf](https://github.com/nolimits4web/Swiper/commit/7b7cccf610078a189731eecb542546353a5ad772)), closes [#4285](https://github.com/nolimits4web/Swiper/issues/4285)
- **pagination:** don't hide pagination on navigation click ([68b8a93](https://github.com/nolimits4web/Swiper/commit/68b8a935a9032cf90b996ceb9d795ee61d7c18fc)), closes [#4285](https://github.com/nolimits4web/Swiper/issues/4285)
- **svelte:** fix Svelte cjs exports ([478289c](https://github.com/nolimits4web/Swiper/commit/478289ce2ca8fc857434da65182b1bd14c3447c4)), closes [#4297](https://github.com/nolimits4web/Swiper/issues/4297)

### Features

- **components:** added "resizeObserver" boolean option/prop to enable ResizeObserver ([f03ffbb](https://github.com/nolimits4web/Swiper/commit/f03ffbb0ed2148da44540856251519b0845eeaa6)), closes [#4244](https://github.com/nolimits4web/Swiper/issues/4244)
- **core:** added support to use ResizeObserver with new "resizeObserver" parameter ([5f80052](https://github.com/nolimits4web/Swiper/commit/5f8005274ee0f379cfe31d4cde65951816595aad)), closes [#4244](https://github.com/nolimits4web/Swiper/issues/4244)
- **core:** possible to enable breakpoints based on container width (instead of window width) ([42db86d](https://github.com/nolimits4web/Swiper/commit/42db86d209ce0b199b8fd92160a1278c512d2b9e)), closes [#4244](https://github.com/nolimits4web/Swiper/issues/4244)
- init cypress ([6159524](https://github.com/nolimits4web/Swiper/commit/6159524bc33fa8605eccaeec8ef241ae33b6be7d))

# [6.4.15](https://github.com/nolimits4web/Swiper/compare/v6.4.14...v6.4.15) (2021-02-18)

### Bug Fixes

- **angular, vue, svelte:** add 'observer', etc. to params-list ([8f1cd29](https://github.com/nolimits4web/Swiper/commit/8f1cd290f5e2966d2bba6fca14709d040a250741))
- **core:** correctly store class names ([02265ec](https://github.com/nolimits4web/Swiper/commit/02265ec7a9ee94649004afc312d3c010f79debb4)), closes [#4247](https://github.com/nolimits4web/Swiper/issues/4247)

# [6.4.14](https://github.com/nolimits4web/Swiper/compare/v6.4.12...v6.4.14) (2021-02-17)

### Bug Fixes

- **svelte:** add "observer" params support to props ([703ea53](https://github.com/nolimits4web/Swiper/commit/703ea5301fb1739e904dd60ff2f35dbe0f0544ed))
- **vue:** add "observer" params support to props ([1d37ff7](https://github.com/nolimits4web/Swiper/commit/1d37ff73407fa742cbd1855b668044e63ffd61eb))
- fixed error bundling CJS module ([0cda5e4](https://github.com/nolimits4web/Swiper/commit/0cda5e4708ddb662dfddce3e058cbe57c28696b3)), closes [#4242](https://github.com/nolimits4web/Swiper/issues/4242)
- **react:** add 'observer', etc. to params-list ([205c14e](https://github.com/nolimits4web/Swiper/commit/205c14eb619676c050f7708542ed716570faae48))

### Features

- **angular:** thumbs & controller support ([76acd28](https://github.com/nolimits4web/Swiper/commit/76acd2887139bb722e791c1473183cc7059afd82))

# [6.4.12](https://github.com/nolimits4web/Swiper/compare/v6.4.11...v6.4.12) (2021-02-16)

### Bug Fixes

- **angular:** autoplay SSR ([4f1e9c4](https://github.com/nolimits4web/Swiper/commit/4f1e9c44bc00d2cc3c247ea7299e3530d7ee2405))
- **angular:** don't enable observer when virtual enabled ([8810b18](https://github.com/nolimits4web/Swiper/commit/8810b188b59ca117f961bdd77ad4748dac1f97df))
- **angular:** virtual SSR ([63fed99](https://github.com/nolimits4web/Swiper/commit/63fed999eed7b328b9ae01c0e229ad25601515ba))

### Performance Improvements

- **angular:** call swiperRef outside of angular ([4e544ef](https://github.com/nolimits4web/Swiper/commit/4e544ef337c167ba6d5171d59a70d7be59a99549))

# [6.4.11](https://github.com/nolimits4web/Swiper/compare/v6.4.10...v6.4.11) (2021-02-06)

### Bug Fixes

- **angular:** BrowserAnimationsModule slides deletion ([fef6ebd](https://github.com/nolimits4web/Swiper/commit/fef6ebd89663b6bea5dd4dc30150ab642b3d23b4))
- **react:** navigation, pagination and scrollbar is not disabled when [#4181](https://github.com/nolimits4web/Swiper/issues/4181) ([460787d](https://github.com/nolimits4web/Swiper/commit/460787d081915a927b217bd4b2588d0d979f949d))
- **react:** correctly check for virtual params ([92c0137](https://github.com/nolimits4web/Swiper/commit/92c0137e4045dc926a44f1bced0b927a3ad17fb4))
- **react:** support SwiperSlider components wrapped in higher order components and fix nested fragments bug [#4144](https://github.com/nolimits4web/Swiper/issues/4144)
- **vue:** update virtual slides on nextTick ([5208b1a](https://github.com/nolimits4web/Swiper/commit/5208b1a63b63d1337a65841c873bcd8c0c01e49f)), closes [#4172](https://github.com/nolimits4web/Swiper/issues/4172)
- **svelte/vue** navigation, pagination and scrollbar is not disabled when `false` [#4181](https://github.com/nolimits4web/Swiper/issues/4181) ([ffedb6b](https://github.com/nolimits4web/Swiper/commit/ffedb6baf44794098565b408d172c34119c33323))

### Features

- **angular:** use observer to update swiper on slides changes ([962a0c0](https://github.com/nolimits4web/Swiper/commit/962a0c037a2dfb3f37d2bbf10615ecd47dd8c123))
- **angular:** use swipers observer ([30dd7c9](https://github.com/nolimits4web/Swiper/commit/30dd7c95a3bbc6ed3687f1f7581eabe261d278d9))

## [6.4.10](https://github.com/nolimits4web/Swiper/compare/v6.4.9...v6.4.10) (2021-01-29)

### Bug Fixes

- **core:** don't throw error when trying to init on non existent element ([31aa87a](https://github.com/nolimits4web/Swiper/commit/31aa87a4d948912a855c06740180104a8feb56c7))
- **core:** fixed issue with "scroll container" ([c3d0b97](https://github.com/nolimits4web/Swiper/commit/c3d0b9761aa641d0029a5f045db5eb4298e81a04)), closes [#4161](https://github.com/nolimits4web/Swiper/issues/4161)
- **react:** fixed issut with Virtual Slides not working correctly ([c24f7ef](https://github.com/nolimits4web/Swiper/commit/c24f7ef8e3a1e5553dae7eed2710087d1e636571)), closes [#4162](https://github.com/nolimits4web/Swiper/issues/4162)
- **vue:** fixed updating virtual slides on virtual data change ([5979102](https://github.com/nolimits4web/Swiper/commit/59791021b7c800e1c0a96243b96fd0ca541f0d24))

## [6.4.9](https://github.com/nolimits4web/swiper/compare/v6.4.8...v6.4.9) - Released on January 28th, 2021

### Bug Fixes

- **angular:** Cannot set property 'classNames' of undefined ([13bcf39](https://github.com/nolimits4web/Swiper/commit/13bcf3988ac44718d75106c16cf1045e64c7d143))
- **angular:** content slider ngIf ([4ca13e4](https://github.com/nolimits4web/Swiper/commit/4ca13e449135c0b7735bfabb04a9d4f05e78a8e3))
- **angular:** tsconfig path ([f2dcf16](https://github.com/nolimits4web/Swiper/commit/f2dcf1664eea9601c760a9e2b0e68e0d564cac6b))
- **angular:** zoom container custom class ([5d4f11c](https://github.com/nolimits4web/Swiper/commit/5d4f11c9d6a954803945e5d84fa38e33e67416c7))
- **core:** disable extra grid item for free mode ([9159d89](https://github.com/nolimits4web/Swiper/commit/9159d899ec93df6f34824f72a48699676ef20b13)), closes [#4010](https://github.com/nolimits4web/Swiper/issues/4010)
- **docs:** change url api -> swiper-api ([3dc9203](https://github.com/nolimits4web/Swiper/commit/3dc92037e728c9b4ade664ef2f45805f6328ff23))
- **docs:** heading levels ([e8157e6](https://github.com/nolimits4web/Swiper/commit/e8157e6221e7bd44f9f91111c3eeb7f288dbe4fe))
- **scrollbar:** fixed issue when initialized with empty `scrollbar.el` will throw an error on destroy
- **svelte:** slots container start & end ([b23b4e1](https://github.com/nolimits4web/Swiper/commit/b23b4e1695f43563ba051aa1fcf7636009f1c4dd))
- **zoom:** consider window scroll for offsets ([60cd60a](https://github.com/nolimits4web/Swiper/commit/60cd60ad0cfc681b16d984aed52b08f769794926)), closes [#4039](https://github.com/nolimits4web/Swiper/issues/4039)

### Features

- add allcontributors ([95b49b1](https://github.com/nolimits4web/Swiper/commit/95b49b14c60458fd258707f12f0aaa874cb9d781))
- **angular:** custom classes ([acc678a](https://github.com/nolimits4web/Swiper/commit/acc678a1a6bdf76eebf8ab43cd1b66e12fab0309))

## [6.4.8](https://github.com/nolimits4web/swiper/compare/v6.4.7...v6.4.8) - Released on January 22th, 2021

- Core
  - Improved default behavior on Windows touch screen devices
- Types
  - Some docs comments fixes

## [6.4.7](https://github.com/nolimits4web/swiper/compare/v6.4.6...v6.4.7) - Released on January 21th, 2021

- Types
  - Added full docs comments for all Swiper parameters
- Angular
  - Proper support for zoom functionality with required extra "zoom" element. Can be enabled with `zoom` prop on slides, e.g. `<ng-template swiperSlide [zoom]="true">`
  - Fixed issue with SSR
  - Fixed issue with not working custom `pagination.el`

## [6.4.6](https://github.com/nolimits4web/swiper/compare/v6.4.5...v6.4.6) - Released on January 20th, 2021

- Core
  - `edgeSwipeDetection` parameter now can receive string `'prevent'` to prevent system swipe-back navigation
  - Fixed issue when with decimal `slidesPerView` last slide never received "active" class/state
  - Cube
    - Fixed shadow rendering issues in Chrome
- React/Svelte/Vue/Angular
  - Fixed rendering issue when virtual slides used with breakpoints
- Minor fixes

## [6.4.5](https://github.com/nolimits4web/swiper/compare/v6.4.4...v6.4.5) - Released on December 18th, 2020

- Fixed issue with `postinstall` script

## [6.4.4](https://github.com/nolimits4web/swiper/compare/v6.4.1...v6.4.4) - Released on December 18th, 2020

- Fixed issue with `postinstall` script
- Now `.css` files are also available for all components
- Svelte
  - Fixed issue with wrong location of `.svelte` files in package
- Angular
  - Types fixes
  - Added `[config]` support to pass all Swiper params as single object (https://github.com/nolimits4web/swiper/commit/f7d21c5f49860fdca62a31ccb62b01a790fd0df3)
  - Added `(index)` active slide binding (https://github.com/nolimits4web/swiper/commit/86670bd7c1b95268919147662383804e664011a7)
- Minor fixes

## [6.4.1](https://github.com/nolimits4web/swiper/compare/v6.4.0...v6.4.1) - Released on December 9th, 2020

- Fixed types errors introduced in `6.4.0`

## [6.4.0](https://github.com/nolimits4web/swiper/compare/v6.3.5...v6.4.0) - Released on December 8th, 2020

- All new Swiper Angular components (kudos to @vltansky) 🎉
- React
  - Now Swiper won't cleanup styles on destroy
- Svelte
  - Now svelte package contains source `.svelte` components
  - Now Swiper won't cleanup styles on destroy
- Vue
  - Now Swiper won't cleanup styles on destroy
- Lazy
  - Now it has options to check is Swiper also is in view before loading the images (thanks to @ygj6)
- Build
  - Fixed sourcemap missing original sources
- Lots of minor fixes

## [6.3.5](https://github.com/nolimits4web/swiper/compare/v6.3.4...v6.3.5) - Released on October 30th, 2020

- Build
  - Fixed builds on Windows
- Core
  - Fixed no swiping class in shadow component (#3868)
  - Typecheck for `slideTo`'s `index` parameter

## [6.3.4](https://github.com/nolimits4web/swiper/compare/v6.3.3...v6.3.4) - Released on October 20th, 2020

- Vue
  - Fixed issue with `Maximum recursive updates`

## [6.3.3](https://github.com/nolimits4web/swiper/compare/v6.3.2...v6.3.3) - Released on October 9th, 2020

- Core
  - Fixed issue with wrong slides calculation when slides have inner scrollbars
- Autoplay
  - Now it will continue autoplay if it reaches the end and new slides will be added later
- React
  - Fixed issue when slide render function data was set only after interaction
- Minor fixes

## [6.3.2](https://github.com/nolimits4web/swiper/compare/v6.3.1...v6.3.2) - Released on September 28th, 2020

- Svelte
  - Fixed issue with throwing error when using breakpoints

## [6.3.1](https://github.com/nolimits4web/swiper/compare/v6.3.0...v6.3.1) - Released on September 25th, 2020

- Core

  - A11y
    - Init module after all other modules initialized

## [6.3.0](https://github.com/nolimits4web/swiper/compare/v6.2.0...v6.3.0) - Released on September 25th, 2020

- Core

  - A11y
    - Added new parameters `containerMessage`, `containerRoleDescriptionMessage` and `itemRoleDescriptionMessage` (#3834 thanks to @jenemde)

- React

  - Now `SwiperSlide` component requires unique `virtualIndex` to be set so Swiper can know which slide is rendered exactly

- Vue

  - Fixed issue when `SwiperSlide` was not rendered if used with `v-for`
  - Now `SwiperSlide` component requires unique `virtualIndex` to be set so Swiper can know which slide is rendered exactly

- All new Swiper Svelte components:

  ```html
  <Swiper spaceBetween="{50}" slidesPerView="{3}">
    <SwiperSlide>Slide 1</SwiperSlide>
    <SwiperSlide>Slide 2</SwiperSlide>
    ...
  </Swiper>
  <script>
    import { Swiper, SwiperSlide } from 'swiper/svelte';
  </script>
  ```

## [6.2.0](https://github.com/nolimits4web/swiper/compare/v6.1.3...v6.2.0) - Released on September 4rd, 2020

- All new Swiper Vue.js (v3) components:

  ```html
  <template>
    <swiper :space-between="50" :slides-per-view="3">
      <swiper-slide>Slide 1</swiper-slide>
      <swiper-slide>Slide 2</swiper-slide>
      ...
    </swiper>
  </template>
  <script>
    import { Swiper, SwiperSlide } from 'swiper/vue';

    export default {
      components: {
        Swiper,
        SwiperSlide,
      },
    };
  </script>
  ```

## [6.1.3](https://github.com/nolimits4web/swiper/compare/v6.1.2...v6.1.3) - Released on September 3rd, 2020

- Core
  - Pagination
    - Now it won't set a11y attributes on customly rendered bullets
- React
  - Fixed issue with loop mode and breakpoints not being recalculate slides

## [6.1.2](https://github.com/nolimits4web/swiper/compare/v6.1.1...v6.1.2) - Released on August 17th, 2020

- React
  - Fixed issue generating `useLayoutEffect` warning in Next.js
  - Fixed issue with Virtual List in RTL mode

## [6.1.1](https://github.com/nolimits4web/swiper/compare/v6.1.0...v6.1.1) - Released on July 31th, 2020

- Fixed ESM/CJS import paths

## [6.1.0](https://github.com/nolimits4web/swiper/compare/v6.0.4...v6.1.0) - Released on July 31th, 2020

- Core
  - Mousewheel
    - New mousewheel parameters `thresholdDelta` and `thresholdTime` (#3720)
  - Fixed issue with Navigation and Pagination `.less` files (#3724)
  - Fixed issue with setting proper `sideEffects` causing some bundlers to not include imported styles (#3708)
- React
  - Now `SwiperSlide` accepts render function with `isActive`, `isVisible`, `isPrev`, `isNext`, `isDuplicate` props:
    ```jsx
    <Swiper>
      <SwiperSlide>
        {({ isActive }) => <div>Current slide is {isActive ? 'active' : 'not active'}</div>}
      </SwiperSlide>
      <SwiperSlide>...</SwiperSlide>
      ...
    </Swiper>
    ```
- Minor fixes

## [6.0.4](https://github.com/nolimits4web/swiper/compare/v6.0.3...v6.0.4) - Released on July 15th, 2020

- Fixed TS definitions for Swiper React component (#3692)

## [6.0.3](https://github.com/nolimits4web/swiper/compare/v6.0.2...v6.0.3) - Released on July 14th, 2020

- Dom7 updated to latest with correct `__proto__` setters/getters

## [6.0.2](https://github.com/nolimits4web/swiper/compare/v6.0.1...v6.0.2) - Released on July 9th, 2020

- React
  - Now Swiper will be auto updated if `pagination.el`, `scrollbar.el`, `navigation.nextEl` and `navigation.prevEl` are passed from later-available refs

## [6.0.1](https://github.com/nolimits4web/swiper/compare/v6.0.0...v6.0.1) - Released on July 7th, 2020

- Core

  - SCSS:Fixed issue with missing `$colors` var in Navigation and Pagination

- React

  - Fixed Swiper instance argument typings in event handler props
  - Added event handler props definitions for modules events

## [6.0.0](https://github.com/nolimits4web/swiper/compare/v5.4.5...v6.0.0) - Released on July 3rd, 2020

- New NPM package structure

  - All scripts transpiled to ES5
  - New and renamed files (**BREAKING CHANGE**):
    - `swiper.less` - core Swiper LESS
    - `swiper.scss` - core Swiper SCSS
    - `swiper-bundle.css` - Swiper bundle CSS
    - `swiper-bundle.js` - Swiper bundle JavaScript in UMD format
    - `swiper-bundle.cjs.js` - Swiper bundle JavaScript in CommonJS format
    - `swiper-bundle.esm.js` - Swiper bundle JavaScript in ESM format
    - `swiper.cjs.js` - Swiper core JavaScript in CommonJS format
    - `swiper.esm.js` - Swiper core JavaScript in ESM format
  - Following imports are now available
    - `import Swiper from 'swiper'` - imports core version
    - `import Swiper from 'swiper/bundle'` - imports bundle version
    - `import Swiper from 'swiper/core'` - imports core version
  - Components can be imported from core version using named imports, or using direct import:

    ```js
    import { Navigation } from 'swiper';
    // or
    import Navigation from 'swiper/components/navigation';

    // and styles (Less or SCSS only)
    import 'swiper/components/navigation/navigation.less';
    ```

- Full server-side rendering support (SSR) with new parameters:
  - `userAgent` - device user agent, required for some initial detection
  - `url` - required to correctly detect and set initial slide if Hash Navigation or History modules are used
- New `loopPreventsSlide` boolean parameter (by default enabled), that prevents slidePrev/Next transitions while transition is in progress
- Full support for Node.js DOM libraries like JSDOM and Domino
- Added new `onAny(callback)` listener to listen for any swiper event
- All events now emit `swiper` instance as a first argument (**BREAKING CHANGE**)
- Added official TypeScript definitions
- Updated to use next generation `dom7` and `ssr-window` libraries
- All new Swiper React components:

  ```jsx
  import { Swiper, SwiperSlide } from 'swiper/react';

  export default () => {
    return (
      <Swiper
        spaceBetween={50}
        slidesPerView={3}
        onSwiper={(swiper) => console.log(swiper)}
        onSlideChange={() => console.log('slide change')}
      >
        <SwiperSlide>Slide 1</SwiperSlide>
        <SwiperSlide>Slide 2</SwiperSlide>
        ...
      </Swiper>
    );
  };
  ```

## [5.4.5](https://github.com/nolimits4web/swiper/compare/v5.4.3...v5.4.5) - Released on June 16th, 2020

- Core
  - Fixed issue when checkOverflow method could throw error if Navigation module wasn't installed (#3621)
- Keyboard
  - New parameter `pageUpDown` to enable/disable pageUp and pageDown keys (enabled by default)

## [5.4.3](https://github.com/nolimits4web/swiper/compare/v5.4.2...v5.4.3) - Released on June 13th, 2020

- Core
  - Removed `UIWebView` text from code
  - Fixed resize handler calling `slideTo` to last slide when it shouldn't

## [5.4.2](https://github.com/nolimits4web/swiper/compare/v5.4.1...v5.4.2) - Released on June 3rd, 2020

- Mousewheel
  - Fixed issue when enabling `forceToAxis` also inverted scrolling
- Coverflow Effect
  - Added support for `scale` parameter (#3598)
- Pagination
  - Fixed detection of `uniqueNavElements` (#3590)

## [5.4.1](https://github.com/nolimits4web/swiper/compare/v5.4.0...v5.4.1) - Released on May 20th, 2020

- Fixed dependencies versions

## [5.4.0](https://github.com/nolimits4web/swiper/compare/v5.3.8...v5.4.0) - Released on May 15th, 2020

- Hash Navigation
  - Added `hashChange` and `hashSet` events (#3557)
- Lazy
  - Added support for `<picture>` lazy loading (#3560)
- Mousewheel
  - Potentially improved vertical scrolling issues on Windows/Linux OS
- Updated `ssr-window` and `dom7` dependencies to latest versions
- Minor fixes

## [5.3.8](https://github.com/nolimits4web/swiper/compare/v5.3.7...v5.3.8) - Released on April 24th, 2020

- Core
  - Fix iOS bug with double bounce on free mode momentum bounce
- A11y
  - Fixed focus ring on navigation buttons (#3544)
  - Fixed RegExp issue in `paginationBulletMessage` (#3540, #3541)
- Thumbs
  - Added `thumbs.autoScrollOffset` parameter that allows to set on what thumbs active slide from edge. It should automatically move scroll thumbs
- Minor fixes

## [5.3.7](https://github.com/nolimits4web/swiper/compare/v5.3.6...v5.3.7) - Released on April 10th, 2020

- Core
  - Fixed `cssMode` behavior in RTL layout
- Zoom
  - Fixed issue with not working double-tap to toggle with virtual slides
- Minor fixes

## [5.3.6](https://github.com/nolimits4web/swiper/compare/v5.3.1...v5.3.6) - Released on February 29th, 2020

- Core
  - Fixed wrong auto height calculation with `centeredSlides` enabled
- Lazy
  - Now it will update auto height (if enabled) on lazy image loaded (#3466)
- Zoom
  - Fixed issue when previously active slide could be zoomed with `zoom.in()` API (#3451)
  - Fixed issue when zoom didn't work on `<picture>` element (#3456)
  - Added support for custom zoom-target element by adding `swiper-zoom-target` class to such elements
- Coverflow Effect
  - `stretch` parameter now can be set in `%` (#3468)
- Minor fixes

## [5.3.1](https://github.com/nolimits4web/swiper/compare/v5.3.0...v5.3.1) - Released on February 8th, 2020

- Core
  - Fixed issue when slider could stuck after last slide (#3414)
  - Added `label` to list of form events to keep clicks on it (#3407)

## [5.3.0](https://github.com/nolimits4web/swiper/compare/v5.2.1...v5.3.0) - Released on January 11th, 2020

- Core
  - New `slidesPerGroupSkip` behavior (#3361)
  - New ratio-based breakpoints (#3389)
  - Added SCSS interpolation (#3373, #3374)
- Mousehweel
  - Fixed issue when it can fail on load (#3383)
- Minor fixes

## [5.2.1](https://github.com/nolimits4web/swiper/compare/v5.2.0...v5.2.1) - Released on November 16th, 2019

- Core
  - New loop events `beforeLoopFix` and `loopFix`
  - New parameter `updateOnWindowResize` (by default `true`) that will update/recalc swiper on window resize/orientationchange
  - Added SCSS interpolation for `--swiper-theme-color` variable when not building from source (#3334)
  - Quote SCSS color names (#3316)
  - 
