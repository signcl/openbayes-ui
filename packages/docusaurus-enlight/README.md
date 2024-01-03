# `@openbayes/docusaurus-enlight`

Docusaurus Enlight'ed by Kladenets color system made for OpenBayes

## Demo

General appearance:

<img width="1606" alt="Demo" src="https://user-images.githubusercontent.com/96356/158656116-fdb050fe-ad6b-4d7f-b930-c4f41834a91b.png">

Auto dark mode via Kladenets for product pages:

<img width="1606" alt="Dark mode" src="https://user-images.githubusercontent.com/96356/158656169-ab9ce6cd-cc1d-44da-9104-0a9331cec113.png">

## Install

```bash
pnpm add @openbayes/docusaurus-enlight kladenets@next
```

## Usage

In React:

```jsx
import 'kladenets';

// CSS
import '@openbayes/docusaurus-enlight';

// SCSS (this method will expose `_variables.scss` in your project)
import '@openbayes/docusaurus-enlight/src/index.scss';
```

In Sass with Webpack:

```scss
@import '~kladenets';

// CSS
@import "~@openbayes/docusaurus-enlight";

// SCSS (this method will expose `_variables.scss` in your project)
@import "@openbayes/docusaurus-enlight/src/index.scss";

```

## License

MPL-2.0
