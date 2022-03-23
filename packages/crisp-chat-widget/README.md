# `@openbayes/crisp-chat-widget`

Theme-aware Crisp chat widget based on Kladenets color system

## Demo

![Demo for auto color switching](https://user-images.githubusercontent.com/96356/159696299-213fbfe0-c80c-4a02-9e20-6624e78d4cb1.gif)

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
