---
title: "History"
permalink: /website-history/
excerpt: "Change log of enhancements and bug fixes made to the theme."
---

## [4.19.2](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.19.2)

### Enhancements

- Add support for bilibili videos in [responsive video helper](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#responsive-video-embed). [#2512](https://github.com/mmistakes/minimal-mistakes/pull/2512)
- Add Myanmar (Burmese) localized UI text strings. [#2500](https://github.com/mmistakes/minimal-mistakes/pull/2500)
- Improve author links underline on hover. [#2472](https://github.com/mmistakes/minimal-mistakes/pull/2472)
- Add documentation for applying Front Matter defaults to jekyll-archives pages. [#2466](https://github.com/mmistakes/minimal-mistakes/pull/2466)
- Add missing Vietnamese translations. [#2459](https://github.com/mmistakes/minimal-mistakes/pull/2459) [#2486](https://github.com/mmistakes/minimal-mistakes/pull/2486)
- Fix Finnish localized UI text strings. [#2455](https://github.com/mmistakes/minimal-mistakes/pull/2455)
- Clarify documentation that Lunr only searches documents in collections. [#2450](https://github.com/mmistakes/minimal-mistakes/pull/2450)
- Add guide on applying Front Matter defaults to jekyll-archives pages [#2466](https://github.com/mmistakes/minimal-mistakes/pull/2466)

### Bug Fixes

- Fix typo in configuration documentation. [#2497](https://github.com/mmistakes/minimal-mistakes/pull/2497)
- Fix "Follow menu falls under post links" on small screens. [#2479](https://github.com/mmistakes/minimal-mistakes/issues/2479)
- Hide index page from page-archive. [#2482](https://github.com/mmistakes/minimal-mistakes/pull/2482)

## [4.19.1](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.19.1)

### Enhancements

- Add [Dracula](https://draculatheme.com/) Base16 syntax highlighting theme Sass variables to [stylesheets documentation](https://mmistakes.github.io/minimal-mistakes/docs/stylesheets/#syntax-highlighting). [#2438](https://github.com/mmistakes/minimal-mistakes/pull/2438)
- Update links to `HTTPS` and remove Google+ from configuration documentation. [#2432](https://github.com/mmistakes/minimal-mistakes/pull/2432)
- Use `first_page_path` from jekyll-paginate-v2 if available. [#2431](https://github.com/mmistakes/minimal-mistakes/pull/2431)
- Update onchange and uglify-js dependencies.
- Update smooth-scroll.js to `v16.1.2`. [#2430](https://github.com/mmistakes/minimal-mistakes/issues/2430)

### Bug Fixes

- Fix author profile links `z-index` order on small screens. [#2440](https://github.com/mmistakes/minimal-mistakes/issues/2440)

## [4.19.0](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.19.0)

### Enhancements

- Add "click" overlay to close masthead and follow button menus when open. [#1168](https://github.com/mmistakes/minimal-mistakes/issues/1168)
- Remove deprecated Staticman v1 configurations from `_config.yml`. [#2386](https://github.com/mmistakes/minimal-mistakes/issues/2386)
- Use `relative_url` and `absolute_url` filters where possible. [#2387](https://github.com/mmistakes/minimal-mistakes/pull/2387)
- Improve headline hierarchy and add Sass specific variables `$h-size-x`. [#2423](https://github.com/mmistakes/minimal-mistakes/issues/2423)
- Improve accessibility of `default` skin by increasing color contrast of text and links.
- Hide posts with `hidden: true` YAML front matter from appearing in listings. [#2345](https://github.com/mmistakes/minimal-mistakes/pull/2345)
- Add Irish (Gaeilge) localized UI text strings. [#2422](https://github.com/mmistakes/minimal-mistakes/pull/2422)
- Remove `box-shadow` on radio and checkbox inputs. [#2398](https://github.com/mmistakes/minimal-mistakes/pull/2398)
- Bump Jekyll gem dependency to `v3.7`.

### Bug Fixes

- Fix documentation around using `bundle info` command. [#2425](https://github.com/mmistakes/minimal-mistakes/pull/2425)
- Fix rake vulnerability in `.gemspec` file.
- Fix Staticman v2 comment submission. [#2402](https://github.com/mmistakes/minimal-mistakes/pull/2402)
- Fix repeated site base path for masthead logo. [#2385](https://github.com/mmistakes/minimal-mistakes/pull/2385)

## [4.18.1](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.18.1)

### Bug Fixes

- Fix compatibility issue with jekyll-paginate-v2. [#2381](https://github.com/mmistakes/minimal-mistakes/pull/2381)

## [4.18.0](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.18.0)

### Enhancements

- Allow `home` layout to display posts without pagination. [#2378](https://github.com/mmistakes/minimal-mistakes/pull/2378)
- Add links to high resolution skin screenshots in README. [#2363](https://github.com/mmistakes/minimal-mistakes/issues/2363)
- Update README and LICENSE. [#2367](https://github.com/mmistakes/minimal-mistakes/pull/2367)
- Update `.gitignore` file. [#2366](https://github.com/mmistakes/minimal-mistakes/pull/2366)
- Allow override of page excerpt in hero header via `tagline` YAML front matter. [#2307](https://github.com/mmistakes/minimal-mistakes/pull/2307)
- Exclude `package-lock.json` from Jekyll build. [#2364](https://github.com/mmistakes/minimal-mistakes/pull/2364)
- Use `%-d` instead of `%d` so displayed dates aren't padded with zero. [#2359](https://github.com/mmistakes/minimal-mistakes/pull/2359)
- Update table of contents helper (`toc.html`) to [v1.0.8](https://github.com/allejo/jekyll-toc/releases). [#2355](https://github.com/mmistakes/minimal-mistakes/pull/2355)
- Add missing Dutch localized UI text strings. [#2321](https://github.com/mmistakes/minimal-mistakes/pull/2321)
- Support page header (hero) in `archive-taxonomy` layout. [#2320](https://github.com/mmistakes/minimal-mistakes/pull/2320)
- Add social icon color for Keybase. [#2302](https://github.com/mmistakes/minimal-mistakes/pull/2302)

### Bug Fixes

- Fix JavaScript comments in Disqus include to be compatible with `compress` layout. [#2373](https://github.com/mmistakes/minimal-mistakes/pull/2373)
- Fix wrong newline concatenation in SEO description [#2368](https://github.com/mmistakes/minimal-mistakes/pull/2368) [#2354](https://github.com/mmistakes/minimal-mistakes/issues/2354)
- Fix Staticman v2/v3 conditional for showing comments. [#2351](https://github.com/mmistakes/minimal-mistakes/pull/2351)
- Fix masthead logo path. [#2332](https://github.com/mmistakes/minimal-mistakes/pull/2332)
- Fix schema.org dates to ISO-8601. [#2339](https://github.com/mmistakes/minimal-mistakes/pull/2339)
- Fix background color of code blocks in notices. [#2328](https://github.com/mmistakes/minimal-mistakes/pull/2328)
- Fix alignment of feature rows when placed next to a sticky sidebar. [#2327](https://github.com/mmistakes/minimal-mistakes/issues/2327)
- Fix `seo_description` in `_includes/seo.html`. [#2326](https://github.com/mmistakes/minimal-mistakes/pull/2326)
- Fix typo in `_config.yml`. [#2319](https://github.com/mmistakes/minimal-mistakes/pull/2319)

## [4.17.2](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.17.2)

### Enhancements

- Add collection step to documentation about creating a portfolio page. [#2294](https://github.com/mmistakes/minimal-mistakes/pull/2294)
- Replace sticky footer JavaScript with flexbox styles. [#2289](https://github.com/mmistakes/minimal-mistakes/pull/2289)

### Bug Fixes

- Fix sticky footer when using MozBar extension. [#2281](https://github.com/mmistakes/minimal-mistakes/issues/2281)

## [4.17.1](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.17.1)

### Enhancements

- Update Chinese (Simplified) localized UI text strings. [#2286](https://github.com/mmistakes/minimal-mistakes/pull/2286)
- Update list of 3rd party JavaScript used and licenses. [#2276](https://github.com/mmistakes/minimal-mistakes/pull/2276)

### Bug Fixes

- Fix indention of nested GFM task lists. [#2283](https://github.com/mmistakes/minimal-mistakes/issues/2283)

## [4.17.0](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.17.0)

### Enhancements

- Show a permalink anchor when hovering over headings in main content area. [#2251](https://github.com/mmistakes/minimal-mistakes/pull/2251)
- Allow per-page override of `words_per_minute`. [#2250](https://github.com/mmistakes/minimal-mistakes/pull/2250)
- Update [onchange](https://www.npmjs.com/package/onchange) development dependency in `package.json`. [#2241](https://github.com/mmistakes/minimal-mistakes/issues/2241)
- Add Catalan localized UI text strings. [#2237](https://github.com/mmistakes/minimal-mistakes/pull/2237)

### Bug Fixes

- Remove extraneous space from Internet Explorer conditional statement. [#2273](https://github.com/mmistakes/minimal-mistakes/pull/2273)
- Fix typo in `_config.yml`. [#2243](https://github.com/mmistakes/minimal-mistakes/pull/2243)
- Replace `http` URLs with `https` where applicable in `_config.yml`. [#2244](https://github.com/mmistakes/minimal-mistakes/pull/2244)
