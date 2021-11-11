# Chrome Extension Svelte Boilerplate 
![icon](https://github.com/micro-artwork/chrome-extension-svelte-boilerplate/blob/main/src/assets/icons/icon128.png?raw=true)

This boilerplate is a bare minimum for developing chrome extensions with Svelte. And to build it, can choose Webpack 5 or Rollup bundler.

## Getting Started
1. Clone or Download the repo
```
https://github.com/micro-artwork/chrome-extension-svelte-boilerplate.git
```

2. Install NPM packages

package.json file is for Webpack basically, If want to use Rollup bundler to build, replace package.rollup.json with package.json.
```
npm install
```

3. Excute NPM command for development
```
npm start
```

4. Open and browse chrome extensions management
```
chrome://extensions/
```

5. Turn on developer mode and load the unpacked extension from dist folder
```
./dist
```

6. Test

![test](https://micro-artwork.github.io/images/etc/boilerplate.gif)


## Note

Content-scripts template base is Svelte. But if won't need to insert UI components, need not Svelte and can use Vanilla JS.
