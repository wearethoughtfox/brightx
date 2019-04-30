## Usage
This will give you file watching, browser synchronisation, auto-rebuild, CSS injecting etc etc.

```shell
$ gulp
```

## Jekyll
As this is just a Jekyll project, you can use any of the commands listed in their [docs](http://jekyllrb.com/docs/usage/)

```
jekyll serve --watch --incremental
```

## Issues
To solve:

- Wrap everything in Gulp command
- Jekyll base url

## Netlify set up
To install on Netlify, follow these instructions:
- https://www.netlify.com/blog/2015/10/28/a-step-by-step-guide-jekyll-3.0-on-netlify/#netlifystart
- Don't forget to `bundle install` to install the Ruby dependencies
- https://www.netlifycms.org/docs/intro/
- https://www.netlifycms.org/docs/editorial-workflow/
- Use Github for authentication https://www.netlify.com/docs/authentication-providers/#using-an-authentication-provider
- Add Netlify identity widget as a snippet in Build & Deploy > Post processing

## Based on jekyll-gulp-sass-browser-sync and Tachyons
- https://medium.com/@simonswiss/full-re-write-in-10-days-with-tachyons-and-functional-css-a-case-study-part-4-b565745ca1e5
- https://github.com/shakyShane/jekyll-gulp-sass-browser-sync
- https://aaronlasseigne.com/2016/02/03/using-gulp-with-jekyll/

- Use variables to customise
- Don't touch the main Tachyons folder
- Comment partials that you don't need in the master Tachyons file
- To customise, create a file with the same name and import into tachyons-extend

## SEO tags
Provided by https://github.com/jekyll/jekyll-seo-tag/blob/master/docs/usage.md

## Animation on scroll examples
https://codepen.io/michalsnik/pen/WxNdvq

## Smooth scroll
https://github.com/alicelieutier/smoothScroll

## Scroll to top button
https://www.shareicon.net/arrow-up-app-ui-essential-884106

## Notes
- https://stayintech.com/info/UX
- https://www.netlifycms.org
- https://github.com/giakki/uncss

## To do
- Netlify
- Image gulp process workflow
- Accessibility: http://a11yproject.com/checklist.html / http://pa11y.org
- Get permalinks working locally - no .html





