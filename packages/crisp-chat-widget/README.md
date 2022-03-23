# `@openbayes/crisp-chat-widget`

Theme-aware Crisp chat widget based on Kladenets color system

## Demo

https://user-images.githubusercontent.com/96356/159698418-35d50563-86ec-48fe-b766-2d5de5614c6b.mp4

## Install

```bash
yarn add @openbayes/crisp-chat-widget kladenets@next
```

## Usage

In React:

```jsx
import 'kladenets';

// CSS
import '@openbayes/crisp-chat-widget';

// SCSS (this method will expose `_variables.scss` in your project)
import '@openbayes/crisp-chat-widget/src/index.scss';
```

In Sass with Webpack:

```scss
@import '~kladenets';

// CSS
@import "~@openbayes/crisp-chat-widget";

// SCSS (this method will expose `_variables.scss` in your project)
@import "@openbayes/crisp-chat-widget/src/index.scss";

```

## License

MPL-2.0
