dframe8
==========
This is a Port of framework 7 http://framework7.io/

Full Featured Mobile HTML Framework For Building iOS & Android Apps Extended version!

## Dist vs Build versions

On production use files (JS and CSS) only from `dist/` folder, there will be the most stable versions, `build/` folder is only for development purpose

## Build

dframe8 uses `gulp` to build a development (build) and dist versions.

First you need to have `gulp-cli` which you should install globally.

```
$ npm install --global gulp
```

Then install all dependencies, in repo's root:

```
$ npm install
```

And build development version of dframe8:
```
$ gulp build
```

The result is available in `build/` folder.

## Dist/Release

After you have made build:

```
$ gulp dist
```

Distributable version will available in `dist/` folder.

## Custom build

You can build custom version of dframe8 with only required components/modules. For example, if we need to include only Accordion, Modals and Tabs modules in addition to dFrame 8 core: 

```
$ gulp custom -accordion,modals,tabs
```
After that you will find created `custom/` folder with generated JS and CSS files. Here is the list of available additional modules:

* cards
* accordion
* searchbar
* messages
* modals
* swipeout
* sortable
* smart-select
* virtual-list
* pull-to-refresh
* infinite-scroll
* scroll-toolbars
* tabs
* fast-clicks
* forms (means Ajax forms and forms storage)
* push-state
* swiper
* photo-browser
* picker
* calendar
* notifications
