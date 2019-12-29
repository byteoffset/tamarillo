# tiny-css

`tiny-css` is a project which combine simplicity of less and css flexibility. Created styles may help you to create clean and nice-looking web layouts.
<br>

## Quick install
```
npm install --save tiny-css
```

## Assumptions
* Should be lightweight
* Must be easy to learn and understand
* Should be ergonomic

## What do you need before start?
* Node.js > 10.x.x
* Internet access

## Just develop
At the beginig you have to run:
```
npm install
```
Dependencies should be installed.

### Build
If you installed dependencies, you are able to compile sources with:
```
npm run build
```
Ready to use. Directory `dist` and file `tiny.less` should be created.

### Build tiny.min.css
To create `tiny.min.css` file, please run:
```
npm run build-cleancss
```

### Dynamic compilation
In case when you would like to start development and get your changes in `tiny.css` just in time, please run:
```
npm run start
```
