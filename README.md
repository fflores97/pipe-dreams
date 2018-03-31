Blog site for Felipe Flores

## Custom syntax highlighting

I used the tranquilpeak theme's documentation to customize the highlighting.
```
cd themes/hugo-tranquilpeak-theme
```

And set up a development environment

```
hugo-tranquilpeak-theme$ npm install
```

Then modify `src/scss/themes/_hljs-custom.scss` and `src/scss/tranquilpeak.scss` as instructed in the first file according to highlight.js's Tomorrow Night Bright specification css. Finally, run it all together
```
hugo-tranquilpeak-theme$ npm run prod
```

And finally run hugo to build the new site

```
hugo-tranquilpeak-theme$ cd ../.. && hugo
```

## Add Content

Add content accordint to R Markdown's instructions. Recommended: copy the first post's format, etc.
