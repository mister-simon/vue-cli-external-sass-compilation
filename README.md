# vue-cli-external-sass-compilation

This is just a test to work out a way to handle sass compilation without relying on the `.vue` template system for it. Whilst still getting the benefits of using the vue cli for development.

Turns out you can just `require()` whatever scss files you want from `main.js`, and it'll be compiled as if it was in one of your `.vue` templates.

That way it still hot-reloads, builds down to a single `app.css` file, and you can still opt to use the `.vue` template styles if you want.

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```
