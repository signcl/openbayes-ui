# OpenBayes UI

OpenBayes UI Library

## Development

If you need to update one of the libraries and see live result in corrsesponding project. For example, if you want to update the `@openbayes/docsearch-css` library and see the changes in `signcl/openbayes-docs` project. You can:

```bash
$ cd openbayes-ui
$ yarn docsearch-css link
...
success Registered "@openbayes/docsearch-css".
info You can now run `yarn link "@openbayes/docsearch-css"` in the projects where you want to use this package and it will be used instead.
```

Then:

```bash
$ cd ../openbayes-docs
$ yarn link @openbayes/docsearch-css
...
success Using linked package for "@openbayes/docsearch-css".
```

## License

MPL-2.0
