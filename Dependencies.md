### Dependencies

#### **Font Awesome Icons**
- `@fortawesome/fontawesome-svg-core`: Core library for Font Awesome SVG icons.
- `@fortawesome/free-brands-svg-icons`: Free brand icons from Font Awesome.
- `@fortawesome/free-regular-svg-icons`: Free regular style icons.
- `@fortawesome/free-solid-svg-icons`: Free solid style icons.
- `@fortawesome/vue-fontawesome`: Vue component for Font Awesome icons.

#### **Database & Storage**
- `@seald-io/nedb`: Lightweight embedded database for Node.js applications.

#### **Utilities**
- `autolinker`: Automatically links URLs, email addresses, and more in text.
- `lodash.debounce`: Debounce function to limit the rate of function execution.
- `marked`: Markdown parser and compiler.
- `path-browserify`: Browser-compatible path utilities.
- `process`: Polyfill for Node.js `process` object in the browser.
- `portal-vue`: Render components outside their parent hierarchy.
- `shaka-player`: Open-source media player library for adaptive streaming.
- `swiper`: Modern touch slider/carousel.
- `vue`: Vue.js framework for building user interfaces.
- `vue-i18n`: Internationalization plugin for Vue.js.
- `vue-observe-visibility`: Detect visibility changes of Vue components.
- `vue-router`: Official router for Vue.js.
- `vuex`: State management pattern + library for Vue.js.
- `youtubei.js`: Interact with YouTube's internal APIs.

#### **Electron**
- `electron-context-menu`: Context menu for Electron applications.

### DevDependencies

#### **Babel**
- `@babel/core`: Babel compiler core.
- `@babel/eslint-parser`: Babel parser for ESLint.
- `@babel/plugin-transform-class-properties`: Transform class properties syntax.
- `@babel/preset-env`: Smart preset for compiling ES2015+.

#### **ESLint & Plugins**
- `@eslint/compat`: ESLint plugin for compatibility checks.
- `@eslint/eslintrc`: ESLint configuration utilities.
- `@eslint/js`: ESLint core rules.
- `@intlify/eslint-plugin-vue-i18n`: ESLint plugin for Vue I18n.
- `eslint`: Linting utility for JavaScript.
- `eslint-config-prettier`: Disables ESLint rules that conflict with Prettier.
- `eslint-config-standard`: JavaScript Standard Style for ESLint.
- `eslint-plugin-import`: Support linting of ES2015+ import/export syntax.
- `eslint-plugin-jsonc`: ESLint rules for JSON with comments.
- `eslint-plugin-n`: Additional ESLint rules for Node.js.
- `eslint-plugin-prettier`: Runs Prettier as an ESLint rule.
- `eslint-plugin-promise`: Promises linting rules for ESLint.
- `eslint-plugin-unicorn`: Various improvements for ESLint.
- `eslint-plugin-vue`: Official Vue.js ESLint rules.
- `eslint-plugin-vuejs-accessibility`: Accessibility linting for Vue.js.
- `eslint-plugin-yml`: ESLint rules for YAML files.
- `vue-eslint-parser`: ESLint parser for Vue.js.

#### **Stylelint & Plugins**
- `@double-great/stylelint-a11y`: Accessibility linting for Stylelint.
- `stylelint`: CSS/SCSS linter.
- `stylelint-config-sass-guidelines`: Stylelint config based on Sass guidelines.
- `stylelint-config-standard`: Standard Stylelint rules.
- `stylelint-high-performance-animation`: Performance checks for CSS animations.
- `stylelint-use-logical-spec`: Enforce logical properties in CSS.

#### **Webpack & Plugins**
- `babel-loader`: Babel loader for Webpack.
- `copy-webpack-plugin`: Copies files during Webpack build.
- `css-loader`: Resolves CSS imports.
- `css-minimizer-webpack-plugin`: Minimizes CSS.
- `html-webpack-plugin`: Generates HTML files for Webpack bundles.
- `json-minimizer-webpack-plugin`: Minimizes JSON files.
- `mini-css-extract-plugin`: Extracts CSS into separate files.
- `sass-loader`: Loads and compiles Sass/SCSS files.
- `tree-kill`: Cross-platform process termination.
- `vue-loader`: Handles `.vue` files in Webpack.
- `webpack`: Module bundler.
- `webpack-cli`: Command-line interface for Webpack.
- `webpack-dev-server`: Development server for Webpack.

#### **Other Tools**
- `copy-webpack-plugin`: Copies files during the build process.
- `js-yaml`: YAML parser and dumper.
- `lefthook`: Git hooks manager.
- `npm-run-all2`: Run multiple npm scripts in parallel or sequential.
- `postcss`: Tool for transforming CSS with JavaScript.
- `postcss-scss`: SCSS parser for PostCSS.
- `prettier`: Code formatter.
- `rimraf`: Cross-platform `rm -rf` for Node.js.
- `sass`: Sass compiler.
- `stylelint`: CSS linter.
- `tree-kill`: Kill processes by PID.
- `vue-devtools`: Debugging tools for Vue.js.

### Scripts

- **Build Scripts**
  - `build`: Runs a series of scripts to build the application.
  - `build:arm64` / `build:arm32`: Builds for specific ARM architectures.
  - `build-release`: Executes the build release script.
  
- **Development Scripts**
  - `dev`: Runs development server scripts.
  - `debug`: Starts the application in debug mode.
  
- **Linting & Formatting**
  - `lint-all`: Runs all linting scripts.
  - `lint`: Runs ESLint and Stylelint.
  - `lint-fix`: Fixes linting issues automatically.
  
- **Packaging**
  - `pack`: Packages main and renderer processes.
  
- **Utility Scripts**
  - `postinstall`: Rebuilds Electron dependencies after install.
  - `release`: Runs tests and builds the project.
  
- **Continuous Integration**
  - `ci`: Installs dependencies with frozen lockfile for CI environments.

---

*This 

package.json

 is configured for the FreeTube application, leveraging Vue.js for the frontend, Electron for the desktop environment, and various tools for development, building, and linting.*
